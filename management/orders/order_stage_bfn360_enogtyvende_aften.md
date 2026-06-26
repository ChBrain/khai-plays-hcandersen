---
khai: order
title: "Stage BFN 360 En og tyvende Aften"
language: english
license: CC-BY-NC-SA-4.0
stamp:
  owner: KAI HACKS AI
  version: v0.0.1
  date: "2026-06-26"
---

# Order: Stage BFN 360 En og tyvende Aften

## Direction

The house must stage BFN 360 (_En og tyvende Aften_) to establish a production in the H.C. Andersen house. The production must model maanen, pigen, the positions (fortaeller, bedroevet), the pieces (dukke, trae), the environments (haven, traeet), the fortaelling and omsorg processes, and the plots representing natten and dukken. It must be written in authentic Danish for all prose sections.

## Orders

1. The Playwright (Hans Christian Andersen) must author the play definition, the 2 personas, the 2 positions, the 2 pieces, the 2 places, the 2 processes, the 1 in-world plans, the pitch of troestende, and the 2 plots.
2. The Theatre Manager (Edvard Collin) must verify the local registry, ensure correct versioning, check formatting, and validate that the cast conforms to the canon.
3. The Roadie (Vilhelm Pedersen) must set the stage, verify the local test suite is green, and prepare the files for packaging.

## Implementation

The play files must be placed in `plays/bfn360_enogtyvende_aften/` and follow the house language policy:

- Structural elements and frontmatter in English.
- Narrative prose, projections, actions, shadows, tells, and staging notes in Danish.

## Targets

- [x] `plays/bfn360_enogtyvende_aften/play_enogtyvende_aften.md` is created and lists the complete company
- [x] `plays/bfn360_enogtyvende_aften/persona_maanen.md` is created and links to `position_fortaeller.md`
- [x] `plays/bfn360_enogtyvende_aften/persona_pigen.md` is created and links to `position_bedroevet.md`
- [x] `plays/bfn360_enogtyvende_aften/position_fortaeller.md` is created
- [x] `plays/bfn360_enogtyvende_aften/position_bedroevet.md` is created
- [x] `plays/bfn360_enogtyvende_aften/piece_dukke.md` is created
- [x] `plays/bfn360_enogtyvende_aften/piece_trae.md` is created
- [x] `plays/bfn360_enogtyvende_aften/place_haven.md` is created
- [x] `plays/bfn360_enogtyvende_aften/place_traeet.md` is created
- [x] `plays/bfn360_enogtyvende_aften/process_fortaelling.md` is created
- [x] `plays/bfn360_enogtyvende_aften/process_omsorg.md` is created
- [x] `plays/bfn360_enogtyvende_aften/plan_troest.md` is created and linked to `persona_pigen.md`
- [x] `plays/bfn360_enogtyvende_aften/pitch_troestende.md` is created
- [x] `plays/bfn360_enogtyvende_aften/plot_natten.md` is created and casts company elements
- [x] `plays/bfn360_enogtyvende_aften/plot_dukken.md` is created and casts company elements
- [x] The local validation tests (`npm test`) run successfully with zero errors
