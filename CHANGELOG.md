# @chbrain/khai-plays-hcandersen

## 0.7.1

### Patch Changes

- ef82d17: Ship and export `registry.json`. The file exists in the repo but was excluded
  from the published package (absent from `files`, no `exports`), so consumers fell
  back to deprecated `## Arc` markdown parsing. Add `registry.json` to `files` and
  an `exports` map (`.`, `./package.json`, `./registry.json`), matching the other
  houses. Packaging fix only — no play change, so it ships at the same play count.
- 93d8025: Staging the sixth play BFN 280 (Den uartige Dreng) under plays/

## 0.5.1

### Patch Changes

- cb41a6f: Staging the fifth play BFN 278 (Tommelise) under plays/

## 0.0.1

### Patch Changes

- ce31aed: First release of the H.C. Andersen production house: raised and empty, ready to receive plays (written later in khai-playwright mode). Cuts the initial publish of the programme package; the minor stays at the play count (0).
