---
khai: order
title: "Stage BFN 409"
language: english
license: CC-BY-NC-SA-4.0
stamp:
  owner: KAI HACKS AI
  version: v0.0.1
  date: "2026-06-19"
---

# Order: Stage BFN 409

## Direction

The house must stage BFN 409 (_Ole Lukøje_) to establish the eighteenth production in the H.C. Andersen house. The production must model Ole, Hjalmar, Døden, the positions (Vejviser, Drømmer, Dommer), the pieces (Billedparaplyen, Den tomme paraply, Karakterbogen), the environments (Sengen, Drømmeriget), the sleep insufflation and transition processes, and the plots leading to their realization. It must be written in authentic Danish for all prose sections.

## Orders

1. The Playwright (Hans Christian Andersen) must author the play definition, the three personas, the three positions, the three pieces, the two places, the two processes, the two in-world plans, the pitch of Dream, and the three plots.
2. The Theatre Manager (Edvard Collin) must verify the local registry, ensure correct versioning, check formatting, and validate that the entire cast conforms to the canon.
3. The Roadie (Vilhelm Pedersen) must set the stage, verify the local test suite is green, and prepare the files for packaging.

## Implementation

The play files must be placed in `plays/bfn409_ole_lukoeje/` and follow the house language policy:

- Structural elements and frontmatter in English.
- Narrative prose, projections, actions, shadows, tells, and staging notes in Danish.

## Targets

- [x] `plays/bfn409_ole_lukoeje/play_ole_lukoeje.md` is created and lists the complete company
- [x] `plays/bfn409_ole_lukoeje/persona_ole.md` is created and links to `position_vejviser.md`
- [x] `plays/bfn409_ole_lukoeje/persona_hjalmar.md` is created and links to `position_droemmer.md`
- [x] `plays/bfn409_ole_lukoeje/persona_doeden.md` is created and links to `position_dommer.md`
- [x] `plays/bfn409_ole_lukoeje/position_vejviser.md` is created
- [x] `plays/bfn409_ole_lukoeje/position_droemmer.md` is created
- [x] `plays/bfn409_ole_lukoeje/position_dommer.md` is created
- [x] `plays/bfn409_ole_lukoeje/piece_paraply_billeder.md` is created
- [x] `plays/bfn409_ole_lukoeje/piece_paraply_tom.md` is created
- [x] `plays/bfn409_ole_lukoeje/piece_karakterbog.md` is created
- [x] `plays/bfn409_ole_lukoeje/place_sengen.md` is created
- [x] `plays/bfn409_ole_lukoeje/place_droemmeriget.md` is created
- [x] `plays/bfn409_ole_lukoeje/process_indsproejtning.md` is created
- [x] `plays/bfn409_ole_lukoeje/process_overgang.md` is created
- [x] `plays/bfn409_ole_lukoeje/plan_oles_plan.md` is created and linked to `persona_ole.md`
- [x] `plays/bfn409_ole_lukoeje/plan_doedens_plan.md` is created and linked to `persona_doeden.md`
- [x] `plays/bfn409_ole_lukoeje/pitch_dream.md` is created
- [x] `plays/bfn409_ole_lukoeje/plot_soevnen.md` is created and casts company elements
- [x] `plays/bfn409_ole_lukoeje/plot_rejsen.md` is created and casts company elements
- [x] `plays/bfn409_ole_lukoeje/plot_doeden.md` is created and casts company elements
- [x] The local validation tests (`npm test`) run successfully with zero errors
