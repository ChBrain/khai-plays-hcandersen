---
khai: order
title: "Stage BFN 606 Verdens dejligste Rose"
language: english
license: CC-BY-NC-SA-4.0
stamp:
  owner: KAI HACKS AI
  version: v0.0.1
  date: "2026-06-22"
---

# Order: Stage BFN 606 Verdens dejligste Rose

## Direction

The house must stage BFN 606 (_Verdens dejligste Rose_) to establish the forty-seventh production in the H.C. Andersen house. The production must model Dronning, Sogere, the positions (Lider, Dyrker), the piece (Rose), the environments (Have, Verden), the sogen and aabenbaring processes, and the plots leading to their realization. It must be written in authentic Danish for all prose sections.

## Orders

1. The Playwright (Hans Christian Andersen) must author the play definition, the two personas, the two positions, the piece, the two places, the two processes, the two in-world plans, the pitch of Andagt, and the four plots.
2. The Theatre Manager (Edvard Collin) must verify the local registry, ensure correct versioning, check formatting, and validate that the entire cast conforms to the canon.
3. The Roadie (Vilhelm Pedersen) must set the stage, verify the local test suite is green, and prepare the files for packaging.

## Implementation

The play files must be placed in `plays/bfn606_verdens_dejligste_rose/` and follow the house language policy:

- Structural elements and frontmatter in English.
- Narrative prose, projections, actions, shadows, tells, and staging notes in Danish.

## Targets

- [x] `plays/bfn606_verdens_dejligste_rose/play_verdens_dejligste_rose.md` is created and lists the complete company
- [x] `plays/bfn606_verdens_dejligste_rose/persona_dronning.md` is created and links to `position_lider.md`
- [x] `plays/bfn606_verdens_dejligste_rose/persona_sogere.md` is created and links to `position_dyrker.md`
- [x] `plays/bfn606_verdens_dejligste_rose/position_lider.md` is created
- [x] `plays/bfn606_verdens_dejligste_rose/position_dyrker.md` is created
- [x] `plays/bfn606_verdens_dejligste_rose/piece_rose.md` is created
- [x] `plays/bfn606_verdens_dejligste_rose/place_have.md` is created
- [x] `plays/bfn606_verdens_dejligste_rose/place_verden.md` is created
- [x] `plays/bfn606_verdens_dejligste_rose/process_sogen.md` is created
- [x] `plays/bfn606_verdens_dejligste_rose/process_aabenbaring.md` is created
- [x] `plays/bfn606_verdens_dejligste_rose/plan_helsot.md` is created and linked to `persona_dronning.md`
- [x] `plays/bfn606_verdens_dejligste_rose/plan_kjaerlighedssoeg.md` is created and linked to `persona_sogere.md`
- [x] `plays/bfn606_verdens_dejligste_rose/pitch_andagt.md` is created
- [x] `plays/bfn606_verdens_dejligste_rose/plot_helsot.md` is created and casts company elements
- [x] `plays/bfn606_verdens_dejligste_rose/plot_haven.md` is created and casts company elements
- [x] `plays/bfn606_verdens_dejligste_rose/plot_verden.md` is created and casts company elements
- [x] `plays/bfn606_verdens_dejligste_rose/plot_rose.md` is created and casts company elements
- [x] The local validation tests (`npm test`) run successfully with zero errors
