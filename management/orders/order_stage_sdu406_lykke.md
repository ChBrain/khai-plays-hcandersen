---
khai: order
title: "Stage SDU 406"
language: english
license: CC-BY-NC-SA-4.0
stamp:
  owner: KAI HACKS AI
  version: v0.0.1
  date: "2026-07-09"
---

# Order: Stage SDU 406

## Direction

The house must stage SDU 406 (_Lykke-Peer_) to establish the sixth and final novel-length production in the H.C. Andersen house. The production must model the artistic rise and tragic-triumphant death of Peer (the lucky artist) contrasted with Felix (the privileged merchant's son). It must also model the laurel wreath ("Laurbærkransen"), Peer's childhood in the garret ("Kvisten"), his education with Hr. Gabriel in the country ("Landsbyen"), and the theater stage ("Teatret"). It must be written in authentic Danish for all staging and prose sections.

## Orders

1. The Playwright (Hans Christian Andersen) must author the play definition, the three personas (Peer, Felix, Gabriel), the two positions (kunstner, rigmandssoen), the one piece (laurbaerkransen), the three places (kvisten, landsbyen, teatret), the two processes (kunsten, doedstriumf), the in-world plan (succes), the pitch (triumf), and the three plots.
2. The Theatre Manager (Edvard Collin) must verify the local registry, ensure correct versioning, check formatting, and validate that the entire cast conforms to the canon.
3. The Roadie (Vilhelm Pedersen) must set the stage, verify the local test suite is green, and prepare the files for packaging.

## Implementation

The play files must be placed in `plays/sdu406_lykke/` and follow the house language policy:

- Structural elements and frontmatter in English.
- Narrative prose, projections, actions, shadows, tells, and staging notes in Danish.

## Targets

- [x] `plays/sdu406_lykke/play_lykke.md` is created and lists the complete company
- [x] `plays/sdu406_lykke/persona_peer.md` is created and links to `position_kunstner.md`
- [x] `plays/sdu406_lykke/persona_felix.md` is created and links to `position_rigmandssoen.md`
- [x] `plays/sdu406_lykke/persona_gabriel.md` is created
- [x] `plays/sdu406_lykke/position_kunstner.md` is created
- [x] `plays/sdu406_lykke/position_rigmandssoen.md` is created
- [x] `plays/sdu406_lykke/piece_laurbaerkransen.md` is created
- [x] `plays/sdu406_lykke/place_kvisten.md` is created
- [x] `plays/sdu406_lykke/place_landsbyen.md` is created
- [x] `plays/sdu406_lykke/place_teatret.md` is created
- [x] `plays/sdu406_lykke/process_kunsten.md` is created
- [x] `plays/sdu406_lykke/process_doedstriumf.md` is created
- [x] `plays/sdu406_lykke/plan_succes.md` is created
- [x] `plays/sdu406_lykke/pitch_triumf.md` is created
- [x] `plays/sdu406_lykke/plot_kvistbarndommen.md` is created and casts company elements
- [x] `plays/sdu406_lykke/plot_landsbydannelsen.md` is created and casts company elements
- [x] `plays/sdu406_lykke/plot_scenedoeden.md` is created and casts company elements
- [x] The local validation tests (`npm test`) run successfully with zero errors
