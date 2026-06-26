---
khai: order
title: "Stage BFN 748 Ærens Tornevei"
language: english
license: CC-BY-NC-SA-4.0
stamp:
  owner: KAI HACKS AI
  version: v0.0.1
  date: "2026-06-26"
---

# Order: Stage BFN 748 Ærens Tornevei

## Direction

The house must stage BFN 748 (_"Ærens Tornevei"_) to establish a production in the H.C. Andersen house. The production must model geniet, verden, the positions (lidende, foragtende), the pieces (torneskrift, krone), the environments (vejen, historien), the kamp and anerkendelse processes, and the plots representing vandringen and eftermaelet. It must be written in authentic Danish for all prose sections.

## Orders

1. The Playwright (Hans Christian Andersen) must author the play definition, the 2 personas, the 2 positions, the 2 pieces, the 2 places, the 2 processes, the 2 in-world plans, the pitch of alvorlig, and the 2 plots.
2. The Theatre Manager (Edvard Collin) must verify the local registry, ensure correct versioning, check formatting, and validate that the cast conforms to the canon.
3. The Roadie (Vilhelm Pedersen) must set the stage, verify the local test suite is green, and prepare the files for packaging.

## Implementation

The play files must be placed in `plays/bfn748_aerens_tornevei/` and follow the house language policy:

- Structural elements and frontmatter in English.
- Narrative prose, projections, actions, shadows, tells, and staging notes in Danish.

## Targets

- [x] `plays/bfn748_aerens_tornevei/play_aerens_tornevei.md` is created and lists the complete company
- [x] `plays/bfn748_aerens_tornevei/persona_geniet.md` is created and links to `position_lidende.md`
- [x] `plays/bfn748_aerens_tornevei/persona_verden.md` is created and links to `position_foragtende.md`
- [x] `plays/bfn748_aerens_tornevei/position_lidende.md` is created
- [x] `plays/bfn748_aerens_tornevei/position_foragtende.md` is created
- [x] `plays/bfn748_aerens_tornevei/piece_torneskrift.md` is created
- [x] `plays/bfn748_aerens_tornevei/piece_krone.md` is created
- [x] `plays/bfn748_aerens_tornevei/place_vejen.md` is created
- [x] `plays/bfn748_aerens_tornevei/place_historien.md` is created
- [x] `plays/bfn748_aerens_tornevei/process_kamp.md` is created
- [x] `plays/bfn748_aerens_tornevei/process_anerkendelse.md` is created
- [x] `plays/bfn748_aerens_tornevei/plan_skabelse.md` is created and linked to `persona_geniet.md`
- [x] `plays/bfn748_aerens_tornevei/plan_fordoemmelse.md` is created and linked to `persona_verden.md`
- [x] `plays/bfn748_aerens_tornevei/pitch_alvorlig.md` is created
- [x] `plays/bfn748_aerens_tornevei/plot_vandringen.md` is created and casts company elements
- [x] `plays/bfn748_aerens_tornevei/plot_eftermaelet.md` is created and casts company elements
- [x] The local validation tests (`npm test`) run successfully with zero errors
