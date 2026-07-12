---
khai: order
title: "Stage SDU 628"
language: english
license: CC-BY-NC-SA-4.0
stamp:
  owner: KAI HACKS AI
  version: v0.0.1
  date: "2026-07-12"
---

# Order: Stage SDU 628

## Direction

The house must stage SDU 628 (_Ole Lukøie_) to establish the twenty-eighth work in the "Drama" genre. The production must model the fantastical, moral dialogues of Ole Lukøie, Christian, and Marie. It must model Christian's garret room place, the dream-bringing umbrella piece, the processes representing the dream journey and the moral realization, Christian's plan to find true happiness, the whimsical eventyrkomedie tone, and the three plots. All staging, prose, projections, actions, shadows, and tells must be authored in authentic Danish.

## Orders

1. The Playwright (Hans Christian Andersen) must author the play definition, the three personas (ole, christian, marie), the three positions (ole_stilling, christian_stilling, marie_stilling), the one piece (paraply), the one place (kammer), the two processes (droem, indsigt), the in-world plan (sjaelefred), the pitch (komedie), and the three plots.
2. The Theatre Manager (Edvard Collin) must verify the local registry, ensure correct versioning, check formatting, and validate that the entire cast conforms to the canon.
3. The Roadie (Vilhelm Pedersen) must set the stage, verify the local test suite is green, and prepare the files for packaging.

## Implementation

The play files must be placed in `plays/sdu628_ole_lukoeie/` and follow the house language policy:

- Structural elements and frontmatter in English.
- Narrative prose, projections, actions, shadows, tells, and staging notes in Danish.

## Targets

- [x] `plays/sdu628_ole_lukoeie/play_ole_lukoeie.md` is created and lists the complete company
- [x] `plays/sdu628_ole_lukoeie/persona_ole.md` is created and links to `position_ole_stilling.md`
- [x] `plays/sdu628_ole_lukoeie/persona_christian.md` is created and links to `position_christian_stilling.md`
- [x] `plays/sdu628_ole_lukoeie/persona_marie.md` is created and links to `position_marie_stilling.md`
- [x] `plays/sdu628_ole_lukoeie/position_ole_stilling.md` is created
- [x] `plays/sdu628_ole_lukoeie/position_christian_stilling.md` is created
- [x] `plays/sdu628_ole_lukoeie/position_marie_stilling.md` is created
- [x] `plays/sdu628_ole_lukoeie/piece_paraply.md` is created
- [x] `plays/sdu628_ole_lukoeie/place_kammer.md` is created
- [x] `plays/sdu628_ole_lukoeie/process_droem.md` is created
- [x] `plays/sdu628_ole_lukoeie/process_indsigt.md` is created
- [x] `plays/sdu628_ole_lukoeie/plan_sjaelefred.md` is created
- [x] `plays/sdu628_ole_lukoeie/pitch_komedie.md` is created
- [x] `plays/sdu628_ole_lukoeie/plot_droem.md` is created and casts company elements
- [x] `plays/sdu628_ole_lukoeie/plot_rigdom.md` is created and casts company elements
- [x] `plays/sdu628_ole_lukoeie/plot_vaagnen.md` is created and casts company elements
- [x] The local validation tests (`npm test`) run successfully with zero errors
