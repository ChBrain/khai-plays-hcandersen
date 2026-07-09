---
khai: order
title: "Stage SDU 610"
language: english
license: CC-BY-NC-SA-4.0
stamp:
  owner: KAI HACKS AI
  version: v0.0.1
  date: "2026-07-09"
---

# Order: Stage SDU 610

## Direction

The house must stage SDU 610 (_Festen paa Kenilworth_) to establish the tenth work in the "Drama" genre. The production must model the romantic syngespil, featuring Emmy Robsart, Grev Leicester, and Dronning Elisabeth. It must model the places Cumnor Hall and Kenilworth Castle, the piece representing the loyalty ring, the processes representing intrigue and court life, the plan for disclosure, the romantic/ambitious tenor, and the three plots. All staging, prose, projections, actions, shadows, and tells must be authored in authentic Danish.

## Orders

1. The Playwright (Hans Christian Andersen) must author the play definition, the three personas (emmy, leicester, elisabeth), the three positions (gemal, hofmand, monark), the one piece (troskabsring), the two places (cumnor, kenilworth), the two processes (intrige, hofliv), the in-world plan (afsloering), the pitch (romantisk), and the three plots.
2. The Theatre Manager (Edvard Collin) must verify the local registry, ensure correct versioning, check formatting, and validate that the entire cast conforms to the canon.
3. The Roadie (Vilhelm Pedersen) must set the stage, verify the local test suite is green, and prepare the files for packaging.

## Implementation

The play files must be placed in `plays/sdu610_kenilworth/` and follow the house language policy:

- Structural elements and frontmatter in English.
- Narrative prose, projections, actions, shadows, tells, and staging notes in Danish.

## Targets

- [x] `plays/sdu610_kenilworth/play_kenilworth.md` is created and lists the complete company
- [x] `plays/sdu610_kenilworth/persona_emmy.md` is created and links to `position_gemal.md`
- [x] `plays/sdu610_kenilworth/persona_leicester.md` is created and links to `position_hofmand.md`
- [x] `plays/sdu610_kenilworth/persona_elisabeth.md` is created and links to `position_monark.md`
- [x] `plays/sdu610_kenilworth/position_gemal.md` is created
- [x] `plays/sdu610_kenilworth/position_hofmand.md` is created
- [x] `plays/sdu610_kenilworth/position_monark.md` is created
- [x] `plays/sdu610_kenilworth/piece_troskabsring.md` is created
- [x] `plays/sdu610_kenilworth/place_cumnor.md` is created
- [x] `plays/sdu610_kenilworth/place_kenilworth.md` is created
- [x] `plays/sdu610_kenilworth/process_intrige.md` is created
- [x] `plays/sdu610_kenilworth/process_hofliv.md` is created
- [x] `plays/sdu610_kenilworth/plan_afsloering.md` is created
- [x] `plays/sdu610_kenilworth/pitch_romantisk.md` is created
- [x] `plays/sdu610_kenilworth/plot_hemmeligheden.md` is created and casts company elements
- [x] `plays/sdu610_kenilworth/plot_festen.md` is created and casts company elements
- [x] `plays/sdu610_kenilworth/plot_forloesningen.md` is created and casts company elements
- [x] The local validation tests (`npm test`) run successfully with zero errors
