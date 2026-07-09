---
khai: order
title: "Stage SDU 603"
language: english
license: CC-BY-NC-SA-4.0
stamp:
  owner: KAI HACKS AI
  version: v0.0.1
  date: "2026-07-09"
---

# Order: Stage SDU 603

## Direction

The house must stage SDU 603 (_Kjærlighed paa Nicolai Taarn eller Hvad siger Parterret_) to establish the third work in the "Drama" genre. The production must model the heroic vaudeville and parody in one act, featuring Ole Tårnvægter, his daughter Ellen, and the deciding audience (Parterret). It must model Nikolaj Tårn, the theater pit, the watchman's telescope, the parody and vote processes, the audience's disruption plan, and the final vote on the play's ending. All staging, prose, projections, actions, shadows, and tells must be authored in authentic Danish.

## Orders

1. The Playwright (Hans Christian Andersen) must author the play definition, the three personas (Ole, Ellen, Parterret), the two positions (vaegter, publikum), the one piece (kikkert), the two places (taarnet, teatret), the two processes (parodi, afstemning), the in-world plan (afbrydelse), the pitch (vaudeville), and the three plots.
2. The Theatre Manager (Edvard Collin) must verify the local registry, ensure correct versioning, check formatting, and validate that the entire cast conforms to the canon.
3. The Roadie (Vilhelm Pedersen) must set the stage, verify the local test suite is green, and prepare the files for packaging.

## Implementation

The play files must be placed in `plays/sdu603_nicolaitaarn/` and follow the house language policy:

- Structural elements and frontmatter in English.
- Narrative prose, projections, actions, shadows, tells, and staging notes in Danish.

## Targets

- [x] `plays/sdu603_nicolaitaarn/play_nicolaitaarn.md` is created and lists the complete company
- [x] `plays/sdu603_nicolaitaarn/persona_ole.md` is created and links to `position_vaegter.md`
- [x] `plays/sdu603_nicolaitaarn/persona_ellen.md` is created
- [x] `plays/sdu603_nicolaitaarn/persona_parterret.md` is created and links to `position_publikum.md`
- [x] `plays/sdu603_nicolaitaarn/position_vaegter.md` is created
- [x] `plays/sdu603_nicolaitaarn/position_publikum.md` is created
- [x] `plays/sdu603_nicolaitaarn/piece_kikkert.md` is created
- [x] `plays/sdu603_nicolaitaarn/place_taarnet.md` is created
- [x] `plays/sdu603_nicolaitaarn/place_teatret.md` is created
- [x] `plays/sdu603_nicolaitaarn/process_parodi.md` is created
- [x] `plays/sdu603_nicolaitaarn/process_afstemning.md` is created
- [x] `plays/sdu603_nicolaitaarn/plan_afbrydelse.md` is created
- [x] `plays/sdu603_nicolaitaarn/pitch_vaudeville.md` is created
- [x] `plays/sdu603_nicolaitaarn/plot_vagten.md` is created and casts company elements
- [x] `plays/sdu603_nicolaitaarn/plot_afstemningen.md` is created and casts company elements
- [x] `plays/sdu603_nicolaitaarn/plot_parodien.md` is created and casts company elements
- [x] The local validation tests (`npm test`) run successfully with zero errors
