---
khai: order
title: "Stage BFN 621 Fem fra en Ærtebælg"
language: english
license: CC-BY-NC-SA-4.0
stamp:
  owner: KAI HACKS AI
  version: v0.0.1
  date: "2026-06-26"
---

# Order: Stage BFN 621 Fem fra en Ærtebælg

## Direction

The house must stage BFN 621 (_Fem fra en Ærtebælg_) to establish a production in the H.C. Andersen house. The production must model aerten, pigen, moderen, the positions (hjaelpende, syg, plejende), the pieces (aertebaelg, urtepotte), the environments (tagrenden, stuen), the spiring and helbredelse processes, and the plots representing rejsen and spiringen. It must be written in authentic Danish for all prose sections.

## Orders

1. The Playwright (Hans Christian Andersen) must author the play definition, the 3 personas, the 3 positions, the 2 pieces, the 2 places, the 2 processes, the 2 in-world plans, the pitch of troestende, and the 2 plots.
2. The Theatre Manager (Edvard Collin) must verify the local registry, ensure correct versioning, check formatting, and validate that the cast conforms to the canon.
3. The Roadie (Vilhelm Pedersen) must set the stage, verify the local test suite is green, and prepare the files for packaging.

## Implementation

The play files must be placed in `plays/bfn621_fem_fra_en_aertebaelg/` and follow the house language policy:

- Structural elements and frontmatter in English.
- Narrative prose, projections, actions, shadows, tells, and staging notes in Danish.

## Targets

- [x] `plays/bfn621_fem_fra_en_aertebaelg/play_fem_fra_en_aertebaelg.md` is created and lists the complete company
- [x] `plays/bfn621_fem_fra_en_aertebaelg/persona_aerten.md` is created and links to `position_hjaelpende.md`
- [x] `plays/bfn621_fem_fra_en_aertebaelg/persona_pigen.md` is created and links to `position_syg.md`
- [x] `plays/bfn621_fem_fra_en_aertebaelg/persona_moderen.md` is created and links to `position_plejende.md`
- [x] `plays/bfn621_fem_fra_en_aertebaelg/position_hjaelpende.md` is created
- [x] `plays/bfn621_fem_fra_en_aertebaelg/position_syg.md` is created
- [x] `plays/bfn621_fem_fra_en_aertebaelg/position_plejende.md` is created
- [x] `plays/bfn621_fem_fra_en_aertebaelg/piece_aertebaelg.md` is created
- [x] `plays/bfn621_fem_fra_en_aertebaelg/piece_urtepotte.md` is created
- [x] `plays/bfn621_fem_fra_en_aertebaelg/place_tagrenden.md` is created
- [x] `plays/bfn621_fem_fra_en_aertebaelg/place_stuen.md` is created
- [x] `plays/bfn621_fem_fra_en_aertebaelg/process_spiring.md` is created
- [x] `plays/bfn621_fem_fra_en_aertebaelg/process_helbredelse.md` is created
- [x] `plays/bfn621_fem_fra_en_aertebaelg/plan_vaekst.md` is created and linked to `persona_aerten.md`
- [x] `plays/bfn621_fem_fra_en_aertebaelg/plan_haab.md` is created and linked to `persona_pigen.md`
- [x] `plays/bfn621_fem_fra_en_aertebaelg/pitch_troestende.md` is created
- [x] `plays/bfn621_fem_fra_en_aertebaelg/plot_rejsen.md` is created and casts company elements
- [x] `plays/bfn621_fem_fra_en_aertebaelg/plot_spiringen.md` is created and casts company elements
- [x] The local validation tests (`npm test`) run successfully with zero errors
