---
khai: order
title: "Stage BFN 162 Et Børneeventyr"
language: english
license: CC-BY-NC-SA-4.0
stamp:
  owner: KAI HACKS AI
  version: v0.0.1
  date: "2026-06-26"
---

# Order: Stage BFN 162 Et Børneeventyr

## Direction

The house must stage BFN 162 (_Et Børneeventyr_) to establish a production in the H.C. Andersen house. The production must model drengen, pigen, the positions (leger, leger), the pieces (legetoej, blomst), the environments (haven, huset), the leg and vaekst processes, and the plots representing barndom and haven. It must be written in authentic Danish for all prose sections.

## Orders

1. The Playwright (Hans Christian Andersen) must author the play definition, the 2 personas, the 2 positions, the 2 pieces, the 2 places, the 2 processes, the 1 in-world plans, the pitch of hjertevarm, and the 2 plots.
2. The Theatre Manager (Edvard Collin) must verify the local registry, ensure correct versioning, check formatting, and validate that the cast conforms to the canon.
3. The Roadie (Vilhelm Pedersen) must set the stage, verify the local test suite is green, and prepare the files for packaging.

## Implementation

The play files must be placed in `plays/bfn162_et_boerneeventyr/` and follow the house language policy:

- Structural elements and frontmatter in English.
- Narrative prose, projections, actions, shadows, tells, and staging notes in Danish.

## Targets

- [x] `plays/bfn162_et_boerneeventyr/play_et_boerneeventyr.md` is created and lists the complete company
- [x] `plays/bfn162_et_boerneeventyr/persona_drengen.md` is created and links to `position_leger.md`
- [x] `plays/bfn162_et_boerneeventyr/persona_pigen.md` is created and links to `position_leger.md`
- [x] `plays/bfn162_et_boerneeventyr/position_leger.md` is created
- [x] `plays/bfn162_et_boerneeventyr/position_leger.md` is created
- [x] `plays/bfn162_et_boerneeventyr/piece_legetoej.md` is created
- [x] `plays/bfn162_et_boerneeventyr/piece_blomst.md` is created
- [x] `plays/bfn162_et_boerneeventyr/place_haven.md` is created
- [x] `plays/bfn162_et_boerneeventyr/place_huset.md` is created
- [x] `plays/bfn162_et_boerneeventyr/process_leg.md` is created
- [x] `plays/bfn162_et_boerneeventyr/process_vaekst.md` is created
- [x] `plays/bfn162_et_boerneeventyr/plan_leg.md` is created and linked to `persona_drengen.md`
- [x] `plays/bfn162_et_boerneeventyr/pitch_hjertevarm.md` is created
- [x] `plays/bfn162_et_boerneeventyr/plot_barndom.md` is created and casts company elements
- [x] `plays/bfn162_et_boerneeventyr/plot_haven.md` is created and casts company elements
- [x] The local validation tests (`npm test`) run successfully with zero errors
