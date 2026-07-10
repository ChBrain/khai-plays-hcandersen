---
khai: order
title: "Stage SDU 619"
language: english
license: CC-BY-NC-SA-4.0
stamp:
  owner: KAI HACKS AI
  version: v0.0.1
  date: "2026-07-10"
---

# Order: Stage SDU 619

## Direction

The house must stage SDU 619 (_Kongen drømmer_) to establish the nineteenth work in the "Drama" genre. The production must model the romantic dreamscapes of Christian II, Dyveke, and Madame Sigbrith. It must model the Sonderburg Castle cell, the heavy chains piece, the processes representing the dream projections and the confinement, the king's plan for inner peace, the melancholic romantic tone, and the three plots. All staging, prose, projections, actions, shadows, and tells must be authored in authentic Danish.

## Orders

1. The Playwright (Hans Christian Andersen) must author the play definition, the three personas (christian, dyveke, sigbrith), the three positions (fange_monark, droemmeaand, raadgiver), the one piece (laenke), the one place (slot), the two processes (droemmesyn, faengsling), the in-world plan (forsoning), the pitch (romantisk), and the three plots.
2. The Theatre Manager (Edvard Collin) must verify the local registry, ensure correct versioning, check formatting, and validate that the entire cast conforms to the canon.
3. The Roadie (Vilhelm Pedersen) must set the stage, verify the local test suite is green, and prepare the files for packaging.

## Implementation

The play files must be placed in `plays/sdu619_kongen_droemmer/` and follow the house language policy:

- Structural elements and frontmatter in English.
- Narrative prose, projections, actions, shadows, tells, and staging notes in Danish.

## Targets

- [x] `plays/sdu619_kongen_droemmer/play_kongen_droemmer.md` is created and lists the complete company
- [x] `plays/sdu619_kongen_droemmer/persona_christian.md` is created and links to `position_fange_monark.md`
- [x] `plays/sdu619_kongen_droemmer/persona_dyveke.md` is created and links to `position_droemmeaand.md`
- [x] `plays/sdu619_kongen_droemmer/persona_sigbrith.md` is created and links to `position_raadgiver.md`
- [x] `plays/sdu619_kongen_droemmer/position_fange_monark.md` is created
- [x] `plays/sdu619_kongen_droemmer/position_droemmeaand.md` is created
- [x] `plays/sdu619_kongen_droemmer/position_raadgiver.md` is created
- [x] `plays/sdu619_kongen_droemmer/piece_laenke.md` is created
- [x] `plays/sdu619_kongen_droemmer/place_slot.md` is created
- [x] `plays/sdu619_kongen_droemmer/process_droemmesyn.md` is created
- [x] `plays/sdu619_kongen_droemmer/process_faengsling.md` is created
- [x] `plays/sdu619_kongen_droemmer/plan_forsoning.md` is created
- [x] `plays/sdu619_kongen_droemmer/pitch_romantisk.md` is created
- [x] `plays/sdu619_kongen_droemmer/plot_cellelivet.md` is created and casts company elements
- [x] `plays/sdu619_kongen_droemmer/plot_bergen.md` is created and casts company elements
- [x] `plays/sdu619_kongen_droemmer/plot_ende.md` is created and casts company elements
- [x] The local validation tests (`npm test`) run successfully with zero errors
