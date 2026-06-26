---
khai: order
title: "Stage BFN 360 To og tyvende Aften"
language: english
license: CC-BY-NC-SA-4.0
stamp:
  owner: KAI HACKS AI
  version: v0.0.1
  date: "2026-06-26"
---

# Order: Stage BFN 360 To og tyvende Aften

## Direction

The house must stage BFN 360 (_To og tyvende Aften_) to establish a production in the H.C. Andersen house. The production must model maanen, manden, the positions (fortaeller, troende), the pieces (billede, kors), the environments (tyrol, huset), the fortaelling and tilbedelse processes, and the plots representing natten and tyrol. It must be written in authentic Danish for all prose sections.

## Orders

1. The Playwright (Hans Christian Andersen) must author the play definition, the 2 personas, the 2 positions, the 2 pieces, the 2 places, the 2 processes, the 1 in-world plans, the pitch of poetisk, and the 2 plots.
2. The Theatre Manager (Edvard Collin) must verify the local registry, ensure correct versioning, check formatting, and validate that the cast conforms to the canon.
3. The Roadie (Vilhelm Pedersen) must set the stage, verify the local test suite is green, and prepare the files for packaging.

## Implementation

The play files must be placed in `plays/bfn360_toogtyvende_aften/` and follow the house language policy:

- Structural elements and frontmatter in English.
- Narrative prose, projections, actions, shadows, tells, and staging notes in Danish.

## Targets

- [x] `plays/bfn360_toogtyvende_aften/play_toogtyvende_aften.md` is created and lists the complete company
- [x] `plays/bfn360_toogtyvende_aften/persona_maanen.md` is created and links to `position_fortaeller.md`
- [x] `plays/bfn360_toogtyvende_aften/persona_manden.md` is created and links to `position_troende.md`
- [x] `plays/bfn360_toogtyvende_aften/position_fortaeller.md` is created
- [x] `plays/bfn360_toogtyvende_aften/position_troende.md` is created
- [x] `plays/bfn360_toogtyvende_aften/piece_billede.md` is created
- [x] `plays/bfn360_toogtyvende_aften/piece_kors.md` is created
- [x] `plays/bfn360_toogtyvende_aften/place_tyrol.md` is created
- [x] `plays/bfn360_toogtyvende_aften/place_huset.md` is created
- [x] `plays/bfn360_toogtyvende_aften/process_fortaelling.md` is created
- [x] `plays/bfn360_toogtyvende_aften/process_tilbedelse.md` is created
- [x] `plays/bfn360_toogtyvende_aften/plan_beskyttelse.md` is created and linked to `persona_manden.md`
- [x] `plays/bfn360_toogtyvende_aften/pitch_poetisk.md` is created
- [x] `plays/bfn360_toogtyvende_aften/plot_natten.md` is created and casts company elements
- [x] `plays/bfn360_toogtyvende_aften/plot_tyrol.md` is created and casts company elements
- [x] The local validation tests (`npm test`) run successfully with zero errors
