---
khai: order
title: "Stage BFN 602 Den gamle Gravsteen"
language: english
license: CC-BY-NC-SA-4.0
stamp:
  owner: KAI HACKS AI
  version: v0.0.1
  date: "2026-06-26"
---

# Order: Stage BFN 602 Den gamle Gravsteen

## Direction

The house must stage BFN 602 (_Den gamle Gravsteen_) to establish a production in the H.C. Andersen house. The production must model manden, konen, the positions (trofast, erindrende), the pieces (gravsten, hus), the environments (gaarden, graven), the erindring and forvandling processes, and the plots representing livet and trappen. It must be written in authentic Danish for all prose sections.

## Orders

1. The Playwright (Hans Christian Andersen) must author the play definition, the 2 personas, the 2 positions, the 2 pieces, the 2 places, the 2 processes, the 2 in-world plans, the pitch of melankolsk, and the 2 plots.
2. The Theatre Manager (Edvard Collin) must verify the local registry, ensure correct versioning, check formatting, and validate that the cast conforms to the canon.
3. The Roadie (Vilhelm Pedersen) must set the stage, verify the local test suite is green, and prepare the files for packaging.

## Implementation

The play files must be placed in `plays/bfn602_den_gamle_gravsteen/` and follow the house language policy:

- Structural elements and frontmatter in English.
- Narrative prose, projections, actions, shadows, tells, and staging notes in Danish.

## Targets

- [x] `plays/bfn602_den_gamle_gravsteen/play_den_gamle_gravsteen.md` is created and lists the complete company
- [x] `plays/bfn602_den_gamle_gravsteen/persona_manden.md` is created and links to `position_trofast.md`
- [x] `plays/bfn602_den_gamle_gravsteen/persona_konen.md` is created and links to `position_erindrende.md`
- [x] `plays/bfn602_den_gamle_gravsteen/position_trofast.md` is created
- [x] `plays/bfn602_den_gamle_gravsteen/position_erindrende.md` is created
- [x] `plays/bfn602_den_gamle_gravsteen/piece_gravsten.md` is created
- [x] `plays/bfn602_den_gamle_gravsteen/piece_hus.md` is created
- [x] `plays/bfn602_den_gamle_gravsteen/place_gaarden.md` is created
- [x] `plays/bfn602_den_gamle_gravsteen/place_graven.md` is created
- [x] `plays/bfn602_den_gamle_gravsteen/process_erindring.md` is created
- [x] `plays/bfn602_den_gamle_gravsteen/process_forvandling.md` is created
- [x] `plays/bfn602_den_gamle_gravsteen/plan_sammenhold.md` is created and linked to `persona_manden.md`
- [x] `plays/bfn602_den_gamle_gravsteen/plan_erindring.md` is created and linked to `persona_konen.md`
- [x] `plays/bfn602_den_gamle_gravsteen/pitch_melankolsk.md` is created
- [x] `plays/bfn602_den_gamle_gravsteen/plot_livet.md` is created and casts company elements
- [x] `plays/bfn602_den_gamle_gravsteen/plot_trappen.md` is created and casts company elements
- [x] The local validation tests (`npm test`) run successfully with zero errors
