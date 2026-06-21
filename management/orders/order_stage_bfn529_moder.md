---
khai: order
title: "Stage BFN 529 Historien om en moder"
language: english
license: CC-BY-NC-SA-4.0
stamp:
  owner: KAI HACKS AI
  version: v0.0.1
  date: "2026-06-21"
---

# Order: Stage BFN 529 Historien om en moder

## Direction

The house must stage BFN 529 (_Historien om en moder_) to establish the forty-third production in the H.C. Andersen house. The production must model Moderen, Doeden, the positions (Opofrende, Hoster), the piece (Barnesjael), the environments (Drivhus, Verden), the rejse and kapitulation processes, and the plots leading to their realization. It must be written in authentic Danish for all prose sections.

## Orders

1. The Playwright (Hans Christian Andersen) must author the play definition, the two personas, the two positions, the piece, the two places, the two processes, the two in-world plans, the pitch of Patos, and the four plots.
2. The Theatre Manager (Edvard Collin) must verify the local registry, ensure correct versioning, check formatting, and validate that the entire cast conforms to the canon.
3. The Roadie (Vilhelm Pedersen) must set the stage, verify the local test suite is green, and prepare the files for packaging.

## Implementation

The play files must be placed in `plays/bfn529_historien_om_en_moder/` and follow the house language policy:

- Structural elements and frontmatter in English.
- Narrative prose, projections, actions, shadows, tells, and staging notes in Danish.

## Targets

- [x] `plays/bfn529_historien_om_en_moder/play_historien_om_en_moder.md` is created and lists the complete company
- [x] `plays/bfn529_historien_om_en_moder/persona_moderen.md` is created and links to `position_opofrende.md`
- [x] `plays/bfn529_historien_om_en_moder/persona_doeden.md` is created and links to `position_hoster.md`
- [x] `plays/bfn529_historien_om_en_moder/position_opofrende.md` is created
- [x] `plays/bfn529_historien_om_en_moder/position_hoster.md` is created
- [x] `plays/bfn529_historien_om_en_moder/piece_barnesjael.md` is created
- [x] `plays/bfn529_historien_om_en_moder/place_drivhus.md` is created
- [x] `plays/bfn529_historien_om_en_moder/place_verden.md` is created
- [x] `plays/bfn529_historien_om_en_moder/process_rejse.md` is created
- [x] `plays/bfn529_historien_om_en_moder/process_kapitulation.md` is created
- [x] `plays/bfn529_historien_om_en_moder/plan_redning.md` is created and linked to `persona_moderen.md`
- [x] `plays/bfn529_historien_om_en_moder/plan_doedsrejse.md` is created and linked to `persona_doeden.md`
- [x] `plays/bfn529_historien_om_en_moder/pitch_patos.md` is created
- [x] `plays/bfn529_historien_om_en_moder/plot_barnets_doed.md` is created and casts company elements
- [x] `plays/bfn529_historien_om_en_moder/plot_rejsen.md` is created and casts company elements
- [x] `plays/bfn529_historien_om_en_moder/plot_drivhuset.md` is created and casts company elements
- [x] `plays/bfn529_historien_om_en_moder/plot_overgivelsen.md` is created and casts company elements
- [x] The local validation tests (`npm test`) run successfully with zero errors
