---
khai: order
title: "Stage BFN 591 Svinene"
language: english
license: CC-BY-NC-SA-4.0
stamp:
  owner: KAI HACKS AI
  version: v0.0.1
  date: "2026-06-26"
---

# Order: Stage BFN 591 Svinene

## Direction

The house must stage BFN 591 (_Svinene_) to establish a production in the H.C. Andersen house. The production must model ornen, soen, the positions (stolt, stolt), the pieces (trug, halm), the environments (stalden, marken), the aede and pludder processes, and the plots representing stalden and striden. It must be written in authentic Danish for all prose sections.

## Orders

1. The Playwright (Hans Christian Andersen) must author the play definition, the 2 personas, the 2 positions, the 2 pieces, the 2 places, the 2 processes, the 1 in-world plans, the pitch of satirisk, and the 2 plots.
2. The Theatre Manager (Edvard Collin) must verify the local registry, ensure correct versioning, check formatting, and validate that the cast conforms to the canon.
3. The Roadie (Vilhelm Pedersen) must set the stage, verify the local test suite is green, and prepare the files for packaging.

## Implementation

The play files must be placed in `plays/bfn591_svinene/` and follow the house language policy:

- Structural elements and frontmatter in English.
- Narrative prose, projections, actions, shadows, tells, and staging notes in Danish.

## Targets

- [x] `plays/bfn591_svinene/play_svinene.md` is created and lists the complete company
- [x] `plays/bfn591_svinene/persona_ornen.md` is created and links to `position_stolt.md`
- [x] `plays/bfn591_svinene/persona_soen.md` is created and links to `position_stolt.md`
- [x] `plays/bfn591_svinene/position_stolt.md` is created
- [x] `plays/bfn591_svinene/position_stolt.md` is created
- [x] `plays/bfn591_svinene/piece_trug.md` is created
- [x] `plays/bfn591_svinene/piece_halm.md` is created
- [x] `plays/bfn591_svinene/place_stalden.md` is created
- [x] `plays/bfn591_svinene/place_marken.md` is created
- [x] `plays/bfn591_svinene/process_aede.md` is created
- [x] `plays/bfn591_svinene/process_pludder.md` is created
- [x] `plays/bfn591_svinene/plan_status.md` is created and linked to `persona_ornen.md`
- [x] `plays/bfn591_svinene/pitch_satirisk.md` is created
- [x] `plays/bfn591_svinene/plot_stalden.md` is created and casts company elements
- [x] `plays/bfn591_svinene/plot_striden.md` is created and casts company elements
- [x] The local validation tests (`npm test`) run successfully with zero errors
