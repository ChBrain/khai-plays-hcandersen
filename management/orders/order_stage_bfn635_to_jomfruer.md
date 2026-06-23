---
khai: order
title: "Stage BFN 635 To Jomfruer"
language: english
license: CC-BY-NC-SA-4.0
stamp:
  owner: KAI HACKS AI
  version: v0.0.1
  date: "2026-06-23"
---

# Order: Stage BFN 635 To Jomfruer

## Direction

The house must stage BFN 635 (_To Jomfruer_) to establish the fifty-ninth production in the H.C. Andersen house. The production must model Jomfru, Dampramler, the positions (Stolt, Magtfuld), the piece (Brosten), the environments (Materialgaard, Gade), the stampning and navneskifte processes, and the plots leading to their realization. It must be written in authentic Danish for all prose sections.

## Orders

1. The Playwright (Hans Christian Andersen) must author the play definition, the two personas, the two positions, the piece, the two places, the two processes, the two in-world plans, the pitch of Humor, and the four plots.
2. The Theatre Manager (Edvard Collin) must verify the local registry, ensure correct versioning, check formatting, and validate that the entire cast conforms to the canon.
3. The Roadie (Vilhelm Pedersen) must set the stage, verify the local test suite is green, and prepare the files for packaging.

## Implementation

The play files must be placed in `plays/bfn635_to_jomfruer/` and follow the house language policy:

- Structural elements and frontmatter in English.
- Narrative prose, projections, actions, shadows, tells, and staging notes in Danish.

## Targets

- [x] `plays/bfn635_to_jomfruer/play_to_jomfruer.md` is created and lists the complete company
- [x] `plays/bfn635_to_jomfruer/persona_jomfru.md` is created and links to `position_stolt.md`
- [x] `plays/bfn635_to_jomfruer/persona_dampramler.md` is created and links to `position_magtfuld.md`
- [x] `plays/bfn635_to_jomfruer/position_stolt.md` is created
- [x] `plays/bfn635_to_jomfruer/position_magtfuld.md` is created
- [x] `plays/bfn635_to_jomfruer/piece_brosten.md` is created
- [x] `plays/bfn635_to_jomfruer/place_materialgaard.md` is created
- [x] `plays/bfn635_to_jomfruer/place_gade.md` is created
- [x] `plays/bfn635_to_jomfruer/process_stampning.md` is created
- [x] `plays/bfn635_to_jomfruer/process_navneskifte.md` is created
- [x] `plays/bfn635_to_jomfruer/plan_bevarelse.md` is created and linked to `persona_jomfru.md`
- [x] `plays/bfn635_to_jomfruer/plan_forlovelse.md` is created and linked to `persona_dampramler.md`
- [x] `plays/bfn635_to_jomfruer/pitch_humor.md` is created
- [x] `plays/bfn635_to_jomfruer/plot_samtale.md` is created and casts company elements
- [x] `plays/bfn635_to_jomfruer/plot_rygte.md` is created and casts company elements
- [x] `plays/bfn635_to_jomfruer/plot_afvisning.md` is created and casts company elements
- [x] `plays/bfn635_to_jomfruer/plot_arbejde.md` is created and casts company elements
- [x] The local validation tests (`npm test`) run successfully with zero errors
