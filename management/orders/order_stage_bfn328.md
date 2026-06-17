---
khai: order
title: "Stage BFN 328"
language: english
license: CC-BY-NC-SA-4.0
stamp:
  owner: KAI HACKS AI
  version: v0.0.1
  date: "2026-06-17"
---

# Order: Stage BFN 328

## Direction

The house must stage BFN 328 (_De vilde Svaner_) to establish the thirteenth production in the H.C. Andersen house. The production must model Elisa, the brothers, the queen, the king, the positions (Silent, Cursed, Witch, Judge), the pieces (Nettle Shirts, Nettles, Stake), the environments (King's Castle, Cave, Churchyard), the knitting and redemption processes, and the plots leading to their realization. It must be written in authentic Danish for all prose sections.

## Orders

1. The Playwright (Hans Christian Andersen) must author the play definition, the four personas, the four positions, the three pieces, the three places, the two processes, the two in-world plans, and the four plots.
2. The Theatre Manager (Edvard Collin) must verify the local registry, ensure correct versioning, check formatting, and validate that the entire cast conforms to the canon.
3. The Roadie (Vilhelm Pedersen) must set the stage, verify the local test suite is green, and prepare the files for packaging.

## Implementation

The play files must be placed in `plays/bfn328_svanerne/` and follow the house language policy:

- Structural elements and frontmatter in English.
- Narrative prose, projections, actions, shadows, tells, and staging notes in Danish.

## Targets

- [x] `plays/bfn328_svanerne/play_svanerne.md` is created and lists the complete company
- [x] `plays/bfn328_svanerne/persona_elisa.md` is created and links to `position_tavs.md`
- [x] `plays/bfn328_svanerne/persona_broedrene.md` is created and links to `position_forbandet.md`
- [x] `plays/bfn328_svanerne/persona_dronningen.md` is created and links to `position_heks.md`
- [x] `plays/bfn328_svanerne/persona_kongen.md` is created and links to `position_dommer.md`
- [x] `plays/bfn328_svanerne/position_tavs.md` is created
- [x] `plays/bfn328_svanerne/position_forbandet.md` is created
- [x] `plays/bfn328_svanerne/position_heks.md` is created
- [x] `plays/bfn328_svanerne/position_dommer.md` is created
- [x] `plays/bfn328_svanerne/piece_naeldeskjorter.md` is created
- [x] `plays/bfn328_svanerne/piece_braendenaelder.md` is created
- [x] `plays/bfn328_svanerne/piece_baalet.md` is created
- [x] `plays/bfn328_svanerne/place_kongeslottet.md` is created
- [x] `plays/bfn328_svanerne/place_grotten.md` is created
- [x] `plays/bfn328_svanerne/place_kirkegaarden.md` is created
- [x] `plays/bfn328_svanerne/process_strikning.md` is created
- [x] `plays/bfn328_svanerne/process_forloesning.md` is created
- [x] `plays/bfn328_svanerne/plan_elisas_plan.md` is created and linked to `persona_elisa.md`
- [x] `plays/bfn328_svanerne/plan_dronningens_plan.md` is created and linked to `persona_dronningen.md`
- [x] `plays/bfn328_svanerne/plot_forbandelsen.md` is created and casts company elements
- [x] `plays/bfn328_svanerne/plot_moedet.md` is created and casts company elements
- [x] `plays/bfn328_svanerne/plot_arbejdet.md` is created and casts company elements
- [x] `plays/bfn328_svanerne/plot_redningen.md` is created and casts company elements
- [x] The local validation tests (`npm test`) run successfully with zero errors
