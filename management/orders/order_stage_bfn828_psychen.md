---
khai: order
title: "Stage BFN 828 Psychen"
language: english
license: CC-BY-NC-SA-4.0
stamp:
  owner: KAI HACKS AI
  version: v0.0.1
  date: "2026-06-24"
---

# Order: Stage BFN 828 Psychen

## Direction

The house must stage BFN 828 (_Psychen_) to establish the eighty-eighth production in the H.C. Andersen house. The production must model Kunstner, Psyche, the positions (Skaber, Eftermaele), the piece (Ler), the environments (Atelier, Kloster), the skabelse and forgaengelse processes, and the plots leading to their realization. It must be written in authentic Danish for all prose sections.

## Orders

1. The Playwright (Hans Christian Andersen) must author the play definition, the two personas, the two positions, the piece, the two places, the two processes, the two in-world plans, the pitch of Melankoli, and the four plots.
2. The Theatre Manager (Edvard Collin) must verify the local registry, ensure correct versioning, check formatting, and validate that the cast conforms to the canon.
3. The Roadie (Vilhelm Pedersen) must set the stage, verify the local test suite is green, and prepare the files for packaging.

## Implementation

The play files must be placed in `plays/bfn828_psychen/` and follow the house language policy:

- Structural elements and frontmatter in English.
- Narrative prose, projections, actions, shadows, tells, and staging notes in Danish.

## Targets

- [x] `plays/bfn828_psychen/play_psychen.md` is created and lists the complete company
- [x] `plays/bfn828_psychen/persona_kunstner.md` is created and links to `position_skaber.md`
- [x] `plays/bfn828_psychen/persona_psyche.md` is created and links to `position_eftermaele.md`
- [x] `plays/bfn828_psychen/position_skaber.md` is created
- [x] `plays/bfn828_psychen/position_eftermaele.md` is created
- [x] `plays/bfn828_psychen/piece_ler.md` is created
- [x] `plays/bfn828_psychen/place_atelier.md` is created
- [x] `plays/bfn828_psychen/place_kloster.md` is created
- [x] `plays/bfn828_psychen/process_skabelse.md` is created
- [x] `plays/bfn828_psychen/process_forgaengelse.md` is created
- [x] `plays/bfn828_psychen/plan_straeben.md` is created and linked to `persona_kunstner.md`
- [x] `plays/bfn828_psychen/plan_forglemmelse.md` is created and linked to `persona_psyche.md`
- [x] `plays/bfn828_psychen/pitch_melankoli.md` is created
- [x] `plays/bfn828_psychen/plot_modelleringen.md` is created and casts company elements
- [x] `plays/bfn828_psychen/plot_nedsaenkningen.md` is created and casts company elements
- [x] `plays/bfn828_psychen/plot_klosterlivet.md` is created and casts company elements
- [x] `plays/bfn828_psychen/plot_gendoebelsen.md` is created and casts company elements
- [x] The local validation tests (`npm test`) run successfully with zero errors
