# CLAUDE.md, the H.C. Andersen house

This is the H.C. Andersen production house (`khai-plays-hcandersen`), raised by
khai-stage. The plays are written separately, in khai-playwright mode.

**Voice first.** Operate under the
[management instructions](management/management_instructions.md): the khai
**voice and mechanics** (who speaks, the company, management orders). _Then_ this
file is the **coding contract** for the house. Voice and mechanics there; coding
rules here. The order matters: management voice first, coding second.

## Branching

Computed, not chosen. Let the guard pick the lane:

```
npx khai-guard branch <topic>
```

- `play/<topic>` owns `plays/**` (the productions).
- `governance/<topic>` owns the gates and config (`.github/**`, `.husky/**`,
  `khai-guard.config.json`, `tests/**`, `audit/**`, `CLAUDE.md`, `GEMINI.md`, `README.md`, `REFERENCE.md`, `REFERENCES.md`, `management/**`).
- `changeset-release/*` is a bot-controlled general lane for version releases.

A **management order** (`management/orders/**`) is a **rider**: an order directs
work in any lane, so it rides the lane of the change it drives. Write the order
beside that change and the guard folds both onto one branch (an order that
restages a play lands as one `play/` PR); committed alone, an order homes to
`governance/`. So an order and the change it commands are one PR, never two.

Never `--no-verify`. Never merge; open the PR and stop.

## Versioning

The minor version IS the play count, computed not chosen; the **Version Packages**
PR is the deploy gate every release passes through. `npx khai-tests registry
build` (run by the `version` script) sets the version from the play count:
`0.<count>.0` (the minor is the count, the patch resets to 0), reconciling both
`package.json` and `registry.json`. The build is the single writer of the version
number; never hand-edit it.

- **Adding a play** -> a `minor` changeset. The play PR carries it, so the deploy
  is steered through the Version Packages PR and the CHANGELOG names the play.
  `changeset version` bumps the minor and the build reconciles it back to the play
  count, resetting the patch to 0 (`0.<count>.0`). It **must** be `minor`: a
  `patch` (or empty) changeset survives the reconcile (count === minor) and drifts
  the version to `0.<count>.1`, so the `changeset-check` gate rejects it.
- **A non-play change that ships package content** (a fix to an existing play,
  the registry, the README) -> a `patch` changeset; it ships at the same play
  count.
- **A change that ships no package content** -> an **empty** changeset
  (`npx changeset add --empty`). Anything outside the package `files`
  (`REFERENCES.md`, docs, tooling, the gates, this file) ships nothing, so a
  `patch` changeset there republishes identical content and drifts the version
  (the `0.<count>.1` patch). An empty changeset records the PR and merges green
  without cutting a release. Staging a coming play in `REFERENCES.md` is the
  common case: empty, not patch. `changeset-check` flags a releasing changeset
  that ships nothing.

A non-zero major resets the minor while the count keeps climbing, so a house
stays `0.x`; the numbering guard rejects a major bump.

## Protection

Content is CC-BY-NC-SA, code is MIT (see `LICENSE` and `LICENSE-CODE`); the
source is credited where it is in the public domain, never claimed. `main` is
protected: pull requests and the gate checks are required before merge.

## Provenance

Invention is legitimate; unmarked invention is the defect. The rule is canon,
not house-local: `@chbrain/khai-arch` owns the vocabulary (`provenanceValues`)
and the kit enforces it per file. Every content file declares in frontmatter
where its substance stands relative to the declared source - the file is
always this house's authorship; provenance says whether the substance derives
from the source:

```yaml
provenance: sourced | free | unverified
```

- **sourced** - the substance derives from the declared work; divergence from
  the source is a finding.
- **free** - declared invention, knowingly beyond or beside the source; a
  marked invention reviews as clean, and fidelity findings do not apply to it.
- **unverified** - the sourcing is not yet proven; the file claims no
  fidelity until resolved.

An absent key reads as **sourced** - the strictest class is the default, so
silence never launders invention. Class moves are Choregos rulings, by order
only. The house adopts the canon-borne key via the kit bump and backfills its
declarations in the same change.
