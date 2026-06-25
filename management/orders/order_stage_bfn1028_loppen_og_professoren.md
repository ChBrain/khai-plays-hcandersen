---
khai: order
title: "Stage BFN 1028 Loppen og Professoren"
language: english
license: CC-BY-NC-SA-4.0
stamp:
  owner: KAI HACKS AI
  version: v0.0.1
  date: "2026-06-25"
---

# Order: Stage BFN 1028 Loppen og Professoren

## Direction

The house must stage BFN 1028 (_Loppen og Professoren_) to establish the hundred and thirty-first production in the H.C. Andersen house. The production must model Professoren (the professor/aeronaut) and Loppen (the trick-performing flea), their positions (Aeronaut, Dresseret), the pieces representing the balloon (Ballon) and the golden carriage/cannon (Kanon), the environments of the land of savages (De vildes land) and the homeland (Hjemmet), the processes of training/performing (Dressur) and escaping (Flugt), their plans of wealth/fortune (Rigdom) and escape (Flugt), the humorous pitch, and the plots representing the performances and the escape from the savages. It must be written in authentic Danish for all prose sections.

## Orders

1. The Playwright (Hans Christian Andersen) must author the play definition, the two personas, the two positions, the two pieces, the two places, the two processes, the two in-world plans, the pitch of Humoer, and the two plots.
2. The Theatre Manager (Edvard Collin) must verify the local registry, ensure correct versioning, check formatting, and validate that the cast conforms to the canon.
3. The Roadie (Vilhelm Pedersen) must set the stage, verify the local test suite is green, and prepare the files for packaging.

## Implementation

The play files must be placed in `plays/bfn1028_loppen_og_professoren/` and follow the house language policy:

- Structural elements and frontmatter in English.
- Narrative prose, projections, actions, shadows, tells, and staging notes in Danish.

## Targets

- [x] `plays/bfn1028_loppen_og_professoren/play_loppen_og_professoren.md` is created and lists the complete company
- [x] `plays/bfn1028_loppen_og_professoren/persona_professoren.md` is created and links to `position_aeronaut.md`
- [x] `plays/bfn1028_loppen_og_professoren/persona_loppen.md` is created and links to `position_dresseret.md`
- [x] `plays/bfn1028_loppen_og_professoren/position_aeronaut.md` is created
- [x] `plays/bfn1028_loppen_og_professoren/position_dresseret.md` is created
- [x] `plays/bfn1028_loppen_og_professoren/piece_ballon.md` is created
- [x] `plays/bfn1028_loppen_og_professoren/piece_kanon.md` is created
- [x] `plays/bfn1028_loppen_og_professoren/place_de_vildes_land.md` is created
- [x] `plays/bfn1028_loppen_og_professoren/place_hjemmet.md` is created
- [x] `plays/bfn1028_loppen_og_professoren/process_dressur.md` is created
- [x] `plays/bfn1028_loppen_og_professoren/process_flugt.md` is created
- [x] `plays/bfn1028_loppen_og_professoren/plan_rigdom.md` is created and linked to `persona_professoren.md`
- [x] `plays/bfn1028_loppen_og_professoren/plan_flugt.md` is created and linked to `persona_loppen.md`
- [x] `plays/bfn1028_loppen_og_professoren/pitch_humoer.md` is created
- [x] `plays/bfn1028_loppen_og_professoren/plot_dressuren.md` is created and casts company elements
- [x] `plays/bfn1028_loppen_og_professoren/plot_flugten.md` is created and casts company elements
- [x] The local validation tests (`npm test`) run successfully with zero errors
