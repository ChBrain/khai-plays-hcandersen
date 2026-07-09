---
khai: order
title: "Stage SDU 611"
language: english
license: CC-BY-NC-SA-4.0
stamp:
  owner: KAI HACKS AI
  version: v0.0.1
  date: "2026-07-09"
---

# Order: Stage SDU 611

## Direction

The house must stage SDU 611 (_Skilles og mødes_) to establish the eleventh work in the "Drama" genre. The production must model the vaudeville, featuring Ingeborg, Andreas Meier, and Theodor Granner. It must model the places Sprogø and the inn, the piece representing the mason's song sheet, the processes representing drift ice and vaudeville singing, the plan for Theodor's aid, the lyrical/romantic tenor, and the three plots. All staging, prose, projections, actions, shadows, and tells must be authored in authentic Danish.

## Orders

1. The Playwright (Hans Christian Andersen) must author the play definition, the three personas (ingeborg, andreas, theodor), the three positions (elskerinde, bejler, formidler), the one piece (murersang), the two places (sprogoe, kroen), the two processes (drivis, vaudeville), the in-world plan (hjaelp), the pitch (svaermerisk), and the three plots.
2. The Theatre Manager (Edvard Collin) must verify the local registry, ensure correct versioning, check formatting, and validate that the entire cast conforms to the canon.
3. The Roadie (Vilhelm Pedersen) must set the stage, verify the local test suite is green, and prepare the files for packaging.

## Implementation

The play files must be placed in `plays/sdu611_skilles/` and follow the house language policy:

- Structural elements and frontmatter in English.
- Narrative prose, projections, actions, shadows, tells, and staging notes in Danish.

## Targets

- [x] `plays/sdu611_skilles/play_skilles.md` is created and lists the complete company
- [x] `plays/sdu611_skilles/persona_ingeborg.md` is created and links to `position_elskerinde.md`
- [x] `plays/sdu611_skilles/persona_andreas.md` is created and links to `position_bejler.md`
- [x] `plays/sdu611_skilles/persona_theodor.md` is created and links to `position_formidler.md`
- [x] `plays/sdu611_skilles/position_elskerinde.md` is created
- [x] `plays/sdu611_skilles/position_bejler.md` is created
- [x] `plays/sdu611_skilles/position_formidler.md` is created
- [x] `plays/sdu611_skilles/piece_murersang.md` is created
- [x] `plays/sdu611_skilles/place_sprogoe.md` is created
- [x] `plays/sdu611_skilles/place_kroen.md` is created
- [x] `plays/sdu611_skilles/process_drivis.md` is created
- [x] `plays/sdu611_skilles/process_vaudeville.md` is created
- [x] `plays/sdu611_skilles/plan_hjaelp.md` is created
- [x] `plays/sdu611_skilles/pitch_svaermerisk.md` is created
- [x] `plays/sdu611_skilles/plot_strandingen.md` is created and casts company elements
- [x] `plays/sdu611_skilles/plot_forviklingen.md` is created and casts company elements
- [x] `plays/sdu611_skilles/plot_foreningen.md` is created and casts company elements
- [x] The local validation tests (`npm test`) run successfully with zero errors
