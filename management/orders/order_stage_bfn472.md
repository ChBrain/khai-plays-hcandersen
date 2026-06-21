---
khai: order
title: "Stage BFN 472"
language: english
license: CC-BY-NC-SA-4.0
stamp:
  owner: KAI HACKS AI
  version: v0.0.1
  date: "2026-06-21"
---

# Order: Stage BFN 472

## Direction

The house must stage BFN 472 (_Holger Danske_) to establish the thirty-first production in the H.C. Andersen house. The production must model Holger Danske, Billedskæreren, the positions (Vogter, Fortolker), the pieces (Galionsfigur, Skjoldet), the environments (Kronborg, Værkstedet), the erindring and vækning processes, and the plots leading to their realization. It must be written in authentic Danish for all prose sections.

## Orders

1. The Playwright (Hans Christian Andersen) must author the play definition, the two personas, the two positions, the two pieces, the two places, the two processes, the two in-world plans, the pitch of Patriotisme, and the four plots.
2. The Theatre Manager (Edvard Collin) must verify the local registry, ensure correct versioning, check formatting, and validate that the entire cast conforms to the canon.
3. The Roadie (Vilhelm Pedersen) must set the stage, verify the local test suite is green, and prepare the files for packaging.

## Implementation

The play files must be placed in `plays/bfn472_holger_danske/` and follow the house language policy:

- Structural elements and frontmatter in English.
- Narrative prose, projections, actions, shadows, tells, and staging notes in Danish.

## Targets

- [x] `plays/bfn472_holger_danske/play_holger_danske.md` is created and lists the complete company
- [x] `plays/bfn472_holger_danske/persona_holger_danske.md` is created and links to `position_vogter.md`
- [x] `plays/bfn472_holger_danske/persona_billedskaereren.md` is created and links to `position_fortolker.md`
- [x] `plays/bfn472_holger_danske/position_vogter.md` is created
- [x] `plays/bfn472_holger_danske/position_fortolker.md` is created
- [x] `plays/bfn472_holger_danske/piece_galionsfigur.md` is created
- [x] `plays/bfn472_holger_danske/piece_skjoldet.md` is created
- [x] `plays/bfn472_holger_danske/place_kronborg.md` is created
- [x] `plays/bfn472_holger_danske/place_vaerkstedet.md` is created
- [x] `plays/bfn472_holger_danske/process_erindring.md` is created
- [x] `plays/bfn472_holger_danske/process_vaekning.md` is created
- [x] `plays/bfn472_holger_danske/plan_holger_danske_drøm.md` is created and linked to `persona_holger_danske.md`
- [x] `plays/bfn472_holger_danske/plan_billedskaerer_skabning.md` is created and linked to `persona_billedskaereren.md`
- [x] `plays/bfn472_holger_danske/pitch_patriotisme.md` is created
- [x] `plays/bfn472_holger_danske/plot_vaerksted.md` is created and casts company elements
- [x] `plays/bfn472_holger_danske/plot_kasematter.md` is created and casts company elements
- [x] `plays/bfn472_holger_danske/plot_drømmen.md` is created and casts company elements
- [x] `plays/bfn472_holger_danske/plot_sejlads.md` is created and casts company elements
- [x] The local validation tests (`npm test`) run successfully with zero errors
