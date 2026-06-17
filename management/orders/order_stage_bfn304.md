---
khai: order
title: "Stage BFN 304"
language: english
license: CC-BY-NC-SA-4.0
stamp:
  owner: KAI HACKS AI
  version: v0.0.1
  date: "2026-06-17"
---

# Order: Stage BFN 304

## Direction

The house must stage BFN 304 (_Den lille Havfrue_) to establish the eighth production in the H.C. Andersen house. The production must model the little mermaid, the prince, the sea witch, the environments (the Sea Floor and the Castle), the voice, the magic potion, and the dagger pieces, the transformation and sacrifice processes, and the plots leading to her spiritual transformation. It must be written in authentic Danish for all prose sections.

## Orders

1. The Playwright (Hans Christian Andersen) must author the play definition, the three personas, the three positions, the three pieces, the two places, the two processes, the two in-world plans, and the four plots.
2. The Theatre Manager (Edvard Collin) must verify the local registry, ensure correct versioning, check formatting, and validate that the entire cast conforms to the canon.
3. The Roadie (Vilhelm Pedersen) must set the stage, verify the local test suite is green, and prepare the files for packaging.

## Implementation

The play files must be placed in `plays/bfn304_den_lille_havfrue/` and follow the house language policy:

- Structural elements and frontmatter in English.
- Narrative prose, projections, actions, shadows, tells, and staging notes in Danish.

## Targets

- [x] `plays/bfn304_den_lille_havfrue/play_havfrue.md` is created and lists the complete company
- [x] `plays/bfn304_den_lille_havfrue/persona_havfrue.md` is created and links to `position_havfrue.md`
- [x] `plays/bfn304_den_lille_havfrue/persona_prins.md` is created and links to `position_menneske.md`
- [x] `plays/bfn304_den_lille_havfrue/persona_heks.md` is created and links to `position_heks.md`
- [x] `plays/bfn304_den_lille_havfrue/position_havfrue.md` is created
- [x] `plays/bfn304_den_lille_havfrue/position_menneske.md` is created
- [x] `plays/bfn304_den_lille_havfrue/position_heks.md` is created
- [x] `plays/bfn304_den_lille_havfrue/piece_stemmen.md` is created
- [x] `plays/bfn304_den_lille_havfrue/piece_trylledrik.md` is created
- [x] `plays/bfn304_den_lille_havfrue/piece_dolk.md` is created
- [x] `plays/bfn304_den_lille_havfrue/place_havbund.md` is created
- [x] `plays/bfn304_den_lille_havfrue/place_slot.md` is created
- [x] `plays/bfn304_den_lille_havfrue/process_forvandling.md` is created
- [x] `plays/bfn304_den_lille_havfrue/process_opofrelse.md` is created
- [x] `plays/bfn304_den_lille_havfrue/plan_havfruens_plan.md` is created and linked to `persona_havfrue.md`
- [x] `plays/bfn304_den_lille_havfrue/plan_heksens_plan.md` is created and linked to `persona_heks.md`
- [x] `plays/bfn304_den_lille_havfrue/plot_redningen.md` is created and casts company elements
- [x] `plays/bfn304_den_lille_havfrue/plot_pagten.md` is created and casts company elements
- [x] `plays/bfn304_den_lille_havfrue/plot_proevelsen.md` is created and casts company elements
- [x] `plays/bfn304_den_lille_havfrue/plot_afskeden.md` is created and casts company elements
- [x] The local validation tests (`npm test`) run successfully with zero errors
