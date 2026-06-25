---
khai: order
title: "Stage BFN 1002 Oldefaer"
language: english
license: CC-BY-NC-SA-4.0
stamp:
  owner: KAI HACKS AI
  version: v0.0.1
  date: "2026-06-25"
---

# Order: Stage BFN 1002 Oldefaer

## Direction

The house must stage BFN 1002 (_Oldefa'er_) to establish the hundred and twenty-first production in the H.C. Andersen house. The production must model the shift in perception of Oldefar (Great-grandfather) towards the modern era. It must model the positions (Erfaren, Fremskridtsven), the pieces representing the rescue rocket (Redningsraket) and the Ørsted monument/donation (Monument), the environments of the parlor (Stuen) and the stormy coast (Vestkysten), the processes of generational transition (Generationsskifte) and rescue (Redning), their plans of conservation (Konservering) and progress (Fremskridt), the nostalgic pitch, and the plots representing the debate in the parlor and the shipwreck rescue. It must be written in authentic Danish for all prose sections.

## Orders

1. The Playwright (Hans Christian Andersen) must author the play definition, the two personas, the two positions, the two pieces, the two places, the two processes, the two in-world plans, the pitch of Nostalgisk, and the two plots.
2. The Theatre Manager (Edvard Collin) must verify the local registry, ensure correct versioning, check formatting, and validate that the cast conforms to the canon.
3. The Roadie (Vilhelm Pedersen) must set the stage, verify the local test suite is green, and prepare the files for packaging.

## Implementation

The play files must be placed in `plays/bfn1002_oldefaer/` and follow the house language policy:

- Structural elements and frontmatter in English.
- Narrative prose, projections, actions, shadows, tells, and staging notes in Danish.

## Targets

- [x] `plays/bfn1002_oldefaer/play_oldefaer.md` is created and lists the complete company
- [x] `plays/bfn1002_oldefaer/persona_oldefar.md` is created and links to `position_erfaren.md`
- [x] `plays/bfn1002_oldefaer/persona_frederik.md` is created and links to `position_fremskridtsven.md`
- [x] `plays/bfn1002_oldefaer/position_erfaren.md` is created
- [x] `plays/bfn1002_oldefaer/position_fremskridtsven.md` is created
- [x] `plays/bfn1002_oldefaer/piece_redningsraket.md` is created
- [x] `plays/bfn1002_oldefaer/piece_monument.md` is created
- [x] `plays/bfn1002_oldefaer/place_stuen.md` is created
- [x] `plays/bfn1002_oldefaer/place_vestkysten.md` is created
- [x] `plays/bfn1002_oldefaer/process_generationsskifte.md` is created
- [x] `plays/bfn1002_oldefaer/process_redning.md` is created
- [x] `plays/bfn1002_oldefaer/plan_konservering.md` is created and linked to `persona_oldefar.md`
- [x] `plays/bfn1002_oldefaer/plan_fremskridt.md` is created and linked to `persona_frederik.md`
- [x] `plays/bfn1002_oldefaer/pitch_nostalgisk.md` is created
- [x] `plays/bfn1002_oldefaer/plot_hjemmet.md` is created and casts company elements
- [x] `plays/bfn1002_oldefaer/plot_forliset.md` is created and casts company elements
- [x] The local validation tests (`npm test`) run successfully with zero errors
