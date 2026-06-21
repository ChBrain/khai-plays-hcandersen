---
khai: order
title: "Stage BFN 549 Hørren"
language: english
license: CC-BY-NC-SA-4.0
stamp:
  owner: KAI HACKS AI
  version: v0.0.1
  date: "2026-06-21"
---

# Order: Stage BFN 549 Hørren

## Direction

The house must stage BFN 549 (_Hørren_) to establish the forty-fourth production in the H.C. Andersen house. The production must model Hoerren, Ild, the positions (Optimist, Forvandler), the piece (Traad), the environments (Mark, Papirmoelle), the forarbejdning and forbraending processes, and the plots leading to their realization. It must be written in authentic Danish for all prose sections.

## Orders

1. The Playwright (Hans Christian Andersen) must author the play definition, the two personas, the two positions, the piece, the two places, the two processes, the two in-world plans, the pitch of Nostalgi, and the four plots.
2. The Theatre Manager (Edvard Collin) must verify the local registry, ensure correct versioning, check formatting, and validate that the entire cast conforms to the canon.
3. The Roadie (Vilhelm Pedersen) must set the stage, verify the local test suite is green, and prepare the files for packaging.

## Implementation

The play files must be placed in `plays/bfn549_hoerren/` and follow the house language policy:

- Structural elements and frontmatter in English.
- Narrative prose, projections, actions, shadows, tells, and staging notes in Danish.

## Targets

- [x] `plays/bfn549_hoerren/play_hoerren.md` is created and lists the complete company
- [x] `plays/bfn549_hoerren/persona_hoerren.md` is created and links to `position_optimist.md`
- [x] `plays/bfn549_hoerren/persona_ild.md` is created and links to `position_forvandler.md`
- [x] `plays/bfn549_hoerren/position_optimist.md` is created
- [x] `plays/bfn549_hoerren/position_forvandler.md` is created
- [x] `plays/bfn549_hoerren/piece_traad.md` is created
- [x] `plays/bfn549_hoerren/place_mark.md` is created
- [x] `plays/bfn549_hoerren/place_papirmoelle.md` is created
- [x] `plays/bfn549_hoerren/process_forarbejdning.md` is created
- [x] `plays/bfn549_hoerren/process_forbraending.md` is created
- [x] `plays/bfn549_hoerren/plan_optimisme.md` is created and linked to `persona_hoerren.md`
- [x] `plays/bfn549_hoerren/plan_nytte.md` is created and linked to `persona_ild.md`
- [x] `plays/bfn549_hoerren/pitch_nostalgi.md` is created
- [x] `plays/bfn549_hoerren/plot_marken.md` is created and casts company elements
- [x] `plays/bfn549_hoerren/plot_linned.md` is created and casts company elements
- [x] `plays/bfn549_hoerren/plot_papir.md` is created and casts company elements
- [x] `plays/bfn549_hoerren/plot_flammerne.md` is created and casts company elements
- [x] The local validation tests (`npm test`) run successfully with zero errors
