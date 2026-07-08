---
khai: order
title: "Stage SDU 402"
language: english
license: CC-BY-NC-SA-4.0
stamp:
  owner: KAI HACKS AI
  version: v0.0.1
  date: "2026-07-08"
---

# Order: Stage SDU 402

## Direction

The house must stage SDU 402 (_O.T._) to establish the second novel-length production in the H.C. Andersen house. The production must model Otto Thostrup's struggle, his brand mark ("O.T."), his aristocrat friend Vilhelm, the shadows from Odense Tugthus, his travel and social integration, and his final resolution with Eva. It must be written in authentic Danish for all staging and prose sections.

## Orders

1. The Playwright (Hans Christian Andersen) must author the play definition, the five personas (Otto, Vilhelm, Eva, Heinrich, Sophie), the three positions (outsider, aristokrat, afpresser), the one piece (braendemaerket), the three places (odense_tugthus, koebenhavn, herregaarden), the two processes (frigorelse, rejse), the in-world plan (integration), the pitch (melankolsk), and the three plots.
2. The Theatre Manager (Edvard Collin) must verify the local registry, ensure correct versioning, check formatting, and validate that the entire cast conforms to the canon.
3. The Roadie (Vilhelm Pedersen) must set the stage, verify the local test suite is green, and prepare the files for packaging.

## Implementation

The play files must be placed in `plays/sdu402_ot/` and follow the house language policy:

- Structural elements and frontmatter in English.
- Narrative prose, projections, actions, shadows, tells, and staging notes in Danish.

## Targets

- [x] `plays/sdu402_ot/play_ot.md` is created and lists the complete company
- [x] `plays/sdu402_ot/persona_otto.md` is created and links to `position_outsider.md`
- [x] `plays/sdu402_ot/persona_vilhelm.md` is created and links to `position_aristokrat.md`
- [x] `plays/sdu402_ot/persona_eva.md` is created
- [x] `plays/sdu402_ot/persona_heinrich.md` is created and links to `position_afpresser.md`
- [x] `plays/sdu402_ot/persona_sophie.md` is created
- [x] `plays/sdu402_ot/position_outsider.md` is created
- [x] `plays/sdu402_ot/position_aristokrat.md` is created
- [x] `plays/sdu402_ot/position_afpresser.md` is created
- [x] `plays/sdu402_ot/piece_braendemaerket.md` is created
- [x] `plays/sdu402_ot/place_odense_tugthus.md` is created
- [x] `plays/sdu402_ot/place_koebenhavn.md` is created
- [x] `plays/sdu402_ot/place_herregaarden.md` is created
- [x] `plays/sdu402_ot/process_frigorelse.md` is created
- [x] `plays/sdu402_ot/process_rejse.md` is created
- [x] `plays/sdu402_ot/plan_integration.md` is created
- [x] `plays/sdu402_ot/pitch_melankolsk.md` is created
- [x] `plays/sdu402_ot/plot_barndomsskyggen.md` is created and casts company elements
- [x] `plays/sdu402_ot/plot_studietiden.md` is created and casts company elements
- [x] `plays/sdu402_ot/plot_forloesningen.md` is created and casts company elements
- [x] The local validation tests (`npm test`) run successfully with zero errors
