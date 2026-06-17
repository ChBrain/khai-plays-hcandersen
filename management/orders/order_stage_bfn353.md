---
khai: order
title: "Stage BFN 353"
language: english
license: CC-BY-NC-SA-4.0
stamp:
  owner: KAI HACKS AI
  version: v0.0.1
  date: "2026-06-17"
---

# Order: Stage BFN 353

## Direction

The house must stage BFN 353 (_Paradisets Have_) to establish the fourteenth production in the H.C. Andersen house. The production must model Prinsen, Vinden, Feen, Moderen, the positions (Søgende, Ledsager, Vogter, Fristerinde), the pieces (Bøgerne, Kundskabstræet, Kysset), the environments (Vindgrotten, Paradisets Have, Verden), the travel and fall processes, and the plots leading to their realization. It must be written in authentic Danish for all prose sections.

## Orders

1. The Playwright (Hans Christian Andersen) must author the play definition, the four personas, the four positions, the three pieces, the three places, the two processes, the two in-world plans, and the four plots.
2. The Theatre Manager (Edvard Collin) must verify the local registry, ensure correct versioning, check formatting, and validate that the entire cast conforms to the canon.
3. The Roadie (Vilhelm Pedersen) must set the stage, verify the local test suite is green, and prepare the files for packaging.

## Implementation

The play files must be placed in `plays/bfn353_paradisets_have/` and follow the house language policy:

- Structural elements and frontmatter in English.
- Narrative prose, projections, actions, shadows, tells, and staging notes in Danish.

## Targets

- [x] `plays/bfn353_paradisets_have/play_paradisets_have.md` is created and lists the complete company
- [x] `plays/bfn353_paradisets_have/persona_prinsen.md` is created and links to `position_soegende.md`
- [x] `plays/bfn353_paradisets_have/persona_vinden.md` is created and links to `position_ledsager.md`
- [x] `plays/bfn353_paradisets_have/persona_feen.md` is created and links to `position_fristerinde.md`
- [x] `plays/bfn353_paradisets_have/persona_moderen.md` is created and links to `position_vogter.md`
- [x] `plays/bfn353_paradisets_have/position_soegende.md` is created
- [x] `plays/bfn353_paradisets_have/position_ledsager.md` is created
- [x] `plays/bfn353_paradisets_have/position_vogter.md` is created
- [x] `plays/bfn353_paradisets_have/position_fristerinde.md` is created
- [x] `plays/bfn353_paradisets_have/piece_boeger.md` is created
- [x] `plays/bfn353_paradisets_have/piece_kundskabstrae.md` is created
- [x] `plays/bfn353_paradisets_have/piece_kysset.md` is created
- [x] `plays/bfn353_paradisets_have/place_hulen.md` is created
- [x] `plays/bfn353_paradisets_have/place_haven.md` is created
- [x] `plays/bfn353_paradisets_have/place_verden.md` is created
- [x] `plays/bfn353_paradisets_have/process_rejse.md` is created
- [x] `plays/bfn353_paradisets_have/process_syndefald.md` is created
- [x] `plays/bfn353_paradisets_have/plan_prinsens_plan.md` is created and linked to `persona_prinsen.md`
- [x] `plays/bfn353_paradisets_have/plan_vindenes_plan.md` is created and linked to `persona_vinden.md`
- [x] `plays/bfn353_paradisets_have/plot_hulen.md` is created and casts company elements
- [x] `plays/bfn353_paradisets_have/plot_rejsen.md` is created and casts company elements
- [x] `plays/bfn353_paradisets_have/plot_haven.md` is created and casts company elements
- [x] `plays/bfn353_paradisets_have/plot_syndefaldet.md` is created and casts company elements
- [x] The local validation tests (`npm test`) run successfully with zero errors
