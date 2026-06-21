---
khai: order
title: "Stage BFN 520"
language: english
license: CC-BY-NC-SA-4.0
stamp:
  owner: KAI HACKS AI
  version: v0.0.1
  date: "2026-06-21"
---

# Order: Stage BFN 520

## Direction

The house must stage BFN 520 (_Skyggen_) to establish the thirty-eighth production in the H.C. Andersen house. The production must model Lærde mand, Skyggen, the positions (Filosof, Opportunist), the piece (Poesien), the environments (Altanen, Verden), the frigoerelse and inversion processes, and the plots leading to their realization. It must be written in authentic Danish for all prose sections.

## Orders

1. The Playwright (Hans Christian Andersen) must author the play definition, the two personas, the two positions, the piece, the two places, the two processes, the two in-world plans, the pitch of Kynisme, and the four plots.
2. The Theatre Manager (Edvard Collin) must verify the local registry, ensure correct versioning, check formatting, and validate that the entire cast conforms to the canon.
3. The Roadie (Vilhelm Pedersen) must set the stage, verify the local test suite is green, and prepare the files for packaging.

## Implementation

The play files must be placed in `plays/bfn520_skyggen/` and follow the house language policy:

- Structural elements and frontmatter in English.
- Narrative prose, projections, actions, shadows, tells, and staging notes in Danish.

## Targets

- [x] `plays/bfn520_skyggen/play_skyggen.md` is created and lists the complete company
- [x] `plays/bfn520_skyggen/persona_laerde_mand.md` is created and links to `position_filosof.md`
- [x] `plays/bfn520_skyggen/persona_skyggen.md` is created and links to `position_opportunist.md`
- [x] `plays/bfn520_skyggen/position_filosof.md` is created
- [x] `plays/bfn520_skyggen/position_opportunist.md` is created
- [x] `plays/bfn520_skyggen/piece_poesien.md` is created
- [x] `plays/bfn520_skyggen/place_altanen.md` is created
- [x] `plays/bfn520_skyggen/place_verden.md` is created
- [x] `plays/bfn520_skyggen/process_frigoerelse.md` is created
- [x] `plays/bfn520_skyggen/process_inversion.md` is created
- [x] `plays/bfn520_skyggen/plan_sandhedsoegning.md` is created and linked to `persona_laerde_mand.md`
- [x] `plays/bfn520_skyggen/plan_magtovertagelse.md` is created and linked to `persona_skyggen.md`
- [x] `plays/bfn520_skyggen/pitch_kynisme.md` is created
- [x] `plays/bfn520_skyggen/plot_altanen.md` is created and casts company elements
- [x] `plays/bfn520_skyggen/plot_gensyn.md` is created and casts company elements
- [x] `plays/bfn520_skyggen/plot_rejsen.md` is created and casts company elements
- [x] `plays/bfn520_skyggen/plot_undergang.md` is created and casts company elements
- [x] The local validation tests (`npm test`) run successfully with zero errors
