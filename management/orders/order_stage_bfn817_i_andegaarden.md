---
khai: order
title: "Stage BFN 817 I Andegaarden"
language: english
license: CC-BY-NC-SA-4.0
stamp:
  owner: KAI HACKS AI
  version: v0.0.1
  date: "2026-06-24"
---

# Order: Stage BFN 817 I Andegaarden

## Direction

The house must stage BFN 817 (_I Andegaarden_) to establish the eighty-five production in the H.C. Andersen house. The production must model Portugiser, Sangfugl, the positions (Hersker, Fremmed), the piece (Foede), the environments (Andegaard, Haven), the socialisering and udstoedelse processes, and the plots leading to their realization. It must be written in authentic Danish for all prose sections.

## Orders

1. The Playwright (Hans Christian Andersen) must author the play definition, the two personas, the two positions, the piece, the two places, the two processes, the two in-world plans, the pitch of Satire, and the four plots.
2. The Theatre Manager (Edvard Collin) must verify the local registry, ensure correct versioning, check formatting, and validate that the cast conforms to the canon.
3. The Roadie (Vilhelm Pedersen) must set the stage, verify the local test suite is green, and prepare the files for packaging.

## Implementation

The play files must be placed in `plays/bfn817_i_andegaarden/` and follow the house language policy:

- Structural elements and frontmatter in English.
- Narrative prose, projections, actions, shadows, tells, and staging notes in Danish.

## Targets

- [x] `plays/bfn817_i_andegaarden/play_i_andegaarden.md` is created and lists the complete company
- [x] `plays/bfn817_i_andegaarden/persona_portugiser.md` is created and links to `position_hersker.md`
- [x] `plays/bfn817_i_andegaarden/persona_sangfugl.md` is created and links to `position_fremmed.md`
- [x] `plays/bfn817_i_andegaarden/position_hersker.md` is created
- [x] `plays/bfn817_i_andegaarden/position_fremmed.md` is created
- [x] `plays/bfn817_i_andegaarden/piece_foede.md` is created
- [x] `plays/bfn817_i_andegaarden/place_andegaard.md` is created
- [x] `plays/bfn817_i_andegaarden/place_haven.md` is created
- [x] `plays/bfn817_i_andegaarden/process_socialisering.md` is created
- [x] `plays/bfn817_i_andegaarden/process_udstoedelse.md` is created
- [x] `plays/bfn817_i_andegaarden/plan_selvhaevelse.md` is created and linked to `persona_portugiser.md`
- [x] `plays/bfn817_i_andegaarden/plan_overlevelse.md` is created and linked to `persona_sangfugl.md`
- [x] `plays/bfn817_i_andegaarden/pitch_satire.md` is created
- [x] `plays/bfn817_i_andegaarden/plot_ankomsten.md` is created and casts company elements
- [x] `plays/bfn817_i_andegaarden/plot_plejen.md` is created and casts company elements
- [x] `plays/bfn817_i_andegaarden/plot_vendingen.md` is created and casts company elements
- [x] `plays/bfn817_i_andegaarden/plot_udfald.md` is created and casts company elements
- [x] The local validation tests (`npm test`) run successfully with zero errors
