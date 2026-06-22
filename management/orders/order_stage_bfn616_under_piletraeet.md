---
khai: order
title: "Stage BFN 616 Under Piletræet"
language: english
license: CC-BY-NC-SA-4.0
stamp:
  owner: KAI HACKS AI
  version: v0.0.1
  date: "2026-06-22"
---

# Order: Stage BFN 616 Under Piletræet

## Direction

The house must stage BFN 616 (_Under Piletræet_) to establish the fifty-seventh production in the H.C. Andersen house. The production must model Knud, Johanne, the positions (Laengselsfuld, Ambitioes), the piece (Peberkage), the environments (Piletrae, Fremmede), the rejse and droem processes, and the plots leading to their realization. It must be written in authentic Danish for all prose sections.

## Orders

1. The Playwright (Hans Christian Andersen) must author the play definition, the two personas, the two positions, the piece, the two places, the two processes, the two in-world plans, the pitch of Tender, and the four plots.
2. The Theatre Manager (Edvard Collin) must verify the local registry, ensure correct versioning, check formatting, and validate that the entire cast conforms to the canon.
3. The Roadie (Vilhelm Pedersen) must set the stage, verify the local test suite is green, and prepare the files for packaging.

## Implementation

The play files must be placed in `plays/bfn616_under_piletraeet/` and follow the house language policy:

- Structural elements and frontmatter in English.
- Narrative prose, projections, actions, shadows, tells, and staging notes in Danish.

## Targets

- [x] `plays/bfn616_under_piletraeet/play_under_piletraeet.md` is created and lists the complete company
- [x] `plays/bfn616_under_piletraeet/persona_knud.md` is created and links to `position_laengselsfuld.md`
- [x] `plays/bfn616_under_piletraeet/persona_johanne.md` is created and links to `position_ambitioes.md`
- [x] `plays/bfn616_under_piletraeet/position_laengselsfuld.md` is created
- [x] `plays/bfn616_under_piletraeet/position_ambitioes.md` is created
- [x] `plays/bfn616_under_piletraeet/piece_peberkage.md` is created
- [x] `plays/bfn616_under_piletraeet/place_piletrae.md` is created
- [x] `plays/bfn616_under_piletraeet/place_fremmede.md` is created
- [x] `plays/bfn616_under_piletraeet/process_rejse.md` is created
- [x] `plays/bfn616_under_piletraeet/process_droem.md` is created
- [x] `plays/bfn616_under_piletraeet/plan_gensynsoeg.md` is created and linked to `persona_knud.md`
- [x] `plays/bfn616_under_piletraeet/plan_kunstnerfaerd.md` is created and linked to `persona_johanne.md`
- [x] `plays/bfn616_under_piletraeet/pitch_tender.md` is created
- [x] `plays/bfn616_under_piletraeet/plot_barndom.md` is created and casts company elements
- [x] `plays/bfn616_under_piletraeet/plot_adskillelse.md` is created and casts company elements
- [x] `plays/bfn616_under_piletraeet/plot_afvisning.md` is created and casts company elements
- [x] `plays/bfn616_under_piletraeet/plot_doed.md` is created and casts company elements
- [x] The local validation tests (`npm test`) run successfully with zero errors
