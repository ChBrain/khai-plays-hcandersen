---
khai: order
title: "Stage SDU 608"
language: english
license: CC-BY-NC-SA-4.0
stamp:
  owner: KAI HACKS AI
  version: v0.0.1
  date: "2026-07-09"
---

# Order: Stage SDU 608

## Direction

The house must stage SDU 608 (_Dronningen paa 16 Aar_) to establish the eighth work in the "Drama" genre. The production must model the court drama, featuring Christina, Axel, and Oxenstierna. It must model the Queen's cabinet, the audience hall, the royal decree, the translation and duty processes, the state governance plan, the historical pitch, and the three plots. All staging, prose, projections, actions, shadows, and tells must be authored in authentic Danish.

## Orders

1. The Playwright (Hans Christian Andersen) must author the play definition, the three personas (christina, axel, oxenstierna), the three positions (dronning, officer, kansler), the one piece (dekret), the two places (kabinettet, audienssalen), the two processes (oversaettelse, pligt), the in-world plan (statsstyre), the pitch (historisk), and the three plots.
2. The Theatre Manager (Edvard Collin) must verify the local registry, ensure correct versioning, check formatting, and validate that the entire cast conforms to the canon.
3. The Roadie (Vilhelm Pedersen) must set the stage, verify the local test suite is green, and prepare the files for packaging.

## Implementation

The play files must be placed in `plays/sdu608_dronningen/` and follow the house language policy:

- Structural elements and frontmatter in English.
- Narrative prose, projections, actions, shadows, tells, and staging notes in Danish.

## Targets

- [x] `plays/sdu608_dronningen/play_dronningen.md` is created and lists the complete company
- [x] `plays/sdu608_dronningen/persona_christina.md` is created and links to `position_dronning.md`
- [x] `plays/sdu608_dronningen/persona_axel.md` is created and links to `position_officer.md`
- [x] `plays/sdu608_dronningen/persona_oxenstierna.md` is created and links to `position_kansler.md`
- [x] `plays/sdu608_dronningen/position_dronning.md` is created
- [x] `plays/sdu608_dronningen/position_officer.md` is created
- [x] `plays/sdu608_dronningen/position_kansler.md` is created
- [x] `plays/sdu608_dronningen/piece_dekret.md` is created
- [x] `plays/sdu608_dronningen/place_kabinettet.md` is created
- [x] `plays/sdu608_dronningen/place_audienssalen.md` is created
- [x] `plays/sdu608_dronningen/process_oversaettelse.md` is created
- [x] `plays/sdu608_dronningen/process_pligt.md` is created
- [x] `plays/sdu608_dronningen/plan_statsstyre.md` is created
- [x] `plays/sdu608_dronningen/pitch_historisk.md` is created
- [x] `plays/sdu608_dronningen/plot_forelskelsen.md` is created and casts company elements
- [x] `plays/sdu608_dronningen/plot_afkaldet.md` is created and casts company elements
- [x] `plays/sdu608_dronningen/plot_dekretet.md` is created and casts company elements
- [x] The local validation tests (`npm test`) run successfully with zero errors
