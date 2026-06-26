---
khai: order
title: "Stage BFN 523 Tre og tredivte Aften"
language: english
license: CC-BY-NC-SA-4.0
stamp:
  owner: KAI HACKS AI
  version: v0.0.1
  date: "2026-06-26"
---

# Order: Stage BFN 523 Tre og tredivte Aften

## Direction

The house must stage BFN 523 (_Tre og tredivte Aften_) to establish a production in the H.C. Andersen house. The production must model maanen, maleren, the positions (fortaeller, kunstner), the pieces (billedbog, skrivepen), the environments (tagkammeret, himlen), the fortaelling and afsked processes, and the plots representing natten and afskeden. It must be written in authentic Danish for all prose sections.

## Orders

1. The Playwright (Hans Christian Andersen) must author the play definition, the 2 personas, the 2 positions, the 2 pieces, the 2 places, the 2 processes, the 1 in-world plans, the pitch of melankolsk, and the 2 plots.
2. The Theatre Manager (Edvard Collin) must verify the local registry, ensure correct versioning, check formatting, and validate that the cast conforms to the canon.
3. The Roadie (Vilhelm Pedersen) must set the stage, verify the local test suite is green, and prepare the files for packaging.

## Implementation

The play files must be placed in `plays/bfn523_tre_og_tredivte_aften/` and follow the house language policy:

- Structural elements and frontmatter in English.
- Narrative prose, projections, actions, shadows, tells, and staging notes in Danish.

## Targets

- [x] `plays/bfn523_tre_og_tredivte_aften/play_tre_og_tredivte_aften.md` is created and lists the complete company
- [x] `plays/bfn523_tre_og_tredivte_aften/persona_maanen.md` is created and links to `position_fortaeller.md`
- [x] `plays/bfn523_tre_og_tredivte_aften/persona_maleren.md` is created and links to `position_kunstner.md`
- [x] `plays/bfn523_tre_og_tredivte_aften/position_fortaeller.md` is created
- [x] `plays/bfn523_tre_og_tredivte_aften/position_kunstner.md` is created
- [x] `plays/bfn523_tre_og_tredivte_aften/piece_billedbog.md` is created
- [x] `plays/bfn523_tre_og_tredivte_aften/piece_skrivepen.md` is created
- [x] `plays/bfn523_tre_og_tredivte_aften/place_tagkammeret.md` is created
- [x] `plays/bfn523_tre_og_tredivte_aften/place_himlen.md` is created
- [x] `plays/bfn523_tre_og_tredivte_aften/process_fortaelling.md` is created
- [x] `plays/bfn523_tre_og_tredivte_aften/process_afsked.md` is created
- [x] `plays/bfn523_tre_og_tredivte_aften/plan_bevaring.md` is created and linked to `persona_maleren.md`
- [x] `plays/bfn523_tre_og_tredivte_aften/pitch_melankolsk.md` is created
- [x] `plays/bfn523_tre_og_tredivte_aften/plot_natten.md` is created and casts company elements
- [x] `plays/bfn523_tre_og_tredivte_aften/plot_afskeden.md` is created and casts company elements
- [x] The local validation tests (`npm test`) run successfully with zero errors
