---
khai: order
title: "Stage BFN 327"
language: english
license: CC-BY-NC-SA-4.0
stamp:
  owner: KAI HACKS AI
  version: v0.0.1
  date: "2026-06-17"
---

# Order: Stage BFN 327

## Direction

The house must stage BFN 327 (_Den standhaftige Tinsoldat_) to establish the twelfth production in the H.C. Andersen house. The production must model the tin soldier, the paper dancer, the snuffbox goblin, the boy, the positions (Steadfast, Artist, Tormentor, Owner), the pieces (Tin Soldier, Paper Dancer, Snuffbox), the environments (Nursery, Gutter, Stove), the trial and incineration processes, and the plots leading to their realization. It must be written in authentic Danish for all prose sections.

## Orders

1. The Playwright (Hans Christian Andersen) must author the play definition, the four personas, the four positions, the three pieces, the three places, the two processes, the two in-world plans, and the four plots.
2. The Theatre Manager (Edvard Collin) must verify the local registry, ensure correct versioning, check formatting, and validate that the entire cast conforms to the canon.
3. The Roadie (Vilhelm Pedersen) must set the stage, verify the local test suite is green, and prepare the files for packaging.

## Implementation

The play files must be placed in `plays/bfn327_tinsoldaten/` and follow the house language policy:

- Structural elements and frontmatter in English.
- Narrative prose, projections, actions, shadows, tells, and staging notes in Danish.

## Targets

- [x] `plays/bfn327_tinsoldaten/play_tinsoldaten.md` is created and lists the complete company
- [x] `plays/bfn327_tinsoldaten/persona_soldaten.md` is created and links to `position_standhaftig.md`
- [x] `plays/bfn327_tinsoldaten/persona_danserinden.md` is created and links to `position_kunstner.md`
- [x] `plays/bfn327_tinsoldaten/persona_trolden.md` is created and links to `position_plageaand.md`
- [x] `plays/bfn327_tinsoldaten/persona_drengen.md` is created and links to `position_ejer.md`
- [x] `plays/bfn327_tinsoldaten/position_standhaftig.md` is created
- [x] `plays/bfn327_tinsoldaten/position_kunstner.md` is created
- [x] `plays/bfn327_tinsoldaten/position_plageaand.md` is created
- [x] `plays/bfn327_tinsoldaten/position_ejer.md` is created
- [x] `plays/bfn327_tinsoldaten/piece_tinsoldat.md` is created
- [x] `plays/bfn327_tinsoldaten/piece_papirdanserinde.md` is created
- [x] `plays/bfn327_tinsoldaten/piece_troldaeske.md` is created
- [x] `plays/bfn327_tinsoldaten/place_boernevaerelse.md` is created
- [x] `plays/bfn327_tinsoldaten/place_rendensten.md` is created
- [x] `plays/bfn327_tinsoldaten/place_kakkelovn.md` is created
- [x] `plays/bfn327_tinsoldaten/process_proevelse.md` is created
- [x] `plays/bfn327_tinsoldaten/process_forbraending.md` is created
- [x] `plays/bfn327_tinsoldaten/plan_soldatens_plan.md` is created and linked to `persona_soldaten.md`
- [x] `plays/bfn327_tinsoldaten/plan_troldens_plan.md` is created and linked to `persona_trolden.md`
- [x] `plays/bfn327_tinsoldaten/plot_legetoejet.md` is created and casts company elements
- [x] `plays/bfn327_tinsoldaten/plot_sejladsen.md` is created and casts company elements
- [x] `plays/bfn327_tinsoldaten/plot_hjemkomsten.md` is created and casts company elements
- [x] `plays/bfn327_tinsoldaten/plot_flammerne.md` is created and casts company elements
- [x] The local validation tests (`npm test`) run successfully with zero errors
