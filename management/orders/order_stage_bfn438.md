---
khai: order
title: "Stage BFN 438"
language: english
license: CC-BY-NC-SA-4.0
stamp:
  owner: KAI HACKS AI
  version: v0.0.1
  date: "2026-06-20"
---

# Order: Stage BFN 438

## Direction

The house must stage BFN 438 (_Kjærestefolkene_) to establish the twenty-third production in the H.C. Andersen house. The production must model Toppen, Bolden, the positions (Bejler, Koket), the pieces (Guldmalingen, Korken), the environments (Skuffen, Tagrenden, Skraldebunken), the snurren and decay processes, and the plots leading to their realization. It must be written in authentic Danish for all prose sections.

## Orders

1. The Playwright (Hans Christian Andersen) must author the play definition, the two personas, the two positions, the two pieces, the three places, the two processes, the two in-world plans, the pitch of Ironi, and the four plots.
2. The Theatre Manager (Edvard Collin) must verify the local registry, ensure correct versioning, check formatting, and validate that the entire cast conforms to the canon.
3. The Roadie (Vilhelm Pedersen) must set the stage, verify the local test suite is green, and prepare the files for packaging.

## Implementation

The play files must be placed in `plays/bfn438_kjaerestefolkene/` and follow the house language policy:

- Structural elements and frontmatter in English.
- Narrative prose, projections, actions, shadows, tells, and staging notes in Danish.

## Targets

- [x] `plays/bfn438_kjaerestefolkene/play_kjaerestefolkene.md` is created and lists the complete company
- [x] `plays/bfn438_kjaerestefolkene/persona_toppen.md` is created and links to `position_bejler.md`
- [x] `plays/bfn438_kjaerestefolkene/persona_bolden.md` is created and links to `position_koket.md`
- [x] `plays/bfn438_kjaerestefolkene/position_bejler.md` is created
- [x] `plays/bfn438_kjaerestefolkene/position_koket.md` is created
- [x] `plays/bfn438_kjaerestefolkene/piece_guldmalingen.md` is created
- [x] `plays/bfn438_kjaerestefolkene/piece_korken.md` is created
- [x] `plays/bfn438_kjaerestefolkene/place_skuffen.md` is created
- [x] `plays/bfn438_kjaerestefolkene/place_tagrenden.md` is created
- [x] `plays/bfn438_kjaerestefolkene/place_skraldebunken.md` is created
- [x] `plays/bfn438_kjaerestefolkene/process_snurren.md` is created
- [x] `plays/bfn438_kjaerestefolkene/process_forgaengelighed.md` is created
- [x] `plays/bfn438_kjaerestefolkene/plan_toppens_bejlen.md` is created and linked to `persona_toppen.md`
- [x] `plays/bfn438_kjaerestefolkene/plan_boldens_droem.md` is created and linked to `persona_bolden.md`
- [x] `plays/bfn438_kjaerestefolkene/pitch_ironi.md` is created
- [x] `plays/bfn438_kjaerestefolkene/plot_frieriet.md` is created and casts company elements
- [x] `plays/bfn438_kjaerestefolkene/plot_flugten.md` is created and casts company elements
- [x] `plays/bfn438_kjaerestefolkene/plot_forgyldningen.md` is created and casts company elements
- [x] `plays/bfn438_kjaerestefolkene/plot_moedet_i_skraldet.md` is created and casts company elements
- [x] The local validation tests (`npm test`) run successfully with zero errors
