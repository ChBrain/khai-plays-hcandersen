---
---

ci: skip the changeset-presence gate on the bot's `changeset-release/*` Version
PR. That PR consumes changesets and so carries none by design; the gate was
red-flagging every release PR. The job still runs (the required check reports),
only the gate step is skipped. Tooling-only change, no package content — empty
changeset.
