---
khai: order
title: "Stage BFN 992 Hoense-Grethes Familie"
language: english
license: CC-BY-NC-SA-4.0
stamp:
  owner: KAI HACKS AI
  version: v0.0.1
  date: "2026-06-25"
---

# Order: Stage BFN 992 Hoense-Grethes Familie

## Direction

The house must stage BFN 992 (_Hønse-Grethes Familie_) to establish the hundred and eighteenth production in the H.C. Andersen house. The production must model the contrast between the quiet life of Grethe (Hønse-Grethe) and the historical memory of Marie (Marie Grubbe). It must model their positions (Passer, Adelsdame), the pieces representing the chicken house (Hoensehus) and the ancient castle (Borg), the environments of the manor (Herregaarden) and the past (Fortiden), the processes of caring (Pasning) and decay (Forfald), their respective plans of care (Omhu) and will (Viljestyrke), the historical pitch, and the plots representing the chicken house and the historical memories. It must be written in authentic Danish for all prose sections.

## Orders

1. The Playwright (Hans Christian Andersen) must author the play definition, the two personas, the two positions, the two pieces, the two places, the two processes, the two in-world plans, the pitch of Historisk, and the two plots.
2. The Theatre Manager (Edvard Collin) must verify the local registry, ensure correct versioning, check formatting, and validate that the cast conforms to the canon.
3. The Roadie (Vilhelm Pedersen) must set the stage, verify the local test suite is green, and prepare the files for packaging.

## Implementation

The play files must be placed in `plays/bfn992_hoense_grethes_familie/` and follow the house language policy:

- Structural elements and frontmatter in English.
- Narrative prose, projections, actions, shadows, tells, and staging notes in Danish.

## Targets

- [x] `plays/bfn992_hoense_grethes_familie/play_hoense_grethes_familie.md` is created and lists the complete company
- [x] `plays/bfn992_hoense_grethes_familie/persona_grethe.md` is created and links to `position_passer.md`
- [x] `plays/bfn992_hoense_grethes_familie/persona_marie.md` is created and links to `position_adelsdame.md`
- [x] `plays/bfn992_hoense_grethes_familie/position_passer.md` is created
- [x] `plays/bfn992_hoense_grethes_familie/position_adelsdame.md` is created
- [x] `plays/bfn992_hoense_grethes_familie/piece_hoensehus.md` is created
- [x] `plays/bfn992_hoense_grethes_familie/piece_borg.md` is created
- [x] `plays/bfn992_hoense_grethes_familie/place_herregaarden.md` is created
- [x] `plays/bfn992_hoense_grethes_familie/place_fortiden.md` is created
- [x] `plays/bfn992_hoense_grethes_familie/process_pasning.md` is created
- [x] `plays/bfn992_hoense_grethes_familie/process_forfald.md` is created
- [x] `plays/bfn992_hoense_grethes_familie/plan_omhu.md` is created and linked to `persona_grethe.md`
- [x] `plays/bfn992_hoense_grethes_familie/plan_viljestyrke.md` is created and linked to `persona_marie.md`
- [x] `plays/bfn992_hoense_grethes_familie/pitch_historisk.md` is created
- [x] `plays/bfn992_hoense_grethes_familie/plot_hoensehuset.md` is created and casts company elements
- [x] `plays/bfn992_hoense_grethes_familie/plot_historien.md` is created and casts company elements
- [x] The local validation tests (`npm test`) run successfully with zero errors
