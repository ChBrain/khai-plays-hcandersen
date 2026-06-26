---
khai: order
title: "Stage BFN 16 Dykker-Klokken"
language: english
license: CC-BY-NC-SA-4.0
stamp:
  owner: KAI HACKS AI
  version: v0.0.1
  date: "2026-06-26"
---

# Order: Stage BFN 16 Dykker-Klokken

## Direction

The house must stage BFN 16 (_Dykker-Klokken_) to establish a production in the H.C. Andersen house. The production must model dykkeren, havfruen, the positions (opdager, vaert), the pieces (dykkerklokke, luftslange), the environments (havbunden, overfladen), the dykning and opdagelse processes, and the plots representing nedstigningen and moedet. It must be written in authentic Danish for all prose sections.

## Orders

1. The Playwright (Hans Christian Andersen) must author the play definition, the 2 personas, the 2 positions, the 2 pieces, the 2 places, the 2 processes, the 1 in-world plans, the pitch of eventyrlig, and the 2 plots.
2. The Theatre Manager (Edvard Collin) must verify the local registry, ensure correct versioning, check formatting, and validate that the cast conforms to the canon.
3. The Roadie (Vilhelm Pedersen) must set the stage, verify the local test suite is green, and prepare the files for packaging.

## Implementation

The play files must be placed in `plays/bfn16_dykker_klokken/` and follow the house language policy:

- Structural elements and frontmatter in English.
- Narrative prose, projections, actions, shadows, tells, and staging notes in Danish.

## Targets

- [x] `plays/bfn16_dykker_klokken/play_dykker_klokken.md` is created and lists the complete company
- [x] `plays/bfn16_dykker_klokken/persona_dykkeren.md` is created and links to `position_opdager.md`
- [x] `plays/bfn16_dykker_klokken/persona_havfruen.md` is created and links to `position_vaert.md`
- [x] `plays/bfn16_dykker_klokken/position_opdager.md` is created
- [x] `plays/bfn16_dykker_klokken/position_vaert.md` is created
- [x] `plays/bfn16_dykker_klokken/piece_dykkerklokke.md` is created
- [x] `plays/bfn16_dykker_klokken/piece_luftslange.md` is created
- [x] `plays/bfn16_dykker_klokken/place_havbunden.md` is created
- [x] `plays/bfn16_dykker_klokken/place_overfladen.md` is created
- [x] `plays/bfn16_dykker_klokken/process_dykning.md` is created
- [x] `plays/bfn16_dykker_klokken/process_opdagelse.md` is created
- [x] `plays/bfn16_dykker_klokken/plan_udforskning.md` is created and linked to `persona_dykkeren.md`
- [x] `plays/bfn16_dykker_klokken/pitch_eventyrlig.md` is created
- [x] `plays/bfn16_dykker_klokken/plot_nedstigningen.md` is created and casts company elements
- [x] `plays/bfn16_dykker_klokken/plot_moedet.md` is created and casts company elements
- [x] The local validation tests (`npm test`) run successfully with zero errors
