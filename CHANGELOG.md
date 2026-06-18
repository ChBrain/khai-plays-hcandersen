# @chbrain/khai-plays-hcandersen

## 0.14.1

### Patch Changes

- f686729: Converge hcandersen management onto the shared blueprint core (Order 0c). The voice layer
  and the chain-owned core (positions, shared Choregos personas, plan_stage_the_score)
  now match the blueprint verbatim; cast the house Director (Jean Hersholt) as overlay.
  Keeps its existing Roadie + touring as overlay (deferred); homes already present. The convergence gate reports 0 findings; house conformance passes.
- 0805bbe: Sync the Director position to the current blueprint: the cast named as the
  producer (the separation of two stances), and "tune the pitch" added to the
  redirect idioms. Brings the house in line with the chain canon (khai #505/#506).
- 62979db: Re-converge the Director seat to the control loop: position_director and
  plan_stage_the_score match the rewritten blueprint core (the Director runs a
  living production and captures a run, not a teller).

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
