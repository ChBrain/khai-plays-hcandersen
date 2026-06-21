---
khai: order
title: "Stage BFN 455"
language: english
license: CC-BY-NC-SA-4.0
stamp:
  owner: KAI HACKS AI
  version: v0.0.1
  date: "2026-06-21"
---

# Order: Stage BFN 455

## Direction

The house must stage BFN 455 (_Grantræet_) to establish the twenty-fifth production in the H.C. Andersen house. The production must model Grantræet, Musene, the positions (Søgende, Tilskuer), the pieces (Pynten, Fortællingen), the environments (Skoven, Stuen, Loftet, Gaarden), the længsel and forbrænding processes, and the plots leading to their realization. It must be written in authentic Danish for all prose sections.

## Orders

1. The Playwright (Hans Christian Andersen) must author the play definition, the two personas, the two positions, the two pieces, the four places, the two processes, the two in-world plans, the pitch of Melankoli, and the four plots.
2. The Theatre Manager (Edvard Collin) must verify the local registry, ensure correct versioning, check formatting, and validate that the entire cast conforms to the canon.
3. The Roadie (Vilhelm Pedersen) must set the stage, verify the local test suite is green, and prepare the files for packaging.

## Implementation

The play files must be placed in `plays/bfn455_grantraeet/` and follow the house language policy:

- Structural elements and frontmatter in English.
- Narrative prose, projections, actions, shadows, tells, and staging notes in Danish.

## Targets

- [x] `plays/bfn455_grantraeet/play_grantraeet.md` is created and lists the complete company
- [x] `plays/bfn455_grantraeet/persona_grantraet.md` is created and links to `position_soegende.md`
- [x] `plays/bfn455_grantraeet/persona_musene.md` is created and links to `position_tilskuer.md`
- [x] `plays/bfn455_grantraeet/position_soegende.md` is created
- [x] `plays/bfn455_grantraeet/position_tilskuer.md` is created
- [x] `plays/bfn455_grantraeet/piece_pynt.md` is created
- [x] `plays/bfn455_grantraeet/piece_fortaelling.md` is created
- [x] `plays/bfn455_grantraeet/place_skoven.md` is created
- [x] `plays/bfn455_grantraeet/place_stuen.md` is created
- [x] `plays/bfn455_grantraeet/place_loftet.md` is created
- [x] `plays/bfn455_grantraeet/place_gaarden.md` is created
- [x] `plays/bfn455_grantraeet/process_laengsel.md` is created
- [x] `plays/bfn455_grantraeet/process_forbraending.md` is created
- [x] `plays/bfn455_grantraeet/plan_grantraets_draem.md` is created and linked to `persona_grantraet.md`
- [x] `plays/bfn455_grantraeet/plan_musenes_lytten.md` is created and linked to `persona_musene.md`
- [x] `plays/bfn455_grantraeet/pitch_melankoli.md` is created
- [x] `plays/bfn455_grantraeet/plot_skovliv.md` is created and casts company elements
- [x] `plays/bfn455_grantraeet/plot_juleaften.md` is created and casts company elements
- [x] `plays/bfn455_grantraeet/plot_loftet.md` is created and casts company elements
- [x] `plays/bfn455_grantraeet/plot_baalet.md` is created and casts company elements
- [x] The local validation tests (`npm test`) run successfully with zero errors
