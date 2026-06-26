---
khai: order
title: "Stage BFN 345 Rosen-Alfen"
language: english
license: CC-BY-NC-SA-4.0
stamp:
  owner: KAI HACKS AI
  version: v0.0.1
  date: "2026-06-26"
---

# Order: Stage BFN 345 Rosen-Alfen

## Direction

The house must stage BFN 345 (_Rosen-Alfen_) to establish a production in the H.C. Andersen house. The production must model alfen, broderen, pigen, the positions (alf, morder, elsket), the pieces (rosenblomst, lindeblad, kniv), the environments (rosenbusk, haven), the haevn and sorg processes, and the plots representing mordet and haevnen. It must be written in authentic Danish for all prose sections.

## Orders

1. The Playwright (Hans Christian Andersen) must author the play definition, the 3 personas, the 3 positions, the 3 pieces, the 2 places, the 2 processes, the 2 in-world plans, the pitch of melankolsk, and the 2 plots.
2. The Theatre Manager (Edvard Collin) must verify the local registry, ensure correct versioning, check formatting, and validate that the cast conforms to the canon.
3. The Roadie (Vilhelm Pedersen) must set the stage, verify the local test suite is green, and prepare the files for packaging.

## Implementation

The play files must be placed in `plays/bfn345_rosen_alfen/` and follow the house language policy:

- Structural elements and frontmatter in English.
- Narrative prose, projections, actions, shadows, tells, and staging notes in Danish.

## Targets

- [x] `plays/bfn345_rosen_alfen/play_rosen_alfen.md` is created and lists the complete company
- [x] `plays/bfn345_rosen_alfen/persona_alfen.md` is created and links to `position_alf.md`
- [x] `plays/bfn345_rosen_alfen/persona_broderen.md` is created and links to `position_morder.md`
- [x] `plays/bfn345_rosen_alfen/persona_pigen.md` is created and links to `position_elsket.md`
- [x] `plays/bfn345_rosen_alfen/position_alf.md` is created
- [x] `plays/bfn345_rosen_alfen/position_morder.md` is created
- [x] `plays/bfn345_rosen_alfen/position_elsket.md` is created
- [x] `plays/bfn345_rosen_alfen/piece_rosenblomst.md` is created
- [x] `plays/bfn345_rosen_alfen/piece_lindeblad.md` is created
- [x] `plays/bfn345_rosen_alfen/piece_kniv.md` is created
- [x] `plays/bfn345_rosen_alfen/place_rosenbusk.md` is created
- [x] `plays/bfn345_rosen_alfen/place_haven.md` is created
- [x] `plays/bfn345_rosen_alfen/process_haevn.md` is created
- [x] `plays/bfn345_rosen_alfen/process_sorg.md` is created
- [x] `plays/bfn345_rosen_alfen/plan_kaerlighed.md` is created and linked to `persona_alfen.md`
- [x] `plays/bfn345_rosen_alfen/plan_haevn.md` is created and linked to `persona_alfen.md`
- [x] `plays/bfn345_rosen_alfen/pitch_melankolsk.md` is created
- [x] `plays/bfn345_rosen_alfen/plot_mordet.md` is created and casts company elements
- [x] `plays/bfn345_rosen_alfen/plot_haevnen.md` is created and casts company elements
- [x] The local validation tests (`npm test`) run successfully with zero errors
