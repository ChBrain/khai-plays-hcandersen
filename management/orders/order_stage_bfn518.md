---
khai: order
title: "Stage BFN 518"
language: english
license: CC-BY-NC-SA-4.0
stamp:
  owner: KAI HACKS AI
  version: v0.0.1
  date: "2026-06-21"
---

# Order: Stage BFN 518

## Direction

The house must stage BFN 518 (_Nabofamilierne_) to establish the thirty-sixth production in the H.C. Andersen house. The production must model Roserne, Graaspurvene, the positions (Skaber, Stoejende), the piece (Hegnet), the environments (Haven, Reden), the snoes and kvidren processes, and the plots leading to their realization. It must be written in authentic Danish for all prose sections.

## Orders

1. The Playwright (Hans Christian Andersen) must author the play definition, the two personas, the two positions, the piece, the two places, the two processes, the two in-world plans, the pitch of Refleksion, and the four plots.
2. The Theatre Manager (Edvard Collin) must verify the local registry, ensure correct versioning, check formatting, and validate that the entire cast conforms to the canon.
3. The Roadie (Vilhelm Pedersen) must set the stage, verify the local test suite is green, and prepare the files for packaging.

## Implementation

The play files must be placed in `plays/bfn518_nabofamilierne/` and follow the house language policy:

- Structural elements and frontmatter in English.
- Narrative prose, projections, actions, shadows, tells, and staging notes in Danish.

## Targets

- [x] `plays/bfn518_nabofamilierne/play_nabofamilierne.md` is created and lists the complete company
- [x] `plays/bfn518_nabofamilierne/persona_roserne.md` is created and links to `position_skaber.md`
- [x] `plays/bfn518_nabofamilierne/persona_graaspurvene.md` is created and links to `position_stoejende.md`
- [x] `plays/bfn518_nabofamilierne/position_skaber.md` is created
- [x] `plays/bfn518_nabofamilierne/position_stoejende.md` is created
- [x] `plays/bfn518_nabofamilierne/piece_hegnet.md` is created
- [x] `plays/bfn518_nabofamilierne/place_haven.md` is created
- [x] `plays/bfn518_nabofamilierne/place_reden.md` is created
- [x] `plays/bfn518_nabofamilierne/process_snoes.md` is created
- [x] `plays/bfn518_nabofamilierne/process_kvidren.md` is created
- [x] `plays/bfn518_nabofamilierne/plan_spredning.md` is created and linked to `persona_roserne.md`
- [x] `plays/bfn518_nabofamilierne/plan_overlevelse.md` is created and linked to `persona_graaspurvene.md`
- [x] `plays/bfn518_nabofamilierne/pitch_refleksion.md` is created
- [x] `plays/bfn518_nabofamilierne/plot_naboskab.md` is created and casts company elements
- [x] `plays/bfn518_nabofamilierne/plot_aarstider.md` is created and casts company elements
- [x] `plays/bfn518_nabofamilierne/plot_forgaengelighed.md` is created and casts company elements
- [x] `plays/bfn518_nabofamilierne/plot_eftermaele.md` is created and casts company elements
- [x] The local validation tests (`npm test`) run successfully with zero errors
