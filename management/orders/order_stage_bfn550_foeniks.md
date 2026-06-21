---
khai: order
title: "Stage BFN 550 Fugl Føniks"
language: english
license: CC-BY-NC-SA-4.0
stamp:
  owner: KAI HACKS AI
  version: v0.0.1
  date: "2026-06-21"
---

# Order: Stage BFN 550 Fugl Føniks

## Direction

The house must stage BFN 550 (_Fugl Føniks_) to establish the forty-fifth production in the H.C. Andersen house. The production must model Foeniks, Menneskehed, the positions (Baerer, Modtager), the piece (Sang), the environments (Paradis, Verden), the genfoedsel and spredning processes, and the plots leading to their realization. It must be written in authentic Danish for all prose sections.

## Orders

1. The Playwright (Hans Christian Andersen) must author the play definition, the two personas, the two positions, the piece, the two places, the two processes, the two in-world plans, the pitch of Poesi, and the four plots.
2. The Theatre Manager (Edvard Collin) must verify the local registry, ensure correct versioning, check formatting, and validate that the entire cast conforms to the canon.
3. The Roadie (Vilhelm Pedersen) must set the stage, verify the local test suite is green, and prepare the files for packaging.

## Implementation

The play files must be placed in `plays/bfn550_fugl_foeniks/` and follow the house language policy:

- Structural elements and frontmatter in English.
- Narrative prose, projections, actions, shadows, tells, and staging notes in Danish.

## Targets

- [x] `plays/bfn550_fugl_foeniks/play_fugl_foeniks.md` is created and lists the complete company
- [x] `plays/bfn550_fugl_foeniks/persona_foeniks.md` is created and links to `position_baerer.md`
- [x] `plays/bfn550_fugl_foeniks/persona_menneskehed.md` is created and links to `position_modtager.md`
- [x] `plays/bfn550_fugl_foeniks/position_baerer.md` is created
- [x] `plays/bfn550_fugl_foeniks/position_modtager.md` is created
- [x] `plays/bfn550_fugl_foeniks/piece_sang.md` is created
- [x] `plays/bfn550_fugl_foeniks/place_paradis.md` is created
- [x] `plays/bfn550_fugl_foeniks/place_verden.md` is created
- [x] `plays/bfn550_fugl_foeniks/process_genfoedsel.md` is created
- [x] `plays/bfn550_fugl_foeniks/process_spredning.md` is created
- [x] `plays/bfn550_fugl_foeniks/plan_sangrejse.md` is created and linked to `persona_foeniks.md`
- [x] `plays/bfn550_fugl_foeniks/plan_inspiration.md` is created and linked to `persona_menneskehed.md`
- [x] `plays/bfn550_fugl_foeniks/pitch_poesi.md` is created
- [x] `plays/bfn550_fugl_foeniks/plot_paradisets_have.md` is created and casts company elements
- [x] `plays/bfn550_fugl_foeniks/plot_flyvning.md` is created and casts company elements
- [x] `plays/bfn550_fugl_foeniks/plot_flamme.md` is created and casts company elements
- [x] `plays/bfn550_fugl_foeniks/plot_sang.md` is created and casts company elements
- [x] The local validation tests (`npm test`) run successfully with zero errors
