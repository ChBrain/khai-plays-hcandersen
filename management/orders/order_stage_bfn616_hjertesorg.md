---
khai: order
title: "Stage BFN 616 Hjertesorg"
language: english
license: CC-BY-NC-SA-4.0
stamp:
  owner: KAI HACKS AI
  version: v0.0.1
  date: "2026-06-22"
---

# Order: Stage BFN 616 Hjertesorg

## Direction

The house must stage BFN 616 (_Hjertesorg_) to establish the fifty-third production in the H.C. Andersen house. The production must model Niese, Dreng, the positions (Handler, Udelukket), the piece (Knap), the environments (Have, Port), the handel and sorg processes, and the plots leading to their realization. It must be written in authentic Danish for all prose sections.

## Orders

1. The Playwright (Hans Christian Andersen) must author the play definition, the two personas, the two positions, the piece, the two places, the two processes, the two in-world plans, the pitch of Humor, and the four plots.
2. The Theatre Manager (Edvard Collin) must verify the local registry, ensure correct versioning, check formatting, and validate that the entire cast conforms to the canon.
3. The Roadie (Vilhelm Pedersen) must set the stage, verify the local test suite is green, and prepare the files for packaging.

## Implementation

The play files must be placed in `plays/bfn616_hjertesorg/` and follow the house language policy:

- Structural elements and frontmatter in English.
- Narrative prose, projections, actions, shadows, tells, and staging notes in Danish.

## Targets

- [x] `plays/bfn616_hjertesorg/play_hjertesorg.md` is created and lists the complete company
- [x] `plays/bfn616_hjertesorg/persona_niese.md` is created and links to `position_handler.md`
- [x] `plays/bfn616_hjertesorg/persona_dreng.md` is created and links to `position_udelukket.md`
- [x] `plays/bfn616_hjertesorg/position_handler.md` is created
- [x] `plays/bfn616_hjertesorg/position_udelukket.md` is created
- [x] `plays/bfn616_hjertesorg/piece_knap.md` is created
- [x] `plays/bfn616_hjertesorg/place_have.md` is created
- [x] `plays/bfn616_hjertesorg/place_port.md` is created
- [x] `plays/bfn616_hjertesorg/process_handel.md` is created
- [x] `plays/bfn616_hjertesorg/process_sorg.md` is created
- [x] `plays/bfn616_hjertesorg/plan_gravegilde.md` is created and linked to `persona_niese.md`
- [x] `plays/bfn616_hjertesorg/plan_kigen.md` is created and linked to `persona_dreng.md`
- [x] `plays/bfn616_hjertesorg/pitch_humor.md` is created
- [x] `plays/bfn616_hjertesorg/plot_grav.md` is created and casts company elements
- [x] `plays/bfn616_hjertesorg/plot_adgang.md` is created and casts company elements
- [x] `plays/bfn616_hjertesorg/plot_sorg.md` is created and casts company elements
- [x] `plays/bfn616_hjertesorg/plot_refleksion.md` is created and casts company elements
- [x] The local validation tests (`npm test`) run successfully with zero errors
