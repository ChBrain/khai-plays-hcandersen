---
khai: order
title: "Stage BFN 305"
language: english
license: CC-BY-NC-SA-4.0
stamp:
  owner: KAI HACKS AI
  version: v0.0.1
  date: "2026-06-17"
---

# Order: Stage BFN 305

## Direction

The house must stage BFN 305 (_Kejserens nye Klæder_) to establish the ninth production in the H.C. Andersen house. The production must model the emperor, the impostors, the minister, the child, the environments (the Throne Room, the Weaving Room, and the Streets), the loom, the gold, and the invisible clothes pieces, the deception and reveal processes, and the plots leading to the public revelation. It must be written in authentic Danish for all prose sections.

## Orders

1. The Playwright (Hans Christian Andersen) must author the play definition, the four personas, the four positions, the three pieces, the three places, the two processes, the two in-world plans, and the four plots.
2. The Theatre Manager (Edvard Collin) must verify the local registry, ensure correct versioning, check formatting, and validate that the entire cast conforms to the canon.
3. The Roadie (Vilhelm Pedersen) must set the stage, verify the local test suite is green, and prepare the files for packaging.

## Implementation

The play files must be placed in `plays/bfn305_kejserens_nye_klaeder/` and follow the house language policy:

- Structural elements and frontmatter in English.
- Narrative prose, projections, actions, shadows, tells, and staging notes in Danish.

## Targets

- [x] `plays/bfn305_kejserens_nye_klaeder/play_kejseren.md` is created and lists the complete company
- [x] `plays/bfn305_kejserens_nye_klaeder/persona_kejseren.md` is created and links to `position_kejser.md`
- [x] `plays/bfn305_kejserens_nye_klaeder/persona_bedragerne.md` is created and links to `position_bedrager.md`
- [x] `plays/bfn305_kejserens_nye_klaeder/persona_ministeren.md` is created and links to `position_embedsmand.md`
- [x] `plays/bfn305_kejserens_nye_klaeder/persona_barnet.md` is created and links to `position_sandhedssiger.md`
- [x] `plays/bfn305_kejserens_nye_klaeder/position_kej.md` (or `position_kejser.md`) is created
- [x] `plays/bfn305_kejserens_nye_klaeder/position_bedrager.md` is created
- [x] `plays/bfn305_kejserens_nye_klaeder/position_embedsmand.md` is created
- [x] `plays/bfn305_kejserens_nye_klaeder/position_sandhedssiger.md` is created
- [x] `plays/bfn305_kejserens_nye_klaeder/piece_vaevestolen.md` is created
- [x] `plays/bfn305_kejserens_nye_klaeder/piece_guld.md` is created
- [x] `plays/bfn305_kejserens_nye_klaeder/piece_klaederne.md` is created
- [x] `plays/bfn305_kejserens_nye_klaeder/place_tronen.md` is created
- [x] `plays/bfn305_kejserens_nye_klaeder/place_vaevestuen.md` is created
- [x] `plays/bfn305_kejserens_nye_klaeder/place_gaderne.md` is created
- [x] `plays/bfn305_kejserens_nye_klaeder/process_bedraget.md` is created
- [x] `plays/bfn305_kejserens_nye_klaeder/process_afsloeringen.md` is created
- [x] `plays/bfn305_kejserens_nye_klaeder/plan_kejserens_plan.md` is created and linked to `persona_kejseren.md`
- [x] `plays/bfn305_kejserens_nye_klaeder/plan_bedragernes_plan.md` is created and linked to `persona_bedragerne.md`
- [x] `plays/bfn305_kejserens_nye_klaeder/plot_bestillingen.md` is created and casts company elements
- [x] `plays/bfn305_kejserens_nye_klaeder/plot_proeven.md` is created and casts company elements
- [x] `plays/bfn305_kejserens_nye_klaeder/plot_kejserens_besoeg.md` is created and casts company elements
- [x] `plays/bfn305_kejserens_nye_klaeder/plot_processionen.md` is created and casts company elements
- [x] The local validation tests (`npm test`) run successfully with zero errors
