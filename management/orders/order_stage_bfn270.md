---
khai: order
title: "Stage BFN 270"
language: english
license: CC-BY-NC-SA-4.0
stamp:
  owner: KAI HACKS AI
  version: v0.0.1
  date: "2026-06-17"
---

# Order: Stage BFN 270

## Direction

The house must stage BFN 270 (_Den lille Idas Blomster_) to establish the fourth production in the H.C. Andersen house. The production must model little Ida, the student, the chancery counselor, the dancing flowers, the doll Sofie, the playroom and garden environments, the doll bed, the paper castle, the flower grave, the midnight ball process, the burial process, and the plots leading to the flowers' burial. It must be written in authentic Danish for all prose sections.

## Orders

1. The Playwright (Hans Christian Andersen) must author the play definition, the five personas (Ida, Studenten, Kancelliraaden, Blomsterne, Dukken Sofie), the four positions (droemmer, fortaeller, skeptiker, danser), the three pieces (duksesengen, papirslottet, blomstergraven), the two places (stuen, haven), the two processes (blomsterballet, begravelsen), the two in-world plans (idas plan, studentens plan), and the four plots.
2. The Theatre Manager (Edvard Collin) must verify the local registry, ensure correct versioning, check formatting, and validate that the entire cast conforms to the canon.
3. The Roadie (Vilhelm Pedersen) must set the stage, verify the local test suite is green, and prepare the files for packaging.

## Implementation

The play files must be placed in `plays/bfn270_den_lille_idas_blomster/` and follow the house language policy:

- Structural elements and frontmatter in English.
- Narrative prose, projections, actions, shadows, tells, and staging notes in Danish.

## Targets

- [x] `plays/bfn270_den_lille_idas_blomster/play_idas_blomster.md` is created and lists the complete company
- [x] `plays/bfn270_den_lille_idas_blomster/persona_ida.md` is created and links to `position_droemmer.md`
- [x] `plays/bfn270_den_lille_idas_blomster/persona_studenten.md` is created and links to `position_fortaeller.md`
- [x] `plays/bfn270_den_lille_idas_blomster/persona_kancelliraaden.md` is created and links to `position_skeptiker.md`
- [x] `plays/bfn270_den_lille_idas_blomster/persona_blomsterne.md` is created and links to `position_danser.md`
- [x] `plays/bfn270_den_lille_idas_blomster/persona_dukken_sofie.md` is created and links to `position_danser.md`
- [x] `plays/bfn270_den_lille_idas_blomster/position_droemmer.md` is created
- [x] `plays/bfn270_den_lille_idas_blomster/position_fortaeller.md` is created
- [x] `plays/bfn270_den_lille_idas_blomster/position_skeptiker.md` is created
- [x] `plays/bfn270_den_lille_idas_blomster/position_danser.md` is created
- [x] `plays/bfn270_den_lille_idas_blomster/piece_duksesengen.md` is created
- [x] `plays/bfn270_den_lille_idas_blomster/piece_papirslottet.md` is created
- [x] `plays/bfn270_den_lille_idas_blomster/piece_blomstergraven.md` is created
- [x] `plays/bfn270_den_lille_idas_blomster/place_stuen.md` is created
- [x] `plays/bfn270_den_lille_idas_blomster/place_haven.md` is created
- [x] `plays/bfn270_den_lille_idas_blomster/process_blomsterballet.md` is created
- [x] `plays/bfn270_den_lille_idas_blomster/process_begravelsen.md` is created
- [x] `plays/bfn270_den_lille_idas_blomster/plan_idas_plan.md` is created and linked to `persona_ida.md`
- [x] `plays/bfn270_den_lille_idas_blomster/plan_studentens_plan.md` is created and linked to `persona_studenten.md`
- [x] `plays/bfn270_den_lille_idas_blomster/plot_visne_blomster.md` is created and casts company elements
- [x] `plays/bfn270_den_lille_idas_blomster/plot_sengen.md` is created and casts company elements
- [x] `plays/bfn270_den_lille_idas_blomster/plot_ballet.md` is created and casts company elements
- [x] `plays/bfn270_den_lille_idas_blomster/plot_begravelsen.md` is created and casts company elements
- [x] The local validation tests (`npm test`) run successfully with zero errors
