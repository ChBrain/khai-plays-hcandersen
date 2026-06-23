---
khai: order
title: "Stage BFN 794 Deilig"
language: english
license: CC-BY-NC-SA-4.0
stamp:
  owner: KAI HACKS AI
  version: v0.0.1
  date: "2026-06-23"
---

# Order: Stage BFN 794 Deilig

## Direction

The house must stage BFN 794 (_Deilig!_) to establish the seventy-third production in the H.C. Andersen house. The production must model Kunstner, Kone, the positions (Soegende, Praktisk), the piece (Billede), the environments (Atelier, Grav), the skabelse and forgaengelighed processes, and the plots leading to their realization. It must be written in authentic Danish for all prose sections.

## Orders

1. The Playwright (Hans Christian Andersen) must author the play definition, the two personas, the two positions, the piece, the two places, the two processes, the two in-world plans, the pitch of Melankoli, and the four plots.
2. The Theatre Manager (Edvard Collin) must verify the local registry, ensure correct versioning, check formatting, and validate that the entire cast conforms to the canon.
3. The Roadie (Vilhelm Pedersen) must set the stage, verify the local test suite is green, and prepare the files for packaging.

## Implementation

The play files must be placed in `plays/bfn794_deilig/` and follow the house language policy:

- Structural elements and frontmatter in English.
- Narrative prose, projections, actions, shadows, tells, and staging notes in Danish.

## Targets

- [x] `plays/bfn794_deilig/play_deilig.md` is created and lists the complete company
- [x] `plays/bfn794_deilig/persona_kunstner.md` is created and links to `position_soegende.md`
- [x] `plays/bfn794_deilig/persona_kone.md` is created and links to `position_praktisk.md`
- [x] `plays/bfn794_deilig/position_soegende.md` is created
- [x] `plays/bfn794_deilig/position_praktisk.md` is created
- [x] `plays/bfn794_deilig/piece_billede.md` is created
- [x] `plays/bfn794_deilig/place_atelier.md` is created
- [x] `plays/bfn794_deilig/place_grav.md` is created
- [x] `plays/bfn794_deilig/process_skabelse.md` is created
- [x] `plays/bfn794_deilig/process_forgaengelighed.md` is created
- [x] `plays/bfn794_deilig/plan_aabenbaring.md` is created and linked to `persona_kunstner.md`
- [x] `plays/bfn794_deilig/plan_husholdning.md` is created and linked to `persona_kone.md`
- [x] `plays/bfn794_deilig/pitch_melankoli.md` is created
- [x] `plays/bfn794_deilig/plot_soegen.md` is created and casts company elements
- [x] `plays/bfn794_deilig/plot_aegteskab.md` is created and casts company elements
- [x] `plays/bfn794_deilig/plot_tab.md` is created and casts company elements
- [x] `plays/bfn794_deilig/plot_erkendelse.md` is created and casts company elements
- [x] The local validation tests (`npm test`) run successfully with zero errors
