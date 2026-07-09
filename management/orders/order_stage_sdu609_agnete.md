---
khai: order
title: "Stage SDU 609"
language: english
license: CC-BY-NC-SA-4.0
stamp:
  owner: KAI HACKS AI
  version: v0.0.1
  date: "2026-07-09"
---

# Order: Stage SDU 609

## Direction

The house must stage SDU 609 (_Agnete og Havmanden_) to establish the ninth work in the "Drama" genre. The production must model the dramatic poem, featuring Agnete and Havmanden. It must model the ocean floor, the church, the church bell, the folk ballad and home-longing processes, the renunciation plan, the tragic pitch, and the three plots. All staging, prose, projections, actions, shadows, and tells must be authored in authentic Danish.

## Orders

1. The Playwright (Hans Christian Andersen) must author the play definition, the two personas (agnete, havmanden), the two positions (jfr, havkonge), the one piece (kirkeklokke), the two places (dybet, kirken), the two processes (folkevise, hjemlaengsel), the in-world plan (afsvaergelse), the pitch (tragisk), and the three plots.
2. The Theatre Manager (Edvard Collin) must verify the local registry, ensure correct versioning, check formatting, and validate that the entire cast conforms to the canon.
3. The Roadie (Vilhelm Pedersen) must set the stage, verify the local test suite is green, and prepare the files for packaging.

## Implementation

The play files must be placed in `plays/sdu609_agnete/` and follow the house language policy:

- Structural elements and frontmatter in English.
- Narrative prose, projections, actions, shadows, tells, and staging notes in Danish.

## Targets

- [x] `plays/sdu609_agnete/play_agnete.md` is created and lists the complete company
- [x] `plays/sdu609_agnete/persona_agnete.md` is created and links to `position_jfr.md`
- [x] `plays/sdu609_agnete/persona_havmanden.md` is created and links to `position_havkonge.md`
- [x] `plays/sdu609_agnete/position_jfr.md` is created
- [x] `plays/sdu609_agnete/position_havkonge.md` is created
- [x] `plays/sdu609_agnete/piece_kirkeklokke.md` is created
- [x] `plays/sdu609_agnete/place_dybet.md` is created
- [x] `plays/sdu609_agnete/place_kirken.md` is created
- [x] `plays/sdu609_agnete/process_folkevise.md` is created
- [x] `plays/sdu609_agnete/process_hjemlaengsel.md` is created
- [x] `plays/sdu609_agnete/plan_afsvaergelse.md` is created
- [x] `plays/sdu609_agnete/pitch_tragisk.md` is created
- [x] `plays/sdu609_agnete/plot_dybet.md` is created and casts company elements
- [x] `plays/sdu609_agnete/plot_klokkerne.md` is created and casts company elements
- [x] `plays/sdu609_agnete/plot_bruddet.md` is created and casts company elements
- [x] The local validation tests (`npm test`) run successfully with zero errors
