---
khai: order
title: "Stage BFN 267"
language: english
license: CC-BY-NC-SA-4.0
stamp:
  owner: KAI HACKS AI
  version: v0.0.1
  date: "2026-06-16"
---

# Order: Stage BFN 267

## Direction

The house must stage BFN 267 (_Fyrtøjet_) to establish the second production in the H.C. Andersen house. The production must model the soldier's social ascent, the magical summoning mechanism of the tinderbox, the witch's apron, the princess, and the three giant dogs with teacup, millwheel, and Round Tower eyes. It must be written in authentic Danish for all prose sections.

## Orders

1. The Playwright (Hans Christian Andersen) must author the play definition, the five personas (Soldaten, Heksen, Hundene, Prinsessen, Kongen), the five positions (soldat, heks, tjener, fange, monark), the three pieces (fyrtoejet, guldet, forklaedet), the five places (landevejen, traeet, kroen, kobberslottet, galgen), the two processes (paakaldelse, transport), the two in-world plans (heksens plan, soldatens plan), and the four plots.
2. The Theatre Manager (Edvard Collin) must verify the local registry, ensure correct versioning, check formatting, and validate that the entire cast conforms to the canon.
3. The Roadie (Vilhelm Pedersen) must set the stage, verify the local test suite is green, and prepare the files for packaging.

## Implementation

The play files must be placed in `plays/bfn267_fyrtoejet/` and follow the house language policy:

- Structural elements and frontmatter in English.
- Narrative prose, projections, actions, shadows, tells, and staging notes in Danish.

## Targets

- [x] `plays/bfn267_fyrtoejet/play_fyrtoejet.md` is created and lists the complete company
- [x] `plays/bfn267_fyrtoejet/persona_soldaten.md` is created and links to `position_soldat.md`
- [x] `plays/bfn267_fyrtoejet/persona_heksen.md` is created and links to `position_heks.md`
- [x] `plays/bfn267_fyrtoejet/persona_hundene.md` is created and links to `position_tjener.md`
- [x] `plays/bfn267_fyrtoejet/persona_prinsessen.md` is created and links to `position_fange.md`
- [x] `plays/bfn267_fyrtoejet/persona_kongen.md` is created and links to `position_monark.md`
- [x] `plays/bfn267_fyrtoejet/position_soldat.md` is created
- [x] `plays/bfn267_fyrtoejet/position_heks.md` is created
- [x] `plays/bfn267_fyrtoejet/position_tjener.md` is created
- [x] `plays/bfn267_fyrtoejet/position_fange.md` is created
- [x] `plays/bfn267_fyrtoejet/position_monark.md` is created
- [x] `plays/bfn267_fyrtoejet/piece_fyrtoejet.md` is created
- [x] `plays/bfn267_fyrtoejet/piece_guldet.md` is created
- [x] `plays/bfn267_fyrtoejet/piece_forklaedet.md` is created
- [x] `plays/bfn267_fyrtoejet/place_landevejen.md` is created
- [x] `plays/bfn267_fyrtoejet/place_traeet.md` is created
- [x] `plays/bfn267_fyrtoejet/place_kroen.md` is created
- [x] `plays/bfn267_fyrtoejet/place_kobberslottet.md` is created
- [x] `plays/bfn267_fyrtoejet/place_galgen.md` is created
- [x] `plays/bfn267_fyrtoejet/process_paakaldelse.md` is created
- [x] `plays/bfn267_fyrtoejet/process_transport.md` is created
- [x] `plays/bfn267_fyrtoejet/plan_heksens_plan.md` is created and linked to `persona_heksen.md`
- [x] `plays/bfn267_fyrtoejet/plan_soldatens_plan.md` is created and linked to `persona_soldaten.md`
- [x] `plays/bfn267_fyrtoejet/plot_moedet.md` is created and casts company elements
- [x] `plays/bfn267_fyrtoejet/plot_rigdom.md` is created and casts company elements
- [x] `plays/bfn267_fyrtoejet/plot_besoegene.md` is created and casts company elements
- [x] `plays/bfn267_fyrtoejet/plot_galgen.md` is created and casts company elements
- [x] The local validation tests (`npm test`) run successfully with zero errors
