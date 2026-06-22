---
khai: order
title: "Stage BFN 616 Nissen hos Spekhøkeren"
language: english
license: CC-BY-NC-SA-4.0
stamp:
  owner: KAI HACKS AI
  version: v0.0.1
  date: "2026-06-22"
---

# Order: Stage BFN 616 Nissen hos Spekhøkeren

## Direction

The house must stage BFN 616 (_Nissen hos Spekhøkeren_) to establish the fifty-fifth production in the H.C. Andersen house. The production must model Nisse, Student, the positions (Materiel, Poetisk), the piece (Bog), the environments (Butik, Loftkammer), the laesning and fristelse processes, and the plots leading to their realization. It must be written in authentic Danish for all prose sections.

## Orders

1. The Playwright (Hans Christian Andersen) must author the play definition, the two personas, the two positions, the piece, the two places, the two processes, the two in-world plans, the pitch of Andagt, and the four plots.
2. The Theatre Manager (Edvard Collin) must verify the local registry, ensure correct versioning, check formatting, and validate that the entire cast conforms to the canon.
3. The Roadie (Vilhelm Pedersen) must set the stage, verify the local test suite is green, and prepare the files for packaging.

## Implementation

The play files must be placed in `plays/bfn616_nissen_hos_spekhoekeren/` and follow the house language policy:

- Structural elements and frontmatter in English.
- Narrative prose, projections, actions, shadows, tells, and staging notes in Danish.

## Targets

- [x] `plays/bfn616_nissen_hos_spekhoekeren/play_nissen_hos_spekhoekeren.md` is created and lists the complete company
- [x] `plays/bfn616_nissen_hos_spekhoekeren/persona_nisse.md` is created and links to `position_materiel.md`
- [x] `plays/bfn616_nissen_hos_spekhoekeren/persona_student.md` is created and links to `position_poetisk.md`
- [x] `plays/bfn616_nissen_hos_spekhoekeren/position_materiel.md` is created
- [x] `plays/bfn616_nissen_hos_spekhoekeren/position_poetisk.md` is created
- [x] `plays/bfn616_nissen_hos_spekhoekeren/piece_bog.md` is created
- [x] `plays/bfn616_nissen_hos_spekhoekeren/place_butik.md` is created
- [x] `plays/bfn616_nissen_hos_spekhoekeren/place_loftkammer.md` is created
- [x] `plays/bfn616_nissen_hos_spekhoekeren/process_laesning.md` is created
- [x] `plays/bfn616_nissen_hos_spekhoekeren/process_fristelse.md` is created
- [x] `plays/bfn616_nissen_hos_spekhoekeren/plan_groedsoeg.md` is created and linked to `persona_nisse.md`
- [x] `plays/bfn616_nissen_hos_spekhoekeren/plan_aandssoeg.md` is created and linked to `persona_student.md`
- [x] `plays/bfn616_nissen_hos_spekhoekeren/pitch_andagt.md` is created
- [x] `plays/bfn616_nissen_hos_spekhoekeren/plot_butikken.md` is created and casts company elements
- [x] `plays/bfn616_nissen_hos_spekhoekeren/plot_loftet.md` is created and casts company elements
- [x] `plays/bfn616_nissen_hos_spekhoekeren/plot_brand.md` is created and casts company elements
- [x] `plays/bfn616_nissen_hos_spekhoekeren/plot_valg.md` is created and casts company elements
- [x] The local validation tests (`npm test`) run successfully with zero errors
