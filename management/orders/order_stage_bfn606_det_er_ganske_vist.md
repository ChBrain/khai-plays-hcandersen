---
khai: order
title: "Stage BFN 606 Det er ganske vist"
language: english
license: CC-BY-NC-SA-4.0
stamp:
  owner: KAI HACKS AI
  version: v0.0.1
  date: "2026-06-22"
---

# Order: Stage BFN 606 Det er ganske vist

## Direction

The house must stage BFN 606 (_Det er ganske vist_) to establish the fiftieth production in the H.C. Andersen house. The production must model Hons, Rygte, the positions (Tankeloes, Spreder), the piece (Fjer), the environments (Hoensehus, Skov), the sladder and forstoerrelse processes, and the plots leading to their realization. It must be written in authentic Danish for all prose sections.

## Orders

1. The Playwright (Hans Christian Andersen) must author the play definition, the two personas, the two positions, the piece, the two places, the two processes, the two in-world plans, the pitch of Satire, and the four plots.
2. The Theatre Manager (Edvard Collin) must verify the local registry, ensure correct versioning, check formatting, and validate that the entire cast conforms to the canon.
3. The Roadie (Vilhelm Pedersen) must set the stage, verify the local test suite is green, and prepare the files for packaging.

## Implementation

The play files must be placed in `plays/bfn606_det_er_ganske_vist/` and follow the house language policy:

- Structural elements and frontmatter in English.
- Narrative prose, projections, actions, shadows, tells, and staging notes in Danish.

## Targets

- [x] `plays/bfn606_det_er_ganske_vist/play_det_er_ganske_vist.md` is created and lists the complete company
- [x] `plays/bfn606_det_er_ganske_vist/persona_hons.md` is created and links to `position_tankeloes.md`
- [x] `plays/bfn606_det_er_ganske_vist/persona_rygte.md` is created and links to `position_spreder.md`
- [x] `plays/bfn606_det_er_ganske_vist/position_tankeloes.md` is created
- [x] `plays/bfn606_det_er_ganske_vist/position_spreder.md` is created
- [x] `plays/bfn606_det_er_ganske_vist/piece_fjer.md` is created
- [x] `plays/bfn606_det_er_ganske_vist/place_hoensehus.md` is created
- [x] `plays/bfn606_det_er_ganske_vist/place_skov.md` is created
- [x] `plays/bfn606_det_er_ganske_vist/process_sladder.md` is created
- [x] `plays/bfn606_det_er_ganske_vist/process_forstoerrelse.md` is created
- [x] `plays/bfn606_det_er_ganske_vist/plan_leg.md` is created and linked to `persona_hons.md`
- [x] `plays/bfn606_det_er_ganske_vist/plan_rygtespredning.md` is created and linked to `persona_rygte.md`
- [x] `plays/bfn606_det_er_ganske_vist/pitch_satire.md` is created
- [x] `plays/bfn606_det_er_ganske_vist/plot_fjertab.md` is created and casts company elements
- [x] `plays/bfn606_det_er_ganske_vist/plot_naboerne.md` is created and casts company elements
- [x] `plays/bfn606_det_er_ganske_vist/plot_skoven.md` is created and casts company elements
- [x] `plays/bfn606_det_er_ganske_vist/plot_avis.md` is created and casts company elements
- [x] The local validation tests (`npm test`) run successfully with zero errors
