---
khai: order
title: "Stage BFN 1026 Kroeblingen"
language: english
license: CC-BY-NC-SA-4.0
stamp:
  owner: KAI HACKS AI
  version: v0.0.1
  date: "2026-06-25"
---

# Order: Stage BFN 1026 Kroeblingen

## Direction

The house must stage BFN 1026 (_Krøblingen_) to establish the hundred and twenty-ninth production in the H.C. Andersen house. The production must model Hans (the crippled boy) and Faderen (the poor father/gardener), their positions (Syg, Flittig), the pieces representing the fairy tale book (Eventyrbog) and the songbird (Sangfugl), the environments of the small bedchamber (Kammeret) and the manor house (Herregaarden), the processes of reading/inspiration (Laesning) and sudden physical recovery/rescue (Redning), their plans of mental escape/faith (Tro) and survival (Overlevelse), the melancholic/hopeful pitch, and the plots representing the reading of the book and the rescue of the bird. It must be written in authentic Danish for all prose sections.

## Orders

1. The Playwright (Hans Christian Andersen) must author the play definition, the two personas, the two positions, the two pieces, the two places, the two processes, the two in-world plans, the pitch of Melankolsk, and the two plots.
2. The Theatre Manager (Edvard Collin) must verify the local registry, ensure correct versioning, check formatting, and validate that the cast conforms to the canon.
3. The Roadie (Vilhelm Pedersen) must set the stage, verify the local test suite is green, and prepare the files for packaging.

## Implementation

The play files must be placed in `plays/bfn1026_kroeblingen/` and follow the house language policy:

- Structural elements and frontmatter in English.
- Narrative prose, projections, actions, shadows, tells, and staging notes in Danish.

## Targets

- [x] `plays/bfn1026_kroeblingen/play_kroeblingen.md` is created and lists the complete company
- [x] `plays/bfn1026_kroeblingen/persona_hans.md` is created and links to `position_syg.md`
- [x] `plays/bfn1026_kroeblingen/persona_faderen.md` is created and links to `position_flittig.md`
- [x] `plays/bfn1026_kroeblingen/position_syg.md` is created
- [x] `plays/bfn1026_kroeblingen/position_flittig.md` is created
- [x] `plays/bfn1026_kroeblingen/piece_eventyrbog.md` is created
- [x] `plays/bfn1026_kroeblingen/piece_sangfugl.md` is created
- [x] `plays/bfn1026_kroeblingen/place_kammeret.md` is created
- [x] `plays/bfn1026_kroeblingen/place_herregaarden.md` is created
- [x] `plays/bfn1026_kroeblingen/process_laesning.md` is created
- [x] `plays/bfn1026_kroeblingen/process_redning.md` is created
- [x] `plays/bfn1026_kroeblingen/plan_tro.md` is created and linked to `persona_hans.md`
- [x] `plays/bfn1026_kroeblingen/plan_overlevelse.md` is created and linked to `persona_faderen.md`
- [x] `plays/bfn1026_kroeblingen/pitch_melankolsk.md` is created
- [x] `plays/bfn1026_kroeblingen/plot_laesningen.md` is created and casts company elements
- [x] `plays/bfn1026_kroeblingen/plot_redningen.md` is created and casts company elements
- [x] The local validation tests (`npm test`) run successfully with zero errors
