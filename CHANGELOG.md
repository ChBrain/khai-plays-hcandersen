# @chbrain/khai-plays-hcandersen

## 0.45.1

### Patch Changes

- 5916668: Transliterate four play-element filenames from Danish characters to ASCII (ø→oe, æ→ae), matching the house's own convention (stoppenaalen, koekkenet, gadeloegten): plan_holger_danske_droem, plot_droemmen (bfn472), process_knaek (bfn482), plot_droemme (bfn517). Non-ASCII filenames break their links across platforms (NFC/NFD normalization, tooling, zip bundling). The Danish prose in the play bodies is untouched; only the filenames and the links and management orders that reference them are updated.

## 0.40.1

### Patch Changes

- 5eec50c: Declare `@chbrain/khai-engine-spine` as a runtime dependency. Every house runs on the spine — the neutral collaboration contract, the architecture seam, and the per-host setup plan — so it belongs in the production dependency graph, the single source of truth from which the zip bundler derives the engines a house carries (no hardcoded list). Adds a conformance guard that requires the spine engine and fails if any `@chbrain/khai-engine-*` is stranded in devDependencies.

## 0.19.1

### Patch Changes

- 9e3662a: Stage BFN 410 in REFERENCES.md.

## 0.14.2

### Patch Changes

- 1610977: Add a pitch (the tonal key: tenor, undertow, nerve, echo) to every H.C. Andersen play, in Danish and wired into each play's Company. 16 pitches across 14 plays.

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
