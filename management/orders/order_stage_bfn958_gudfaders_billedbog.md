---
khai: order
title: "Stage BFN 958 Gudfaders Billedbog"
language: english
license: CC-BY-NC-SA-4.0
stamp:
  owner: KAI HACKS AI
  version: v0.0.1
  date: "2026-06-25"
---

# Order: Stage BFN 958 Gudfaders Billedbog

## Direction

The house must stage BFN 958 (_Gudfaders Billedbog_) to establish the hundred and seventh production in the H.C. Andersen house. The production must model Gudfader, Barnet, and Tranlygten, the positions (Fortællende, Lyttende, Forældet), the pieces (Billedbog, Sax), the environments (Stuen, København), the klipning and oplysning processes, and the plots representing the book, the scissors, the old light, and the gaslight. It must be written in authentic Danish for all prose sections.

## Orders

1. The Playwright (Hans Christian Andersen) must author the play definition, the three personas, the three positions, the two pieces, the two places, the two processes, the two in-world plans, the pitch of Erindring, and the four plots.
2. The Theatre Manager (Edvard Collin) must verify the local registry, ensure correct versioning, check formatting, and validate that the cast conforms to the canon.
3. The Roadie (Vilhelm Pedersen) must set the stage, verify the local test suite is green, and prepare the files for packaging.

## Implementation

The play files must be placed in `plays/bfn958_gudfaders_billedbog/` and follow the house language policy:

- Structural elements and frontmatter in English.
- Narrative prose, projections, actions, shadows, tells, and staging notes in Danish.

## Targets

- [x] `plays/bfn958_gudfaders_billedbog/play_gudfaders_billedbog.md` is created and lists the complete company
- [x] `plays/bfn958_gudfaders_billedbog/persona_gudfader.md` is created and links to `position_fortaellende.md`
- [x] `plays/bfn958_gudfaders_billedbog/persona_barn.md` is created and links to `position_lyttende.md`
- [x] `plays/bfn958_gudfaders_billedbog/persona_tranlygten.md` is created and links to `position_foraeldet.md`
- [x] `plays/bfn958_gudfaders_billedbog/position_fortaellende.md` is created
- [x] `plays/bfn958_gudfaders_billedbog/position_lyttende.md` is created
- [x] `plays/bfn958_gudfaders_billedbog/position_foraeldet.md` is created
- [x] `plays/bfn958_gudfaders_billedbog/piece_billedbog.md` is created
- [x] `plays/bfn958_gudfaders_billedbog/piece_sax.md` is created
- [x] `plays/bfn958_gudfaders_billedbog/place_stuen.md` is created
- [x] `plays/bfn958_gudfaders_billedbog/place_koebenhavn.md` is created
- [x] `plays/bfn958_gudfaders_billedbog/process_klipning.md` is created
- [x] `plays/bfn958_gudfaders_billedbog/process_oplysning.md` is created
- [x] `plays/bfn958_gudfaders_billedbog/plan_erindring.md` is created and linked to `persona_gudfader.md`
- [x] `plays/bfn958_gudfaders_billedbog/plan_fremskridt.md` is created and linked to `persona_tranlygten.md`
- [x] `plays/bfn958_gudfaders_billedbog/pitch_erindring.md` is created
- [x] `plays/bfn958_gudfaders_billedbog/plot_billedbogen.md` is created and casts company elements
- [x] `plays/bfn958_gudfaders_billedbog/plot_saxen.md` is created and casts company elements
- [x] `plays/bfn958_gudfaders_billedbog/plot_tranlygten.md` is created and casts company elements
- [x] `plays/bfn958_gudfaders_billedbog/plot_gaslyset.md` is created and casts company elements
- [x] The local validation tests (`npm test`) run successfully with zero errors
