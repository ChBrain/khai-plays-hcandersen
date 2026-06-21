---
khai: order
title: "Stage BFN 439"
language: english
license: CC-BY-NC-SA-4.0
stamp:
  owner: KAI HACKS AI
  version: v0.0.1
  date: "2026-06-20"
---

# Order: Stage BFN 439

## Direction

The house must stage BFN 439 (_Den grimme Ælling_) to establish the twenty-fourth production in the H.C. Andersen house. The production must model Ællingen, Andemoderen, Hønen_Og_Katten, Svanerne, the positions (Udstødt, Vogter, Forklarer), the pieces (Spejlbilledet, Andegaarden, Isen), the environments (Ruinemarken, Bondestuen, Søen), the persecution and transformation processes, and the plots leading to their realization. It must be written in authentic Danish for all prose sections.

## Orders

1. The Playwright (Hans Christian Andersen) must author the play definition, the four personas, the three positions, the three pieces, the three places, the two processes, the two in-world plans, the pitch of Forvandling, and the four plots.
2. The Theatre Manager (Edvard Collin) must verify the local registry, ensure correct versioning, check formatting, and validate that the entire cast conforms to the canon.
3. The Roadie (Vilhelm Pedersen) must set the stage, verify the local test suite is green, and prepare the files for packaging.

## Implementation

The play files must be placed in `plays/bfn439_grimme_aelling/` and follow the house language policy:

- Structural elements and frontmatter in English.
- Narrative prose, projections, actions, shadows, tells, and staging notes in Danish.

## Targets

- [x] `plays/bfn439_grimme_aelling/play_grimme_aelling.md` is created and lists the complete company
- [x] `plays/bfn439_grimme_aelling/persona_aellingen.md` is created and links to `position_udstoedt.md`
- [x] `plays/bfn439_grimme_aelling/persona_andemoderen.md` is created and links to `position_vogter.md`
- [x] `plays/bfn439_grimme_aelling/persona_hoenen_og_katten.md` is created and links to `position_vogter.md`
- [x] `plays/bfn439_grimme_aelling/persona_svanerne.md` is created and links to `position_forklarer.md`
- [x] `plays/bfn439_grimme_aelling/position_udstoedt.md` is created
- [x] `plays/bfn439_grimme_aelling/position_vogter.md` is created
- [x] `plays/bfn439_grimme_aelling/position_forklarer.md` is created
- [x] `plays/bfn439_grimme_aelling/piece_spejlbilledet.md` is created
- [x] `plays/bfn439_grimme_aelling/piece_andegaarden.md` is created
- [x] `plays/bfn439_grimme_aelling/piece_isen.md` is created
- [x] `plays/bfn439_grimme_aelling/place_ruinemarken.md` is created
- [x] `plays/bfn439_grimme_aelling/place_bondestuen.md` is created
- [x] `plays/bfn439_grimme_aelling/place_soeen.md` is created
- [x] `plays/bfn439_grimme_aelling/process_forfoegelse.md` is created
- [x] `plays/bfn439_grimme_aelling/process_forvandling.md` is created
- [x] `plays/bfn439_grimme_aelling/plan_aellingens_overlevelse.md` is created and linked to `persona_aellingen.md`
- [x] `plays/bfn439_grimme_aelling/plan_andegaardens_orden.md` is created and linked to `persona_andemoderen.md`
- [x] `plays/bfn439_grimme_aelling/pitch_forvandling.md` is created
- [x] `plays/bfn439_grimme_aelling/plot_andegaarden.md` is created and casts company elements
- [x] `plays/bfn439_grimme_aelling/plot_bondestuen.md` is created and casts company elements
- [x] `plays/bfn439_grimme_aelling/plot_vinterkulden.md` is created and casts company elements
- [x] `plays/bfn439_grimme_aelling/plot_svanesoeen.md` is created and casts company elements
- [x] The local validation tests (`npm test`) run successfully with zero errors
