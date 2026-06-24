---
khai: order
title: "Stage BFN 817 Tolv med Posten"
language: english
license: CC-BY-NC-SA-4.0
stamp:
  owner: KAI HACKS AI
  version: v0.0.1
  date: "2026-06-24"
---

# Order: Stage BFN 817 Tolv med Posten

## Direction

The house must stage BFN 817 (_Tolv med Posten_) to establish the seventy-eighth production in the H.C. Andersen house. The production must model Postillon, Rejsende, the positions (Udfoerende, Ventende), the piece (Vogn), the environments (Postgaard, Landevej), the tidsrejse and aarstidsforandring processes, and the plots leading to their realization. It must be written in authentic Danish for all prose sections.

## Orders

1. The Playwright (Hans Christian Andersen) must author the play definition, the two personas, the two positions, the piece, the two places, the two processes, the two in-world plans, the pitch of Poesi, and the four plots.
2. The Theatre Manager (Edvard Collin) must verify the local registry, ensure correct versioning, check formatting, and validate that the entire cast conforms to the canon.
3. The Roadie (Vilhelm Pedersen) must set the stage, verify the local test suite is green, and prepare the files for packaging.

## Implementation

The play files must be placed in `plays/bfn817_tolv_med_posten/` and follow the house language policy:

- Structural elements and frontmatter in English.
- Narrative prose, projections, actions, shadows, tells, and staging notes in Danish.

## Targets

- [x] `plays/bfn817_tolv_med_posten/play_tolv_med_posten.md` is created and lists the complete company
- [x] `plays/bfn817_tolv_med_posten/persona_postillon.md` is created and links to `position_udfoerende.md`
- [x] `plays/bfn817_tolv_med_posten/persona_rejsende.md` is created and links to `position_ventende.md`
- [x] `plays/bfn817_tolv_med_posten/position_udfoerende.md` is created
- [x] `plays/bfn817_tolv_med_posten/position_ventende.md` is created
- [x] `plays/bfn817_tolv_med_posten/piece_vogn.md` is created
- [x] `plays/bfn817_tolv_med_posten/place_postgaard.md` is created
- [x] `plays/bfn817_tolv_med_posten/place_landevej.md` is created
- [x] `plays/bfn817_tolv_med_posten/process_tidsrejse.md` is created
- [x] `plays/bfn817_tolv_med_posten/process_aarstidsforandring.md` is created
- [x] `plays/bfn817_tolv_med_posten/plan_fordeling.md` is created and linked to `persona_postillon.md`
- [x] `plays/bfn817_tolv_med_posten/plan_modtagelse.md` is created and linked to `persona_rejsende.md`
- [x] `plays/bfn817_tolv_med_posten/pitch_poesi.md` is created
- [x] `plays/bfn817_tolv_med_posten/plot_ankomst.md` is created and casts company elements
- [x] `plays/bfn817_tolv_med_posten/plot_passagererne.md` is created and casts company elements
- [x] `plays/bfn817_tolv_med_posten/plot_uddelingen.md` is created and casts company elements
- [x] `plays/bfn817_tolv_med_posten/plot_afrejse.md` is created and casts company elements
- [x] The local validation tests (`npm test`) run successfully with zero errors
