---
khai: order
title: "Stage BFN 932 Vaenoe og Glaenoe"
language: english
license: CC-BY-NC-SA-4.0
stamp:
  owner: KAI HACKS AI
  version: v0.0.1
  date: "2026-06-25"
---

# Order: Stage BFN 932 Vaenoe og Glaenoe

## Direction

The house must stage BFN 932 (_Vænø og Glænø_) to establish the hundred and third production in the H.C. Andersen house. The production must model Vænø, Glænø, and Mennesket, the positions (Sunken, Truet, Omformende), the pieces (Sandrev, Dæmning), the environments (Havbunden, Kysten), the inddæmning and opslugning processes, and the plots representing the legend, the storm, the plans, and the reclamation. It must be written in authentic Danish for all prose sections.

## Orders

1. The Playwright (Hans Christian Andersen) must author the play definition, the three personas, the three positions, the two pieces, the two places, the two processes, the two in-world plans, the pitch of Naturkræfter, and the four plots.
2. The Theatre Manager (Edvard Collin) must verify the local registry, ensure correct versioning, check formatting, and validate that the cast conforms to the canon.
3. The Roadie (Vilhelm Pedersen) must set the stage, verify the local test suite is green, and prepare the files for packaging.

## Implementation

The play files must be placed in `plays/bfn932_vaenoe_og_glaenoe/` and follow the house language policy:

- Structural elements and frontmatter in English.
- Narrative prose, projections, actions, shadows, tells, and staging notes in Danish.

## Targets

- [x] `plays/bfn932_vaenoe_og_glaenoe/play_vaenoe_og_glaenoe.md` is created and lists the complete company
- [x] `plays/bfn932_vaenoe_og_glaenoe/persona_vaenoe.md` is created and links to `position_sunken.md`
- [x] `plays/bfn932_vaenoe_og_glaenoe/persona_glaenoe.md` is created and links to `position_truet.md`
- [x] `plays/bfn932_vaenoe_og_glaenoe/persona_mennesket.md` is created and links to `position_omformende.md`
- [x] `plays/bfn932_vaenoe_og_glaenoe/position_sunken.md` is created
- [x] `plays/bfn932_vaenoe_og_glaenoe/position_truet.md` is created
- [x] `plays/bfn932_vaenoe_og_glaenoe/position_omformende.md` is created
- [x] `plays/bfn932_vaenoe_og_glaenoe/piece_sandrev.md` is created
- [x] `plays/bfn932_vaenoe_og_glaenoe/piece_daemning.md` is created
- [x] `plays/bfn932_vaenoe_og_glaenoe/place_havbunden.md` is created
- [x] `plays/bfn932_vaenoe_og_glaenoe/place_kysten.md` is created
- [x] `plays/bfn932_vaenoe_og_glaenoe/process_inddaemning.md` is created
- [x] `plays/bfn932_vaenoe_og_glaenoe/process_opslugning.md` is created
- [x] `plays/bfn932_vaenoe_og_glaenoe/plan_forbindelse.md` is created and linked to `persona_mennesket.md`
- [x] `plays/bfn932_vaenoe_og_glaenoe/plan_forsvinding.md` is created and linked to `persona_glaenoe.md`
- [x] `plays/bfn932_vaenoe_og_glaenoe/pitch_naturkraefter.md` is created
- [x] `plays/bfn932_vaenoe_og_glaenoe/plot_legende.md` is created and casts company elements
- [x] `plays/bfn932_vaenoe_og_glaenoe/plot_stormen.md` is created and casts company elements
- [x] `plays/bfn932_vaenoe_og_glaenoe/plot_planerne.md` is created and casts company elements
- [x] `plays/bfn932_vaenoe_og_glaenoe/plot_inddaemningen.md` is created and casts company elements
- [x] The local validation tests (`npm test`) run successfully with zero errors
