---
khai: order
title: "Stage BFN 782 Anne Lisbeth"
language: english
license: CC-BY-NC-SA-4.0
stamp:
  owner: KAI HACKS AI
  version: v0.0.1
  date: "2026-06-23"
---

# Order: Stage BFN 782 Anne Lisbeth

## Direction

The house must stage BFN 782 (_Anne Lisbeth_) to establish the seventy-first production in the H.C. Andersen house. The production must model Anne_Lisbeth, Druknet_Barn, the positions (Synder, Paaminder), the piece (Gravsten), the environments (Herregaard, Strand), the fornegtelse and anger processes, and the plots leading to their realization. It must be written in authentic Danish for all prose sections.

## Orders

1. The Playwright (Hans Christian Andersen) must author the play definition, the two personas, the two positions, the piece, the two places, the two processes, the two in-world plans, the pitch of Skyld, and the four plots.
2. The Theatre Manager (Edvard Collin) must verify the local registry, ensure correct versioning, check formatting, and validate that the entire cast conforms to the canon.
3. The Roadie (Vilhelm Pedersen) must set the stage, verify the local test suite is green, and prepare the files for packaging.

## Implementation

The play files must be placed in `plays/bfn782_anne_lisbeth/` and follow the house language policy:

- Structural elements and frontmatter in English.
- Narrative prose, projections, actions, shadows, tells, and staging notes in Danish.

## Targets

- [x] `plays/bfn782_anne_lisbeth/play_anne_lisbeth.md` is created and lists the complete company
- [x] `plays/bfn782_anne_lisbeth/persona_anne_lisbeth.md` is created and links to `position_synder.md`
- [x] `plays/bfn782_anne_lisbeth/persona_druknet_barn.md` is created and links to `position_paaminder.md`
- [x] `plays/bfn782_anne_lisbeth/position_synder.md` is created
- [x] `plays/bfn782_anne_lisbeth/position_paaminder.md` is created
- [x] `plays/bfn782_anne_lisbeth/piece_gravsten.md` is created
- [x] `plays/bfn782_anne_lisbeth/place_herregaard.md` is created
- [x] `plays/bfn782_anne_lisbeth/place_strand.md` is created
- [x] `plays/bfn782_anne_lisbeth/process_fornegtelse.md` is created
- [x] `plays/bfn782_anne_lisbeth/process_anger.md` is created
- [x] `plays/bfn782_anne_lisbeth/plan_statussoegen.md` is created and linked to `persona_anne_lisbeth.md`
- [x] `plays/bfn782_anne_lisbeth/plan_soning.md` is created and linked to `persona_anne_lisbeth.md`
- [x] `plays/bfn782_anne_lisbeth/pitch_skyld.md` is created
- [x] `plays/bfn782_anne_lisbeth/plot_adskillelse.md` is created and casts company elements
- [x] `plays/bfn782_anne_lisbeth/plot_tabet.md` is created and casts company elements
- [x] `plays/bfn782_anne_lisbeth/plot_spoegelse.md` is created and casts company elements
- [x] `plays/bfn782_anne_lisbeth/plot_graven.md` is created and casts company elements
- [x] The local validation tests (`npm test`) run successfully with zero errors
