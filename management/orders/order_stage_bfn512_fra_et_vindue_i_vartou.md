---
khai: order
title: "Stage BFN 512 Fra et Vindue i Vartou"
language: english
license: CC-BY-NC-SA-4.0
stamp:
  owner: KAI HACKS AI
  version: v0.0.1
  date: "2026-06-26"
---

# Order: Stage BFN 512 Fra et Vindue i Vartou

## Direction

The house must stage BFN 512 (_Fra et Vindue i Vartou_) to establish a production in the H.C. Andersen house. The production must model pigen, verden, the positions (observatoer, deltager), the pieces (vindue, salmebog), the environments (stuen, volden), the tilbageskuen and forgaengelighed processes, and the plots representing udsigten and fortiden. It must be written in authentic Danish for all prose sections.

## Orders

1. The Playwright (Hans Christian Andersen) must author the play definition, the 2 personas, the 2 positions, the 2 pieces, the 2 places, the 2 processes, the 2 in-world plans, the pitch of melankolsk, and the 2 plots.
2. The Theatre Manager (Edvard Collin) must verify the local registry, ensure correct versioning, check formatting, and validate that the cast conforms to the canon.
3. The Roadie (Vilhelm Pedersen) must set the stage, verify the local test suite is green, and prepare the files for packaging.

## Implementation

The play files must be placed in `plays/bfn512_fra_et_vindue_i_vartou/` and follow the house language policy:

- Structural elements and frontmatter in English.
- Narrative prose, projections, actions, shadows, tells, and staging notes in Danish.

## Targets

- [x] `plays/bfn512_fra_et_vindue_i_vartou/play_fra_et_vindue_i_vartou.md` is created and lists the complete company
- [x] `plays/bfn512_fra_et_vindue_i_vartou/persona_pigen.md` is created and links to `position_observatoer.md`
- [x] `plays/bfn512_fra_et_vindue_i_vartou/persona_verden.md` is created and links to `position_deltager.md`
- [x] `plays/bfn512_fra_et_vindue_i_vartou/position_observatoer.md` is created
- [x] `plays/bfn512_fra_et_vindue_i_vartou/position_deltager.md` is created
- [x] `plays/bfn512_fra_et_vindue_i_vartou/piece_vindue.md` is created
- [x] `plays/bfn512_fra_et_vindue_i_vartou/piece_salmebog.md` is created
- [x] `plays/bfn512_fra_et_vindue_i_vartou/place_stuen.md` is created
- [x] `plays/bfn512_fra_et_vindue_i_vartou/place_volden.md` is created
- [x] `plays/bfn512_fra_et_vindue_i_vartou/process_tilbageskuen.md` is created
- [x] `plays/bfn512_fra_et_vindue_i_vartou/process_forgaengelighed.md` is created
- [x] `plays/bfn512_fra_et_vindue_i_vartou/plan_stille_fred.md` is created and linked to `persona_pigen.md`
- [x] `plays/bfn512_fra_et_vindue_i_vartou/plan_erindring.md` is created and linked to `persona_pigen.md`
- [x] `plays/bfn512_fra_et_vindue_i_vartou/pitch_melankolsk.md` is created
- [x] `plays/bfn512_fra_et_vindue_i_vartou/plot_udsigten.md` is created and casts company elements
- [x] `plays/bfn512_fra_et_vindue_i_vartou/plot_fortiden.md` is created and casts company elements
- [x] The local validation tests (`npm test`) run successfully with zero errors
