---
khai: order
title: "Stage SDU 625"
language: english
license: CC-BY-NC-SA-4.0
stamp:
  owner: KAI HACKS AI
  version: v0.0.1
  date: "2026-07-11"
---

# Order: Stage SDU 625

## Direction

The house must stage SDU 625 (_Brylluppet ved Como-Søen_) to establish the twenty-fifth work in the "Drama" genre. The production must model the dramatic operatic dialogues of Renzo, Lucia, and Don Rodrigo. It must model the Como lakeshore, the Madonna icon piece, the processes representing the separation of the lovers and the plague-based divine rescue, the couple's plan to complete their marriage, the emotional operatic tone, and the three plots. All staging, prose, projections, actions, shadows, and tells must be authored in authentic Danish.

## Orders

1. The Playwright (Hans Christian Andersen) must author the play definition, the three personas (renzo, lucia, rodrigo), the three positions (silkevaever, gudfrygtig_brud, tyrant), the one piece (relikvie), the one place (soebredden), the two processes (adskillelse, redning), the in-world plan (trolovelse), the pitch (syngespil), and the three plots.
2. The Theatre Manager (Edvard Collin) must verify the local registry, ensure correct versioning, check formatting, and validate that the entire cast conforms to the canon.
3. The Roadie (Vilhelm Pedersen) must set the stage, verify the local test suite is green, and prepare the files for packaging.

## Implementation

The play files must be placed in `plays/sdu625_como_soeen/` and follow the house language policy:

- Structural elements and frontmatter in English.
- Narrative prose, projections, actions, shadows, tells, and staging notes in Danish.

## Targets

- [x] `plays/sdu625_como_soeen/play_como_soeen.md` is created and lists the complete company
- [x] `plays/sdu625_como_soeen/persona_renzo.md` is created and links to `position_silkevaever.md`
- [x] `plays/sdu625_como_soeen/persona_lucia.md` is created and links to `position_gudfrygtig_brud.md`
- [x] `plays/sdu625_como_soeen/persona_rodrigo.md` is created and links to `position_tyrant.md`
- [x] `plays/sdu625_como_soeen/position_silkevaever.md` is created
- [x] `plays/sdu625_como_soeen/position_gudfrygtig_brud.md` is created
- [x] `plays/sdu625_como_soeen/position_tyrant.md` is created
- [x] `plays/sdu625_como_soeen/piece_relikvie.md` is created
- [x] `plays/sdu625_como_soeen/place_soebredden.md` is created
- [x] `plays/sdu625_como_soeen/process_adskillelse.md` is created
- [x] `plays/sdu625_como_soeen/process_redning.md` is created
- [x] `plays/sdu625_como_soeen/plan_trolovelse.md` is created
- [x] `plays/sdu625_como_soeen/pitch_syngespil.md` is created
- [x] `plays/sdu625_como_soeen/plot_afbrydelsen.md` is created and casts company elements
- [x] `plays/sdu625_como_soeen/plot_boennen.md` is created and casts company elements
- [x] `plays/sdu625_como_soeen/plot_genforeningen.md` is created and casts company elements
- [x] The local validation tests (`npm test`) run successfully with zero errors
