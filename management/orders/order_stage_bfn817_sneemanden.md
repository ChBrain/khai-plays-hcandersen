---
khai: order
title: "Stage BFN 817 Sneemanden"
language: english
license: CC-BY-NC-SA-4.0
stamp:
  owner: KAI HACKS AI
  version: v0.0.1
  date: "2026-06-24"
---

# Order: Stage BFN 817 Sneemanden

## Direction

The house must stage BFN 817 (_Sneemanden_) to establish the eighty-second production in the H.C. Andersen house. The production must model Sneemand, Laenkehund, the positions (Laengselsfuld, Erfaren), the piece (Kakkelovn), the environments (Gaard, Koecken), the frysning and forgaengelighed processes, and the plots leading to their realization. It must be written in authentic Danish for all prose sections.

## Orders

1. The Playwright (Hans Christian Andersen) must author the play definition, the two personas, the two positions, the piece, the two places, the two processes, the two in-world plans, the pitch of Melankoli, and the four plots.
2. The Theatre Manager (Edvard Collin) must verify the local registry, ensure correct versioning, check formatting, and validate that the entire cast conforms to the canon.
3. The Roadie (Vilhelm Pedersen) must set the stage, verify the local test suite is green, and prepare the files for packaging.

## Implementation

The play files must be placed in `plays/bfn817_sneemanden/` and follow the house language policy:

- Structural elements and frontmatter in English.
- Narrative prose, projections, actions, shadows, tells, and staging notes in Danish.

## Targets

- [x] `plays/bfn817_sneemanden/play_sneemanden.md` is created and lists the complete company
- [x] `plays/bfn817_sneemanden/persona_sneemand.md` is created and links to `position_laengselsfuld.md`
- [x] `plays/bfn817_sneemanden/persona_laenkehund.md` is created and links to `position_erfaren.md`
- [x] `plays/bfn817_sneemanden/position_laengselsfuld.md` is created
- [x] `plays/bfn817_sneemanden/position_erfaren.md` is created
- [x] `plays/bfn817_sneemanden/piece_kakkelovn.md` is created
- [x] `plays/bfn817_sneemanden/place_gaard.md` is created
- [x] `plays/bfn817_sneemanden/place_koecken.md` is created
- [x] `plays/bfn817_sneemanden/process_frysning.md` is created
- [x] `plays/bfn817_sneemanden/process_forgaengelighed.md` is created
- [x] `plays/bfn817_sneemanden/plan_sammensmeltning.md` is created and linked to `persona_sneemand.md`
- [x] `plays/bfn817_sneemanden/plan_livserfaring.md` is created and linked to `persona_laenkehund.md`
- [x] `plays/bfn817_sneemanden/pitch_melankoli.md` is created
- [x] `plays/bfn817_sneemanden/plot_skabelsen.md` is created and casts company elements
- [x] `plays/bfn817_sneemanden/plot_laengslen.md` is created and casts company elements
- [x] `plays/bfn817_sneemanden/plot_forandringen.md` is created and casts company elements
- [x] `plays/bfn817_sneemanden/plot_smeltningen.md` is created and casts company elements
- [x] The local validation tests (`npm test`) run successfully with zero errors
