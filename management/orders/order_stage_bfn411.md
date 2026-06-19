---
khai: order
title: "Stage BFN 411"
language: english
license: CC-BY-NC-SA-4.0
stamp:
  owner: KAI HACKS AI
  version: v0.0.1
  date: "2026-06-20"
---

# Order: Stage BFN 411

## Direction

The house must stage BFN 411 (_Boghveden_) to establish the twentieth production in the H.C. Andersen house. The production must model Boghveden, Piletræet, Kornet, Spurven, the positions (Hovmodig, Ydmyg, Fortæller), the pieces (Lynilden, Tårerne, Tordenenglen), the environments (Ageren, Piletræets Rod, Himlen), the storm bending and scorching processes, and the plots leading to their realization. It must be written in authentic Danish for all prose sections.

## Orders

1. The Playwright (Hans Christian Andersen) must author the play definition, the four personas, the three positions, the three pieces, the three places, the two processes, the two in-world plans, the pitch of Humility, and the four plots.
2. The Theatre Manager (Edvard Collin) must verify the local registry, ensure correct versioning, check formatting, and validate that the entire cast conforms to the canon.
3. The Roadie (Vilhelm Pedersen) must set the stage, verify the local test suite is green, and prepare the files for packaging.

## Implementation

The play files must be placed in `plays/bfn411_boghveden/` and follow the house language policy:

- Structural elements and frontmatter in English.
- Narrative prose, projections, actions, shadows, tells, and staging notes in Danish.

## Targets

- [x] `plays/bfn411_boghveden/play_boghveden.md` is created and lists the complete company
- [x] `plays/bfn411_boghveden/persona_boghveden.md` is created and links to `position_hovmodig.md`
- [x] `plays/bfn411_boghveden/persona_piletraeet.md` is created and links to `position_fortaeller.md`
- [x] `plays/bfn411_boghveden/persona_kornet.md` is created and links to `position_ydmyg.md`
- [x] `plays/bfn411_boghveden/persona_spurven.md` is created and links to `position_fortaeller.md`
- [x] `plays/bfn411_boghveden/position_hovmodig.md` is created
- [x] `plays/bfn411_boghveden/position_ydmyg.md` is created
- [x] `plays/bfn411_boghveden/position_fortaeller.md` is created
- [x] `plays/bfn411_boghveden/piece_lynilden.md` is created
- [x] `plays/bfn411_boghveden/piece_taarer.md` is created
- [x] `plays/bfn411_boghveden/piece_torden_engel.md` is created
- [x] `plays/bfn411_boghveden/place_ageren.md` is created
- [x] `plays/bfn411_boghveden/place_piletraeets_rod.md` is created
- [x] `plays/bfn411_boghveden/place_himlen.md` is created
- [x] `plays/bfn411_boghveden/process_stormboejning.md` is created
- [x] `plays/bfn411_boghveden/process_forbraending.md` is created
- [x] `plays/bfn411_boghveden/plan_boghvedens_trods.md` is created and linked to `persona_boghveden.md`
- [x] `plays/bfn411_boghveden/plan_piletraeets_advarsel.md` is created and linked to `persona_piletraeet.md`
- [x] `plays/bfn411_boghveden/pitch_humility.md` is created
- [x] `plays/bfn411_boghveden/plot_rammen.md` is created and casts company elements
- [x] `plays/bfn411_boghveden/plot_advarslen.md` is created and casts company elements
- [x] `plays/bfn411_boghveden/plot_lynild.md` is created and casts company elements
- [x] `plays/bfn411_boghveden/plot_graaden.md` is created and casts company elements
- [x] The local validation tests (`npm test`) run successfully with zero errors
