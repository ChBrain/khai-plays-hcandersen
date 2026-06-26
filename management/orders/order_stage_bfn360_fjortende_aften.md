---
khai: order
title: "Stage BFN 360 Fjortende Aften"
language: english
license: CC-BY-NC-SA-4.0
stamp:
  owner: KAI HACKS AI
  version: v0.0.1
  date: "2026-06-26"
---

# Order: Stage BFN 360 Fjortende Aften

## Direction

The house must stage BFN 360 (_Fjortende Aften_) to establish a production in the H.C. Andersen house. The production must model maanen, soldaten, the positions (fortaeller, veteran), the pieces (medalje, sabel), the environments (stuen, volden), the fortaelling and erindring processes, and the plots representing natten and mindet. It must be written in authentic Danish for all prose sections.

## Orders

1. The Playwright (Hans Christian Andersen) must author the play definition, the 2 personas, the 2 positions, the 2 pieces, the 2 places, the 2 processes, the 1 in-world plans, the pitch of historisk, and the 2 plots.
2. The Theatre Manager (Edvard Collin) must verify the local registry, ensure correct versioning, check formatting, and validate that the cast conforms to the canon.
3. The Roadie (Vilhelm Pedersen) must set the stage, verify the local test suite is green, and prepare the files for packaging.

## Implementation

The play files must be placed in `plays/bfn360_fjortende_aften/` and follow the house language policy:

- Structural elements and frontmatter in English.
- Narrative prose, projections, actions, shadows, tells, and staging notes in Danish.

## Targets

- [x] `plays/bfn360_fjortende_aften/play_fjortende_aften.md` is created and lists the complete company
- [x] `plays/bfn360_fjortende_aften/persona_maanen.md` is created and links to `position_fortaeller.md`
- [x] `plays/bfn360_fjortende_aften/persona_soldaten.md` is created and links to `position_veteran.md`
- [x] `plays/bfn360_fjortende_aften/position_fortaeller.md` is created
- [x] `plays/bfn360_fjortende_aften/position_veteran.md` is created
- [x] `plays/bfn360_fjortende_aften/piece_medalje.md` is created
- [x] `plays/bfn360_fjortende_aften/piece_sabel.md` is created
- [x] `plays/bfn360_fjortende_aften/place_stuen.md` is created
- [x] `plays/bfn360_fjortende_aften/place_volden.md` is created
- [x] `plays/bfn360_fjortende_aften/process_fortaelling.md` is created
- [x] `plays/bfn360_fjortende_aften/process_erindring.md` is created
- [x] `plays/bfn360_fjortende_aften/plan_aere.md` is created and linked to `persona_soldaten.md`
- [x] `plays/bfn360_fjortende_aften/pitch_historisk.md` is created
- [x] `plays/bfn360_fjortende_aften/plot_natten.md` is created and casts company elements
- [x] `plays/bfn360_fjortende_aften/plot_mindet.md` is created and casts company elements
- [x] The local validation tests (`npm test`) run successfully with zero errors
