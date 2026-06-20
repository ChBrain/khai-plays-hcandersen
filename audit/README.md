# Audit lane

The NLP review of this house, run as an **audit PR**. Where the gates in
`tests/` and `khai-guard` check structure deterministically, the audit lane
reviews the prose against named rubrics with a model, and records the verdict so
a human can treat each finding. It is advisory by design: an audit never edits
content and never hard-fails the build; it surfaces drift and holds the audit PR
until the human has reconciled it.

## What an audit is

Each audit is a directory under `audit/<id>/` with a manifest:

```
audit/<id>/audit.json   the manifest: { id, review: { rubrics, targets } }
audit/<id>/meta.json    freshness stamp: the content sha the audit last ran on
audit/<id>/ledger.json  the findings and their treatments (the table)
audit/<id>/log.md       the human-readable log
```

`rubrics` names what to review for; `targets` is the set of paths the review
reads. `meta.json`, `ledger.json`, and `log.md` are machine-written (the review
job commits them) and are kept out of prettier by `.prettierignore`.

The audits this house carries:

- **`voice-conformance`** the house stays in the khai voice declared in
  `README.md` and the personas.
- **`khai-type`** each file matches the khai type it claims in its frontmatter.
- **`conciseness`** the prose says what it means without padding.

## How the lane runs (`.github/workflows/audit.yml`)

Two jobs both post their verdict as a `consistency` **commit status** on the
head commit (the required branch-protection check), rather than as a job
conclusion, because a `GITHUB_TOKEN` push does not re-fire workflows.

- **review (model, advisory)** runs on PR open/reopen, a `/audit` comment, or
  manual dispatch (it calls the model, so it does not run on every push). It
  reviews each touched audit, syncs the PR's comment treatments into the ledger,
  commits `ledger.json` + `log.md` + `meta.json`, posts new findings as inline
  comments, and stamps the `consistency` status. `/audit <id>` re-runs one named
  audit on demand.
- **audit checks** runs on every push and dispatch with no model calls. It
  recomputes freshness (each audit ran against the current content) and
  reconciles the table against the comment treatments, then posts the same
  `consistency` status. Together with "require conversation resolution," this
  holds the audit PR until the table is clean.

## Treating a finding

Each finding is posted as an inline review comment. Reply on the thread with the
treatment the human chooses (for example Accept / Reduce / Transfer) and resolve
it; the next review run reads the thread and syncs the decision into the ledger.
The supporting scripts live in `.github/scripts/` (`audit-decisions.mjs`,
`audit-stamp.mjs`, `audit-gate.mjs`).
