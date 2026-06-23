---
khai: order
title: "Stage BFN 782 Taarnvaegteren Ole"
language: english
license: CC-BY-NC-SA-4.0
stamp:
  owner: KAI HACKS AI
  version: v0.0.1
  date: "2026-06-23"
---

# Order: Stage BFN 782 Taarnvaegteren Ole

## Direction

The house must stage BFN 782 (_Taarnvægteren Ole_) to establish the seventieth production in the H.C. Andersen house. The production must model Ole, Besoegende, the positions (Vogter, Lytter), the piece (Kikkert), the environments (Taarn, By), the observation and historiefortaelling processes, and the plots leading to their realization. It must be written in authentic Danish for all prose sections.

## Orders

1. The Playwright (Hans Christian Andersen) must author the play definition, the two personas, the two positions, the piece, the two places, the two processes, the two in-world plans, the pitch of Satire, and the four plots.
2. The Theatre Manager (Edvard Collin) must verify the local registry, ensure correct versioning, check formatting, and validate that the entire cast conforms to the canon.
3. The Roadie (Vilhelm Pedersen) must set the stage, verify the local test suite is green, and prepare the files for packaging.

## Implementation

The play files must be placed in `plays/bfn782_taarnvaegteren_ole/` and follow the house language policy:

- Structural elements and frontmatter in English.
- Narrative prose, projections, actions, shadows, tells, and staging notes in Danish.

## Targets

- [x] `plays/bfn782_taarnvaegteren_ole/play_taarnvaegteren_ole.md` is created and lists the complete company
- [x] `plays/bfn782_taarnvaegteren_ole/persona_ole.md` is created and links to `position_vogter.md`
- [x] `plays/bfn782_taarnvaegteren_ole/persona_besoegende.md` is created and links to `position_lytter.md`
- [x] `plays/bfn782_taarnvaegteren_ole/position_vogter.md` is created
- [x] `plays/bfn782_taarnvaegteren_ole/position_lytter.md` is created
- [x] `plays/bfn782_taarnvaegteren_ole/piece_kikkert.md` is created
- [x] `plays/bfn782_taarnvaegteren_ole/place_taarn.md` is created
- [x] `plays/bfn782_taarnvaegteren_ole/place_by.md` is created
- [x] `plays/bfn782_taarnvaegteren_ole/process_observation.md` is created
- [x] `plays/bfn782_taarnvaegteren_ole/process_historiefortaelling.md` is created
- [x] `plays/bfn782_taarnvaegteren_ole/plan_overskue.md` is created and linked to `persona_ole.md`
- [x] `plays/bfn782_taarnvaegteren_ole/plan_dokumentation.md` is created and linked to `persona_besoegende.md`
- [x] `plays/bfn782_taarnvaegteren_ole/pitch_satire.md` is created
- [x] `plays/bfn782_taarnvaegteren_ole/plot_taarnbesoeg.md` is created and casts company elements
- [x] `plays/bfn782_taarnvaegteren_ole/plot_nytaarsnat.md` is created and casts company elements
- [x] `plays/bfn782_taarnvaegteren_ole/plot_spande_historie.md` is created and casts company elements
- [x] `plays/bfn782_taarnvaegteren_ole/plot_afsked.md` is created and casts company elements
- [x] The local validation tests (`npm test`) run successfully with zero errors
