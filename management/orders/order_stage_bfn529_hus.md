---
khai: order
title: "Stage BFN 529 Det gamle Hus"
language: english
license: CC-BY-NC-SA-4.0
stamp:
  owner: KAI HACKS AI
  version: v0.0.1
  date: "2026-06-21"
---

# Order: Stage BFN 529 Det gamle Hus

## Direction

The house must stage BFN 529 (_Det gamle Hus_) to establish the thirty-ninth production in the H.C. Andersen house. The production must model Gamle mand, Drengen, the positions (Ensom, Medfoelende), the piece (Tinsoldat), the environments (Stuen, Haven), the erindring and forfald processes, and the plots leading to their realization. It must be written in authentic Danish for all prose sections.

## Orders

1. The Playwright (Hans Christian Andersen) must author the play definition, the two personas, the two positions, the piece, the two places, the two processes, the two in-world plans, the pitch of Nostalgi, and the four plots.
2. The Theatre Manager (Edvard Collin) must verify the local registry, ensure correct versioning, check formatting, and validate that the entire cast conforms to the canon.
3. The Roadie (Vilhelm Pedersen) must set the stage, verify the local test suite is green, and prepare the files for packaging.

## Implementation

The play files must be placed in `plays/bfn529_det_gamle_hus/` and follow the house language policy:

- Structural elements and frontmatter in English.
- Narrative prose, projections, actions, shadows, tells, and staging notes in Danish.

## Targets

- [x] `plays/bfn529_det_gamle_hus/play_det_gamle_hus.md` is created and lists the complete company
- [x] `plays/bfn529_det_gamle_hus/persona_gamle_mand.md` is created and links to `position_ensom.md`
- [x] `plays/bfn529_det_gamle_hus/persona_drengen.md` is created and links to `position_medfoelende.md`
- [x] `plays/bfn529_det_gamle_hus/position_ensom.md` is created
- [x] `plays/bfn529_det_gamle_hus/position_medfoelende.md` is created
- [x] `plays/bfn529_det_gamle_hus/piece_tinsoldat.md` is created
- [x] `plays/bfn529_det_gamle_hus/place_stuen.md` is created
- [x] `plays/bfn529_det_gamle_hus/place_haven.md` is created
- [x] `plays/bfn529_det_gamle_hus/process_erindring.md` is created
- [x] `plays/bfn529_det_gamle_hus/process_forfald.md` is created
- [x] `plays/bfn529_det_gamle_hus/plan_troest.md` is created and linked to `persona_gamle_mand.md`
- [x] `plays/bfn529_det_gamle_hus/plan_bevaring.md` is created and linked to `persona_drengen.md`
- [x] `plays/bfn529_det_gamle_hus/pitch_nostalgi.md` is created
- [x] `plays/bfn529_det_gamle_hus/plot_besoeg.md` is created and casts company elements
- [x] `plays/bfn529_det_gamle_hus/plot_tinsoldatens_klage.md` is created and casts company elements
- [x] `plays/bfn529_det_gamle_hus/plot_afsked.md` is created and casts company elements
- [x] `plays/bfn529_det_gamle_hus/plot_forvandling.md` is created and casts company elements
- [x] The local validation tests (`npm test`) run successfully with zero errors
