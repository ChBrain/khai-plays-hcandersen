---
khai: order
title: "Stage SDU 501"
language: english
license: CC-BY-NC-SA-4.0
stamp:
  owner: KAI HACKS AI
  version: v0.0.1
  date: "2026-07-09"
---

# Order: Stage SDU 501

## Direction

The house must stage SDU 501 (_Gjenfærdet ved Palnatokes Grav_) to establish the first work in the "Anden Prosa" genre. The production must model the gothic, superstitious atmosphere of Odense countryside, the legendary warrior Palnatoke's ghost, the visionary wanderer Stine, and the unfortunate peasant Jochum who is crushed by a falling gravestone at Palleshøj. All staging, prose, projections, actions, shadows, and tells must be authored in authentic Danish.

## Orders

1. The Playwright (Hans Christian Andersen) must author the play definition, the three personas (Stine, Jochum, Palnatoke), the two positions (galen, overtroisk), the one piece (gravstenen), the two places (palleshoej, odense), the two processes (overtro, hjaemsoegning), the in-world plan (opklaring), the pitch (gotisk), and the three plots.
2. The Theatre Manager (Edvard Collin) must verify the local registry, ensure correct versioning, check formatting, and validate that the entire cast conforms to the canon.
3. The Roadie (Vilhelm Pedersen) must set the stage, verify the local test suite is green, and prepare the files for packaging.

## Implementation

The play files must be placed in `plays/sdu501_gjenfaerdet/` and follow the house language policy:

- Structural elements and frontmatter in English.
- Narrative prose, projections, actions, shadows, tells, and staging notes in Danish.

## Targets

- [x] `plays/sdu501_gjenfaerdet/play_gjenfaerdet.md` is created and lists the complete company
- [x] `plays/sdu501_gjenfaerdet/persona_stine.md` is created and links to `position_galen.md`
- [x] `plays/sdu501_gjenfaerdet/persona_jochum.md` is created and links to `position_overtroisk.md`
- [x] `plays/sdu501_gjenfaerdet/persona_palnatoke.md` is created
- [x] `plays/sdu501_gjenfaerdet/position_galen.md` is created
- [x] `plays/sdu501_gjenfaerdet/position_overtroisk.md` is created
- [x] `plays/sdu501_gjenfaerdet/piece_gravstenen.md` is created
- [x] `plays/sdu501_gjenfaerdet/place_palleshoej.md` is created
- [x] `plays/sdu501_gjenfaerdet/place_odense.md` is created
- [x] `plays/sdu501_gjenfaerdet/process_overtro.md` is created
- [x] `plays/sdu501_gjenfaerdet/process_hjaemsoegning.md` is created
- [x] `plays/sdu501_gjenfaerdet/plan_opklaring.md` is created
- [x] `plays/sdu501_gjenfaerdet/pitch_gotisk.md` is created
- [x] `plays/sdu501_gjenfaerdet/plot_sagnfortaellingen.md` is created and casts company elements
- [x] `plays/sdu501_gjenfaerdet/plot_gravfaerden.md` is created and casts company elements
- [x] `plays/sdu501_gjenfaerdet/plot_stenfaldet.md` is created and casts company elements
- [x] The local validation tests (`npm test`) run successfully with zero errors
