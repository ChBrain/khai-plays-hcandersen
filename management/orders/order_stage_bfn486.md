---
khai: order
title: "Stage BFN 486"
language: english
license: CC-BY-NC-SA-4.0
stamp:
  owner: KAI HACKS AI
  version: v0.0.1
  date: "2026-06-21"
---

# Order: Stage BFN 486

## Direction

The house must stage BFN 486 (_Den lille Pige med Svovlstikkerne_) to establish the thirty-fourth production in the H.C. Andersen house. The production must model Pigen, Bedstemoderen, the positions (Lidende, Vejviser), the piece (Svovlstikker), the environments (Gaden, Himlen), the forfrysning and forklarelse processes, and the plots leading to their realization. It must be written in authentic Danish for all prose sections.

## Orders

1. The Playwright (Hans Christian Andersen) must author the play definition, the two personas, the two positions, the piece, the two places, the two processes, the two in-world plans, the pitch of Patos, and the four plots.
2. The Theatre Manager (Edvard Collin) must verify the local registry, ensure correct versioning, check formatting, and validate that the entire cast conforms to the canon.
3. The Roadie (Vilhelm Pedersen) must set the stage, verify the local test suite is green, and prepare the files for packaging.

## Implementation

The play files must be placed in `plays/bfn486_svovlstikkerne/` and follow the house language policy:

- Structural elements and frontmatter in English.
- Narrative prose, projections, actions, shadows, tells, and staging notes in Danish.

## Targets

- [x] `plays/bfn486_svovlstikkerne/play_svovlstikkerne.md` is created and lists the complete company
- [x] `plays/bfn486_svovlstikkerne/persona_pigen.md` is created and links to `position_lidende.md`
- [x] `plays/bfn486_svovlstikkerne/persona_bedstemoderen.md` is created and links to `position_vejviser.md`
- [x] `plays/bfn486_svovlstikkerne/position_lidende.md` is created
- [x] `plays/bfn486_svovlstikkerne/position_vejviser.md` is created
- [x] `plays/bfn486_svovlstikkerne/piece_svovlstikker.md` is created
- [x] `plays/bfn486_svovlstikkerne/place_gaden.md` is created
- [x] `plays/bfn486_svovlstikkerne/place_himlen.md` is created
- [x] `plays/bfn486_svovlstikkerne/process_forfrysning.md` is created
- [x] `plays/bfn486_svovlstikkerne/process_forklarelse.md` is created
- [x] `plays/bfn486_svovlstikkerne/plan_overlevelse.md` is created and linked to `persona_pigen.md`
- [x] `plays/bfn486_svovlstikkerne/plan_bedstemor_kald.md` is created and linked to `persona_bedstemoderen.md`
- [x] `plays/bfn486_svovlstikkerne/pitch_patos.md` is created
- [x] `plays/bfn486_svovlstikkerne/plot_kulden.md` is created and casts company elements
- [x] `plays/bfn486_svovlstikkerne/plot_visionerne.md` is created and casts company elements
- [x] `plays/bfn486_svovlstikkerne/plot_stjerneskud.md` is created and casts company elements
- [x] `plays/bfn486_svovlstikkerne/plot_nytårsmorgen.md` is created and casts company elements
- [x] The local validation tests (`npm test`) run successfully with zero errors
