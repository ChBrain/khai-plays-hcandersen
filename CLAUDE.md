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
  `khai-guard.config.json`, `tests/**`, `CLAUDE.md`, `README.md`, `REFERENCE.md`, `REFERENCES.md`, `management/**`).
- `changeset-release/*` is a bot-controlled general lane for version releases.

A **management order** (`management/orders/**`) is a **rider**: an order directs
work in any lane, so it rides the lane of the change it drives. Write the order
beside that change and the guard folds both onto one branch (an order that
restages a play lands as one `play/` PR); committed alone, an order homes to
`governance/`. So an order and the change it commands are one PR, never two.

Never `--no-verify`. Never merge; open the PR and stop.

## Versioning

The minor version IS the play count, computed not chosen. The `version` script
runs `khai-tests registry build` after `changeset version`, which derives the
version (minor set to the play count) and reconciles both `package.json` and
`registry.json`. So a changeset only ever picks the release level; the count
owns the minor.

- **Adding a play** -> a `patch` changeset is enough to cut the release; the
  build bumps the minor for you when it counts the new play. Do not hand-edit
  the version or add a `minor` changeset for the count, that double-bump is the
  drift the build now heals.
- **Everything else** (governance, formatting, etc.) -> a `patch` changeset.

A non-zero major resets the minor while the count keeps climbing, so a house
stays `0.x`; the numbering guard rejects a major bump.

## Protection

Content is CC-BY-NC-SA, code is MIT (see `LICENSE` and `LICENSE-CODE`); the
source is credited where it is in the public domain, never claimed. `main` is
protected: pull requests and the gate checks are required before merge.
