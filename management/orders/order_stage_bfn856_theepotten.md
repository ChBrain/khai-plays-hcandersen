---
khai: order
title: "Stage BFN 856 Theepotten"
language: english
license: CC-BY-NC-SA-4.0
stamp:
  owner: KAI HACKS AI
  version: v0.0.1
  date: "2026-06-24"
---

# Order: Stage BFN 856 Theepotten

## Direction

The house must stage BFN 856 (_Theepotten_) to establish the ninety-second production in the H.C. Andersen house. The production must model Theepotte, Loeg, the positions (Stolt, Jordbeholder), the piece (Blomst), the environments (Tebord, Vindueskarm), the degradering and forvandling processes, and the plots leading to their realization. It must be written in authentic Danish for all prose sections.

## Orders

1. The Playwright (Hans Christian Andersen) must author the play definition, the two personas, the two positions, the piece, the two places, the two processes, the two in-world plans, the pitch of Stolthed, and the four plots.
2. The Theatre Manager (Edvard Collin) must verify the local registry, ensure correct versioning, check formatting, and validate that the cast conforms to the canon.
3. The Roadie (Vilhelm Pedersen) must set the stage, verify the local test suite is green, and prepare the files for packaging.

## Implementation

The play files must be placed in `plays/bfn856_theepotten/` and follow the house language policy:

- Structural elements and frontmatter in English.
- Narrative prose, projections, actions, shadows, tells, and staging notes in Danish.

## Targets

- [x] `plays/bfn856_theepotten/play_theepotten.md` is created and lists the complete company
- [x] `plays/bfn856_theepotten/persona_theepotte.md` is created and links to `position_stolt.md`
- [x] `plays/bfn856_theepotten/persona_loeg.md` is created and links to `position_jordbeholder.md`
- [x] `plays/bfn856_theepotten/position_stolt.md` is created
- [x] `plays/bfn856_theepotten/position_jordbeholder.md` is created
- [x] `plays/bfn856_theepotten/piece_blomst.md` is created
- [x] `plays/bfn856_theepotten/place_tebord.md` is created
- [x] `plays/bfn856_theepotten/place_vindueskarm.md` is created
- [x] `plays/bfn856_theepotten/process_degradering.md` is created
- [x] `plays/bfn856_theepotten/process_forvandling.md` is created
- [x] `plays/bfn856_theepotten/plan_servering.md` is created and linked to `persona_theepotte.md`
- [x] `plays/bfn856_theepotten/plan_pleje.md` is created and linked to `persona_loeg.md`
- [x] `plays/bfn856_theepotten/pitch_stolthed.md` is created
- [x] `plays/bfn856_theepotten/plot_glansperioden.md` is created and casts company elements
- [x] `plays/bfn856_theepotten/plot_faldet.md` is created and casts company elements
- [x] `plays/bfn856_theepotten/plot_plantningen.md` is created and casts company elements
- [x] `plays/bfn856_theepotten/plot_afskeden.md` is created and casts company elements
- [x] The local validation tests (`npm test`) run successfully with zero errors
