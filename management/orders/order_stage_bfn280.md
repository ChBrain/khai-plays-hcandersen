---
khai: order
title: "Stage BFN 280"
language: english
license: CC-BY-NC-SA-4.0
stamp:
  owner: KAI HACKS AI
  version: v0.0.1
  date: "2026-06-17"
---

# Order: Stage BFN 280

## Direction

The house must stage BFN 280 (_Den uartige Dreng_) to establish the sixth production in the H.C. Andersen house. The production must model the poet, Cupid (Amor), the environments (poet's room), the bow and stove pieces, the warming and shooting processes, and the plots leading to Cupid's mischievous attacks on all social classes. It must be written in authentic Danish for all prose sections.

## Orders

1. The Playwright (Hans Christian Andersen) must author the play definition, the two personas (Digteren, Amor), the two positions (kunstner, lokkedue), the two pieces (buen, kakkelovnen), the one place (stuen), the two processes (varme, beskydning), the two in-world plans (digterens plan, amors plan), and the four plots.
2. The Theatre Manager (Edvard Collin) must verify the local registry, ensure correct versioning, check formatting, and validate that the entire cast conforms to the canon.
3. The Roadie (Vilhelm Pedersen) must set the stage, verify the local test suite is green, and prepare the files for packaging.

## Implementation

The play files must be placed in `plays/bfn280_den_uartige_dreng/` and follow the house language policy:

- Structural elements and frontmatter in English.
- Narrative prose, projections, actions, shadows, tells, and staging notes in Danish.

## Targets

- [x] `plays/bfn280_den_uartige_dreng/play_uartige_dreng.md` is created and lists the complete company
- [x] `plays/bfn280_den_uartige_dreng/persona_digteren.md` is created and links to `position_kunstner.md`
- [x] `plays/bfn280_den_uartige_dreng/persona_amor.md` is created and links to `position_lokkedue.md`
- [x] `plays/bfn280_den_uartige_dreng/position_kunstner.md` is created
- [x] `plays/bfn280_den_uartige_dreng/position_lokkedue.md` is created
- [x] `plays/bfn280_den_uartige_dreng/piece_buen.md` is created
- [x] `plays/bfn280_den_uartige_dreng/piece_kakkelovnen.md` is created
- [x] `plays/bfn280_den_uartige_dreng/place_stuen.md` is created
- [x] `plays/bfn280_den_uartige_dreng/process_varme.md` is created
- [x] `plays/bfn280_den_uartige_dreng/process_beskydning.md` is created
- [x] `plays/bfn280_den_uartige_dreng/plan_digterens_plan.md` is created and linked to `persona_digteren.md`
- [x] `plays/bfn280_den_uartige_dreng/plan_amors_plan.md` is created and linked to `persona_amor.md`
- [x] `plays/bfn280_den_uartige_dreng/plot_stormen.md` is created and casts company elements
- [x] `plays/bfn280_den_uartige_dreng/plot_varmen.md` is created and casts company elements
- [x] `plays/bfn280_den_uartige_dreng/plot_skuddet.md` is created and casts company elements
- [x] `plays/bfn280_den_uartige_dreng/plot_forfoegelsen.md` is created and casts company elements
- [x] The local validation tests (`npm test`) run successfully with zero errors
