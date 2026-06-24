---
khai: order
title: "Stage BFN 817 De Vises Steen"
language: english
license: CC-BY-NC-SA-4.0
stamp:
  owner: KAI HACKS AI
  version: v0.0.1
  date: "2026-06-24"
---

# Order: Stage BFN 817 De Vises Steen

## Direction

The house must stage BFN 817 (_De Vises Steen_) to establish the eighty-first production in the H.C. Andersen house. The production must model Soegende, Skygge, the positions (Laengselsfuld, Vildledende), the piece (Bog), the environments (Paradis, Verden), the soegen and proevelse processes, and the plots leading to their realization. It must be written in authentic Danish for all prose sections.

## Orders

1. The Playwright (Hans Christian Andersen) must author the play definition, the two personas, the two positions, the piece, the two places, the two processes, the two in-world plans, the pitch of Mystik, and the four plots.
2. The Theatre Manager (Edvard Collin) must verify the local registry, ensure correct versioning, check formatting, and validate that the entire cast conforms to the canon.
3. The Roadie (Vilhelm Pedersen) must set the stage, verify the local test suite is green, and prepare the files for packaging.

## Implementation

The play files must be placed in `plays/bfn817_de_vises_steen/` and follow the house language policy:

- Structural elements and frontmatter in English.
- Narrative prose, projections, actions, shadows, tells, and staging notes in Danish.

## Targets

- [x] `plays/bfn817_de_vises_steen/play_de_vises_steen.md` is created and lists the complete company
- [x] `plays/bfn817_de_vises_steen/persona_soegende.md` is created and links to `position_laengselsfuld.md`
- [x] `plays/bfn817_de_vises_steen/persona_skygge.md` is created and links to `position_vildledende.md`
- [x] `plays/bfn817_de_vises_steen/position_laengselsfuld.md` is created
- [x] `plays/bfn817_de_vises_steen/position_vildledende.md` is created
- [x] `plays/bfn817_de_vises_steen/piece_bog.md` is created
- [x] `plays/bfn817_de_vises_steen/place_paradis.md` is created
- [x] `plays/bfn817_de_vises_steen/place_verden.md` is created
- [x] `plays/bfn817_de_vises_steen/process_soegen.md` is created
- [x] `plays/bfn817_de_vises_steen/process_proevelse.md` is created
- [x] `plays/bfn817_de_vises_steen/plan_afsloering.md` is created and linked to `persona_soegende.md`
- [x] `plays/bfn817_de_vises_steen/plan_vildledning.md` is created and linked to `persona_skygge.md`
- [x] `plays/bfn817_de_vises_steen/pitch_mystik.md` is created
- [x] `plays/bfn817_de_vises_steen/plot_udsendelsen.md` is created and casts company elements
- [x] `plays/bfn817_de_vises_steen/plot_verdensvandringen.md` is created and casts company elements
- [x] `plays/bfn817_de_vises_steen/plot_bedraget.md` is created and casts company elements
- [x] `plays/bfn817_de_vises_steen/plot_erkendelsen.md` is created and casts company elements
- [x] The local validation tests (`npm test`) run successfully with zero errors
