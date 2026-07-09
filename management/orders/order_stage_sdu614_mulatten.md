---
khai: order
title: "Stage SDU 614"
language: english
license: CC-BY-NC-SA-4.0
stamp:
  owner: KAI HACKS AI
  version: v0.0.1
  date: "2026-07-10"
---

# Order: Stage SDU 614

## Direction

The house must stage SDU 614 (_Mulatten_) to establish the fourteenth work in the "Drama" genre. The production must model the dramatic conflict of Horatio, Countess Cecilie, and La Rebellière. It must model Martinique, the freedom papers piece, the processes representing slavery and the tropical storm, the plan to free Horatio, the intense romantic and social-critical tenor, and the three plots. All staging, prose, projections, actions, shadows, and tells must be authored in authentic Danish.

## Orders

1. The Playwright (Hans Christian Andersen) must author the play definition, the three personas (horatio, cecilie, rebelliere), the three positions (udstoet, grevinde, plantageejer), the one piece (frihedsbrev), the one place (martinique), the two processes (slaveri, uvejr), the in-world plan (frigoerelse), the pitch (romantik), and the three plots.
2. The Theatre Manager (Edvard Collin) must verify the local registry, ensure correct versioning, check formatting, and validate that the entire cast conforms to the canon.
3. The Roadie (Vilhelm Pedersen) must set the stage, verify the local test suite is green, and prepare the files for packaging.

## Implementation

The play files must be placed in `plays/sdu614_mulatten/` and follow the house language policy:

- Structural elements and frontmatter in English.
- Narrative prose, projections, actions, shadows, tells, and staging notes in Danish.

## Targets

- [x] `plays/sdu614_mulatten/play_mulatten.md` is created and lists the complete company
- [x] `plays/sdu614_mulatten/persona_horatio.md` is created and links to `position_udstoet.md`
- [x] `plays/sdu614_mulatten/persona_cecilie.md` is created and links to `position_grevinde.md`
- [x] `plays/sdu614_mulatten/persona_rebelliere.md` is created and links to `position_plantageejer.md`
- [x] `plays/sdu614_mulatten/position_udstoet.md` is created
- [x] `plays/sdu614_mulatten/position_grevinde.md` is created
- [x] `plays/sdu614_mulatten/position_plantageejer.md` is created
- [x] `plays/sdu614_mulatten/piece_frihedsbrev.md` is created
- [x] `plays/sdu614_mulatten/place_martinique.md` is created
- [x] `plays/sdu614_mulatten/process_slaveri.md` is created
- [x] `plays/sdu614_mulatten/process_uvejr.md` is created
- [x] `plays/sdu614_mulatten/plan_frigoerelse.md` is created
- [x] `plays/sdu614_mulatten/pitch_romantik.md` is created
- [x] `plays/sdu614_mulatten/plot_stormen.md` is created and casts company elements
- [x] `plays/sdu614_mulatten/plot_intrigen.md` is created and casts company elements
- [x] `plays/sdu614_mulatten/plot_befrielsen.md` is created and casts company elements
- [x] The local validation tests (`npm test`) run successfully with zero errors
