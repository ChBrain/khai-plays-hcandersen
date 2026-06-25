---
khai: order
title: "Stage BFN 978 Dryaden"
language: english
license: CC-BY-NC-SA-4.0
stamp:
  owner: KAI HACKS AI
  version: v0.0.1
  date: "2026-06-25"
---

# Order: Stage BFN 978 Dryaden

## Direction

The house must stage BFN 978 (_Dryaden_) to establish the hundred and tenth production in the H.C. Andersen house. The production must model Dryade, Djævel, and Menneske, the positions (Bundet, Fritsvævende, Skabende), the pieces (Kastanietræ, Udstilling), the environments (Landskab, Paris), the frigørelse and forgængelse processes, and the plots representing the longing, the pact, the exhibition, and the demise. It must be written in authentic Danish for all prose sections.

## Orders

1. The Playwright (Hans Christian Andersen) must author the play definition, the three personas, the three positions, the two pieces, the two places, the two processes, the two in-world plans, the pitch of Modernitet, and the four plots.
2. The Theatre Manager (Edvard Collin) must verify the local registry, ensure correct versioning, check formatting, and validate that the cast conforms to the canon.
3. The Roadie (Vilhelm Pedersen) must set the stage, verify the local test suite is green, and prepare the files for packaging.

## Implementation

The play files must be placed in `plays/bfn978_dryaden/` and follow the house language policy:

- Structural elements and frontmatter in English.
- Narrative prose, projections, actions, shadows, tells, and staging notes in Danish.

## Targets

- [ ] `plays/bfn978_dryaden/play_dryaden.md` is created and lists the complete company
- [ ] `plays/bfn978_dryaden/persona_dryade.md` is created and links to `position_bundet.md`
- [ ] `plays/bfn978_dryaden/persona_devil.md` is created and links to `position_fritsvaevende.md`
- [ ] `plays/bfn978_dryaden/persona_menneske.md` is created and links to `position_skabende.md`
- [ ] `plays/bfn978_dryaden/position_bundet.md` is created
- [ ] `plays/bfn978_dryaden/position_fritsvaevende.md` is created
- [ ] `plays/bfn978_dryaden/position_skabende.md` is created
- [ ] `plays/bfn978_dryaden/piece_kastanjetrae.md` is created
- [ ] `plays/bfn978_dryaden/piece_udstilling.md` is created
- [ ] `plays/bfn978_dryaden/place_landskab.md` is created
- [ ] `plays/bfn978_dryaden/place_paris.md` is created
- [ ] `plays/bfn978_dryaden/process_frigoerelse.md` is created
- [ ] `plays/bfn978_dryaden/process_forgaengelse.md` is created
- [ ] `plays/bfn978_dryaden/plan_udflugt.md` is created and linked to `persona_dryade.md`
- [ ] `plays/bfn978_dryaden/plan_fristelse.md` is created and linked to `persona_devil.md`
- [ ] `plays/bfn978_dryaden/pitch_modernitet.md` is created
- [ ] `plays/bfn978_dryaden/plot_laengsel.md` is created and casts company elements
- [ ] `plays/bfn978_dryaden/plot_pagten.md` is created and casts company elements
- [ ] `plays/bfn978_dryaden/plot_udstillingen.md` is created and casts company elements
- [ ] `plays/bfn978_dryaden/plot_undergangen.md` is created and casts company elements
- [ ] The local validation tests (`npm test`) run successfully with zero errors
