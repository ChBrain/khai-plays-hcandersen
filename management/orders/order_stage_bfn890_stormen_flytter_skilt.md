---
khai: order
title: "Stage BFN 890 Stormen flytter Skilt"
language: english
license: CC-BY-NC-SA-4.0
stamp:
  owner: KAI HACKS AI
  version: v0.0.1
  date: "2026-06-24"
---

# Order: Stage BFN 890 Stormen flytter Skilt

## Direction

The house must stage BFN 890 (_Stormen flytter Skilt_) to establish the ninety-fifth production in the H.C. Andersen house. The production must model Storm, Skilt, the positions (Omvæltende, Markerende), the piece (Skilt_stykke), the environments (Gade, Nyt_sted), the blæst and ombytning processes, and the plots leading to their realization. It must be written in authentic Danish for all prose sections.

## Orders

1. The Playwright (Hans Christian Andersen) must author the play definition, the two personas, the two positions, the piece, the two places, the two processes, the two in-world plans, the pitch of Satire, and the four plots.
2. The Theatre Manager (Edvard Collin) must verify the local registry, ensure correct versioning, check formatting, and validate that the cast conforms to the canon.
3. The Roadie (Vilhelm Pedersen) must set the stage, verify the local test suite is green, and prepare the files for packaging.

## Implementation

The play files must be placed in `plays/bfn890_stormen_flytter_skilt/` and follow the house language policy:

- Structural elements and frontmatter in English.
- Narrative prose, projections, actions, shadows, tells, and staging notes in Danish.

## Targets

- [x] `plays/bfn890_stormen_flytter_skilt/play_stormen_flytter_skilt.md` is created and lists the complete company
- [x] `plays/bfn890_stormen_flytter_skilt/persona_storm.md` is created and links to `position_omvaeltende.md`
- [x] `plays/bfn890_stormen_flytter_skilt/persona_skilt.md` is created and links to `position_markerende.md`
- [x] `plays/bfn890_stormen_flytter_skilt/position_omvaeltende.md` is created
- [x] `plays/bfn890_stormen_flytter_skilt/position_markerende.md` is created
- [x] `plays/bfn890_stormen_flytter_skilt/piece_skilt_stykke.md` is created
- [x] `plays/bfn890_stormen_flytter_skilt/place_gade.md` is created
- [x] `plays/bfn890_stormen_flytter_skilt/place_nyt_sted.md` is created
- [x] `plays/bfn890_stormen_flytter_skilt/process_blaest.md` is created
- [x] `plays/bfn890_stormen_flytter_skilt/process_ombytning.md` is created
- [x] `plays/bfn890_stormen_flytter_skilt/plan_uvejr.md` is created and linked to `persona_storm.md`
- [x] `plays/bfn890_stormen_flytter_skilt/plan_orden.md` is created and linked to `persona_skilt.md`
- [x] `plays/bfn890_stormen_flytter_skilt/pitch_satire.md` is created
- [x] `plays/bfn890_stormen_flytter_skilt/plot_optakten.md` is created and casts company elements
- [x] `plays/bfn890_stormen_flytter_skilt/plot_stormnatten.md` is created and casts company elements
- [x] `plays/bfn890_stormen_flytter_skilt/plot_morgendagen.md` is created and casts company elements
- [x] `plays/bfn890_stormen_flytter_skilt/plot_afsloeringen.md` is created and casts company elements
- [x] The local validation tests (`npm test`) run successfully with zero errors
