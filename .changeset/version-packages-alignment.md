---
---

Governance: adopt the aligned Version-Packages flow. Add `dependabot/*` to the
`changeset-check` exemptions, bump `@chbrain/khai-guard` to `^0.1.16`, prefix the
`version` script with `npx`, and flip the CLAUDE.md doctrine so a play add carries a
`minor` changeset (steered through the Version Packages PR; the reconcile keeps
`minor = count` and the patch at 0). The empty-vs-patch rule for non-play changes is
unchanged. Ships no package content: an empty changeset.
