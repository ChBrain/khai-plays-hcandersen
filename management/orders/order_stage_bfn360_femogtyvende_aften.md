---
khai: order
title: "Stage BFN 360 Fem og tyvende Aften"
language: english
license: CC-BY-NC-SA-4.0
stamp:
  owner: KAI HACKS AI
  version: v0.0.1
  date: "2026-06-26"
---

# Order: Stage BFN 360 Fem og tyvende Aften

## Direction

The house must stage BFN 360 (_Fem og tyvende Aften_) to establish a production in the H.C. Andersen house. The production must model maanen, drengen, the positions (fortaeller, flittig), the pieces (kost, skorsten), the environments (taget, byen), the fortaelling and arbejde processes, and the plots representing natten and taget. It must be written in authentic Danish for all prose sections.

## Orders

1. The Playwright (Hans Christian Andersen) must author the play definition, the 2 personas, the 2 positions, the 2 pieces, the 2 places, the 2 processes, the 1 in-world plans, the pitch of realistisk, and the 2 plots.
2. The Theatre Manager (Edvard Collin) must verify the local registry, ensure correct versioning, check formatting, and validate that the cast conforms to the canon.
3. The Roadie (Vilhelm Pedersen) must set the stage, verify the local test suite is green, and prepare the files for packaging.

## Implementation

The play files must be placed in `plays/bfn360_femogtyvende_aften/` and follow the house language policy:

- Structural elements and frontmatter in English.
- Narrative prose, projections, actions, shadows, tells, and staging notes in Danish.

## Targets

- [x] `plays/bfn360_femogtyvende_aften/play_femogtyvende_aften.md` is created and lists the complete company
- [x] `plays/bfn360_femogtyvende_aften/persona_maanen.md` is created and links to `position_fortaeller.md`
- [x] `plays/bfn360_femogtyvende_aften/persona_drengen.md` is created and links to `position_flittig.md`
- [x] `plays/bfn360_femogtyvende_aften/position_fortaeller.md` is created
- [x] `plays/bfn360_femogtyvende_aften/position_flittig.md` is created
- [x] `plays/bfn360_femogtyvende_aften/piece_kost.md` is created
- [x] `plays/bfn360_femogtyvende_aften/piece_skorsten.md` is created
- [x] `plays/bfn360_femogtyvende_aften/place_taget.md` is created
- [x] `plays/bfn360_femogtyvende_aften/place_byen.md` is created
- [x] `plays/bfn360_femogtyvende_aften/process_fortaelling.md` is created
- [x] `plays/bfn360_femogtyvende_aften/process_arbejde.md` is created
- [x] `plays/bfn360_femogtyvende_aften/plan_overlevelse.md` is created and linked to `persona_drengen.md`
- [x] `plays/bfn360_femogtyvende_aften/pitch_realistisk.md` is created
- [x] `plays/bfn360_femogtyvende_aften/plot_natten.md` is created and casts company elements
- [x] `plays/bfn360_femogtyvende_aften/plot_taget.md` is created and casts company elements
- [x] The local validation tests (`npm test`) run successfully with zero errors
