---
khai: order
title: "Stage BFN 320"
language: english
license: CC-BY-NC-SA-4.0
stamp:
  owner: KAI HACKS AI
  version: v0.0.1
  date: "2026-06-17"
---

# Order: Stage BFN 320

## Direction

The house must stage BFN 320 (_Lykkens Galoscher_) to establish the tenth production in the H.C. Andersen house. The production must model the fairies, the councillor, the watchman, the copyist, the environments (the Hallway, the Past, and the Sky), the galoshes, the wish, and the birdcage pieces, the wish fulfillment and realization processes, and the plots leading to their realization. It must be written in authentic Danish for all prose sections.

## Orders

1. The Playwright (Hans Christian Andersen) must author the play definition, the four personas, the four positions, the three pieces, the three places, the two processes, the two in-world plans, and the four plots.
2. The Theatre Manager (Edvard Collin) must verify the local registry, ensure correct versioning, check formatting, and validate that the entire cast conforms to the canon.
3. The Roadie (Vilhelm Pedersen) must set the stage, verify the local test suite is green, and prepare the files for packaging.

## Implementation

The play files must be placed in `plays/bfn320_lykkens_galoscher/` and follow the house language policy:

- Structural elements and frontmatter in English.
- Narrative prose, projections, actions, shadows, tells, and staging notes in Danish.

## Targets

- [x] `plays/bfn320_lykkens_galoscher/play_galoscherne.md` is created and lists the complete company
- [x] `plays/bfn320_lykkens_galoscher/persona_feerne.md` is created and links to `position_skaebne.md`
- [x] `plays/bfn320_lykkens_galoscher/persona_knap.md` is created and links to `position_nostalgiker.md`
- [x] `plays/bfn320_lykkens_galoscher/persona_vaegteren.md` is created and links to `position_droemmer.md`
- [x] `plays/bfn320_lykkens_galoscher/persona_kopisten.md` is created and links to `position_digter.md`
- [x] `plays/bfn320_lykkens_galoscher/position_skaebne.md` is created
- [x] `plays/bfn320_lykkens_galoscher/position_nostalgiker.md` is created
- [x] `plays/bfn320_lykkens_galoscher/position_droemmer.md` is created
- [x] `plays/bfn320_lykkens_galoscher/position_digter.md` is created
- [x] `plays/bfn320_lykkens_galoscher/piece_galoscherne.md` is created
- [x] `plays/bfn320_lykkens_galoscher/piece_oensket.md` is created
- [x] `plays/bfn320_lykkens_galoscher/piece_fugleburet.md` is created
- [x] `plays/bfn320_lykkens_galoscher/place_hallen.md` is created
- [x] `plays/bfn320_lykkens_galoscher/place_fortiden.md` is created
- [x] `plays/bfn320_lykkens_galoscher/place_himlen.md` is created
- [x] `plays/bfn320_lykkens_galoscher/process_oenskeopfyldelse.md` is created
- [x] `plays/bfn320_lykkens_galoscher/process_erkendelse.md` is created
- [x] `plays/bfn320_lykkens_galoscher/plan_feernes_plan.md` is created and linked to `persona_feerne.md`
- [x] `plays/bfn320_lykkens_galoscher/plan_menneskets_plan.md` is created and linked to `persona_knap.md`
- [x] `plays/bfn320_lykkens_galoscher/plot_feernes_gave.md` is created and casts company elements
- [x] `plays/bfn320_lykkens_galoscher/plot_historien.md` is created and casts company elements
- [x] `plays/bfn320_lykkens_galoscher/plot_maanen.md` is created and casts company elements
- [x] `plays/bfn320_lykkens_galoscher/plot_digteren.md` is created and casts company elements
- [x] The local validation tests (`npm test`) run successfully with zero errors
