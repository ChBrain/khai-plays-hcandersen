---
khai: order
title: "Stage BFN 981 Laserne"
language: english
license: CC-BY-NC-SA-4.0
stamp:
  owner: KAI HACKS AI
  version: v0.0.1
  date: "2026-06-25"
---

# Order: Stage BFN 981 Laserne

## Direction

The house must stage BFN 981 (_Laserne_) to establish the hundred and eleventh production in the H.C. Andersen house. The production must model Dansk Las and Norsk Las, the positions (Beskeden, Stolt, Lige), the pieces (Kludebunke, Papir), the environments (Fabrik, Bunken), the disput and genanvendelse processes, and the plots representing the encounter, the war of words, and the final recycling. It must be written in authentic Danish for all prose sections.

## Orders

1. The Playwright (Hans Christian Andersen) must author the play definition, the two personas, the three positions, the two pieces, the two places, the two processes, the two in-world plans, the pitch of Satire, and the three plots.
2. The Theatre Manager (Edvard Collin) must verify the local registry, ensure correct versioning, check formatting, and validate that the cast conforms to the canon.
3. The Roadie (Vilhelm Pedersen) must set the stage, verify the local test suite is green, and prepare the files for packaging.

## Implementation

The play files must be placed in `plays/bfn981_laserne/` and follow the house language policy:

- Structural elements and frontmatter in English.
- Narrative prose, projections, actions, shadows, tells, and staging notes in Danish.

## Targets

- [x] `plays/bfn981_laserne/play_laserne.md` is created and lists the complete company
- [x] `plays/bfn981_laserne/persona_dansk_las.md` is created and links to `position_beskeden.md`
- [x] `plays/bfn981_laserne/persona_norsk_las.md` is created and links to `position_stolt.md`
- [x] `plays/bfn981_laserne/position_beskeden.md` is created
- [x] `plays/bfn981_laserne/position_stolt.md` is created
- [x] `plays/bfn981_laserne/position_lige.md` is created
- [x] `plays/bfn981_laserne/piece_kludebunke.md` is created
- [x] `plays/bfn981_laserne/piece_papir.md` is created
- [x] `plays/bfn981_laserne/place_fabrik.md` is created
- [x] `plays/bfn981_laserne/place_bunken.md` is created
- [x] `plays/bfn981_laserne/process_disput.md` is created
- [x] `plays/bfn981_laserne/process_genanvendelse.md` is created
- [x] `plays/bfn981_laserne/plan_selvhaevdelse.md` is created and linked to `persona_norsk_las.md`
- [x] `plays/bfn981_laserne/plan_forsvar.md` is created and linked to `persona_dansk_las.md`
- [x] `plays/bfn981_laserne/pitch_satire.md` is created
- [x] `plays/bfn981_laserne/plot_moedet.md` is created and casts company elements
- [x] `plays/bfn981_laserne/plot_ordkrigen.md` is created and casts company elements
- [x] `plays/bfn981_laserne/plot_skabelsen.md` is created and casts company elements
- [x] The local validation tests (`npm test`) run successfully with zero errors
