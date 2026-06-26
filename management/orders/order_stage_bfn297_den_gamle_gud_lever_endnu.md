---
khai: order
title: "Stage BFN 297 Den gamle Gud lever endnu"
language: english
license: CC-BY-NC-SA-4.0
stamp:
  owner: KAI HACKS AI
  version: v0.0.1
  date: "2026-06-26"
---

# Order: Stage BFN 297 Den gamle Gud lever endnu

## Direction

The house must stage BFN 297 (_Den gamle Gud lever endnu_) to establish a production in the H.C. Andersen house. The production must model den_gamle, barnet, the positions (troende, haabende), the pieces (bibel, broed), the environments (kammeret, vejen), the boen and tro processes, and the plots representing noeden and redningen. It must be written in authentic Danish for all prose sections.

## Orders

1. The Playwright (Hans Christian Andersen) must author the play definition, the 2 personas, the 2 positions, the 2 pieces, the 2 places, the 2 processes, the 1 in-world plans, the pitch of troestende, and the 2 plots.
2. The Theatre Manager (Edvard Collin) must verify the local registry, ensure correct versioning, check formatting, and validate that the cast conforms to the canon.
3. The Roadie (Vilhelm Pedersen) must set the stage, verify the local test suite is green, and prepare the files for packaging.

## Implementation

The play files must be placed in `plays/bfn297_den_gamle_gud_lever_endnu/` and follow the house language policy:

- Structural elements and frontmatter in English.
- Narrative prose, projections, actions, shadows, tells, and staging notes in Danish.

## Targets

- [x] `plays/bfn297_den_gamle_gud_lever_endnu/play_den_gamle_gud_lever_endnu.md` is created and lists the complete company
- [x] `plays/bfn297_den_gamle_gud_lever_endnu/persona_den_gamle.md` is created and links to `position_troende.md`
- [x] `plays/bfn297_den_gamle_gud_lever_endnu/persona_barnet.md` is created and links to `position_haabende.md`
- [x] `plays/bfn297_den_gamle_gud_lever_endnu/position_troende.md` is created
- [x] `plays/bfn297_den_gamle_gud_lever_endnu/position_haabende.md` is created
- [x] `plays/bfn297_den_gamle_gud_lever_endnu/piece_bibel.md` is created
- [x] `plays/bfn297_den_gamle_gud_lever_endnu/piece_broed.md` is created
- [x] `plays/bfn297_den_gamle_gud_lever_endnu/place_kammeret.md` is created
- [x] `plays/bfn297_den_gamle_gud_lever_endnu/place_vejen.md` is created
- [x] `plays/bfn297_den_gamle_gud_lever_endnu/process_boen.md` is created
- [x] `plays/bfn297_den_gamle_gud_lever_endnu/process_tro.md` is created
- [x] `plays/bfn297_den_gamle_gud_lever_endnu/plan_haab.md` is created and linked to `persona_den_gamle.md`
- [x] `plays/bfn297_den_gamle_gud_lever_endnu/pitch_troestende.md` is created
- [x] `plays/bfn297_den_gamle_gud_lever_endnu/plot_noeden.md` is created and casts company elements
- [x] `plays/bfn297_den_gamle_gud_lever_endnu/plot_redningen.md` is created and casts company elements
- [x] The local validation tests (`npm test`) run successfully with zero errors
