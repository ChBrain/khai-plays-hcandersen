---
khai: order
title: "Stage BFN 410"
language: english
license: CC-BY-NC-SA-4.0
stamp:
  owner: KAI HACKS AI
  version: v0.0.1
  date: "2026-06-19"
---

# Order: Stage BFN 410

## Direction

The house must stage BFN 410 (_Svinedrengen_) to establish the nineteenth production in the H.C. Andersen house. The production must model Prinsen, Prinsessen, Kejseren, the positions (Bejlende, Afvisende, Dommer), the pieces (Rosen, Nattergalen, Gryden, Skralden), the environments (Prinsens Rige, Kejserens Slot, Grænsen), the wooing and barter processes, and the plots leading to their realization. It must be written in authentic Danish for all prose sections.

## Orders

1. The Playwright (Hans Christian Andersen) must author the play definition, the three personas, the three positions, the four pieces, the three places, the two processes, the two in-world plans, the pitch of Vanity, and the four plots.
2. The Theatre Manager (Edvard Collin) must verify the local registry, ensure correct versioning, check formatting, and validate that the entire cast conforms to the canon.
3. The Roadie (Vilhelm Pedersen) must set the stage, verify the local test suite is green, and prepare the files for packaging.

## Implementation

The play files must be placed in `plays/bfn410_svinedrengen/` and follow the house language policy:

- Structural elements and frontmatter in English.
- Narrative prose, projections, actions, shadows, tells, and staging notes in Danish.

## Targets

- [x] `plays/bfn410_svinedrengen/play_svinedrengen.md` is created and lists the complete company
- [x] `plays/bfn410_svinedrengen/persona_prinsen.md` is created and links to `position_bejlende.md`
- [x] `plays/bfn410_svinedrengen/persona_prinsessen.md` is created and links to `position_afvisende.md`
- [x] `plays/bfn410_svinedrengen/persona_kejseren.md` is created and links to `position_dommer.md`
- [x] `plays/bfn410_svinedrengen/position_bejlende.md` is created
- [x] `plays/bfn410_svinedrengen/position_afvisende.md` is created
- [x] `plays/bfn410_svinedrengen/position_dommer.md` is created
- [x] `plays/bfn410_svinedrengen/piece_rosen.md` is created
- [x] `plays/bfn410_svinedrengen/piece_nattergalen.md` is created
- [x] `plays/bfn410_svinedrengen/piece_gryden.md` is created
- [x] `plays/bfn410_svinedrengen/piece_skralden.md` is created
- [x] `plays/bfn410_svinedrengen/place_prinsens_rige.md` is created
- [x] `plays/bfn410_svinedrengen/place_kejserens_slot.md` is created
- [x] `plays/bfn410_svinedrengen/place_graensen.md` is created
- [x] `plays/bfn410_svinedrengen/process_bejling.md` is created
- [x] `plays/bfn410_svinedrengen/process_byttehandel.md` is created
- [x] `plays/bfn410_svinedrengen/plan_prinsens_test.md` is created and linked to `persona_prinsen.md`
- [x] `plays/bfn410_svinedrengen/plan_prinsessens_begaer.md` is created and linked to `persona_prinsessen.md`
- [x] `plays/bfn410_svinedrengen/pitch_vanity.md` is created
- [x] `plays/bfn410_svinedrengen/plot_gaverne.md` is created and casts company elements
- [x] `plays/bfn410_svinedrengen/plot_svinestien.md` is created and casts company elements
- [x] `plays/bfn410_svinedrengen/plot_skralden.md` is created and casts company elements
- [x] `plays/bfn410_svinedrengen/plot_afvisningen.md` is created and casts company elements
- [x] The local validation tests (`npm test`) run successfully with zero errors
