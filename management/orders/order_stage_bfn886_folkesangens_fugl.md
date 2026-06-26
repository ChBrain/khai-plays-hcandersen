---
khai: order
title: "Stage BFN 886 Folkesangens Fugl"
language: english
license: CC-BY-NC-SA-4.0
stamp:
  owner: KAI HACKS AI
  version: v0.0.1
  date: "2026-06-26"
---

# Order: Stage BFN 886 Folkesangens Fugl

## Direction

The house must stage BFN 886 (_Folkesangens Fugl_) to establish a production in the H.C. Andersen house. The production must model fuglen, folket, the positions (bringer, lyttende), the pieces (folkesang, vinge), the environments (vandet, skoven), the sang and vaekning processes, and the plots representing flugten and sangen. It must be written in authentic Danish for all prose sections.

## Orders

1. The Playwright (Hans Christian Andersen) must author the play definition, the 2 personas, the 2 positions, the 2 pieces, the 2 places, the 2 processes, the 2 in-world plans, the pitch of poetisk, and the 2 plots.
2. The Theatre Manager (Edvard Collin) must verify the local registry, ensure correct versioning, check formatting, and validate that the cast conforms to the canon.
3. The Roadie (Vilhelm Pedersen) must set the stage, verify the local test suite is green, and prepare the files for packaging.

## Implementation

The play files must be placed in `plays/bfn886_folkesangens_fugl/` and follow the house language policy:

- Structural elements and frontmatter in English.
- Narrative prose, projections, actions, shadows, tells, and staging notes in Danish.

## Targets

- [x] `plays/bfn886_folkesangens_fugl/play_folkesangens_fugl.md` is created and lists the complete company
- [x] `plays/bfn886_folkesangens_fugl/persona_fuglen.md` is created and links to `position_bringer.md`
- [x] `plays/bfn886_folkesangens_fugl/persona_folket.md` is created and links to `position_lyttende.md`
- [x] `plays/bfn886_folkesangens_fugl/position_bringer.md` is created
- [x] `plays/bfn886_folkesangens_fugl/position_lyttende.md` is created
- [x] `plays/bfn886_folkesangens_fugl/piece_folkesang.md` is created
- [x] `plays/bfn886_folkesangens_fugl/piece_vinge.md` is created
- [x] `plays/bfn886_folkesangens_fugl/place_vandet.md` is created
- [x] `plays/bfn886_folkesangens_fugl/place_skoven.md` is created
- [x] `plays/bfn886_folkesangens_fugl/process_sang.md` is created
- [x] `plays/bfn886_folkesangens_fugl/process_vaekning.md` is created
- [x] `plays/bfn886_folkesangens_fugl/plan_erindring.md` is created and linked to `persona_fuglen.md`
- [x] `plays/bfn886_folkesangens_fugl/plan_poesi.md` is created and linked to `persona_fuglen.md`
- [x] `plays/bfn886_folkesangens_fugl/pitch_poetisk.md` is created
- [x] `plays/bfn886_folkesangens_fugl/plot_flugten.md` is created and casts company elements
- [x] `plays/bfn886_folkesangens_fugl/plot_sangen.md` is created and casts company elements
- [x] The local validation tests (`npm test`) run successfully with zero errors
