---
khai: order
title: "Stage BFN 529 Flipperne"
language: english
license: CC-BY-NC-SA-4.0
stamp:
  owner: KAI HACKS AI
  version: v0.0.1
  date: "2026-06-21"
---

# Order: Stage BFN 529 Flipperne

## Direction

The house must stage BFN 529 (_Flipperne_) to establish the forty-first production in the H.C. Andersen house. The production must model Flipperne, Genstandene, the positions (Hovmodig, Afvisende), the piece (Strygejern), the environments (Skuffe, Papirmoelle), the bejlen and genanvendelse processes, and the plots leading to their realization. It must be written in authentic Danish for all prose sections.

## Orders

1. The Playwright (Hans Christian Andersen) must author the play definition, the two personas, the two positions, the piece, the two places, the two processes, the two in-world plans, the pitch of Satire, and the five plots.
2. The Theatre Manager (Edvard Collin) must verify the local registry, ensure correct versioning, check formatting, and validate that the entire cast conforms to the canon.
3. The Roadie (Vilhelm Pedersen) must set the stage, verify the local test suite is green, and prepare the files for packaging.

## Implementation

The play files must be placed in `plays/bfn529_flipperne/` and follow the house language policy:

- Structural elements and frontmatter in English.
- Narrative prose, projections, actions, shadows, tells, and staging notes in Danish.

## Targets

- [x] `plays/bfn529_flipperne/play_flipperne.md` is created and lists the complete company
- [x] `plays/bfn529_flipperne/persona_flipperne.md` is created and links to `position_hovmodig.md`
- [x] `plays/bfn529_flipperne/persona_genstandene.md` is created and links to `position_afvisende.md`
- [x] `plays/bfn529_flipperne/position_hovmodig.md` is created
- [x] `plays/bfn529_flipperne/position_afvisende.md` is created
- [x] `plays/bfn529_flipperne/piece_strygejern.md` is created
- [x] `plays/bfn529_flipperne/place_skuffe.md` is created
- [x] `plays/bfn529_flipperne/place_papirmoelle.md` is created
- [x] `plays/bfn529_flipperne/process_bejlen.md` is created
- [x] `plays/bfn529_flipperne/process_genanvendelse.md` is created
- [x] `plays/bfn529_flipperne/plan_aegteskab.md` is created and linked to `persona_flipperne.md`
- [x] `plays/bfn529_flipperne/plan_forvandling.md` is created and linked to `persona_genstandene.md`
- [x] `plays/bfn529_flipperne/pitch_satire.md` is created
- [x] `plays/bfn529_flipperne/plot_skuffeliv.md` is created and casts company elements
- [x] `plays/bfn529_flipperne/plot_bejlerrejse.md` is created and casts company elements
- [x] `plays/bfn529_flipperne/plot_afvisning.md` is created and casts company elements
- [x] `plays/bfn529_flipperne/plot_papirforvandling.md` is created and casts company elements
- [x] The local validation tests (`npm test`) run successfully with zero errors
