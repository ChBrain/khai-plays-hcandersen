---
khai: order
title: "Stage SDU 401"
language: english
license: CC-BY-NC-SA-4.0
stamp:
  owner: KAI HACKS AI
  version: v0.0.1
  date: "2026-07-08"
---

# Order: Stage SDU 401

## Direction

The house must stage SDU 401 (_Improvisatoren_) to establish the first novel-length production in the H.C. Andersen house. The production must model Antonio's journey, his improvisation skill, his patron relations, his travel, his deep connection to Capri's Blue Grotto, and his ultimate artistic self-realization. It must be written in authentic Danish for all staging and prose sections.

## Orders

1. The Playwright (Hans Christian Andersen) must author the play definition, the five personas (Antonio, Annunciata, Lara, Bernardo, Domenica), the three positions (improvisator, sangerinde, patron), the two pieces (guitaren, improvisation), the two places (rom, den_blaa_grotte), the two processes (improvisering, rejse), the in-world plan (selvrealisering), the pitch (romantisk), and the three plots.
2. The Theatre Manager (Edvard Collin) must verify the local registry, ensure correct versioning, check formatting, and validate that the entire cast conforms to the canon.
3. The Roadie (Vilhelm Pedersen) must set the stage, verify the local test suite is green, and prepare the files for packaging.

## Implementation

The play files must be placed in `plays/sdu401_improvisatoren/` and follow the house language policy:

- Structural elements and frontmatter in English.
- Narrative prose, projections, actions, shadows, tells, and staging notes in Danish.

## Targets

- [x] `plays/sdu401_improvisatoren/play_improvisatoren.md` is created and lists the complete company
- [x] `plays/sdu401_improvisatoren/persona_antonio.md` is created and links to `position_improvisator.md`
- [x] `plays/sdu401_improvisatoren/persona_annunciata.md` is created and links to `position_sangerinde.md`
- [x] `plays/sdu401_improvisatoren/persona_lara.md` is created
- [x] `plays/sdu401_improvisatoren/persona_bernardo.md` is created
- [x] `plays/sdu401_improvisatoren/persona_domenica.md` is created and links to `position_patron.md`
- [x] `plays/sdu401_improvisatoren/position_improvisator.md` is created
- [x] `plays/sdu401_improvisatoren/position_sangerinde.md` is created
- [x] `plays/sdu401_improvisatoren/position_patron.md` is created
- [x] `plays/sdu401_improvisatoren/piece_guitaren.md` is created
- [x] `plays/sdu401_improvisatoren/piece_improvisation.md` is created
- [x] `plays/sdu401_improvisatoren/place_rom.md` is created
- [x] `plays/sdu401_improvisatoren/place_den_blaa_grotte.md` is created
- [x] `plays/sdu401_improvisatoren/process_improvisering.md` is created
- [x] `plays/sdu401_improvisatoren/process_rejse.md` is created
- [x] `plays/sdu401_improvisatoren/plan_selvrealisering.md` is created
- [x] `plays/sdu401_improvisatoren/pitch_romantisk.md` is created
- [x] `plays/sdu401_improvisatoren/plot_barndommen.md` is created and casts company elements
- [x] `plays/sdu401_improvisatoren/plot_gennembruddet.md` is created and casts company elements
- [x] `plays/sdu401_improvisatoren/plot_grotten.md` is created and casts company elements
- [x] The local validation tests (`npm test`) run successfully with zero errors
