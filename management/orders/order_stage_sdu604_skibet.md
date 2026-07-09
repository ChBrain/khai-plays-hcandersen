---
khai: order
title: "Stage SDU 604"
language: english
license: CC-BY-NC-SA-4.0
stamp:
  owner: KAI HACKS AI
  version: v0.0.1
  date: "2026-07-09"
---

# Order: Stage SDU 604

## Direction

The house must stage SDU 604 (_Skibet_) to establish the fourth work in the "Drama" genre. The production must model the vaudeville in one act, featuring the ship captain, the passenger, and the health inspector on land. It must model the ship's deck, the harbor, the yellow quarantine flag, the quarantine and mistaken identity processes, the smuggling plan, and the final liberation. All staging, prose, projections, actions, shadows, and tells must be authored in authentic Danish.

## Orders

1. The Playwright (Hans Christian Andersen) must author the play definition, the three personas (kaptajnen, passageren, officeren), the three positions (soemand, passager, inspektoer), the one piece (karantaeneflag), the two places (skibet, havnen), the two processes (karantaene, misforstaaelse), the in-world plan (smugling), the pitch (vaudeville), and the three plots.
2. The Theatre Manager (Edvard Collin) must verify the local registry, ensure correct versioning, check formatting, and validate that the entire cast conforms to the canon.
3. The Roadie (Vilhelm Pedersen) must set the stage, verify the local test suite is green, and prepare the files for packaging.

## Implementation

The play files must be placed in `plays/sdu604_skibet/` and follow the house language policy:

- Structural elements and frontmatter in English.
- Narrative prose, projections, actions, shadows, tells, and staging notes in Danish.

## Targets

- [x] `plays/sdu604_skibet/play_skibet.md` is created and lists the complete company
- [x] `plays/sdu604_skibet/persona_kaptajnen.md` is created and links to `position_soemand.md`
- [x] `plays/sdu604_skibet/persona_passageren.md` is created and links to `position_passager.md`
- [x] `plays/sdu604_skibet/persona_officeren.md` is created and links to `position_inspektoer.md`
- [x] `plays/sdu604_skibet/position_soemand.md` is created
- [x] `plays/sdu604_skibet/position_passager.md` is created
- [x] `plays/sdu604_skibet/position_inspektoer.md` is created
- [x] `plays/sdu604_skibet/piece_karantaeneflag.md` is created
- [x] `plays/sdu604_skibet/place_skibet.md` is created
- [x] `plays/sdu604_skibet/place_havnen.md` is created
- [x] `plays/sdu604_skibet/process_karantaene.md` is created
- [x] `plays/sdu604_skibet/process_misforstaaelse.md` is created
- [x] `plays/sdu604_skibet/plan_smugling.md` is created
- [x] `plays/sdu604_skibet/pitch_vaudeville.md` is created
- [x] `plays/sdu604_skibet/plot_karantaenen.md` is created and casts company elements
- [x] `plays/sdu604_skibet/plot_brevvekslingen.md` is created and casts company elements
- [x] `plays/sdu604_skibet/plot_frigoerelsen.md` is created and casts company elements
- [x] The local validation tests (`npm test`) run successfully with zero errors
