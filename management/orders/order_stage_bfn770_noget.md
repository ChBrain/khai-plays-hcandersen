---
khai: order
title: "Stage BFN 770 Noget"
language: english
license: CC-BY-NC-SA-4.0
stamp:
  owner: KAI HACKS AI
  version: v0.0.1
  date: "2026-06-23"
---

# Order: Stage BFN 770 Noget

## Direction

The house must stage BFN 770 (_Noget_) to establish the sixty-sixth production in the H.C. Andersen house. The production must model Brodre, Arbejder, the positions (Ambitioes, Nytte), the piece (Mursten), the environments (Byggeplads, Himmelport), the straeben and muring processes, and the plots leading to their realization. It must be written in authentic Danish for all prose sections.

## Orders

1. The Playwright (Hans Christian Andersen) must author the play definition, the two personas, the two positions, the piece, the two places, the two processes, the two in-world plans, the pitch of Refleksion, and the four plots.
2. The Theatre Manager (Edvard Collin) must verify the local registry, ensure correct versioning, check formatting, and validate that the entire cast conforms to the canon.
3. The Roadie (Vilhelm Pedersen) must set the stage, verify the local test suite is green, and prepare the files for packaging.

## Implementation

The play files must be placed in `plays/bfn770_noget/` and follow the house language policy:

- Structural elements and frontmatter in English.
- Narrative prose, projections, actions, shadows, tells, and staging notes in Danish.

## Targets

- [x] `plays/bfn770_noget/play_noget.md` is created and lists the complete company
- [x] `plays/bfn770_noget/persona_brodre.md` is created and links to `position_ambitioes.md`
- [x] `plays/bfn770_noget/persona_arbejder.md` is created and links to `position_nytte.md`
- [x] `plays/bfn770_noget/position_ambitioes.md` is created
- [x] `plays/bfn770_noget/position_nytte.md` is created
- [x] `plays/bfn770_noget/piece_mursten.md` is created
- [x] `plays/bfn770_noget/place_byggeplads.md` is created
- [x] `plays/bfn770_noget/place_himmelport.md` is created
- [x] `plays/bfn770_noget/process_straeben.md` is created
- [x] `plays/bfn770_noget/process_muring.md` is created
- [x] `plays/bfn770_noget/plan_status.md` is created and linked to `persona_brodre.md`
- [x] `plays/bfn770_noget/plan_bidrag.md` is created and linked to `persona_arbejder.md`
- [x] `plays/bfn770_noget/pitch_refleksion.md` is created
- [x] `plays/bfn770_noget/plot_aftale.md` is created and casts company elements
- [x] `plays/bfn770_noget/plot_udfoerelse.md` is created and casts company elements
- [x] `plays/bfn770_noget/plot_dom.md` is created and casts company elements
- [x] `plays/bfn770_noget/plot_eftermaele.md` is created and casts company elements
- [x] The local validation tests (`npm test`) run successfully with zero errors
