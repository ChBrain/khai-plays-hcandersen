---
khai: order
title: "Stage BFN 992 Hvad Tidselen oplevede"
language: english
license: CC-BY-NC-SA-4.0
stamp:
  owner: KAI HACKS AI
  version: v0.0.1
  date: "2026-06-25"
---

# Order: Stage BFN 992 Hvad Tidselen oplevede

## Direction

The house must stage BFN 992 (_Hvad Tidselen oplevede_) to establish the hundred and seventeenth production in the H.C. Andersen house. The production must model Tidsel, Æselet, and Pige, the positions (Stolt, Nydende, Medfølende), the pieces (Tidselblomst, Rose), the environments (Gaarden, Marken), the vækst and fortæring processes, and the plots representing the roses as neighbors, the donkey's feast, and the thistle being picked as a keepsake. It must be written in authentic Danish for all prose sections.

## Orders

1. The Playwright (Hans Christian Andersen) must author the play definition, the three personas, the three positions, the two pieces, the two places, the two processes, the two in-world plans, the pitch of Melankolsk, and the three plots.
2. The Theatre Manager (Edvard Collin) must verify the local registry, ensure correct versioning, check formatting, and validate that the cast conforms to the canon.
3. The Roadie (Vilhelm Pedersen) must set the stage, verify the local test suite is green, and prepare the files for packaging.

## Implementation

The play files must be placed in `plays/bfn992_hvad_tidselen_oplevede/` and follow the house language policy:

- Structural elements and frontmatter in English.
- Narrative prose, projections, actions, shadows, tells, and staging notes in Danish.

## Targets

- [x] `plays/bfn992_hvad_tidselen_oplevede/play_hvad_tidselen_oplevede.md` is created and lists the complete company
- [x] `plays/bfn992_hvad_tidselen_oplevede/persona_tidsel.md` is created and links to `position_stolt.md`
- [x] `plays/bfn992_hvad_tidselen_oplevede/persona_aeselet.md` is created and links to `position_nydende.md`
- [x] `plays/bfn992_hvad_tidselen_oplevede/persona_pige.md` is created and links to `position_medfoelende.md`
- [x] `plays/bfn992_hvad_tidselen_oplevede/position_stolt.md` is created
- [x] `plays/bfn992_hvad_tidselen_oplevede/position_nydende.md` is created
- [x] `plays/bfn992_hvad_tidselen_oplevede/position_medfoelende.md` is created
- [x] `plays/bfn992_hvad_tidselen_oplevede/piece_tidselblomst.md` is created
- [x] `plays/bfn992_hvad_tidselen_oplevede/piece_rose.md` is created
- [x] `plays/bfn992_hvad_tidselen_oplevede/place_gaarden.md` is created
- [x] `plays/bfn992_hvad_tidselen_oplevede/place_marken.md` is created
- [x] `plays/bfn992_hvad_tidselen_oplevede/process_vaekst.md` is created
- [x] `plays/bfn992_hvad_tidselen_oplevede/process_fortaering.md` is created
- [x] `plays/bfn992_hvad_tidselen_oplevede/plan_selvhaevdelse.md` is created and linked to `persona_tidsel.md`
- [x] `plays/bfn992_hvad_tidselen_oplevede/plan_erindring.md` is created and linked to `persona_pige.md`
- [x] `plays/bfn992_hvad_tidselen_oplevede/pitch_melankolsk.md` is created
- [x] `plays/bfn992_hvad_tidselen_oplevede/plot_naboskabet.md` is created and casts company elements
- [x] `plays/bfn992_hvad_tidselen_oplevede/plot_aeselet.md` is created and casts company elements
- [x] `plays/bfn992_hvad_tidselen_oplevede/plot_erindringen.md` is created and casts company elements
- [x] The local validation tests (`npm test`) run successfully with zero errors
