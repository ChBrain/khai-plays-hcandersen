---
khai: order
title: "Stage BFN 481 Bedstemoder"
language: english
license: CC-BY-NC-SA-4.0
stamp:
  owner: KAI HACKS AI
  version: v0.0.1
  date: "2026-06-26"
---

# Order: Stage BFN 481 Bedstemoder

## Direction

The house must stage BFN 481 (_Bedstemoder_) to establish a production in the H.C. Andersen house. The production must model bedstemor, barnet, the positions (kaerlig, lyttende), the pieces (bibel, rose), the environments (stolen, graven), the erindring and afsked processes, and the plots representing livet and graven. It must be written in authentic Danish for all prose sections.

## Orders

1. The Playwright (Hans Christian Andersen) must author the play definition, the 2 personas, the 2 positions, the 2 pieces, the 2 places, the 2 processes, the 2 in-world plans, the pitch of melankolsk, and the 2 plots.
2. The Theatre Manager (Edvard Collin) must verify the local registry, ensure correct versioning, check formatting, and validate that the cast conforms to the canon.
3. The Roadie (Vilhelm Pedersen) must set the stage, verify the local test suite is green, and prepare the files for packaging.

## Implementation

The play files must be placed in `plays/bfn481_bedstemoder/` and follow the house language policy:

- Structural elements and frontmatter in English.
- Narrative prose, projections, actions, shadows, tells, and staging notes in Danish.

## Targets

- [x] `plays/bfn481_bedstemoder/play_bedstemoder.md` is created and lists the complete company
- [x] `plays/bfn481_bedstemoder/persona_bedstemor.md` is created and links to `position_kaerlig.md`
- [x] `plays/bfn481_bedstemoder/persona_barnet.md` is created and links to `position_lyttende.md`
- [x] `plays/bfn481_bedstemoder/position_kaerlig.md` is created
- [x] `plays/bfn481_bedstemoder/position_lyttende.md` is created
- [x] `plays/bfn481_bedstemoder/piece_bibel.md` is created
- [x] `plays/bfn481_bedstemoder/piece_rose.md` is created
- [x] `plays/bfn481_bedstemoder/place_stolen.md` is created
- [x] `plays/bfn481_bedstemoder/place_graven.md` is created
- [x] `plays/bfn481_bedstemoder/process_erindring.md` is created
- [x] `plays/bfn481_bedstemoder/process_afsked.md` is created
- [x] `plays/bfn481_bedstemoder/plan_tro.md` is created and linked to `persona_bedstemor.md`
- [x] `plays/bfn481_bedstemoder/plan_erindring.md` is created and linked to `persona_barnet.md`
- [x] `plays/bfn481_bedstemoder/pitch_melankolsk.md` is created
- [x] `plays/bfn481_bedstemoder/plot_livet.md` is created and casts company elements
- [x] `plays/bfn481_bedstemoder/plot_graven.md` is created and casts company elements
- [x] The local validation tests (`npm test`) run successfully with zero errors
