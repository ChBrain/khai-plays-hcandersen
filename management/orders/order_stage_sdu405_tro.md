---
khai: order
title: "Stage SDU 405"
language: english
license: CC-BY-NC-SA-4.0
stamp:
  owner: KAI HACKS AI
  version: v0.0.1
  date: "2026-07-08"
---

# Order: Stage SDU 405

## Direction

The house must stage SDU 405 (_At være eller ikke være_) to establish the fifth novel-length production in the H.C. Andersen house. The production must model the existential conflict between materialist science and religious faith through the character of Niels Bryde (the skeptical physician) and Esther (the faithful soul). It must also model the surgeon's scalpel ("Skalpel"), Niels' childhood in Rundetårn ("Rundetårn"), his upbringing in the parsonage ("Præstegården"), and the battlefield of Treårskrigen ("Slagmarken"). It must be written in authentic Danish for all staging and prose sections.

## Orders

1. The Playwright (Hans Christian Andersen) must author the play definition, the three personas (Niels, Esther, Præsten), the two positions (fritænker, troende), the one piece (skalpel), the three places (rundetaarn, praestegaarden, slagmarken), the two processes (splittelse, aabenbaring), the in-world plan (videnskab), the pitch (eksistentiel), and the three plots.
2. The Theatre Manager (Edvard Collin) must verify the local registry, ensure correct versioning, check formatting, and validate that the entire cast conforms to the canon.
3. The Roadie (Vilhelm Pedersen) must set the stage, verify the local test suite is green, and prepare the files for packaging.

## Implementation

The play files must be placed in `plays/sdu405_tro/` and follow the house language policy:

- Structural elements and frontmatter in English.
- Narrative prose, projections, actions, shadows, tells, and staging notes in Danish.

## Targets

- [x] `plays/sdu405_tro/play_tro.md` is created and lists the complete company
- [x] `plays/sdu405_tro/persona_niels.md` is created and links to `position_fritaenker.md`
- [x] `plays/sdu405_tro/persona_esther.md` is created and links to `position_troende.md`
- [x] `plays/sdu405_tro/persona_praesten.md` is created
- [x] `plays/sdu405_tro/position_fritaenker.md` is created
- [x] `plays/sdu405_tro/position_troende.md` is created
- [x] `plays/sdu405_tro/piece_skalpel.md` is created
- [x] `plays/sdu405_tro/place_rundetaarn.md` is created
- [x] `plays/sdu405_tro/place_praestegaarden.md` is created
- [x] `plays/sdu405_tro/place_slagmarken.md` is created
- [x] `plays/sdu405_tro/process_splittelse.md` is created
- [x] `plays/sdu405_tro/process_aabenbaring.md` is created
- [x] `plays/sdu405_tro/plan_videnskab.md` is created
- [x] `plays/sdu405_tro/pitch_eksistentiel.md` is created
- [x] `plays/sdu405_tro/plot_taarnbarndommen.md` is created and casts company elements
- [x] `plays/sdu405_tro/plot_esthers_doed.md` is created and casts company elements
- [x] `plays/sdu405_tro/plot_slagmarksundret.md` is created and casts company elements
- [x] The local validation tests (`npm test`) run successfully with zero errors
