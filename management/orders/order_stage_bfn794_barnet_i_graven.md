---
khai: order
title: "Stage BFN 794 Barnet i Graven"
language: english
license: CC-BY-NC-SA-4.0
stamp:
  owner: KAI HACKS AI
  version: v0.0.1
  date: "2026-06-23"
---

# Order: Stage BFN 794 Barnet i Graven

## Direction

The house must stage BFN 794 (_Barnet i Graven_) to establish the seventy-sixth production in the H.C. Andersen house. The production must model Moder, Mand, the positions (Soergende, Troestende), the piece (Grav), the environments (Hjem, Kirkegaard), the sorg and erkendelse processes, and the plots leading to their realization. It must be written in authentic Danish for all prose sections.

## Orders

1. The Playwright (Hans Christian Andersen) must author the play definition, the two personas, the two positions, the piece, the two places, the two processes, the two in-world plans, the pitch of Patos, and the four plots.
2. The Theatre Manager (Edvard Collin) must verify the local registry, ensure correct versioning, check formatting, and validate that the entire cast conforms to the canon.
3. The Roadie (Vilhelm Pedersen) must set the stage, verify the local test suite is green, and prepare the files for packaging.

## Implementation

The play files must be placed in `plays/bfn794_barnet_i_graven/` and follow the house language policy:

- Structural elements and frontmatter in English.
- Narrative prose, projections, actions, shadows, tells, and staging notes in Danish.

## Targets

- [x] `plays/bfn794_barnet_i_graven/play_barnet_i_graven.md` is created and lists the complete company
- [x] `plays/bfn794_barnet_i_graven/persona_moder.md` is created and links to `position_soergende.md`
- [x] `plays/bfn794_barnet_i_graven/persona_mand.md` is created and links to `position_troestende.md`
- [x] `plays/bfn794_barnet_i_graven/position_soergende.md` is created
- [x] `plays/bfn794_barnet_i_graven/position_troestende.md` is created
- [x] `plays/bfn794_barnet_i_graven/piece_grav.md` is created
- [x] `plays/bfn794_barnet_i_graven/place_hjem.md` is created
- [x] `plays/bfn794_barnet_i_graven/place_kirkegaard.md` is created
- [x] `plays/bfn794_barnet_i_graven/process_sorg.md` is created
- [x] `plays/bfn794_barnet_i_graven/process_erkendelse.md` is created
- [x] `plays/bfn794_barnet_i_graven/plan_selvfortabelse.md` is created and linked to `persona_moder.md`
- [x] `plays/bfn794_barnet_i_graven/plan_livsfortsaettelse.md` is created and linked to `persona_mand.md`
- [x] `plays/bfn794_barnet_i_graven/pitch_patos.md` is created
- [x] `plays/bfn794_barnet_i_graven/plot_tabet.md` is created and casts company elements
- [x] `plays/bfn794_barnet_i_graven/plot_graven.md` is created and casts company elements
- [x] `plays/bfn794_barnet_i_graven/plot_aabenbaringen.md` is created and casts company elements
- [x] `plays/bfn794_barnet_i_graven/plot_freden.md` is created and casts company elements
- [x] The local validation tests (`npm test`) run successfully with zero errors
