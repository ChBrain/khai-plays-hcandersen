---
khai: order
title: "Stage BFN 529 Vanddraaben"
language: english
license: CC-BY-NC-SA-4.0
stamp:
  owner: KAI HACKS AI
  version: v0.0.1
  date: "2026-06-21"
---

# Order: Stage BFN 529 Vanddraaben

## Direction

The house must stage BFN 529 (_Vanddraaben_) to establish the fortieth production in the H.C. Andersen house. The production must model Krible-Krable, Vanddyrene, the positions (Iagttager, Stridende), the piece (Forstoerrelsesglas), the environments (Rendestenen, Mikroverden), the forstoerrelse and kamp processes, and the plots leading to their realization. It must be written in authentic Danish for all prose sections.

## Orders

1. The Playwright (Hans Christian Andersen) must author the play definition, the two personas, the two positions, the piece, the two places, the two processes, the two in-world plans, the pitch of Satire, and the four plots.
2. The Theatre Manager (Edvard Collin) must verify the local registry, ensure correct versioning, check formatting, and validate that the entire cast conforms to the canon.
3. The Roadie (Vilhelm Pedersen) must set the stage, verify the local test suite is green, and prepare the files for packaging.

## Implementation

The play files must be placed in `plays/bfn529_vanddraaben/` and follow the house language policy:

- Structural elements and frontmatter in English.
- Narrative prose, projections, actions, shadows, tells, and staging notes in Danish.

## Targets

- [x] `plays/bfn529_vanddraaben/play_vanddraaben.md` is created and lists the complete company
- [x] `plays/bfn529_vanddraaben/persona_krible_krable.md` is created and links to `position_iagttager.md`
- [x] `plays/bfn529_vanddraaben/persona_vanddyrene.md` is created and links to `position_stridende.md`
- [x] `plays/bfn529_vanddraaben/position_iagttager.md` is created
- [x] `plays/bfn529_vanddraaben/position_stridende.md` is created
- [x] `plays/bfn529_vanddraaben/piece_forstoerrelsesglas.md` is created
- [x] `plays/bfn529_vanddraaben/place_rendestenen.md` is created
- [x] `plays/bfn529_vanddraaben/place_mikroverden.md` is created
- [x] `plays/bfn529_vanddraaben/process_forstoerrelse.md` is created
- [x] `plays/bfn529_vanddraaben/process_kamp.md` is created
- [x] `plays/bfn529_vanddraaben/plan_iagttagelse.md` is created and linked to `persona_krible_krable.md`
- [x] `plays/bfn529_vanddraaben/plan_kaos.md` is created and linked to `persona_vanddyrene.md`
- [x] `plays/bfn529_vanddraaben/pitch_satire.md` is created
- [x] `plays/bfn529_vanddraaben/plot_praeparation.md` is created and casts company elements
- [x] `plays/bfn529_vanddraaben/plot_forstoerrelse.md` is created and casts company elements
- [x] `plays/bfn529_vanddraaben/plot_strid.md` is created and casts company elements
- [x] `plays/bfn529_vanddraaben/plot_dommen.md` is created and casts company elements
- [x] The local validation tests (`npm test`) run successfully with zero errors
