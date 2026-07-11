---
khai: order
title: "Stage SDU 623"
language: english
license: CC-BY-NC-SA-4.0
stamp:
  owner: KAI HACKS AI
  version: v0.0.1
  date: "2026-07-10"
---

# Order: Stage SDU 623

## Direction

The house must stage SDU 623 (_Ahasverus_) to establish the twenty-third work in the "Drama" genre. The production must model the grand, epic dialogues of Ahasverus, Titus, and the Angel of the Lord. It must model the Gate of Jerusalem, the wandering staff piece, the processes representing the eternal curse and the historical destruction, Ahasverus' plan for inner peace, the epic verse tone, and the three plots. All staging, prose, projections, actions, shadows, and tells must be authored in authentic Danish.

## Orders

1. The Playwright (Hans Christian Andersen) must author the play definition, the three personas (ahasverus, titus, engel), the three positions (udstoedte, erobrer, sendebud), the one piece (stav), the one place (port), the two processes (forbandelse, verdensdom), the in-world plan (sjaelefred), the pitch (episk_digt), and the three plots.
2. The Theatre Manager (Edvard Collin) must verify the local registry, ensure correct versioning, check formatting, and validate that the entire cast conforms to the canon.
3. The Roadie (Vilhelm Pedersen) must set the stage, verify the local test suite is green, and prepare the files for packaging.

## Implementation

The play files must be placed in `plays/sdu623_ahasverus/` and follow the house language policy:

- Structural elements and frontmatter in English.
- Narrative prose, projections, actions, shadows, tells, and staging notes in Danish.

## Targets

- [x] `plays/sdu623_ahasverus/play_ahasverus.md` is created and lists the complete company
- [x] `plays/sdu623_ahasverus/persona_ahasverus.md` is created and links to `position_udstoedte.md`
- [x] `plays/sdu623_ahasverus/persona_titus.md` is created and links to `position_erobrer.md`
- [x] `plays/sdu623_ahasverus/persona_engel.md` is created and links to `position_sendebud.md`
- [x] `plays/sdu623_ahasverus/position_udstoedte.md` is created
- [x] `plays/sdu623_ahasverus/position_erobrer.md` is created
- [x] `plays/sdu623_ahasverus/position_sendebud.md` is created
- [x] `plays/sdu623_ahasverus/piece_stav.md` is created
- [x] `plays/sdu623_ahasverus/place_port.md` is created
- [x] `plays/sdu623_ahasverus/process_forbandelse.md` is created
- [x] `plays/sdu623_ahasverus/process_verdensdom.md` is created
- [x] `plays/sdu623_ahasverus/plan_sjaelefred.md` is created
- [x] `plays/sdu623_ahasverus/pitch_episk_digt.md` is created
- [x] `plays/sdu623_ahasverus/plot_jerusalems_fald.md` is created and casts company elements
- [x] `plays/sdu623_ahasverus/plot_tidernes_stroem.md` is created and casts company elements
- [x] `plays/sdu623_ahasverus/plot_nyt_haab.md` is created and casts company elements
- [x] The local validation tests (`npm test`) run successfully with zero errors
