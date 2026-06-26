---
khai: order
title: "Stage SDU 209 Temperamenterne"
language: english
license: CC-BY-NC-SA-4.0
stamp:
  owner: KAI HACKS AI
  version: v0.0.1
  date: "2026-06-26"
---

# Order: Stage SDU 209 Temperamenterne

## Direction

The house must stage SDU 209 (_Temperamenterne_) to establish a production in the H.C. Andersen house. The production must model kolerikeren, flegmatikeren, the positions (hidsig, rolig), the pieces (ild, vand), the environments (salen, verden), the strid and balance processes, and the plots representing striden and balancen. It must be written in authentic Danish for all prose sections.

## Orders

1. The Playwright (Hans Christian Andersen) must author the play definition, the 2 personas, the 2 positions, the 2 pieces, the 2 places, the 2 processes, the 1 in-world plans, the pitch of allegorisk, and the 2 plots.
2. The Theatre Manager (Edvard Collin) must verify the local registry, ensure correct versioning, check formatting, and validate that the cast conforms to the canon.
3. The Roadie (Vilhelm Pedersen) must set the stage, verify the local test suite is green, and prepare the files for packaging.

## Implementation

The play files must be placed in `plays/sdu209_temperamenterne/` and follow the house language policy:

- Structural elements and frontmatter in English.
- Narrative prose, projections, actions, shadows, tells, and staging notes in Danish.

## Targets

- [x] `plays/sdu209_temperamenterne/play_temperamenterne.md` is created and lists the complete company
- [x] `plays/sdu209_temperamenterne/persona_kolerikeren.md` is created and links to `position_hidsig.md`
- [x] `plays/sdu209_temperamenterne/persona_flegmatikeren.md` is created and links to `position_rolig.md`
- [x] `plays/sdu209_temperamenterne/position_hidsig.md` is created
- [x] `plays/sdu209_temperamenterne/position_rolig.md` is created
- [x] `plays/sdu209_temperamenterne/piece_ild.md` is created
- [x] `plays/sdu209_temperamenterne/piece_vand.md` is created
- [x] `plays/sdu209_temperamenterne/place_salen.md` is created
- [x] `plays/sdu209_temperamenterne/place_verden.md` is created
- [x] `plays/sdu209_temperamenterne/process_strid.md` is created
- [x] `plays/sdu209_temperamenterne/process_balance.md` is created
- [x] `plays/sdu209_temperamenterne/plan_harmoni.md` is created and linked to `persona_flegmatikeren.md`
- [x] `plays/sdu209_temperamenterne/pitch_allegorisk.md` is created
- [x] `plays/sdu209_temperamenterne/plot_striden.md` is created and casts company elements
- [x] `plays/sdu209_temperamenterne/plot_balancen.md` is created and casts company elements
- [x] The local validation tests (`npm test`) run successfully with zero errors
