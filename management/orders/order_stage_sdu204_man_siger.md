---
khai: order
title: "Stage SDU 204 Man siger -! "
language: english
license: CC-BY-NC-SA-4.0
stamp:
  owner: KAI HACKS AI
  version: v0.0.1
  date: "2026-06-26"
---

# Order: Stage SDU 204 Man siger -! 

## Direction

The house must stage SDU 204 (_"Man siger -"! _) to establish a production in the H.C. Andersen house. The production must model rygtet, borgeren, the positions (spreder, modtager), the pieces (avis, hvisken), the environments (byen, torvet), the rygtedannelse and misforstaaelse processes, and the plots representing torvet and avisen. It must be written in authentic Danish for all prose sections.

## Orders

1. The Playwright (Hans Christian Andersen) must author the play definition, the 2 personas, the 2 positions, the 2 pieces, the 2 places, the 2 processes, the 1 in-world plans, the pitch of satirisk, and the 2 plots.
2. The Theatre Manager (Edvard Collin) must verify the local registry, ensure correct versioning, check formatting, and validate that the cast conforms to the canon.
3. The Roadie (Vilhelm Pedersen) must set the stage, verify the local test suite is green, and prepare the files for packaging.

## Implementation

The play files must be placed in `plays/sdu204_man_siger/` and follow the house language policy:

- Structural elements and frontmatter in English.
- Narrative prose, projections, actions, shadows, tells, and staging notes in Danish.

## Targets

- [x] `plays/sdu204_man_siger/play_man_siger.md` is created and lists the complete company
- [x] `plays/sdu204_man_siger/persona_rygtet.md` is created and links to `position_spreder.md`
- [x] `plays/sdu204_man_siger/persona_borgeren.md` is created and links to `position_modtager.md`
- [x] `plays/sdu204_man_siger/position_spreder.md` is created
- [x] `plays/sdu204_man_siger/position_modtager.md` is created
- [x] `plays/sdu204_man_siger/piece_avis.md` is created
- [x] `plays/sdu204_man_siger/piece_hvisken.md` is created
- [x] `plays/sdu204_man_siger/place_byen.md` is created
- [x] `plays/sdu204_man_siger/place_torvet.md` is created
- [x] `plays/sdu204_man_siger/process_rygtedannelse.md` is created
- [x] `plays/sdu204_man_siger/process_misforstaaelse.md` is created
- [x] `plays/sdu204_man_siger/plan_afsloering.md` is created and linked to `persona_borgeren.md`
- [x] `plays/sdu204_man_siger/pitch_satirisk.md` is created
- [x] `plays/sdu204_man_siger/plot_torvet.md` is created and casts company elements
- [x] `plays/sdu204_man_siger/plot_avisen.md` is created and casts company elements
- [x] The local validation tests (`npm test`) run successfully with zero errors
