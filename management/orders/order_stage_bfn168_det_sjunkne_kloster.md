---
khai: order
title: "Stage BFN 168 Det sjunkne Kloster"
language: english
license: CC-BY-NC-SA-4.0
stamp:
  owner: KAI HACKS AI
  version: v0.0.1
  date: "2026-06-26"
---

# Order: Stage BFN 168 Det sjunkne Kloster

## Direction

The house must stage BFN 168 (_Det sjunkne Kloster_) to establish a production in the H.C. Andersen house. The production must model munk, aamanden, the positions (bedende, observatoer), the pieces (klosterklokke, salmebog), the environments (soe, ruin), the boen and sinking processes, and the plots representing katastrofen and efterklangen. It must be written in authentic Danish for all prose sections.

## Orders

1. The Playwright (Hans Christian Andersen) must author the play definition, the 2 personas, the 2 positions, the 2 pieces, the 2 places, the 2 processes, the 1 in-world plans, the pitch of andagtsfuld, and the 2 plots.
2. The Theatre Manager (Edvard Collin) must verify the local registry, ensure correct versioning, check formatting, and validate that the cast conforms to the canon.
3. The Roadie (Vilhelm Pedersen) must set the stage, verify the local test suite is green, and prepare the files for packaging.

## Implementation

The play files must be placed in `plays/bfn168_det_sjunkne_kloster/` and follow the house language policy:

- Structural elements and frontmatter in English.
- Narrative prose, projections, actions, shadows, tells, and staging notes in Danish.

## Targets

- [x] `plays/bfn168_det_sjunkne_kloster/play_det_sjunkne_kloster.md` is created and lists the complete company
- [x] `plays/bfn168_det_sjunkne_kloster/persona_munk.md` is created and links to `position_bedende.md`
- [x] `plays/bfn168_det_sjunkne_kloster/persona_aamanden.md` is created and links to `position_observatoer.md`
- [x] `plays/bfn168_det_sjunkne_kloster/position_bedende.md` is created
- [x] `plays/bfn168_det_sjunkne_kloster/position_observatoer.md` is created
- [x] `plays/bfn168_det_sjunkne_kloster/piece_klosterklokke.md` is created
- [x] `plays/bfn168_det_sjunkne_kloster/piece_salmebog.md` is created
- [x] `plays/bfn168_det_sjunkne_kloster/place_soe.md` is created
- [x] `plays/bfn168_det_sjunkne_kloster/place_ruin.md` is created
- [x] `plays/bfn168_det_sjunkne_kloster/process_boen.md` is created
- [x] `plays/bfn168_det_sjunkne_kloster/process_sinking.md` is created
- [x] `plays/bfn168_det_sjunkne_kloster/plan_frelse.md` is created and linked to `persona_munk.md`
- [x] `plays/bfn168_det_sjunkne_kloster/pitch_andagtsfuld.md` is created
- [x] `plays/bfn168_det_sjunkne_kloster/plot_katastrofen.md` is created and casts company elements
- [x] `plays/bfn168_det_sjunkne_kloster/plot_efterklangen.md` is created and casts company elements
- [x] The local validation tests (`npm test`) run successfully with zero errors
