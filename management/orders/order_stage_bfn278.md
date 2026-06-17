---
khai: order
title: "Stage BFN 278"
language: english
license: CC-BY-NC-SA-4.0
stamp:
  owner: KAI HACKS AI
  version: v0.0.1
  date: "2026-06-17"
---

# Order: Stage BFN 278

## Direction

The house must stage BFN 278 (_Tommelise_) to establish the fifth production in the H.C. Andersen house. The production must model Tommelise, the toad, the May bug (Oldenborre), the field mouse, the mole, the swallow, the environments (swamp, underworld, and flower country), the walnut shell, lily leaf, and flower crown pieces, the captivity and escape processes, and the plots leading to her escape to the flower country. It must be written in authentic Danish for all prose sections.

## Orders

1. The Playwright (Hans Christian Andersen) must author the play definition, the five personas (Tommelise, Skrubtudsen, Oldenborren, Markmusen, Svalen), the five positions (flygtning, fangevogter, kritiker, vaert, hjaelper), the three pieces (valnoedskallen, aakandebladet, blomsterkronen), the three places (sumpen, muldvarpehullet, blomsterlandet), the two processes (fangenskab, flugt), the two in-world plans (tommelises plan, markmusens plan), and the four plots.
2. The Theatre Manager (Edvard Collin) must verify the local registry, ensure correct versioning, check formatting, and validate that the entire cast conforms to the canon.
3. The Roadie (Vilhelm Pedersen) must set the stage, verify the local test suite is green, and prepare the files for packaging.

## Implementation

The play files must be placed in `plays/bfn278_tommelise/` and follow the house language policy:

- Structural elements and frontmatter in English.
- Narrative prose, projections, actions, shadows, tells, and staging notes in Danish.

## Targets

- [x] `plays/bfn278_tommelise/play_tommelise.md` is created and lists the complete company
- [x] `plays/bfn278_tommelise/persona_tommelise.md` is created and links to `position_flygtning.md`
- [x] `plays/bfn278_tommelise/persona_skrubtudsen.md` is created and links to `position_fangevogter.md`
- [x] `plays/bfn278_tommelise/persona_oldenborren.md` is created and links to `position_kritiker.md`
- [x] `plays/bfn278_tommelise/persona_markmusen.md` is created and links to `position_vaert.md`
- [x] `plays/bfn278_tommelise/persona_svalen.md` is created and links to `position_hjaelper.md`
- [x] `plays/bfn278_tommelise/position_flygtning.md` is created
- [x] `plays/bfn278_tommelise/position_fangevogter.md` is created
- [x] `plays/bfn278_tommelise/position_kritiker.md` is created
- [x] `plays/bfn278_tommelise/position_vaert.md` is created
- [x] `plays/bfn278_tommelise/position_hjaelper.md` is created
- [x] `plays/bfn278_tommelise/piece_valnoedskallen.md` is created
- [x] `plays/bfn278_tommelise/piece_aakandebladet.md` is created
- [x] `plays/bfn278_tommelise/piece_blomsterkronen.md` is created
- [x] `plays/bfn278_tommelise/place_sumpen.md` is created
- [x] `plays/bfn278_tommelise/place_muldvarpehullet.md` is created
- [x] `plays/bfn278_tommelise/place_blomsterlandet.md` is created
- [x] `plays/bfn278_tommelise/process_fangenskab.md` is created
- [x] `plays/bfn278_tommelise/process_flugt.md` is created
- [x] `plays/bfn278_tommelise/plan_tommelises_plan.md` is created and linked to `persona_tommelise.md`
- [x] `plays/bfn278_tommelise/plan_markmusens_plan.md` is created and linked to `persona_markmusen.md`
- [x] `plays/bfn278_tommelise/plot_tudserne.md` is created and casts company elements
- [x] `plays/bfn278_tommelise/plot_oldenborren.md` is created and casts company elements
- [x] `plays/bfn278_tommelise/plot_muldvarpen.md` is created and casts company elements
- [x] `plays/bfn278_tommelise/plot_svaleflugt.md` is created and casts company elements
- [x] The local validation tests (`npm test`) run successfully with zero errors
