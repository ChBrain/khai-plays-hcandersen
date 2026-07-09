---
khai: order
title: "Stage SDU 612"
language: english
license: CC-BY-NC-SA-4.0
stamp:
  owner: KAI HACKS AI
  version: v0.0.1
  date: "2026-07-09"
---

# Order: Stage SDU 612

## Direction

The house must stage SDU 612 (_En rigtig Soldat_) to establish the twelfth work in the "Drama" genre. The production must model the one-act versemaker-bagatelle, featuring the aunt and niece. It must model the places representing the decaying fortress, the pieces representing the drum and trumpet, the processes representing military pretence and rhyming versemaker singing, the niece's plan for defense, the satirical bagatelle tone, and the three plots. All staging, prose, projections, actions, shadows, and tells must be authored in authentic Danish.

## Orders

1. The Playwright (Hans Christian Andersen) must author the play definition, the two personas (tante, niece), the two positions (tante, soldat), the two pieces (tromme, trompet), the one place (faestning), the two processes (militaer, versemageri), the in-world plan (forsvar), the pitch (bagatel), and the three plots.
2. The Theatre Manager (Edvard Collin) must verify the local registry, ensure correct versioning, check formatting, and validate that the entire cast conforms to the canon.
3. The Roadie (Vilhelm Pedersen) must set the stage, verify the local test suite is green, and prepare the files for packaging.

## Implementation

The play files must be placed in `plays/sdu612_soldat/` and follow the house language policy:

- Structural elements and frontmatter in English.
- Narrative prose, projections, actions, shadows, tells, and staging notes in Danish.

## Targets

- [x] `plays/sdu612_soldat/play_soldat.md` is created and lists the complete company
- [x] `plays/sdu612_soldat/persona_tante.md` is created and links to `position_tante.md`
- [x] `plays/sdu612_soldat/persona_niece.md` is created and links to `position_soldat.md`
- [x] `plays/sdu612_soldat/position_tante.md` is created
- [x] `plays/sdu612_soldat/position_soldat.md` is created
- [x] `plays/sdu612_soldat/piece_tromme.md` is created
- [x] `plays/sdu612_soldat/piece_trompet.md` is created
- [x] `plays/sdu612_soldat/place_faestning.md` is created
- [x] `plays/sdu612_soldat/process_militaer.md` is created
- [x] `plays/sdu612_soldat/process_versemageri.md` is created
- [x] `plays/sdu612_soldat/plan_forsvar.md` is created
- [x] `plays/sdu612_soldat/pitch_bagatel.md` is created
- [x] `plays/sdu612_soldat/plot_vagten.md` is created and casts company elements
- [x] `plays/sdu612_soldat/plot_konfrontationen.md` is created and casts company elements
- [x] `plays/sdu612_soldat/plot_forloesningen.md` is created and casts company elements
- [x] The local validation tests (`npm test`) run successfully with zero errors
