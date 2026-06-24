---
khai: order
title: "Stage BFN 890 I Boernestuen"
language: english
license: CC-BY-NC-SA-4.0
stamp:
  owner: KAI HACKS AI
  version: v0.0.1
  date: "2026-06-24"
---

# Order: Stage BFN 890 I Boernestuen

## Direction

The house must stage BFN 890 (_I Børnestuen_) to establish the ninety-sixth production in the H.C. Andersen house. The production must model Gudfader, Barn, the positions (Fortæller, Tilskuer), the piece (Handske), the environments (Børnestue, Teatersal), the dramatisering and leg processes, and the plots leading to their realization. It must be written in authentic Danish for all prose sections.

## Orders

1. The Playwright (Hans Christian Andersen) must author the play definition, the two personas, the two positions, the piece, the two places, the two processes, the two in-world plans, the pitch of Teaterglæde, and the four plots.
2. The Theatre Manager (Edvard Collin) must verify the local registry, ensure correct versioning, check formatting, and validate that the cast conforms to the canon.
3. The Roadie (Vilhelm Pedersen) must set the stage, verify the local test suite is green, and prepare the files for packaging.

## Implementation

The play files must be placed in `plays/bfn890_i_boernestuen/` and follow the house language policy:

- Structural elements and frontmatter in English.
- Narrative prose, projections, actions, shadows, tells, and staging notes in Danish.

## Targets

- [x] `plays/bfn890_i_boernestuen/play_i_boernestuen.md` is created and lists the complete company
- [x] `plays/bfn890_i_boernestuen/persona_gudfader.md` is created and links to `position_fortaeller.md`
- [x] `plays/bfn890_i_boernestuen/persona_barn.md` is created and links to `position_tilskuer.md`
- [x] `plays/bfn890_i_boernestuen/position_fortaeller.md` is created
- [x] `plays/bfn890_i_boernestuen/position_tilskuer.md` is created
- [x] `plays/bfn890_i_boernestuen/piece_handske.md` is created
- [x] `plays/bfn890_i_boernestuen/place_boernestue.md` is created
- [x] `plays/bfn890_i_boernestuen/place_teatersal.md` is created
- [x] `plays/bfn890_i_boernestuen/process_dramatisering.md` is created
- [x] `plays/bfn890_i_boernestuen/process_leg.md` is created
- [x] `plays/bfn890_i_boernestuen/plan_forestilling.md` is created and linked to `persona_gudfader.md`
- [x] `plays/bfn890_i_boernestuen/plan_undervisning.md` is created and linked to `persona_barn.md`
- [x] `plays/bfn890_i_boernestuen/pitch_teaterglaede.md` is created
- [x] `plays/bfn890_i_boernestuen/plot_ensomheden.md` is created and casts company elements
- [x] `plays/bfn890_i_boernestuen/plot_teaterlegen.md` is created and casts company elements
- [x] `plays/bfn890_i_boernestuen/plot_komedien.md` is created and casts company elements
- [x] `plays/bfn890_i_boernestuen/plot_afslutningen.md` is created and casts company elements
- [x] The local validation tests (`npm test`) run successfully with zero errors
