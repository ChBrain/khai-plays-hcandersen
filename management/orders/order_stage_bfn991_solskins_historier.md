---
khai: order
title: "Stage BFN 991 Solskins-Historier"
language: english
license: CC-BY-NC-SA-4.0
stamp:
  owner: KAI HACKS AI
  version: v0.0.1
  date: "2026-06-25"
---

# Order: Stage BFN 991 Solskins-Historier

## Direction

The house must stage BFN 991 (_Solskins-Historier_) to establish the hundred and fifteenth production in the H.C. Andersen house. The production must model Solskin and Vinden, the positions (Fortællende, Forstyrrende, Modtagelig), the pieces (Solstråle, Sky), the environments (Verden, Stuen), the belysning and fortælling processes, and the plots representing the sunbeams, the wind's interruption, and the completed tale of warmth. It must be written in authentic Danish for all prose sections.

## Orders

1. The Playwright (Hans Christian Andersen) must author the play definition, the two personas, the three positions, the two pieces, the two places, the two processes, the two in-world plans, the pitch of Varme, and the three plots.
2. The Theatre Manager (Edvard Collin) must verify the local registry, ensure correct versioning, check formatting, and validate that the cast conforms to the canon.
3. The Roadie (Vilhelm Pedersen) must set the stage, verify the local test suite is green, and prepare the files for packaging.

## Implementation

The play files must be placed in `plays/bfn991_solskins_historier/` and follow the house language policy:

- Structural elements and frontmatter in English.
- Narrative prose, projections, actions, shadows, tells, and staging notes in Danish.

## Targets

- [x] `plays/bfn991_solskins_historier/play_solskins_historier.md` is created and lists the complete company
- [x] `plays/bfn991_solskins_historier/persona_solskin.md` is created and links to `position_fortaellende.md`
- [x] `plays/bfn991_solskins_historier/persona_vinden.md` is created and links to `position_forstyrrende.md`
- [x] `plays/bfn991_solskins_historier/position_fortaellende.md` is created
- [x] `plays/bfn991_solskins_historier/position_forstyrrende.md` is created
- [x] `plays/bfn991_solskins_historier/position_modtagelig.md` is created
- [x] `plays/bfn991_solskins_historier/piece_solstraale.md` is created
- [x] `plays/bfn991_solskins_historier/piece_sky.md` is created
- [x] `plays/bfn991_solskins_historier/place_verden.md` is created
- [x] `plays/bfn991_solskins_historier/place_stuen.md` is created
- [x] `plays/bfn991_solskins_historier/process_belysning.md` is created
- [x] `plays/bfn991_solskins_historier/process_fortaelling.md` is created
- [x] `plays/bfn991_solskins_historier/plan_fortaelling.md` is created and linked to `persona_solskin.md`
- [x] `plays/bfn991_solskins_historier/plan_spredning.md` is created and linked to `persona_solskin.md`
- [x] `plays/bfn991_solskins_historier/pitch_varme.md` is created
- [x] `plays/bfn991_solskins_historier/plot_solstrejf.md` is created and casts company elements
- [x] `plays/bfn991_solskins_historier/plot_afbrydelse.md` is created and casts company elements
- [x] `plays/bfn991_solskins_historier/plot_historien.md` is created and casts company elements
- [x] The local validation tests (`npm test`) run successfully with zero errors
