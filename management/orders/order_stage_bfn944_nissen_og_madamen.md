---
khai: order
title: "Stage BFN 944 Nissen og Madamen"
language: english
license: CC-BY-NC-SA-4.0
stamp:
  owner: KAI HACKS AI
  version: v0.0.1
  date: "2026-06-25"
---

# Order: Stage BFN 944 Nissen og Madamen

## Direction

The house must stage BFN 944 (_Nissen og Madamen_) to establish the hundred and fifth production in the H.C. Andersen house. The production must model Nissen, Madamen, and Gartneren, the positions (Drilagtig, Poetisk, Praktisk), the pieces (Grødskål, Vers), the environments (Kælderen, Haven), the inspiration and forsørgelse processes, and the plots representing the porridge, the verse, the choice, and the compromise. It must be written in authentic Danish for all prose sections.

## Orders

1. The Playwright (Hans Christian Andersen) must author the play definition, the three personas, the three positions, the two pieces, the two places, the two processes, the two in-world plans, the pitch of Hverdagsmagi, and the four plots.
2. The Theatre Manager (Edvard Collin) must verify the local registry, ensure correct versioning, check formatting, and validate that the cast conforms to the canon.
3. The Roadie (Vilhelm Pedersen) must set the stage, verify the local test suite is green, and prepare the files for packaging.

## Implementation

The play files must be placed in `plays/bfn944_nissen_og_madamen/` and follow the house language policy:

- Structural elements and frontmatter in English.
- Narrative prose, projections, actions, shadows, tells, and staging notes in Danish.

## Targets

- [x] `plays/bfn944_nissen_og_madamen/play_nissen_og_madamen.md` is created and lists the complete company
- [x] `plays/bfn944_nissen_og_madamen/persona_nissen.md` is created and links to `position_drilagtig.md`
- [x] `plays/bfn944_nissen_og_madamen/persona_madamen.md` is created and links to `position_poetisk.md`
- [x] `plays/bfn944_nissen_og_madamen/persona_gartneren.md` is created and links to `position_praktisk.md`
- [x] `plays/bfn944_nissen_og_madamen/position_drilagtig.md` is created
- [x] `plays/bfn944_nissen_og_madamen/position_poetisk.md` is created
- [x] `plays/bfn944_nissen_og_madamen/position_praktisk.md` is created
- [x] `plays/bfn944_nissen_og_madamen/piece_groedskaal.md` is created
- [x] `plays/bfn944_nissen_og_madamen/piece_vers.md` is created
- [x] `plays/bfn944_nissen_og_madamen/place_kaelderen.md` is created
- [x] `plays/bfn944_nissen_og_madamen/place_haven.md` is created
- [x] `plays/bfn944_nissen_og_madamen/process_inspiration.md` is created
- [x] `plays/bfn944_nissen_og_madamen/process_forsoergelse.md` is created
- [x] `plays/bfn944_nissen_og_madamen/plan_poesisoegning.md` is created and linked to `persona_nissen.md`
- [x] `plays/bfn944_nissen_og_madamen/plan_husholdning.md` is created and linked to `persona_madamen.md`
- [x] `plays/bfn944_nissen_og_madamen/pitch_hverdagsmagi.md` is created
- [x] `plays/bfn944_nissen_og_madamen/plot_groeden.md` is created and casts company elements
- [x] `plays/bfn944_nissen_og_madamen/plot_verset.md` is created and casts company elements
- [x] `plays/bfn944_nissen_og_madamen/plot_valget.md` is created and casts company elements
- [x] `plays/bfn944_nissen_og_madamen/plot_kompromiset.md` is created and casts company elements
- [x] The local validation tests (`npm test`) run successfully with zero errors
