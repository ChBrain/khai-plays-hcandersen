---
khai: order
title: "Stage BFN 606 Årets Historie"
language: english
license: CC-BY-NC-SA-4.0
stamp:
  owner: KAI HACKS AI
  version: v0.0.1
  date: "2026-06-22"
---

# Order: Stage BFN 606 Årets Historie

## Direction

The house must stage BFN 606 (_Årets Historie_) to establish the forty-sixth production in the H.C. Andersen house. The production must model Aar, Spurve, the positions (Realist, Optimist), the piece (Tid), the environments (Skov, By), the passering and skift processes, and the plots leading to their realization. It must be written in authentic Danish for all prose sections.

## Orders

1. The Playwright (Hans Christian Andersen) must author the play definition, the two personas, the two positions, the piece, the two places, the two processes, the two in-world plans, the pitch of Melankoli, and the four plots.
2. The Theatre Manager (Edvard Collin) must verify the local registry, ensure correct versioning, check formatting, and validate that the entire cast conforms to the canon.
3. The Roadie (Vilhelm Pedersen) must set the stage, verify the local test suite is green, and prepare the files for packaging.

## Implementation

The play files must be placed in `plays/bfn606_aarets_historie/` and follow the house language policy:

- Structural elements and frontmatter in English.
- Narrative prose, projections, actions, shadows, tells, and staging notes in Danish.

## Targets

- [x] `plays/bfn606_aarets_historie/play_aarets_historie.md` is created and lists the complete company
- [x] `plays/bfn606_aarets_historie/persona_aar.md` is created and links to `position_realist.md`
- [x] `plays/bfn606_aarets_historie/persona_spurve.md` is created and links to `position_optimist.md`
- [x] `plays/bfn606_aarets_historie/position_realist.md` is created
- [x] `plays/bfn606_aarets_historie/position_optimist.md` is created
- [x] `plays/bfn606_aarets_historie/piece_tid.md` is created
- [x] `plays/bfn606_aarets_historie/place_skov.md` is created
- [x] `plays/bfn606_aarets_historie/place_by.md` is created
- [x] `plays/bfn606_aarets_historie/process_passering.md` is created
- [x] `plays/bfn606_aarets_historie/process_skift.md` is created
- [x] `plays/bfn606_aarets_historie/plan_aarets_gang.md` is created and linked to `persona_aar.md`
- [x] `plays/bfn606_aarets_historie/plan_overlevelse.md` is created and linked to `persona_spurve.md`
- [x] `plays/bfn606_aarets_historie/pitch_melankoli.md` is created
- [x] `plays/bfn606_aarets_historie/plot_vinter.md` is created and casts company elements
- [x] `plays/bfn606_aarets_historie/plot_foraar.md` is created and casts company elements
- [x] `plays/bfn606_aarets_historie/plot_sommer.md` is created and casts company elements
- [x] `plays/bfn606_aarets_historie/plot_efteraar.md` is created and casts company elements
- [x] The local validation tests (`npm test`) run successfully with zero errors
