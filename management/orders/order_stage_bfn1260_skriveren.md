---
khai: order
title: "Stage BFN 1260 Skriveren"
language: english
license: CC-BY-NC-SA-4.0
stamp:
  owner: KAI HACKS AI
  version: v0.0.1
  date: "2026-06-26"
---

# Order: Stage BFN 1260 Skriveren

## Direction

The house must stage BFN 1260 (_Skriveren_) to establish a production in the H.C. Andersen house. The production must model skriveren, blaekket, the positions (kontorist, vaerktoej), the pieces (fjerpen, blaekhus), the environments (kontoret, papiret), the skrivning and forgaengelighed processes, and the plots representing kontoret and papiret. It must be written in authentic Danish for all prose sections.

## Orders

1. The Playwright (Hans Christian Andersen) must author the play definition, the 2 personas, the 2 positions, the 2 pieces, the 2 places, the 2 processes, the 1 in-world plans, the pitch of realistisk, and the 2 plots.
2. The Theatre Manager (Edvard Collin) must verify the local registry, ensure correct versioning, check formatting, and validate that the cast conforms to the canon.
3. The Roadie (Vilhelm Pedersen) must set the stage, verify the local test suite is green, and prepare the files for packaging.

## Implementation

The play files must be placed in `plays/bfn1260_skriveren/` and follow the house language policy:

- Structural elements and frontmatter in English.
- Narrative prose, projections, actions, shadows, tells, and staging notes in Danish.

## Targets

- [x] `plays/bfn1260_skriveren/play_skriveren.md` is created and lists the complete company
- [x] `plays/bfn1260_skriveren/persona_skriveren.md` is created and links to `position_kontorist.md`
- [x] `plays/bfn1260_skriveren/persona_blaekket.md` is created and links to `position_vaerktoej.md`
- [x] `plays/bfn1260_skriveren/position_kontorist.md` is created
- [x] `plays/bfn1260_skriveren/position_vaerktoej.md` is created
- [x] `plays/bfn1260_skriveren/piece_fjerpen.md` is created
- [x] `plays/bfn1260_skriveren/piece_blaekhus.md` is created
- [x] `plays/bfn1260_skriveren/place_kontoret.md` is created
- [x] `plays/bfn1260_skriveren/place_papiret.md` is created
- [x] `plays/bfn1260_skriveren/process_skrivning.md` is created
- [x] `plays/bfn1260_skriveren/process_forgaengelighed.md` is created
- [x] `plays/bfn1260_skriveren/plan_bevaring.md` is created and linked to `persona_skriveren.md`
- [x] `plays/bfn1260_skriveren/pitch_realistisk.md` is created
- [x] `plays/bfn1260_skriveren/plot_kontoret.md` is created and casts company elements
- [x] `plays/bfn1260_skriveren/plot_papiret.md` is created and casts company elements
- [x] The local validation tests (`npm test`) run successfully with zero errors
