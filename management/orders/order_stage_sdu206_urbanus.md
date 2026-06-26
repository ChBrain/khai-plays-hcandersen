---
khai: order
title: "Stage SDU 206 Urbanus"
language: english
license: CC-BY-NC-SA-4.0
stamp:
  owner: KAI HACKS AI
  version: v0.0.1
  date: "2026-06-26"
---

# Order: Stage SDU 206 Urbanus

## Direction

The house must stage SDU 206 (_Urbanus_) to establish a production in the H.C. Andersen house. The production must model munk, fugl, the positions (tilbedoer, sanger), the pieces (klosterbog, salme), the environments (klostret, skoven), the tilbedelse and forundring processes, and the plots representing klostret and skoven. It must be written in authentic Danish for all prose sections.

## Orders

1. The Playwright (Hans Christian Andersen) must author the play definition, the 2 personas, the 2 positions, the 2 pieces, the 2 places, the 2 processes, the 1 in-world plans, the pitch of religioes, and the 2 plots.
2. The Theatre Manager (Edvard Collin) must verify the local registry, ensure correct versioning, check formatting, and validate that the cast conforms to the canon.
3. The Roadie (Vilhelm Pedersen) must set the stage, verify the local test suite is green, and prepare the files for packaging.

## Implementation

The play files must be placed in `plays/sdu206_urbanus/` and follow the house language policy:

- Structural elements and frontmatter in English.
- Narrative prose, projections, actions, shadows, tells, and staging notes in Danish.

## Targets

- [x] `plays/sdu206_urbanus/play_urbanus.md` is created and lists the complete company
- [x] `plays/sdu206_urbanus/persona_munk.md` is created and links to `position_tilbedoer.md`
- [x] `plays/sdu206_urbanus/persona_fugl.md` is created and links to `position_sanger.md`
- [x] `plays/sdu206_urbanus/position_tilbedoer.md` is created
- [x] `plays/sdu206_urbanus/position_sanger.md` is created
- [x] `plays/sdu206_urbanus/piece_klosterbog.md` is created
- [x] `plays/sdu206_urbanus/piece_salme.md` is created
- [x] `plays/sdu206_urbanus/place_klostret.md` is created
- [x] `plays/sdu206_urbanus/place_skoven.md` is created
- [x] `plays/sdu206_urbanus/process_tilbedelse.md` is created
- [x] `plays/sdu206_urbanus/process_forundring.md` is created
- [x] `plays/sdu206_urbanus/plan_frelse.md` is created and linked to `persona_munk.md`
- [x] `plays/sdu206_urbanus/pitch_religioes.md` is created
- [x] `plays/sdu206_urbanus/plot_klostret.md` is created and casts company elements
- [x] `plays/sdu206_urbanus/plot_skoven.md` is created and casts company elements
- [x] The local validation tests (`npm test`) run successfully with zero errors
