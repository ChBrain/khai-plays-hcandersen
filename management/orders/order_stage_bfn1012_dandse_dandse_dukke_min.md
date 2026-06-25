---
khai: order
title: "Stage BFN 1012 Dandse dandse Dukke min"
language: english
license: CC-BY-NC-SA-4.0
stamp:
  owner: KAI HACKS AI
  version: v0.0.1
  date: "2026-06-25"
---

# Order: Stage BFN 1012 Dandse dandse Dukke min

## Direction

The house must stage BFN 1012 (_Dandse, dandse Dukke min!_) to establish the hundred and twenty-fourth production in the H.C. Andersen house. The production must model little Amalie and Tante (Aunt Malle), their positions (Legende, Forstokket), the pieces representing the doll (Dukke) and the song/verse (Vise), the environments of the parlor (Stuen) and the school (Skolen), the processes of play (Leg) and understanding (Forstaaelse), their plans of play (Leg) and discipline (Disciplin), the child-like pitch, and the plots representing the play and the aunt's intervention. It must be written in authentic Danish for all prose sections.

## Orders

1. The Playwright (Hans Christian Andersen) must author the play definition, the two personas, the two positions, the two pieces, the two places, the two processes, the two in-world plans, the pitch of Barnlig, and the two plots.
2. The Theatre Manager (Edvard Collin) must verify the local registry, ensure correct versioning, check formatting, and validate that the cast conforms to the canon.
3. The Roadie (Vilhelm Pedersen) must set the stage, verify the local test suite is green, and prepare the files for packaging.

## Implementation

The play files must be placed in `plays/bfn1012_dandse_dandse_dukke_min/` and follow the house language policy:

- Structural elements and frontmatter in English.
- Narrative prose, projections, actions, shadows, tells, and staging notes in Danish.

## Targets

- [x] `plays/bfn1012_dandse_dandse_dukke_min/play_dandse_dandse_dukke_min.md` is created and lists the complete company
- [x] `plays/bfn1012_dandse_dandse_dukke_min/persona_amalie.md` is created and links to `position_legende.md`
- [x] `plays/bfn1012_dandse_dandse_dukke_min/persona_tante.md` is created and links to `position_forstokket.md`
- [x] `plays/bfn1012_dandse_dandse_dukke_min/position_legende.md` is created
- [x] `plays/bfn1012_dandse_dandse_dukke_min/position_forstokket.md` is created
- [x] `plays/bfn1012_dandse_dandse_dukke_min/piece_dukke.md` is created
- [x] `plays/bfn1012_dandse_dandse_dukke_min/piece_vise.md` is created
- [x] `plays/bfn1012_dandse_dandse_dukke_min/place_stuen.md` is created
- [x] `plays/bfn1012_dandse_dandse_dukke_min/place_skolen.md` is created
- [x] `plays/bfn1012_dandse_dandse_dukke_min/process_leg.md` is created
- [x] `plays/bfn1012_dandse_dandse_dukke_min/process_forstaaelse.md` is created
- [x] `plays/bfn1012_dandse_dandse_dukke_min/plan_leg.md` is created and linked to `persona_amalie.md`
- [x] `plays/bfn1012_dandse_dandse_dukke_min/plan_disciplin.md` is created and linked to `persona_tante.md`
- [x] `plays/bfn1012_dandse_dandse_dukke_min/pitch_barnlig.md` is created
- [x] `plays/bfn1012_dandse_dandse_dukke_min/plot_legen.md` is created and casts company elements
- [x] `plays/bfn1012_dandse_dandse_dukke_min/plot_tanten.md` is created and casts company elements
- [x] The local validation tests (`npm test`) run successfully with zero errors
