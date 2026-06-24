---
khai: order
title: "Stage BFN 828 Sneglen og Rosenhaekken"
language: english
license: CC-BY-NC-SA-4.0
stamp:
  owner: KAI HACKS AI
  version: v0.0.1
  date: "2026-06-24"
---

# Order: Stage BFN 828 Sneglen og Rosenhaekken

## Direction

The house must stage BFN 828 (_Sneglen og Rosenhækken_) to establish the eighty-ninth production in the H.C. Andersen house. The production must model Snegl, Rosenhaek, the positions (Egoist, Yder), the piece (Slim), the environments (Have, Jord), the indkapsling and udfoldelse processes, and the plots leading to their realization. It must be written in authentic Danish for all prose sections.

## Orders

1. The Playwright (Hans Christian Andersen) must author the play definition, the two personas, the two positions, the piece, the two places, the two processes, the two in-world plans, the pitch of Satire, and the four plots.
2. The Theatre Manager (Edvard Collin) must verify the local registry, ensure correct versioning, check formatting, and validate that the cast conforms to the canon.
3. The Roadie (Vilhelm Pedersen) must set the stage, verify the local test suite is green, and prepare the files for packaging.

## Implementation

The play files must be placed in `plays/bfn828_sneglen_og_rosenhaekken/` and follow the house language policy:

- Structural elements and frontmatter in English.
- Narrative prose, projections, actions, shadows, tells, and staging notes in Danish.

## Targets

- [x] `plays/bfn828_sneglen_og_rosenhaekken/play_sneglen_og_rosenhaekken.md` is created and lists the complete company
- [x] `plays/bfn828_sneglen_og_rosenhaekken/persona_snegl.md` is created and links to `position_egoist.md`
- [x] `plays/bfn828_sneglen_og_rosenhaekken/persona_rosenhaek.md` is created and links to `position_yder.md`
- [x] `plays/bfn828_sneglen_og_rosenhaekken/position_egoist.md` is created
- [x] `plays/bfn828_sneglen_og_rosenhaekken/position_yder.md` is created
- [x] `plays/bfn828_sneglen_og_rosenhaekken/piece_slim.md` is created
- [x] `plays/bfn828_sneglen_og_rosenhaekken/place_have.md` is created
- [x] `plays/bfn828_sneglen_og_rosenhaekken/place_jord.md` is created
- [x] `plays/bfn828_sneglen_og_rosenhaekken/process_indkapsling.md` is created
- [x] `plays/bfn828_sneglen_og_rosenhaekken/process_udfoldelse.md` is created
- [x] `plays/bfn828_sneglen_og_rosenhaekken/plan_foragt.md` is created and linked to `persona_snegl.md`
- [x] `plays/bfn828_sneglen_og_rosenhaekken/plan_glaede.md` is created and linked to `persona_rosenhaek.md`
- [x] `plays/bfn828_sneglen_og_rosenhaekken/pitch_satire.md` is created
- [x] `plays/bfn828_sneglen_og_rosenhaekken/plot_moedet.md` is created and casts company elements
- [x] `plays/bfn828_sneglen_og_rosenhaekken/plot_kritikken.md` is created and casts company elements
- [x] `plays/bfn828_sneglen_og_rosenhaekken/plot_efteraaret.md` is created and casts company elements
- [x] `plays/bfn828_sneglen_og_rosenhaekken/plot_eftermaelet.md` is created and casts company elements
- [x] The local validation tests (`npm test`) run successfully with zero errors
