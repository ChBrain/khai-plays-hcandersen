---
khai: order
title: "Stage BFN 360 Femte Aften"
language: english
license: CC-BY-NC-SA-4.0
stamp:
  owner: KAI HACKS AI
  version: v0.0.1
  date: "2026-06-26"
---

# Order: Stage BFN 360 Femte Aften

## Direction

The house must stage BFN 360 (_Femte Aften_) to establish a production in the H.C. Andersen house. The production must model maanen, pigen, the positions (fortaeller, afskedig), the pieces (skib, brev), the environments (havnen, dækket), the fortaelling and afsked processes, and the plots representing natten and kajen. It must be written in authentic Danish for all prose sections.

## Orders

1. The Playwright (Hans Christian Andersen) must author the play definition, the 2 personas, the 2 positions, the 2 pieces, the 2 places, the 2 processes, the 1 in-world plans, the pitch of tragisk, and the 2 plots.
2. The Theatre Manager (Edvard Collin) must verify the local registry, ensure correct versioning, check formatting, and validate that the cast conforms to the canon.
3. The Roadie (Vilhelm Pedersen) must set the stage, verify the local test suite is green, and prepare the files for packaging.

## Implementation

The play files must be placed in `plays/bfn360_femte_aften/` and follow the house language policy:

- Structural elements and frontmatter in English.
- Narrative prose, projections, actions, shadows, tells, and staging notes in Danish.

## Targets

- [x] `plays/bfn360_femte_aften/play_femte_aften.md` is created and lists the complete company
- [x] `plays/bfn360_femte_aften/persona_maanen.md` is created and links to `position_fortaeller.md`
- [x] `plays/bfn360_femte_aften/persona_pigen.md` is created and links to `position_afskedig.md`
- [x] `plays/bfn360_femte_aften/position_fortaeller.md` is created
- [x] `plays/bfn360_femte_aften/position_afskedig.md` is created
- [x] `plays/bfn360_femte_aften/piece_skib.md` is created
- [x] `plays/bfn360_femte_aften/piece_brev.md` is created
- [x] `plays/bfn360_femte_aften/place_havnen.md` is created
- [x] `plays/bfn360_femte_aften/place_dækket.md` is created
- [x] `plays/bfn360_femte_aften/process_fortaelling.md` is created
- [x] `plays/bfn360_femte_aften/process_afsked.md` is created
- [x] `plays/bfn360_femte_aften/plan_erindring.md` is created and linked to `persona_pigen.md`
- [x] `plays/bfn360_femte_aften/pitch_tragisk.md` is created
- [x] `plays/bfn360_femte_aften/plot_natten.md` is created and casts company elements
- [x] `plays/bfn360_femte_aften/plot_kajen.md` is created and casts company elements
- [x] The local validation tests (`npm test`) run successfully with zero errors
