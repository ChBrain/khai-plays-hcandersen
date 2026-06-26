---
khai: order
title: "Stage BFN 360 Nittende Aften"
language: english
license: CC-BY-NC-SA-4.0
stamp:
  owner: KAI HACKS AI
  version: v0.0.1
  date: "2026-06-26"
---

# Order: Stage BFN 360 Nittende Aften

## Direction

The house must stage BFN 360 (_Nittende Aften_) to establish a production in the H.C. Andersen house. The production must model maanen, goegleren, the positions (fortaeller, spiller), the pieces (vogn, gryde), the environments (skoven, lejren), the fortaelling and hvile processes, and the plots representing natten and lejren. It must be written in authentic Danish for all prose sections.

## Orders

1. The Playwright (Hans Christian Andersen) must author the play definition, the 2 personas, the 2 positions, the 2 pieces, the 2 places, the 2 processes, the 1 in-world plans, the pitch of satirisk, and the 2 plots.
2. The Theatre Manager (Edvard Collin) must verify the local registry, ensure correct versioning, check formatting, and validate that the cast conforms to the canon.
3. The Roadie (Vilhelm Pedersen) must set the stage, verify the local test suite is green, and prepare the files for packaging.

## Implementation

The play files must be placed in `plays/bfn360_nittende_aften/` and follow the house language policy:

- Structural elements and frontmatter in English.
- Narrative prose, projections, actions, shadows, tells, and staging notes in Danish.

## Targets

- [x] `plays/bfn360_nittende_aften/play_nittende_aften.md` is created and lists the complete company
- [x] `plays/bfn360_nittende_aften/persona_maanen.md` is created and links to `position_fortaeller.md`
- [x] `plays/bfn360_nittende_aften/persona_goegleren.md` is created and links to `position_spiller.md`
- [x] `plays/bfn360_nittende_aften/position_fortaeller.md` is created
- [x] `plays/bfn360_nittende_aften/position_spiller.md` is created
- [x] `plays/bfn360_nittende_aften/piece_vogn.md` is created
- [x] `plays/bfn360_nittende_aften/piece_gryde.md` is created
- [x] `plays/bfn360_nittende_aften/place_skoven.md` is created
- [x] `plays/bfn360_nittende_aften/place_lejren.md` is created
- [x] `plays/bfn360_nittende_aften/process_fortaelling.md` is created
- [x] `plays/bfn360_nittende_aften/process_hvile.md` is created
- [x] `plays/bfn360_nittende_aften/plan_overlevelse.md` is created and linked to `persona_goegleren.md`
- [x] `plays/bfn360_nittende_aften/pitch_satirisk.md` is created
- [x] `plays/bfn360_nittende_aften/plot_natten.md` is created and casts company elements
- [x] `plays/bfn360_nittende_aften/plot_lejren.md` is created and casts company elements
- [x] The local validation tests (`npm test`) run successfully with zero errors
