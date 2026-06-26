---
khai: order
title: "Stage BFN 457 Een og tredivte Aften"
language: english
license: CC-BY-NC-SA-4.0
stamp:
  owner: KAI HACKS AI
  version: v0.0.1
  date: "2026-06-26"
---

# Order: Stage BFN 457 Een og tredivte Aften

## Direction

The house must stage BFN 457 (_Een og tredivte Aften_) to establish a production in the H.C. Andersen house. The production must model maanen, fangen, the positions (fortaeller, fange), the pieces (melodi, vaeg), the environments (cellen, himlen), the fortaelling and erindring processes, and the plots representing natten and cellen. It must be written in authentic Danish for all prose sections.

## Orders

1. The Playwright (Hans Christian Andersen) must author the play definition, the 2 personas, the 2 positions, the 2 pieces, the 2 places, the 2 processes, the 1 in-world plans, the pitch of melankolsk, and the 2 plots.
2. The Theatre Manager (Edvard Collin) must verify the local registry, ensure correct versioning, check formatting, and validate that the cast conforms to the canon.
3. The Roadie (Vilhelm Pedersen) must set the stage, verify the local test suite is green, and prepare the files for packaging.

## Implementation

The play files must be placed in `plays/bfn457_een_og_tredivte_aften/` and follow the house language policy:

- Structural elements and frontmatter in English.
- Narrative prose, projections, actions, shadows, tells, and staging notes in Danish.

## Targets

- [x] `plays/bfn457_een_og_tredivte_aften/play_een_og_tredivte_aften.md` is created and lists the complete company
- [x] `plays/bfn457_een_og_tredivte_aften/persona_maanen.md` is created and links to `position_fortaeller.md`
- [x] `plays/bfn457_een_og_tredivte_aften/persona_fangen.md` is created and links to `position_fange.md`
- [x] `plays/bfn457_een_og_tredivte_aften/position_fortaeller.md` is created
- [x] `plays/bfn457_een_og_tredivte_aften/position_fange.md` is created
- [x] `plays/bfn457_een_og_tredivte_aften/piece_melodi.md` is created
- [x] `plays/bfn457_een_og_tredivte_aften/piece_vaeg.md` is created
- [x] `plays/bfn457_een_og_tredivte_aften/place_cellen.md` is created
- [x] `plays/bfn457_een_og_tredivte_aften/place_himlen.md` is created
- [x] `plays/bfn457_een_og_tredivte_aften/process_fortaelling.md` is created
- [x] `plays/bfn457_een_og_tredivte_aften/process_erindring.md` is created
- [x] `plays/bfn457_een_og_tredivte_aften/plan_afsked.md` is created and linked to `persona_fangen.md`
- [x] `plays/bfn457_een_og_tredivte_aften/pitch_melankolsk.md` is created
- [x] `plays/bfn457_een_og_tredivte_aften/plot_natten.md` is created and casts company elements
- [x] `plays/bfn457_een_og_tredivte_aften/plot_cellen.md` is created and casts company elements
- [x] The local validation tests (`npm test`) run successfully with zero errors
