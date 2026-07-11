---
khai: order
title: "Stage SDU 624"
language: english
license: CC-BY-NC-SA-4.0
stamp:
  owner: KAI HACKS AI
  version: v0.0.1
  date: "2026-07-11"
---

# Order: Stage SDU 624

## Direction

The house must stage SDU 624 (_Kunstens Dannevirke_) to establish the twenty-fourth work in the "Drama" genre. The production must model the patriotic, allegorical dialogues of the Digter, Billedhugger, and Valkyrie. It must model the coastal vagtpost, the Dannebrog flag piece, the processes representing the linguistic defense and the centenary celebration, the artists' plan to use art as defense, the festive allegorical tone, and the three plots. All staging, prose, projections, actions, shadows, and tells must be authored in authentic Danish.

## Orders

1. The Playwright (Hans Christian Andersen) must author the play definition, the three personas (digter, kunstner, valkyrie), the three positions (frivillig_digter, frivillig_kunstner, skjoldmoe), the one piece (dannebrog), the one place (vagtpost), the two processes (vaern, fejring), the in-world plan (forsvar), the pitch (lejlighed), and the three plots.
2. The Theatre Manager (Edvard Collin) must verify the local registry, ensure correct versioning, check formatting, and validate that the entire cast conforms to the canon.
3. The Roadie (Vilhelm Pedersen) must set the stage, verify the local test suite is green, and prepare the files for packaging.

## Implementation

The play files must be placed in `plays/sdu624_kunstens_dannevirke/` and follow the house language policy:

- Structural elements and frontmatter in English.
- Narrative prose, projections, actions, shadows, tells, and staging notes in Danish.

## Targets

- [x] `plays/sdu624_kunstens_dannevirke/play_kunstens_dannevirke.md` is created and lists the complete company
- [x] `plays/sdu624_kunstens_dannevirke/persona_digter.md` is created and links to `position_frivillig_digter.md`
- [x] `plays/sdu624_kunstens_dannevirke/persona_kunstner.md` is created and links to `position_frivillig_kunstner.md`
- [x] `plays/sdu624_kunstens_dannevirke/persona_valkyrie.md` is created and links to `position_skjoldmoe.md`
- [x] `plays/sdu624_kunstens_dannevirke/position_frivillig_digter.md` is created
- [x] `plays/sdu624_kunstens_dannevirke/position_frivillig_kunstner.md` is created
- [x] `plays/sdu624_kunstens_dannevirke/position_skjoldmoe.md` is created
- [x] `plays/sdu624_kunstens_dannevirke/piece_dannebrog.md` is created
- [x] `plays/sdu624_kunstens_dannevirke/place_vagtpost.md` is created
- [x] `plays/sdu624_kunstens_dannevirke/process_vaern.md` is created
- [x] `plays/sdu624_kunstens_dannevirke/process_fejring.md` is created
- [x] `plays/sdu624_kunstens_dannevirke/plan_forsvar.md` is created
- [x] `plays/sdu624_kunstens_dannevirke/pitch_lejlighed.md` is created
- [x] `plays/sdu624_kunstens_dannevirke/plot_vagtpost.md` is created and casts company elements
- [x] `plays/sdu624_kunstens_dannevirke/plot_valkyriesyn.md` is created and casts company elements
- [x] `plays/sdu624_kunstens_dannevirke/plot_aandelig_vaern.md` is created and casts company elements
- [x] The local validation tests (`npm test`) run successfully with zero errors
