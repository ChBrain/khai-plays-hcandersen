---
khai: order
title: "Stage SDU 613"
language: english
license: CC-BY-NC-SA-4.0
stamp:
  owner: KAI HACKS AI
  version: v0.0.1
  date: "2026-07-10"
---

# Order: Stage SDU 613

## Direction

The house must stage SDU 613 (_Den Usynlige paa Sprogø_) to establish the thirteenth work in the "Drama" genre. The production must model the comical vaudeville, featuring Agent Blomme, Ingeborg, and Theodor. It must model Sprogø during isvinter, the magic potion bottle piece, the processes representing the freezing winter and invisibility play, the plan to trick Blomme, the comical and carnivalesque tenor, and the three plots. All staging, prose, projections, actions, shadows, and tells must be authored in authentic Danish.

## Orders

1. The Playwright (Hans Christian Andersen) must author the play definition, the three personas (blomme, ingeborg, theodor), the three positions (usynlig, datter, elsker), the one piece (trylledrik), the one place (sprogoe), the two processes (isvinter, trylleri), the in-world plan (komedie), the pitch (spoeg), and the three plots.
2. The Theatre Manager (Edvard Collin) must verify the local registry, ensure correct versioning, check formatting, and validate that the entire cast conforms to the canon.
3. The Roadie (Vilhelm Pedersen) must set the stage, verify the local test suite is green, and prepare the files for packaging.

## Implementation

The play files must be placed in `plays/sdu613_usynlige/` and follow the house language policy:

- Structural elements and frontmatter in English.
- Narrative prose, projections, actions, shadows, tells, and staging notes in Danish.

## Targets

- [x] `plays/sdu613_usynlige/play_usynlige.md` is created and lists the complete company
- [x] `plays/sdu613_usynlige/persona_blomme.md` is created and links to `position_usynlig.md`
- [x] `plays/sdu613_usynlige/persona_ingeborg.md` is created and links to `position_datter.md`
- [x] `plays/sdu613_usynlige/persona_theodor.md` is created and links to `position_elsker.md`
- [x] `plays/sdu613_usynlige/position_usynlig.md` is created
- [x] `plays/sdu613_usynlige/position_datter.md` is created
- [x] `plays/sdu613_usynlige/position_elsker.md` is created
- [x] `plays/sdu613_usynlige/piece_trylledrik.md` is created
- [x] `plays/sdu613_usynlige/place_sprogoe.md` is created
- [x] `plays/sdu613_usynlige/process_isvinter.md` is created
- [x] `plays/sdu613_usynlige/process_trylleri.md` is created
- [x] `plays/sdu613_usynlige/plan_komedie.md` is created
- [x] `plays/sdu613_usynlige/pitch_spoeg.md` is created
- [x] `plays/sdu613_usynlige/plot_strandingen.md` is created and casts company elements
- [x] `plays/sdu613_usynlige/plot_trylledrikken.md` is created and casts company elements
- [x] `plays/sdu613_usynlige/plot_genforeningen.md` is created and casts company elements
- [x] The local validation tests (`npm test`) run successfully with zero errors
