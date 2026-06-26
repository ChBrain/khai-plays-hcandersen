---
khai: order
title: "Stage BFN 360 Tredivte Aften"
language: english
license: CC-BY-NC-SA-4.0
stamp:
  owner: KAI HACKS AI
  version: v0.0.1
  date: "2026-06-26"
---

# Order: Stage BFN 360 Tredivte Aften

## Direction

The house must stage BFN 360 (_Tredivte Aften_) to establish a production in the H.C. Andersen house. The production must model maanen, manden, bjoernen, the positions (fortaeller, foerer, tamt), the pieces (laenke, tromme), the environments (torvet, kroen), the fortaelling and leg processes, and the plots representing natten and leg. It must be written in authentic Danish for all prose sections.

## Orders

1. The Playwright (Hans Christian Andersen) must author the play definition, the 3 personas, the 3 positions, the 2 pieces, the 2 places, the 2 processes, the 1 in-world plans, the pitch of humoristisk, and the 2 plots.
2. The Theatre Manager (Edvard Collin) must verify the local registry, ensure correct versioning, check formatting, and validate that the cast conforms to the canon.
3. The Roadie (Vilhelm Pedersen) must set the stage, verify the local test suite is green, and prepare the files for packaging.

## Implementation

The play files must be placed in `plays/bfn360_tredivte_aften/` and follow the house language policy:

- Structural elements and frontmatter in English.
- Narrative prose, projections, actions, shadows, tells, and staging notes in Danish.

## Targets

- [x] `plays/bfn360_tredivte_aften/play_tredivte_aften.md` is created and lists the complete company
- [x] `plays/bfn360_tredivte_aften/persona_maanen.md` is created and links to `position_fortaeller.md`
- [x] `plays/bfn360_tredivte_aften/persona_manden.md` is created and links to `position_foerer.md`
- [x] `plays/bfn360_tredivte_aften/persona_bjoernen.md` is created and links to `position_tamt.md`
- [x] `plays/bfn360_tredivte_aften/position_fortaeller.md` is created
- [x] `plays/bfn360_tredivte_aften/position_foerer.md` is created
- [x] `plays/bfn360_tredivte_aften/position_tamt.md` is created
- [x] `plays/bfn360_tredivte_aften/piece_laenke.md` is created
- [x] `plays/bfn360_tredivte_aften/piece_tromme.md` is created
- [x] `plays/bfn360_tredivte_aften/place_torvet.md` is created
- [x] `plays/bfn360_tredivte_aften/place_kroen.md` is created
- [x] `plays/bfn360_tredivte_aften/process_fortaelling.md` is created
- [x] `plays/bfn360_tredivte_aften/process_leg.md` is created
- [x] `plays/bfn360_tredivte_aften/plan_overlevelse.md` is created and linked to `persona_manden.md`
- [x] `plays/bfn360_tredivte_aften/pitch_humoristisk.md` is created
- [x] `plays/bfn360_tredivte_aften/plot_natten.md` is created and casts company elements
- [x] `plays/bfn360_tredivte_aften/plot_leg.md` is created and casts company elements
- [x] The local validation tests (`npm test`) run successfully with zero errors
