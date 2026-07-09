---
khai: order
title: "Stage SDU 605"
language: english
license: CC-BY-NC-SA-4.0
stamp:
  owner: KAI HACKS AI
  version: v0.0.1
  date: "2026-07-09"
---

# Order: Stage SDU 605

## Direction

The house must stage SDU 605 (_Fornuftgiftermaalet Nr. 2. En Dramatisk Drøm paa Skagens Rev_) to establish the fifth work in the "Drama" genre. The production must model the allegorical dream, featuring the schoolmaster, the personified comedies as students, and the observing dreamer. It must model Skagens Rev, the schoolroom, the schoolmaster's pointer, the educational and allegorical processes, the examination plan, the satirical pitch, and the three plots. All staging, prose, projections, actions, shadows, and tells must be authored in authentic Danish.

## Orders

1. The Playwright (Hans Christian Andersen) must author the play definition, the three personas (skolemesteren, komedien, droemmeren), the three positions (laerer, elev, iagttager), the one piece (pegepind), the two places (revet, skolestuen), the two processes (undervisning, allegori), the in-world plan (eksamination), the pitch (satire), and the three plots.
2. The Theatre Manager (Edvard Collin) must verify the local registry, ensure correct versioning, check formatting, and validate that the entire cast conforms to the canon.
3. The Roadie (Vilhelm Pedersen) must set the stage, verify the local test suite is green, and prepare the files for packaging.

## Implementation

The play files must be placed in `plays/sdu605_fornuftgiftermaalet/` and follow the house language policy:

- Structural elements and frontmatter in English.
- Narrative prose, projections, actions, shadows, tells, and staging notes in Danish.

## Targets

- [x] `plays/sdu605_fornuftgiftermaalet/play_fornuftgiftermaalet.md` is created and lists the complete company
- [x] `plays/sdu605_fornuftgiftermaalet/persona_skolemesteren.md` is created and links to `position_laerer.md`
- [x] `plays/sdu605_fornuftgiftermaalet/persona_komedien.md` is created and links to `position_elev.md`
- [x] `plays/sdu605_fornuftgiftermaalet/persona_droemmeren.md` is created and links to `position_iagttager.md`
- [x] `plays/sdu605_fornuftgiftermaalet/position_laerer.md` is created
- [x] `plays/sdu605_fornuftgiftermaalet/position_elev.md` is created
- [x] `plays/sdu605_fornuftgiftermaalet/position_iagttager.md` is created
- [x] `plays/sdu605_fornuftgiftermaalet/piece_pegepind.md` is created
- [x] `plays/sdu605_fornuftgiftermaalet/place_revet.md` is created
- [x] `plays/sdu605_fornuftgiftermaalet/place_skolestuen.md` is created
- [x] `plays/sdu605_fornuftgiftermaalet/process_undervisning.md` is created
- [x] `plays/sdu605_fornuftgiftermaalet/process_allegori.md` is created
- [x] `plays/sdu605_fornuftgiftermaalet/plan_eksamination.md` is created
- [x] `plays/sdu605_fornuftgiftermaalet/pitch_satire.md` is created
- [x] `plays/sdu605_fornuftgiftermaalet/plot_droemmen.md` is created and casts company elements
- [x] `plays/sdu605_fornuftgiftermaalet/plot_lektionen.md` is created and casts company elements
- [x] `plays/sdu605_fornuftgiftermaalet/plot_skibbruddet.md` is created and casts company elements
- [x] The local validation tests (`npm test`) run successfully with zero errors
