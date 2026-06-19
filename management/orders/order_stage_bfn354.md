---
khai: order
title: "Stage BFN 354"
language: english
license: CC-BY-NC-SA-4.0
stamp:
  owner: KAI HACKS AI
  version: v0.0.1
  date: "2026-06-17"
---

# Order: Stage BFN 354

## Direction

The house must stage BFN 354 (_Den flyvende Kuffert_) to establish the fifteenth production in the H.C. Andersen house. The production must model Købmandssønnen, Prinsessen, Sultanen, Sultanaen, the positions (Fortæller, Indespærret, Lytter), the pieces (Kufferten, Fyrværkeriet, Fortællingerne), the environments (Hjemmet, Tårnet, Paladset), the flight and transience processes, and the plots leading to their realization. It must be written in authentic Danish for all prose sections.

## Orders

1. The Playwright (Hans Christian Andersen) must author the play definition, the four personas, the three positions, the three pieces, the three places, the two processes, the two in-world plans, and the four plots.
2. The Theatre Manager (Edvard Collin) must verify the local registry, ensure correct versioning, check formatting, and validate that the entire cast conforms to the canon.
3. The Roadie (Vilhelm Pedersen) must set the stage, verify the local test suite is green, and prepare the files for packaging.

## Implementation

The play files must be placed in `plays/bfn354_den_flyvende_kuffert/` and follow the house language policy:

- Structural elements and frontmatter in English.
- Narrative prose, projections, actions, shadows, tells, and staging notes in Danish.

## Targets

- [x] `plays/bfn354_den_flyvende_kuffert/play_flyvende_kuffert.md` is created and lists the complete company
- [x] `plays/bfn354_den_flyvende_kuffert/persona_koebmandsoennen.md` is created and links to `position_fortaeller.md`
- [x] `plays/bfn354_den_flyvende_kuffert/persona_prinsessen.md` is created and links to `position_indespaerret.md`
- [x] `plays/bfn354_den_flyvende_kuffert/persona_sultanen.md` is created and links to `position_lytter.md`
- [x] `plays/bfn354_den_flyvende_kuffert/persona_sultanaen.md` is created and links to `position_lytter.md`
- [x] `plays/bfn354_den_flyvende_kuffert/position_fortaeller.md` is created
- [x] `plays/bfn354_den_flyvende_kuffert/position_indespaerret.md` is created
- [x] `plays/bfn354_den_flyvende_kuffert/position_lytter.md` is created
- [x] `plays/bfn354_den_flyvende_kuffert/piece_kufferten.md` is created
- [x] `plays/bfn354_den_flyvende_kuffert/piece_fyrvaerkeri.md` is created
- [x] `plays/bfn354_den_flyvende_kuffert/piece_fortaellingerne.md` is created
- [x] `plays/bfn354_den_flyvende_kuffert/place_hjemmet.md` is created
- [x] `plays/bfn354_den_flyvende_kuffert/place_taarnet.md` is created
- [x] `plays/bfn354_den_flyvende_kuffert/place_paladset.md` is created
- [x] `plays/bfn354_den_flyvende_kuffert/process_flyvning.md` is created
- [x] `plays/bfn354_den_flyvende_kuffert/process_forgoengelighed.md` is created
- [x] `plays/bfn354_den_flyvende_kuffert/plan_soennens_plan.md` is created and linked to `persona_koebmandsoennen.md`
- [x] `plays/bfn354_den_flyvende_kuffert/plan_sultanens_plan.md` is created and linked to `persona_sultanen.md`
- [x] `plays/bfn354_den_flyvende_kuffert/pitch_comic.md` is created

- [x] `plays/bfn354_den_flyvende_kuffert/plot_afrejsen.md` is created and casts company elements
- [x] `plays/bfn354_den_flyvende_kuffert/plot_moedet.md` is created and casts company elements
- [x] `plays/bfn354_den_flyvende_kuffert/plot_festen.md` is created and casts company elements
- [x] `plays/bfn354_den_flyvende_kuffert/plot_branden.md` is created and casts company elements
- [x] The local validation tests (`npm test`) run successfully with zero errors
