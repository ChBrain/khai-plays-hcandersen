---
khai: order
title: "Stage BFN 529 Den lykkelige familie"
language: english
license: CC-BY-NC-SA-4.0
stamp:
  owner: KAI HACKS AI
  version: v0.0.1
  date: "2026-06-21"
---

# Order: Stage BFN 529 Den lykkelige familie

## Direction

The house must stage BFN 529 (_Den lykkelige familie_) to establish the forty-second production in the H.C. Andersen house. The production must model Gamle snegle, Unge snegle, the positions (Tilfreds, Arving), the piece (Soelvfad), the environments (Skraeppeskov, Herregaard), the formering and forventning processes, and the plots leading to their realization. It must be written in authentic Danish for all prose sections.

## Orders

1. The Playwright (Hans Christian Andersen) must author the play definition, the two personas, the two positions, the piece, the two places, the two processes, the two in-world plans, the pitch of Humor, and the four plots.
2. The Theatre Manager (Edvard Collin) must verify the local registry, ensure correct versioning, check formatting, and validate that the entire cast conforms to the canon.
3. The Roadie (Vilhelm Pedersen) must set the stage, verify the local test suite is green, and prepare the files for packaging.

## Implementation

The play files must be placed in `plays/bfn529_lykkelige_familie/` and follow the house language policy:

- Structural elements and frontmatter in English.
- Narrative prose, projections, actions, shadows, tells, and staging notes in Danish.

## Targets

- [x] `plays/bfn529_lykkelige_familie/play_lykkelige_familie.md` is created and lists the complete company
- [x] `plays/bfn529_lykkelige_familie/persona_gamle_snegle.md` is created and links to `position_tilfreds.md`
- [x] `plays/bfn529_lykkelige_familie/persona_unge_snegle.md` is created and links to `position_arving.md`
- [x] `plays/bfn529_lykkelige_familie/position_tilfreds.md` is created
- [x] `plays/bfn529_lykkelige_familie/position_arving.md` is created
- [x] `plays/bfn529_lykkelige_familie/piece_soelvfad.md` is created
- [x] `plays/bfn529_lykkelige_familie/place_skraeppeskov.md` is created
- [x] `plays/bfn529_lykkelige_familie/place_herregaard.md` is created
- [x] `plays/bfn529_lykkelige_familie/process_formering.md` is created
- [x] `plays/bfn529_lykkelige_familie/process_forventning.md` is created
- [x] `plays/bfn529_lykkelige_familie/plan_snegleliv.md` is created and linked to `persona_gamle_snegle.md`
- [x] `plays/bfn529_lykkelige_familie/plan_bryllup.md` is created and linked to `persona_unge_snegle.md`
- [x] `plays/bfn529_lykkelige_familie/pitch_humor.md` is created
- [x] `plays/bfn529_lykkelige_familie/plot_skraeppeskov.md` is created and casts company elements
- [x] `plays/bfn529_lykkelige_familie/plot_arvingen.md` is created and casts company elements
- [x] `plays/bfn529_lykkelige_familie/plot_brylluppet.md` is created and casts company elements
- [x] `plays/bfn529_lykkelige_familie/plot_forventning.md` is created and casts company elements
- [x] The local validation tests (`npm test`) run successfully with zero errors
