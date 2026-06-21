---
khai: order
title: "Stage BFN 469"
language: english
license: CC-BY-NC-SA-4.0
stamp:
  owner: KAI HACKS AI
  version: v0.0.1
  date: "2026-06-21"
---

# Order: Stage BFN 469

## Direction

The house must stage BFN 469 (_De røde Skoe_) to establish the twenty-eighth production in the H.C. Andersen house. The production must model Karen, Bødlen, the positions (Forfængelig, Bøddel), the pieces (Røde Sko, Øksen), the environments (Kirken, Bødelshus, Himlen), the besættelse and bod processes, and the plots leading to their realization. It must be written in authentic Danish for all prose sections.

## Orders

1. The Playwright (Hans Christian Andersen) must author the play definition, the two personas, the two positions, the two pieces, the three places, the two processes, the two in-world plans, the pitch of Dysterhed, and the four plots.
2. The Theatre Manager (Edvard Collin) must verify the local registry, ensure correct versioning, check formatting, and validate that the entire cast conforms to the canon.
3. The Roadie (Vilhelm Pedersen) must set the stage, verify the local test suite is green, and prepare the files for packaging.

## Implementation

The play files must be placed in `plays/bfn469_roede_skoe/` and follow the house language policy:

- Structural elements and frontmatter in English.
- Narrative prose, projections, actions, shadows, tells, and staging notes in Danish.

## Targets

- [x] `plays/bfn469_roede_skoe/play_roede_skoe.md` is created and lists the complete company
- [x] `plays/bfn469_roede_skoe/persona_karen.md` is created and links to `position_forfaengelig.md`
- [x] `plays/bfn469_roede_skoe/persona_boedlen.md` is created and links to `position_boeddel.md`
- [x] `plays/bfn469_roede_skoe/position_forfaengelig.md` is created
- [x] `plays/bfn469_roede_skoe/position_boeddel.md` is created
- [x] `plays/bfn469_roede_skoe/piece_roede_sko.md` is created
- [x] `plays/bfn469_roede_skoe/piece_oeksen.md` is created
- [x] `plays/bfn469_roede_skoe/place_kirken.md` is created
- [x] `plays/bfn469_roede_skoe/place_boedelshus.md` is created
- [x] `plays/bfn469_roede_skoe/place_himlen.md` is created
- [x] `plays/bfn469_roede_skoe/process_besaettelse.md` is created
- [x] `plays/bfn469_roede_skoe/process_bod.md` is created
- [x] `plays/bfn469_roede_skoe/plan_karens_forfaengelighed.md` is created and linked to `persona_karen.md`
- [x] `plays/bfn469_roede_skoe/plan_bodsoegning.md` is created and linked to `persona_karen.md`
- [x] `plays/bfn469_roede_skoe/pitch_dysterhed.md` is created
- [x] `plays/bfn469_roede_skoe/plot_skoene_koebes.md` is created and casts company elements
- [x] `plays/bfn469_roede_skoe/plot_dansen_begynder.md` is created and casts company elements
- [x] `plays/bfn469_roede_skoe/plot_afhugningen.md` is created and casts company elements
- [x] `plays/bfn469_roede_skoe/plot_tilgivelsen.md` is created and casts company elements
- [x] The local validation tests (`npm test`) run successfully with zero errors
