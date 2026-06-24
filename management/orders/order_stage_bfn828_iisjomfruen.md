---
khai: order
title: "Stage BFN 828 Iisjomfruen"
language: english
license: CC-BY-NC-SA-4.0
stamp:
  owner: KAI HACKS AI
  version: v0.0.1
  date: "2026-06-24"
---

# Order: Stage BFN 828 Iisjomfruen

## Direction

The house must stage BFN 828 (_Iisjomfruen_) to establish the eighty-seventh production in the H.C. Andersen house. The production must model Rudy, Iisjomfru, the positions (Jaeger, Herskerinde), the piece (Iffel), the environments (Bjerge, Soe), the bestigning and indhentning processes, and the plots leading to their realization. It must be written in authentic Danish for all prose sections.

## Orders

1. The Playwright (Hans Christian Andersen) must author the play definition, the two personas, the two positions, the piece, the two places, the two processes, the two in-world plans, the pitch of Tragedie, and the four plots.
2. The Theatre Manager (Edvard Collin) must verify the local registry, ensure correct versioning, check formatting, and validate that the cast conforms to the canon.
3. The Roadie (Vilhelm Pedersen) must set the stage, verify the local test suite is green, and prepare the files for packaging.

## Implementation

The play files must be placed in `plays/bfn828_iisjomfruen/` and follow the house language policy:

- Structural elements and frontmatter in English.
- Narrative prose, projections, actions, shadows, tells, and staging notes in Danish.

## Targets

- [x] `plays/bfn828_iisjomfruen/play_iisjomfruen.md` is created and lists the complete company
- [x] `plays/bfn828_iisjomfruen/persona_rudy.md` is created and links to `position_jaeger.md`
- [x] `plays/bfn828_iisjomfruen/persona_iisjomfru.md` is created and links to `position_herskerinde.md`
- [x] `plays/bfn828_iisjomfruen/position_jaeger.md` is created
- [x] `plays/bfn828_iisjomfruen/position_herskerinde.md` is created
- [x] `plays/bfn828_iisjomfruen/piece_iffel.md` is created
- [x] `plays/bfn828_iisjomfruen/place_bjerge.md` is created
- [x] `plays/bfn828_iisjomfruen/place_soe.md` is created
- [x] `plays/bfn828_iisjomfruen/process_bestigning.md` is created
- [x] `plays/bfn828_iisjomfruen/process_indhentning.md` is created
- [x] `plays/bfn828_iisjomfruen/plan_erobring.md` is created and linked to `persona_rudy.md`
- [x] `plays/bfn828_iisjomfruen/plan_venten.md` is created and linked to `persona_iisjomfru.md`
- [x] `plays/bfn828_iisjomfruen/pitch_tragedie.md` is created
- [x] `plays/bfn828_iisjomfruen/plot_frelsen.md` is created and casts company elements
- [x] `plays/bfn828_iisjomfruen/plot_jaegeren.md` is created and casts company elements
- [x] `plays/bfn828_iisjomfruen/plot_lykken.md` is created and casts company elements
- [x] `plays/bfn828_iisjomfruen/plot_indhentningen.md` is created and casts company elements
- [x] The local validation tests (`npm test`) run successfully with zero errors
