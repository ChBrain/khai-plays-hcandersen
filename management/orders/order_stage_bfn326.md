---
khai: order
title: "Stage BFN 326"
language: english
license: CC-BY-NC-SA-4.0
stamp:
  owner: KAI HACKS AI
  version: v0.0.1
  date: "2026-06-17"
---

# Order: Stage BFN 326

## Direction

The house must stage BFN 326 (_Gåseurten_) to establish the eleventh production in the H.C. Andersen house. The production must model the daisy, the lark, the proud flowers, the boys, the environments (the Ditch, the Garden, and the Room), the turf, the cage, and the water cup pieces, the captivity and empathy processes, and the plots leading to their realization. It must be written in authentic Danish for all prose sections.

## Orders

1. The Playwright (Hans Christian Andersen) must author the play definition, the four personas, the four positions, the three pieces, the three places, the two processes, the two in-world plans, and the four plots.
2. The Theatre Manager (Edvard Collin) must verify the local registry, ensure correct versioning, check formatting, and validate that the entire cast conforms to the canon.
3. The Roadie (Vilhelm Pedersen) must set the stage, verify the local test suite is green, and prepare the files for packaging.

## Implementation

The play files must be placed in `plays/bfn326_gaaseurten/` and follow the house language policy:

- Structural elements and frontmatter in English.
- Narrative prose, projections, actions, shadows, tells, and staging notes in Danish.

## Targets

- [x] `plays/bfn326_gaaseurten/play_gaaseurten.md` is created and lists the complete company
- [x] `plays/bfn326_gaaseurten/persona_gaaseurten.md` is created and links to `position_ydmyg.md`
- [x] `plays/bfn326_gaaseurten/persona_laerken.md` is created and links to `position_fri.md`
- [x] `plays/bfn326_gaaseurten/persona_blomsterne.md` is created and links to `position_hovmodig.md`
- [x] `plays/bfn326_gaaseurten/persona_drengene.md` is created and links to `position_fangevogter.md`
- [x] `plays/bfn326_gaaseurten/position_ydmyg.md` is created
- [x] `plays/bfn326_gaaseurten/position_fri.md` is created
- [x] `plays/bfn326_gaaseurten/position_hovmodig.md` is created
- [x] `plays/bfn326_gaaseurten/position_fangevogter.md` is created
- [x] `plays/bfn326_gaaseurten/piece_graestoerv.md` is created
- [x] `plays/bfn326_gaaseurten/piece_fuglebur.md` is created
- [x] `plays/bfn326_gaaseurten/piece_vandkop.md` is created
- [x] `plays/bfn326_gaaseurten/place_groftkant.md` is created
- [x] `plays/bfn326_gaaseurten/place_haven.md` is created
- [x] `plays/bfn326_gaaseurten/place_stuen.md` is created
- [x] `plays/bfn326_gaaseurten/process_fangenskab.md` is created
- [x] `plays/bfn326_gaaseurten/process_medfoelse.md` is created
- [x] `plays/bfn326_gaaseurten/plan_gaaseurtens_plan.md` is created and linked to `persona_gaaseurten.md`
- [x] `plays/bfn326_gaaseurten/plan_drengenes_plan.md` is created and linked to `persona_drengene.md`
- [x] `plays/bfn326_gaaseurten/plot_moedet.md` is created and casts company elements
- [x] `plays/bfn326_gaaseurten/plot_fangenskabet.md` is created and casts company elements
- [x] `plays/bfn326_gaaseurten/plot_toerven.md` is created and casts company elements
- [x] `plays/bfn326_gaaseurten/plot_doeden.md` is created and casts company elements
- [x] The local validation tests (`npm test`) run successfully with zero errors
