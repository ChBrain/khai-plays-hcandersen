---
khai: order
title: "Stage BFN 771 Det gamle Egetraes sidste Droem"
language: english
license: CC-BY-NC-SA-4.0
stamp:
  owner: KAI HACKS AI
  version: v0.0.1
  date: "2026-06-23"
---

# Order: Stage BFN 771 Det gamle Egetraes sidste Droem

## Direction

The house must stage BFN 771 (_Det gamle Egetræes sidste Drøm_) to establish the sixty-seventh production in the H.C. Andersen house. The production must model Egetrae, Dryade, the positions (Vidne, Doende), the piece (Gren), the environments (Skov, Droemmerum), the vaekst and fald processes, and the plots leading to their realization. It must be written in authentic Danish for all prose sections.

## Orders

1. The Playwright (Hans Christian Andersen) must author the play definition, the two personas, the two positions, the piece, the two places, the two processes, the two in-world plans, the pitch of Andagt, and the four plots.
2. The Theatre Manager (Edvard Collin) must verify the local registry, ensure correct versioning, check formatting, and validate that the entire cast conforms to the canon.
3. The Roadie (Vilhelm Pedersen) must set the stage, verify the local test suite is green, and prepare the files for packaging.

## Implementation

The play files must be placed in `plays/bfn771_det_gamle_egetraes_sidste_droem/` and follow the house language policy:

- Structural elements and frontmatter in English.
- Narrative prose, projections, actions, shadows, tells, and staging notes in Danish.

## Targets

- [x] `plays/bfn771_det_gamle_egetraes_sidste_droem/play_det_gamle_egetraes_sidste_droem.md` is created and lists the complete company
- [x] `plays/bfn771_det_gamle_egetraes_sidste_droem/persona_egetrae.md` is created and links to `position_vidne.md`
- [x] `plays/bfn771_det_gamle_egetraes_sidste_droem/persona_dryade.md` is created and links to `position_doende.md`
- [x] `plays/bfn771_det_gamle_egetraes_sidste_droem/position_vidne.md` is created
- [x] `plays/bfn771_det_gamle_egetraes_sidste_droem/position_doende.md` is created
- [x] `plays/bfn771_det_gamle_egetraes_sidste_droem/piece_gren.md` is created
- [x] `plays/bfn771_det_gamle_egetraes_sidste_droem/place_skov.md` is created
- [x] `plays/bfn771_det_gamle_egetraes_sidste_droem/place_droemmerum.md` is created
- [x] `plays/bfn771_det_gamle_egetraes_sidste_droem/process_vaekst.md` is created
- [x] `plays/bfn771_det_gamle_egetraes_sidste_droem/process_fald.md` is created
- [x] `plays/bfn771_det_gamle_egetraes_sidste_droem/plan_livsforlaengelse.md` is created and linked to `persona_egetrae.md`
- [x] `plays/bfn771_det_gamle_egetraes_sidste_droem/plan_forening.md` is created and linked to `persona_dryade.md`
- [x] `plays/bfn771_det_gamle_egetraes_sidste_droem/pitch_andagt.md` is created
- [x] `plays/bfn771_det_gamle_egetraes_sidste_droem/plot_julenat.md` is created and casts company elements
- [x] `plays/bfn771_det_gamle_egetraes_sidste_droem/plot_droemmen.md` is created and casts company elements
- [x] `plays/bfn771_det_gamle_egetraes_sidste_droem/plot_stormen.md` is created and casts company elements
- [x] `plays/bfn771_det_gamle_egetraes_sidste_droem/plot_forvandling.md` is created and casts company elements
- [x] The local validation tests (`npm test`) run successfully with zero errors
