---
khai: order
title: "Stage BFN 470"
language: english
license: CC-BY-NC-SA-4.0
stamp:
  owner: KAI HACKS AI
  version: v0.0.1
  date: "2026-06-21"
---

# Order: Stage BFN 470

## Direction

The house must stage BFN 470 (_Springfyrene_) to establish the twenty-ninth production in the H.C. Andersen house. The production must model Loppen, Græshoppen, Springgaasen, the position (Konkurrent), the pieces (Brystbenet, Prinsessen), the environments (Kongesalen, Prinsessens Skød), the spring and vurdering processes, and the plots leading to their realization. It must be written in authentic Danish for all prose sections.

## Orders

1. The Playwright (Hans Christian Andersen) must author the play definition, the three personas, the position, the two pieces, the two places, the two processes, the two in-world plans, the pitch of Satire, and the four plots.
2. The Theatre Manager (Edvard Collin) must verify the local registry, ensure correct versioning, check formatting, and validate that the entire cast conforms to the canon.
3. The Roadie (Vilhelm Pedersen) must set the stage, verify the local test suite is green, and prepare the files for packaging.

## Implementation

The play files must be placed in `plays/bfn470_springfyrene/` and follow the house language policy:

- Structural elements and frontmatter in English.
- Narrative prose, projections, actions, shadows, tells, and staging notes in Danish.

## Targets

- [x] `plays/bfn470_springfyrene/play_springfyrene.md` is created and lists the complete company
- [x] `plays/bfn470_springfyrene/persona_loppen.md` is created and links to `position_konkurrent.md`
- [x] `plays/bfn470_springfyrene/persona_graeshoppen.md` is created and links to `position_konkurrent.md`
- [x] `plays/bfn470_springfyrene/persona_springgaasen.md` is created and links to `position_konkurrent.md`
- [x] `plays/bfn470_springfyrene/position_konkurrent.md` is created
- [x] `plays/bfn470_springfyrene/piece_brystbenet.md` is created
- [x] `plays/bfn470_springfyrene/piece_prinsessen.md` is created
- [x] `plays/bfn470_springfyrene/place_kongesalen.md` is created
- [x] `plays/bfn470_springfyrene/place_prinsessens_skoed.md` is created
- [x] `plays/bfn470_springfyrene/process_spring.md` is created
- [x] `plays/bfn470_springfyrene/process_vurdering.md` is created
- [x] `plays/bfn470_springfyrene/plan_springet.md` is created and linked to competitors
- [x] `plays/bfn470_springfyrene/plan_springgaasens_taktik.md` is created and linked to `persona_springgaasen.md`
- [x] `plays/bfn470_springfyrene/pitch_satire.md` is created
- [x] `plays/bfn470_springfyrene/plot_udfordringen.md` is created and casts company elements
- [x] `plays/bfn470_springfyrene/plot_loppens_spring.md` is created and casts company elements
- [x] `plays/bfn470_springfyrene/plot_graeshoppens_spring.md` is created and casts company elements
- [x] `plays/bfn470_springfyrene/plot_springgaasens_triumf.md` is created and casts company elements
- [x] The local validation tests (`npm test`) run successfully with zero errors
