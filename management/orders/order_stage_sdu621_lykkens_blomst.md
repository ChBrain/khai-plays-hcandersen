---
khai: order
title: "Stage SDU 621"
language: english
license: CC-BY-NC-SA-4.0
stamp:
  owner: KAI HACKS AI
  version: v0.0.1
  date: "2026-07-10"
---

# Order: Stage SDU 621

## Direction

The house must stage SDU 621 (_Lykkens Blomst_) to establish the twenty-first work in the "Drama" genre. The production must model the whimsical fairy-tale comedy of Henrik, Johanne, and the Nisse. It must model Jægersborg forest, the magical flower piece, the processes representing the shape-shifting transformations and the testing of happiness, the couple's plan to protect their love, the whimsical comedy tone, and the three plots. All staging, prose, projections, actions, shadows, and tells must be authored in authentic Danish.

## Orders

1. The Playwright (Hans Christian Andersen) must author the play definition, the three personas (henrik, johanne, nisse), the three positions (skovfoged, brud, skovtroll), the one piece (blomst), the one place (skov), the two processes (forvandling, lykkestest), the in-world plan (kaerlighedsvalg), the pitch (eventyr_komedie), and the three plots.
2. The Theatre Manager (Edvard Collin) must verify the local registry, ensure correct versioning, check formatting, and validate that the entire cast conforms to the canon.
3. The Roadie (Vilhelm Pedersen) must set the stage, verify the local test suite is green, and prepare the files for packaging.

## Implementation

The play files must be placed in `plays/sdu621_lykkens_blomst/` and follow the house language policy:

- Structural elements and frontmatter in English.
- Narrative prose, projections, actions, shadows, tells, and staging notes in Danish.

## Targets

- [x] `plays/sdu621_lykkens_blomst/play_lykkens_blomst.md` is created and lists the complete company
- [x] `plays/sdu621_lykkens_blomst/persona_henrik.md` is created and links to `position_skovfoged.md`
- [x] `plays/sdu621_lykkens_blomst/persona_johanne.md` is created and links to `position_brud.md`
- [x] `plays/sdu621_lykkens_blomst/persona_nisse.md` is created and links to `position_skovtroll.md`
- [x] `plays/sdu621_lykkens_blomst/position_skovfoged.md` is created
- [x] `plays/sdu621_lykkens_blomst/position_brud.md` is created
- [x] `plays/sdu621_lykkens_blomst/position_skovtroll.md` is created
- [x] `plays/sdu621_lykkens_blomst/piece_blomst.md` is created
- [x] `plays/sdu621_lykkens_blomst/place_skov.md` is created
- [x] `plays/sdu621_lykkens_blomst/process_forvandling.md` is created
- [x] `plays/sdu621_lykkens_blomst/process_lykkestest.md` is created
- [x] `plays/sdu621_lykkens_blomst/plan_kaerlighedsvalg.md` is created
- [x] `plays/sdu621_lykkens_blomst/pitch_eventyr_komedie.md` is created
- [x] `plays/sdu621_lykkens_blomst/plot_skovlykken.md` is created and casts company elements
- [x] `plays/sdu621_lykkens_blomst/plot_tidenskifter.md` is created and casts company elements
- [x] `plays/sdu621_lykkens_blomst/plot_snoebolden.md` is created and casts company elements
- [x] The local validation tests (`npm test`) run successfully with zero errors
