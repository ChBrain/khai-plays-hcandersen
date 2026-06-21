---
khai: order
title: "Stage BFN 517"
language: english
license: CC-BY-NC-SA-4.0
stamp:
  owner: KAI HACKS AI
  version: v0.0.1
  date: "2026-06-21"
---

# Order: Stage BFN 517

## Direction

The house must stage BFN 517 (_Den gamle Gadeløgte_) to establish the thirty-fifth production in the H.C. Andersen house. The production must model Gadeløgten, Vægteren, the positions (Tjener, Ven), the piece (Olie), the environments (Gaden, Kælderen), the tjeneste and pension processes, and the plots leading to their realization. It must be written in authentic Danish for all prose sections.

## Orders

1. The Playwright (Hans Christian Andersen) must author the play definition, the two personas, the two positions, the piece, the two places, the two processes, the two in-world plans, the pitch of Nostalgi, and the four plots.
2. The Theatre Manager (Edvard Collin) must verify the local registry, ensure correct versioning, check formatting, and validate that the entire cast conforms to the canon.
3. The Roadie (Vilhelm Pedersen) must set the stage, verify the local test suite is green, and prepare the files for packaging.

## Implementation

The play files must be placed in `plays/bfn517_gadeloegten/` and follow the house language policy:

- Structural elements and frontmatter in English.
- Narrative prose, projections, actions, shadows, tells, and staging notes in Danish.

## Targets

- [x] `plays/bfn517_gadeloegten/play_gadeloegten.md` is created and lists the complete company
- [x] `plays/bfn517_gadeloegten/persona_gadeloegten.md` is created and links to `position_tjener.md`
- [x] `plays/bfn517_gadeloegten/persona_vaegteren.md` is created and links to `position_ven.md`
- [x] `plays/bfn517_gadeloegten/position_tjener.md` is created
- [x] `plays/bfn517_gadeloegten/position_ven.md` is created
- [x] `plays/bfn517_gadeloegten/piece_olie.md` is created
- [x] `plays/bfn517_gadeloegten/place_gaden.md` is created
- [x] `plays/bfn517_gadeloegten/place_kaelderen.md` is created
- [x] `plays/bfn517_gadeloegten/process_tjeneste.md` is created
- [x] `plays/bfn517_gadeloegten/process_pension.md` is created
- [x] `plays/bfn517_gadeloegten/plan_lygtens_frygt.md` is created and linked to `persona_gadeloegten.md`
- [x] `plays/bfn517_gadeloegten/plan_vaegterens_redning.md` is created and linked to `persona_vaegteren.md`
- [x] `plays/bfn517_gadeloegten/pitch_nostalgi.md` is created
- [x] `plays/bfn517_gadeloegten/plot_sidste_aften.md` is created and casts company elements
- [x] `plays/bfn517_gadeloegten/plot_afskeden.md` is created and casts company elements
- [x] `plays/bfn517_gadeloegten/plot_kaelderlivet.md` is created and casts company elements
- [x] `plays/bfn517_gadeloegten/plot_drømme.md` is created and casts company elements
- [x] The local validation tests (`npm test`) run successfully with zero errors
