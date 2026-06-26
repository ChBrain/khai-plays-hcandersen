---
khai: order
title: "Stage BFN 833 Den gamle Kirkeklokke"
language: english
license: CC-BY-NC-SA-4.0
stamp:
  owner: KAI HACKS AI
  version: v0.0.1
  date: "2026-06-26"
---

# Order: Stage BFN 833 Den gamle Kirkeklokke

## Direction

The house must stage BFN 833 (_Den gamle Kirkeklokke_) to establish a production in the H.C. Andersen house. The production must model klokken, digterbarnet, the positions (klingende, inspireret), the pieces (smelteovn, stoebeform), the environments (taarnet, stoeberiet), the forvandling and inspiration processes, and the plots representing stoebningen and klingningen. It must be written in authentic Danish for all prose sections.

## Orders

1. The Playwright (Hans Christian Andersen) must author the play definition, the 2 personas, the 2 positions, the 2 pieces, the 2 places, the 2 processes, the 2 in-world plans, the pitch of hoejtidelig, and the 2 plots.
2. The Theatre Manager (Edvard Collin) must verify the local registry, ensure correct versioning, check formatting, and validate that the cast conforms to the canon.
3. The Roadie (Vilhelm Pedersen) must set the stage, verify the local test suite is green, and prepare the files for packaging.

## Implementation

The play files must be placed in `plays/bfn833_den_gamle_kirkeklokke/` and follow the house language policy:

- Structural elements and frontmatter in English.
- Narrative prose, projections, actions, shadows, tells, and staging notes in Danish.

## Targets

- [x] `plays/bfn833_den_gamle_kirkeklokke/play_den_gamle_kirkeklokke.md` is created and lists the complete company
- [x] `plays/bfn833_den_gamle_kirkeklokke/persona_klokken.md` is created and links to `position_klingende.md`
- [x] `plays/bfn833_den_gamle_kirkeklokke/persona_digterbarnet.md` is created and links to `position_inspireret.md`
- [x] `plays/bfn833_den_gamle_kirkeklokke/position_klingende.md` is created
- [x] `plays/bfn833_den_gamle_kirkeklokke/position_inspireret.md` is created
- [x] `plays/bfn833_den_gamle_kirkeklokke/piece_smelteovn.md` is created
- [x] `plays/bfn833_den_gamle_kirkeklokke/piece_stoebeform.md` is created
- [x] `plays/bfn833_den_gamle_kirkeklokke/place_taarnet.md` is created
- [x] `plays/bfn833_den_gamle_kirkeklokke/place_stoeberiet.md` is created
- [x] `plays/bfn833_den_gamle_kirkeklokke/process_forvandling.md` is created
- [x] `plays/bfn833_den_gamle_kirkeklokke/process_inspiration.md` is created
- [x] `plays/bfn833_den_gamle_kirkeklokke/plan_erindring.md` is created and linked to `persona_klokken.md`
- [x] `plays/bfn833_den_gamle_kirkeklokke/plan_skabelse.md` is created and linked to `persona_digterbarnet.md`
- [x] `plays/bfn833_den_gamle_kirkeklokke/pitch_hoejtidelig.md` is created
- [x] `plays/bfn833_den_gamle_kirkeklokke/plot_stoebningen.md` is created and casts company elements
- [x] `plays/bfn833_den_gamle_kirkeklokke/plot_klingningen.md` is created and casts company elements
- [x] The local validation tests (`npm test`) run successfully with zero errors
