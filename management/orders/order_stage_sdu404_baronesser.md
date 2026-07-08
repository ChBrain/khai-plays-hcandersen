---
khai: order
title: "Stage SDU 404"
language: english
license: CC-BY-NC-SA-4.0
stamp:
  owner: KAI HACKS AI
  version: v0.0.1
  date: "2026-07-08"
---

# Order: Stage SDU 404

## Direction

The house must stage SDU 404 (_De to Baronesser_) to establish the fourth novel-length production in the H.C. Andersen house. The production must model the social mobility and transition from the old absolute order to the modern humanist era through the characters of Elisabeth (the young self-made noble) and Baronesse Dorothea (the proud, guilt-ridden elder noble). It must also model the family ring ("Slægtsringen"), Elisabeth's education in Copenhagen, her childhood on the Wadden Sea ("Vadehavet"), and the Funen estate ("Herregaarden"). It must be written in authentic Danish for all staging and prose sections.

## Orders

1. The Playwright (Hans Christian Andersen) must author the play definition, the four personas (Elisabeth, Dorothea, Herman, Moritz), the two positions (unge baronesse, gamle baronesse), the one piece (slægtsringen), the three places (vadehavet, koebenhavn, herregaarden), the two processes (dannelse, forfald), the in-world plan (integration), the pitch (tidsaand), and the three plots.
2. The Theatre Manager (Edvard Collin) must verify the local registry, ensure correct versioning, check formatting, and validate that the entire cast conforms to the canon.
3. The Roadie (Vilhelm Pedersen) must set the stage, verify the local test suite is green, and prepare the files for packaging.

## Implementation

The play files must be placed in `plays/sdu404_baronesser/` and follow the house language policy:

- Structural elements and frontmatter in English.
- Narrative prose, projections, actions, shadows, tells, and staging notes in Danish.

## Targets

- [x] `plays/sdu404_baronesser/play_baronesser.md` is created and lists the complete company
- [x] `plays/sdu404_baronesser/persona_elisabeth.md` is created and links to `position_unge_baronesse.md`
- [x] `plays/sdu404_baronesser/persona_dorothea.md` is created and links to `position_gamle_baronesse.md`
- [x] `plays/sdu404_baronesser/persona_herman.md` is created
- [x] `plays/sdu404_baronesser/persona_moritz.md` is created
- [x] `plays/sdu404_baronesser/position_unge_baronesse.md` is created
- [x] `plays/sdu404_baronesser/position_gamle_baronesse.md` is created
- [x] `plays/sdu404_baronesser/piece_slaegtsringen.md` is created
- [x] `plays/sdu404_baronesser/place_vadehavet.md` is created
- [x] `plays/sdu404_baronesser/place_koebenhavn.md` is created
- [x] `plays/sdu404_baronesser/place_herregaarden.md` is created
- [x] `plays/sdu404_baronesser/process_dannelse.md` is created
- [x] `plays/sdu404_baronesser/process_forfald.md` is created
- [x] `plays/sdu404_baronesser/plan_integration.md` is created
- [x] `plays/sdu404_baronesser/pitch_tidsaand.md` is created
- [x] `plays/sdu404_baronesser/plot_vadehavsbarnet.md` is created and casts company elements
- [x] `plays/sdu404_baronesser/plot_dannelsesaarene.md` is created and casts company elements
- [x] `plays/sdu404_baronesser/plot_forsoningen.md` is created and casts company elements
- [x] The local validation tests (`npm test`) run successfully with zero errors
