---
khai: order
title: "Stage BFN 468"
language: english
license: CC-BY-NC-SA-4.0
stamp:
  owner: KAI HACKS AI
  version: v0.0.1
  date: "2026-06-21"
---

# Order: Stage BFN 468

## Direction

The house must stage BFN 468 (_Elverhøi_) to establish the twenty-seventh production in the H.C. Andersen house. The production must model Elverkongen, Dovrekongen, the positions (Vært, Bejlerfar), the pieces (Guldpokalen, Elverpigernes Kunst), the environments (Elverhøi, Festen), the elverkunst and alliance processes, and the plots leading to their realization. It must be written in authentic Danish for all prose sections.

## Orders

1. The Playwright (Hans Christian Andersen) must author the play definition, the two personas, the two positions, the two pieces, the two places, the two processes, the two in-world plans, the pitch of Folklore, and the four plots.
2. The Theatre Manager (Edvard Collin) must verify the local registry, ensure correct versioning, check formatting, and validate that the entire cast conforms to the canon.
3. The Roadie (Vilhelm Pedersen) must set the stage, verify the local test suite is green, and prepare the files for packaging.

## Implementation

The play files must be placed in `plays/bfn468_elverhoei/` and follow the house language policy:

- Structural elements and frontmatter in English.
- Narrative prose, projections, actions, shadows, tells, and staging notes in Danish.

## Targets

- [x] `plays/bfn468_elverhoei/play_elverhoei.md` is created and lists the complete company
- [x] `plays/bfn468_elverhoei/persona_elverkongen.md` is created and links to `position_vaert.md`
- [x] `plays/bfn468_elverhoei/persona_dovrekongen.md` is created and links to `position_bejlerfar.md`
- [x] `plays/bfn468_elverhoei/position_vaert.md` is created
- [x] `plays/bfn468_elverhoei/position_bejlerfar.md` is created
- [x] `plays/bfn468_elverhoei/piece_guldbaeger.md` is created
- [x] `plays/bfn468_elverhoei/piece_elverpigernes_kunst.md` is created
- [x] `plays/bfn468_elverhoei/place_elverhoei.md` is created
- [x] `plays/bfn468_elverhoei/place_festen.md` is created
- [x] `plays/bfn468_elverhoei/process_elverkunst.md` is created
- [x] `plays/bfn468_elverhoei/process_alliance.md` is created
- [x] `plays/bfn468_elverhoei/plan_elverkongens_gilde.md` is created and linked to `persona_elverkongen.md`
- [x] `plays/bfn468_elverhoei/plan_dovrekongens_rejse.md` is created and linked to `persona_dovrekongen.md`
- [x] `plays/bfn468_elverhoei/pitch_folklore.md` is created
- [x] `plays/bfn468_elverhoei/plot_forberedelsen.md` is created and casts company elements
- [x] `plays/bfn468_elverhoei/plot_gaesternes_ankomst.md` is created and casts company elements
- [x] `plays/bfn468_elverhoei/plot_kunstudstillingen.md` is created and casts company elements
- [x] `plays/bfn468_elverhoei/plot_alliancen.md` is created and casts company elements
- [x] The local validation tests (`npm test`) run successfully with zero errors
