---
"@chbrain/khai-plays-hcandersen": patch
---

Ship and export `registry.json`. The file exists in the repo but was excluded
from the published package (absent from `files`, no `exports`), so consumers fell
back to deprecated `## Arc` markdown parsing. Add `registry.json` to `files` and
an `exports` map (`.`, `./package.json`, `./registry.json`), matching the other
houses. Packaging fix only — no play change, so it ships at the same play count.
