---
khai: order
title: "Stage BFN 737 Et Blad fra Himlen"
language: english
license: CC-BY-NC-SA-4.0
stamp:
  owner: KAI HACKS AI
  version: v0.0.1
  date: "2026-06-26"
---

# Order: Stage BFN 737 Et Blad fra Himlen

## Direction

The house must stage BFN 737 (_Et Blad fra Himlen_) to establish a production in the H.C. Andersen house. The production must model engelen, barnet, den_laerde, the positions (bringer, enfoldig, skeptisk), the pieces (himmelblad, forstoerrelsesglas), the environments (haven, studerekammeret), the aabenbaring and sogning processes, and the plots representing faldet and erkendelsen. It must be written in authentic Danish for all prose sections.

## Orders

1. The Playwright (Hans Christian Andersen) must author the play definition, the 3 personas, the 3 positions, the 2 pieces, the 2 places, the 2 processes, the 2 in-world plans, the pitch of mystisk, and the 2 plots.
2. The Theatre Manager (Edvard Collin) must verify the local registry, ensure correct versioning, check formatting, and validate that the cast conforms to the canon.
3. The Roadie (Vilhelm Pedersen) must set the stage, verify the local test suite is green, and prepare the files for packaging.

## Implementation

The play files must be placed in `plays/bfn737_et_blad_fra_himlen/` and follow the house language policy:

- Structural elements and frontmatter in English.
- Narrative prose, projections, actions, shadows, tells, and staging notes in Danish.

## Targets

- [x] `plays/bfn737_et_blad_fra_himlen/play_et_blad_fra_himlen.md` is created and lists the complete company
- [x] `plays/bfn737_et_blad_fra_himlen/persona_engelen.md` is created and links to `position_bringer.md`
- [x] `plays/bfn737_et_blad_fra_himlen/persona_barnet.md` is created and links to `position_enfoldig.md`
- [x] `plays/bfn737_et_blad_fra_himlen/persona_den_laerde.md` is created and links to `position_skeptisk.md`
- [x] `plays/bfn737_et_blad_fra_himlen/position_bringer.md` is created
- [x] `plays/bfn737_et_blad_fra_himlen/position_enfoldig.md` is created
- [x] `plays/bfn737_et_blad_fra_himlen/position_skeptisk.md` is created
- [x] `plays/bfn737_et_blad_fra_himlen/piece_himmelblad.md` is created
- [x] `plays/bfn737_et_blad_fra_himlen/piece_forstoerrelsesglas.md` is created
- [x] `plays/bfn737_et_blad_fra_himlen/place_haven.md` is created
- [x] `plays/bfn737_et_blad_fra_himlen/place_studerekammeret.md` is created
- [x] `plays/bfn737_et_blad_fra_himlen/process_aabenbaring.md` is created
- [x] `plays/bfn737_et_blad_fra_himlen/process_sogning.md` is created
- [x] `plays/bfn737_et_blad_fra_himlen/plan_sandhed.md` is created and linked to `persona_barnet.md`
- [x] `plays/bfn737_et_blad_fra_himlen/plan_undersoegelse.md` is created and linked to `persona_den_laerde.md`
- [x] `plays/bfn737_et_blad_fra_himlen/pitch_mystisk.md` is created
- [x] `plays/bfn737_et_blad_fra_himlen/plot_faldet.md` is created and casts company elements
- [x] `plays/bfn737_et_blad_fra_himlen/plot_erkendelsen.md` is created and casts company elements
- [x] The local validation tests (`npm test`) run successfully with zero errors
