---
khai: order
title: "Stage SDU 607"
language: english
license: CC-BY-NC-SA-4.0
stamp:
  owner: KAI HACKS AI
  version: v0.0.1
  date: "2026-07-09"
---

# Order: Stage SDU 607

## Direction

The house must stage SDU 607 (_Ravnen eller Broderprøven_) to establish the seventh work in the "Drama" genre. The production must model the trylleopera, featuring Millo, Jennaro, and Armilla. It must model Millo's palace, Norando's cave, the shot raven, the trylleopera and petrification processes, the rescue plan, the fairy-tale pitch, and the three plots. All staging, prose, projections, actions, shadows, and tells must be authored in authentic Danish.

## Orders

1. The Playwright (Hans Christian Andersen) must author the play definition, the three personas (millo, jennaro, armilla), the three positions (prins, broder, fange), the one piece (ravn), the two places (slottet, grotten), the two processes (trylleopera, forvandling), the in-world plan (redningsaktion), the pitch (eventyrlig), and the three plots.
2. The Theatre Manager (Edvard Collin) must verify the local registry, ensure correct versioning, check formatting, and validate that the entire cast conforms to the canon.
3. The Roadie (Vilhelm Pedersen) must set the stage, verify the local test suite is green, and prepare the files for packaging.

## Implementation

The play files must be placed in `plays/sdu607_ravnen/` and follow the house language policy:

- Structural elements and frontmatter in English.
- Narrative prose, projections, actions, shadows, tells, and staging notes in Danish.

## Targets

- [x] `plays/sdu607_ravnen/play_ravnen.md` is created and lists the complete company
- [x] `plays/sdu607_ravnen/persona_millo.md` is created and links to `position_prins.md`
- [x] `plays/sdu607_ravnen/persona_jennaro.md` is created and links to `position_broder.md`
- [x] `plays/sdu607_ravnen/persona_armilla.md` is created and links to `position_fange.md`
- [x] `plays/sdu607_ravnen/position_prins.md` is created
- [x] `plays/sdu607_ravnen/position_broder.md` is created
- [x] `plays/sdu607_ravnen/position_fange.md` is created
- [x] `plays/sdu607_ravnen/piece_ravn.md` is created
- [x] `plays/sdu607_ravnen/place_slottet.md` is created
- [x] `plays/sdu607_ravnen/place_grotten.md` is created
- [x] `plays/sdu607_ravnen/process_trylleopera.md` is created
- [x] `plays/sdu607_ravnen/process_forvandling.md` is created
- [x] `plays/sdu607_ravnen/plan_redningsaktion.md` is created
- [x] `plays/sdu607_ravnen/pitch_eventyrlig.md` is created
- [x] `plays/sdu607_ravnen/plot_forbandelsen.md` is created and casts company elements
- [x] `plays/sdu607_ravnen/plot_broderproeven.md` is created and casts company elements
- [x] `plays/sdu607_ravnen/plot_forloesningen.md` is created and casts company elements
- [x] The local validation tests (`npm test`) run successfully with zero errors
