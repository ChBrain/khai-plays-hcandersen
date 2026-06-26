---
khai: order
title: "Stage BFN 360 Trettende Aften"
language: english
license: CC-BY-NC-SA-4.0
stamp:
  owner: KAI HACKS AI
  version: v0.0.1
  date: "2026-06-26"
---

# Order: Stage BFN 360 Trettende Aften

## Direction

The house must stage BFN 360 (_Trettende Aften_) to establish a production in the H.C. Andersen house. The production must model maanen, manden, konen, the positions (fortaeller, flittig, kaerlig), the pieces (broed, ild), the environments (hytten, ildstedet), the fortaelling and sammenhold processes, and the plots representing natten and hytten. It must be written in authentic Danish for all prose sections.

## Orders

1. The Playwright (Hans Christian Andersen) must author the play definition, the 3 personas, the 3 positions, the 2 pieces, the 2 places, the 2 processes, the 1 in-world plans, the pitch of hjertevarm, and the 2 plots.
2. The Theatre Manager (Edvard Collin) must verify the local registry, ensure correct versioning, check formatting, and validate that the cast conforms to the canon.
3. The Roadie (Vilhelm Pedersen) must set the stage, verify the local test suite is green, and prepare the files for packaging.

## Implementation

The play files must be placed in `plays/bfn360_trettende_aften/` and follow the house language policy:

- Structural elements and frontmatter in English.
- Narrative prose, projections, actions, shadows, tells, and staging notes in Danish.

## Targets

- [x] `plays/bfn360_trettende_aften/play_trettende_aften.md` is created and lists the complete company
- [x] `plays/bfn360_trettende_aften/persona_maanen.md` is created and links to `position_fortaeller.md`
- [x] `plays/bfn360_trettende_aften/persona_manden.md` is created and links to `position_flittig.md`
- [x] `plays/bfn360_trettende_aften/persona_konen.md` is created and links to `position_kaerlig.md`
- [x] `plays/bfn360_trettende_aften/position_fortaeller.md` is created
- [x] `plays/bfn360_trettende_aften/position_flittig.md` is created
- [x] `plays/bfn360_trettende_aften/position_kaerlig.md` is created
- [x] `plays/bfn360_trettende_aften/piece_broed.md` is created
- [x] `plays/bfn360_trettende_aften/piece_ild.md` is created
- [x] `plays/bfn360_trettende_aften/place_hytten.md` is created
- [x] `plays/bfn360_trettende_aften/place_ildstedet.md` is created
- [x] `plays/bfn360_trettende_aften/process_fortaelling.md` is created
- [x] `plays/bfn360_trettende_aften/process_sammenhold.md` is created
- [x] `plays/bfn360_trettende_aften/plan_overlevelse.md` is created and linked to `persona_manden.md`
- [x] `plays/bfn360_trettende_aften/pitch_hjertevarm.md` is created
- [x] `plays/bfn360_trettende_aften/plot_natten.md` is created and casts company elements
- [x] `plays/bfn360_trettende_aften/plot_hytten.md` is created and casts company elements
- [x] The local validation tests (`npm test`) run successfully with zero errors
