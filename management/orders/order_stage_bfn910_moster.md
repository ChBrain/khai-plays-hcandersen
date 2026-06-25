---
khai: order
title: "Stage BFN 910 Moster"
language: english
license: CC-BY-NC-SA-4.0
stamp:
  owner: KAI HACKS AI
  version: v0.0.1
  date: "2026-06-25"
---

# Order: Stage BFN 910 Moster

## Direction

The house must stage BFN 910 (_Moster_) to establish the one-hundred-and-first production in the H.C. Andersen house. The production must model Moster, Sivertsen, and Agent Fab, the positions (Komediegal, Maskinmester, Drilagtig), the pieces (Suurdeig, Rullepølsemad, Kanestøvler), the environments (Teaterloge, Teaterloft), the abonnementsliv and teatergalskab processes, and the plots detailing her theatrical devotion, the attic antics, the sleep judgment vision, and the boot fire panic. It must be written in authentic Danish for all prose sections.

## Orders

1. The Playwright (Hans Christian Andersen) must author the play definition, the three personas, the three positions, the three pieces, the two places, the two processes, the two in-world plans, the pitch of Teaterliv, and the four plots.
2. The Theatre Manager (Edvard Collin) must verify the local registry, ensure correct versioning, check formatting, and validate that the cast conforms to the canon.
3. The Roadie (Vilhelm Pedersen) must set the stage, verify the local test suite is green, and prepare the files for packaging.

## Implementation

The play files must be placed in `plays/bfn910_moster/` and follow the house language policy:

- Structural elements and frontmatter in English.
- Narrative prose, projections, actions, shadows, tells, and staging notes in Danish.

## Targets

- [x] `plays/bfn910_moster/play_moster.md` is created and lists the complete company
- [x] `plays/bfn910_moster/persona_moster.md` is created and links to `position_komediegal.md`
- [x] `plays/bfn910_moster/persona_sivertsen.md` is created and links to `position_maskinmester.md`
- [x] `plays/bfn910_moster/persona_agent_fab.md` is created and links to `position_drilagtig.md`
- [x] `plays/bfn910_moster/position_komediegal.md` is created
- [x] `plays/bfn910_moster/position_maskinmester.md` is created
- [x] `plays/bfn910_moster/position_drilagtig.md` is created
- [x] `plays/bfn910_moster/piece_suurdeig.md` is created
- [x] `plays/bfn910_moster/piece_rullepoelsemad.md` is created
- [x] `plays/bfn910_moster/piece_kanestoevler.md` is created
- [x] `plays/bfn910_moster/place_teaterloge.md` is created
- [x] `plays/bfn910_moster/place_teaterloft.md` is created
- [x] `plays/bfn910_moster/process_abonnementsliv.md` is created
- [x] `plays/bfn910_moster/process_teatergalskab.md` is created
- [x] `plays/bfn910_moster/plan_forestilling.md` is created and linked to `persona_moster.md`
- [x] `plays/bfn910_moster/plan_maskineri.md` is created and linked to `persona_sivertsen.md`
- [x] `plays/bfn910_moster/pitch_teaterliv.md` is created
- [x] `plays/bfn910_moster/plot_teaterglaeden.md` is created and casts company elements
- [x] `plays/bfn910_moster/plot_loftet.md` is created and casts company elements
- [x] `plays/bfn910_moster/plot_agenten.md` is created and casts company elements
- [x] `plays/bfn910_moster/plot_branden.md` is created and casts company elements
- [x] The local validation tests (`npm test`) run successfully with zero errors
