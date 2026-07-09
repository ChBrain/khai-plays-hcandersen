---
khai: order
title: "Stage SDU 606"
language: english
license: CC-BY-NC-SA-4.0
stamp:
  owner: KAI HACKS AI
  version: v0.0.1
  date: "2026-07-09"
---

# Order: Stage SDU 606

## Direction

The house must stage SDU 606 (_Bruden fra Lammermoor_) to establish the sixth work in the "Drama" genre. The production must model the romantic syngestykke, featuring Edgar Ravenswood, Lucy Ashton, and her father Lord Ashton. It must model Ravenswood Castle, the chapel, the forced marriage contract, the syngestykke and curse processes, the alliance plan, the gothic romantic pitch, and the three plots. All staging, prose, projections, actions, shadows, and tells must be authored in authentic Danish.

## Orders

1. The Playwright (Hans Christian Andersen) must author the play definition, the three personas (edgar, lucy, ashton), the three positions (helt, brud, intrige), the one piece (kontrakt), the two places (ravenswood, kapellet), the two processes (syngestykke, forbandelse), the in-world plan (alliance), the pitch (romantisk), and the three plots.
2. The Theatre Manager (Edvard Collin) must verify the local registry, ensure correct versioning, check formatting, and validate that the entire cast conforms to the canon.
3. The Roadie (Vilhelm Pedersen) must set the stage, verify the local test suite is green, and prepare the files for packaging.

## Implementation

The play files must be placed in `plays/sdu606_lammermoor/` and follow the house language policy:

- Structural elements and frontmatter in English.
- Narrative prose, projections, actions, shadows, tells, and staging notes in Danish.

## Targets

- [x] `plays/sdu606_lammermoor/play_lammermoor.md` is created and lists the complete company
- [x] `plays/sdu606_lammermoor/persona_edgar.md` is created and links to `position_helt.md`
- [x] `plays/sdu606_lammermoor/persona_lucy.md` is created and links to `position_brud.md`
- [x] `plays/sdu606_lammermoor/persona_ashton.md` is created and links to `position_intrige.md`
- [x] `plays/sdu606_lammermoor/position_helt.md` is created
- [x] `plays/sdu606_lammermoor/position_brud.md` is created
- [x] `plays/sdu606_lammermoor/position_intrige.md` is created
- [x] `plays/sdu606_lammermoor/piece_kontrakt.md` is created
- [x] `plays/sdu606_lammermoor/place_ravenswood.md` is created
- [x] `plays/sdu606_lammermoor/place_kapellet.md` is created
- [x] `plays/sdu606_lammermoor/process_syngestykke.md` is created
- [x] `plays/sdu606_lammermoor/process_forbandelse.md` is created
- [x] `plays/sdu606_lammermoor/plan_alliance.md` is created
- [x] `plays/sdu606_lammermoor/pitch_romantisk.md` is created
- [x] `plays/sdu606_lammermoor/plot_troskabsed.md` is created and casts company elements
- [x] `plays/sdu606_lammermoor/plot_kontrakten.md` is created and casts company elements
- [x] `plays/sdu606_lammermoor/plot_katastrofen.md` is created and casts company elements
- [x] The local validation tests (`npm test`) run successfully with zero errors
