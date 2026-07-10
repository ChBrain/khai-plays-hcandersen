---
khai: order
title: "Stage SDU 617"
language: english
license: CC-BY-NC-SA-4.0
stamp:
  owner: KAI HACKS AI
  version: v0.0.1
  date: "2026-07-10"
---

# Order: Stage SDU 617

## Direction

The house must stage SDU 617 (_Maurerpigen_) to establish the seventeenth work in the "Drama" genre. The production must model the tragic conflict of Raphaella, Alhakein, and the Spanish King. It must model Cordova, the Moorish signet piece, the processes representing the war and Raphaella's identity crisis, Alhakein's disclosure plan, the dark tragic tone, and the three plots. All staging, prose, projections, actions, shadows, and tells must be authored in authentic Danish.

## Orders

1. The Playwright (Hans Christian Andersen) must author the play definition, the three personas (raphaella, alhakein, kongen), the three positions (heltinde, fange, monark), the one piece (tegn), the one place (cordova), the two processes (krig, identitetskrise), the in-world plan (afsloering), the pitch (tragedie), and the three plots.
2. The Theatre Manager (Edvard Collin) must verify the local registry, ensure correct versioning, check formatting, and validate that the entire cast conforms to the canon.
3. The Roadie (Vilhelm Pedersen) must set the stage, verify the local test suite is green, and prepare the files for packaging.

## Implementation

The play files must be placed in `plays/sdu617_maurerpigen/` and follow the house language policy:

- Structural elements and frontmatter in English.
- Narrative prose, projections, actions, shadows, tells, and staging notes in Danish.

## Targets

- [x] `plays/sdu617_maurerpigen/play_maurerpigen.md` is created and lists the complete company
- [x] `plays/sdu617_maurerpigen/persona_raphaella.md` is created and links to `position_heltinde.md`
- [x] `plays/sdu617_maurerpigen/persona_alhakein.md` is created and links to `position_fange.md`
- [x] `plays/sdu617_maurerpigen/persona_kongen.md` is created and links to `position_monark.md`
- [x] `plays/sdu617_maurerpigen/position_heltinde.md` is created
- [x] `plays/sdu617_maurerpigen/position_fange.md` is created
- [x] `plays/sdu617_maurerpigen/position_monark.md` is created
- [x] `plays/sdu617_maurerpigen/piece_tegn.md` is created
- [x] `plays/sdu617_maurerpigen/place_cordova.md` is created
- [x] `plays/sdu617_maurerpigen/process_krig.md` is created
- [x] `plays/sdu617_maurerpigen/process_identitetskrise.md` is created
- [x] `plays/sdu617_maurerpigen/plan_afsloering.md` is created
- [x] `plays/sdu617_maurerpigen/pitch_tragedie.md` is created
- [x] `plays/sdu617_maurerpigen/plot_heltinden.md` is created and casts company elements
- [x] `plays/sdu617_maurerpigen/plot_sandheden.md` is created and casts company elements
- [x] `plays/sdu617_maurerpigen/plot_faldet.md` is created and casts company elements
- [x] The local validation tests (`npm test`) run successfully with zero errors
