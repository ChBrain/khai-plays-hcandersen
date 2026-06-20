---
khai: order
title: "Stage BFN 437"
language: english
license: CC-BY-NC-SA-4.0
stamp:
  owner: KAI HACKS AI
  version: v0.0.1
  date: "2026-06-20"
---

# Order: Stage BFN 437

## Direction

The house must stage BFN 437 (_Engelen_) to establish the twenty-first production in the H.C. Andersen house. The production must model Engelen, Barnet, Gud, the positions (Vejviser, Sjæl, Modtager), the pieces (Markblomsten, Urtepotten, Blomsterbuketten), the environments (Jordelivet, Kælderen, Himlen), the soul flight and transfiguration processes, and the plots leading to their realization. It must be written in authentic Danish for all prose sections.

## Orders

1. The Playwright (Hans Christian Andersen) must author the play definition, the three personas, the three positions, the three pieces, the three places, the two processes, the two in-world plans, the pitch of Grace, and the four plots.
2. The Theatre Manager (Edvard Collin) must verify the local registry, ensure correct versioning, check formatting, and validate that the entire cast conforms to the canon.
3. The Roadie (Vilhelm Pedersen) must set the stage, verify the local test suite is green, and prepare the files for packaging.

## Implementation

The play files must be placed in `plays/bfn437_engelen/` and follow the house language policy:

- Structural elements and frontmatter in English.
- Narrative prose, projections, actions, shadows, tells, and staging notes in Danish.

## Targets

- [x] `plays/bfn437_engelen/play_engelen.md` is created and lists the complete company
- [x] `plays/bfn437_engelen/persona_engelen.md` is created and links to `position_vejviser.md`
- [x] `plays/bfn437_engelen/persona_barnet.md` is created and links to `position_sjael.md`
- [x] `plays/bfn437_engelen/persona_gud.md` is created and links to `position_modtager.md`
- [x] `plays/bfn437_engelen/position_vejviser.md` is created
- [x] `plays/bfn437_engelen/position_sjael.md` is created
- [x] `plays/bfn437_engelen/position_modtager.md` is created
- [x] `plays/bfn437_engelen/piece_markblomsten.md` is created
- [x] `plays/bfn437_engelen/piece_urtepotten.md` is created
- [x] `plays/bfn437_engelen/piece_blomsterbuketten.md` is created
- [x] `plays/bfn437_engelen/place_jordelivet.md` is created
- [x] `plays/bfn437_engelen/place_kaelderen.md` is created
- [x] `plays/bfn437_engelen/place_himlen.md` is created
- [x] `plays/bfn437_engelen/process_sjaelevandring.md` is created
- [x] `plays/bfn437_engelen/process_forklarelse.md` is created
- [x] `plays/bfn437_engelen/plan_engels_plan.md` is created and linked to `persona_engelen.md`
- [x] `plays/bfn437_engelen/plan_barnets_erindring.md` is created and linked to `persona_barnet.md`
- [x] `plays/bfn437_engelen/pitch_grace.md` is created
- [x] `plays/bfn437_engelen/plot_opstigningen.md` is created and casts company elements
- [x] `plays/bfn437_engelen/plot_skraldedyngen.md` is created and casts company elements
- [x] `plays/bfn437_engelen/plot_drengens_skat.md` is created and casts company elements
- [x] `plays/bfn437_engelen/plot_himmelen.md` is created and casts company elements
- [x] The local validation tests (`npm test`) run successfully with zero errors
