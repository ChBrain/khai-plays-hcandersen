---
khai: order
title: "Stage SDU 622"
language: english
license: CC-BY-NC-SA-4.0
stamp:
  owner: KAI HACKS AI
  version: v0.0.1
  date: "2026-07-10"
---

# Order: Stage SDU 622

## Direction

The house must stage SDU 622 (_Liden Kirsten_) to establish the twenty-second work in the "Drama" genre. The production must model the ballad-inspired operatic dialogues of Kirsten, Sverkel, and Fru Malfred. It must model the castle hall, the convent veil piece, the processes representing the convent preparation and the knight's return, the wedding vow plan, the romantic operatic tone, and the three plots. All staging, prose, projections, actions, shadows, and tells must be authored in authentic Danish.

## Orders

1. The Playwright (Hans Christian Andersen) must author the play definition, the three personas (kirsten, sverkel, malfred), the three positions (klosteraspirant, ridder, adelig_moder), the one piece (sloer), the one place (gaard), the two processes (indvielse, hjemkomst), the in-world plan (bryllupslofte), the pitch (romantisk_opera), and the three plots.
2. The Theatre Manager (Edvard Collin) must verify the local registry, ensure correct versioning, check formatting, and validate that the entire cast conforms to the canon.
3. The Roadie (Vilhelm Pedersen) must set the stage, verify the local test suite is green, and prepare the files for packaging.

## Implementation

The play files must be placed in `plays/sdu622_liden_kirsten/` and follow the house language policy:

- Structural elements and frontmatter in English.
- Narrative prose, projections, actions, shadows, tells, and staging notes in Danish.

## Targets

- [x] `plays/sdu622_liden_kirsten/play_liden_kirsten.md` is created and lists the complete company
- [x] `plays/sdu622_liden_kirsten/persona_kirsten.md` is created and links to `position_klosteraspirant.md`
- [x] `plays/sdu622_liden_kirsten/persona_sverkel.md` is created and links to `position_ridder.md`
- [x] `plays/sdu622_liden_kirsten/persona_malfred.md` is created and links to `position_adelig_moder.md`
- [x] `plays/sdu622_liden_kirsten/position_klosteraspirant.md` is created
- [x] `plays/sdu622_liden_kirsten/position_ridder.md` is created
- [x] `plays/sdu622_liden_kirsten/position_adelig_moder.md` is created
- [x] `plays/sdu622_liden_kirsten/piece_sloer.md` is created
- [x] `plays/sdu622_liden_kirsten/place_gaard.md` is created
- [x] `plays/sdu622_liden_kirsten/process_indvielse.md` is created
- [x] `plays/sdu622_liden_kirsten/process_hjemkomst.md` is created
- [x] `plays/sdu622_liden_kirsten/plan_bryllupslofte.md` is created
- [x] `plays/sdu622_liden_kirsten/pitch_romantisk_opera.md` is created
- [x] `plays/sdu622_liden_kirsten/plot_klosterforberedelse.md` is created and casts company elements
- [x] `plays/sdu622_liden_kirsten/plot_hjemkomst.md` is created and casts company elements
- [x] `plays/sdu622_liden_kirsten/plot_slaegtsgaade.md` is created and casts company elements
- [x] The local validation tests (`npm test`) run successfully with zero errors
