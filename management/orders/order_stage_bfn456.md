---
khai: order
title: "Stage BFN 456"
language: english
license: CC-BY-NC-SA-4.0
stamp:
  owner: KAI HACKS AI
  version: v0.0.1
  date: "2026-06-21"
---

# Order: Stage BFN 456

## Direction

The house must stage BFN 456 (_Snedronningen_) to establish the twenty-sixth production in the H.C. Andersen house. The production must model Gerda, Kay, Snedronningen, the positions (Kærlig, Forblindet, Hersker), the pieces (Troldspejlet, Forstandsspillet), the environments (Taghaven, Slottet, Floden), the forfrysning and optøning processes, and the plots leading to their realization. It must be written in authentic Danish for all prose sections.

## Orders

1. The Playwright (Hans Christian Andersen) must author the play definition, the three personas, the three positions, the two pieces, the three places, the two processes, the two in-world plans, the pitch of Kontrast, and the four plots.
2. The Theatre Manager (Edvard Collin) must verify the local registry, ensure correct versioning, check formatting, and validate that the entire cast conforms to the canon.
3. The Roadie (Vilhelm Pedersen) must set the stage, verify the local test suite is green, and prepare the files for packaging.

## Implementation

The play files must be placed in `plays/bfn456_snedronningen/` and follow the house language policy:

- Structural elements and frontmatter in English.
- Narrative prose, projections, actions, shadows, tells, and staging notes in Danish.

## Targets

- [x] `plays/bfn456_snedronningen/play_snedronningen.md` is created and lists the complete company
- [x] `plays/bfn456_snedronningen/persona_gerda.md` is created and links to `position_kaerlig.md`
- [x] `plays/bfn456_snedronningen/persona_kay.md` is created and links to `position_forblindet.md`
- [x] `plays/bfn456_snedronningen/persona_snedronningen.md` is created and links to `position_hersker.md`
- [x] `plays/bfn456_snedronningen/position_kaerlig.md` is created
- [x] `plays/bfn456_snedronningen/position_forblindet.md` is created
- [x] `plays/bfn456_snedronningen/position_hersker.md` is created
- [x] `plays/bfn456_snedronningen/piece_troldspejlet.md` is created
- [x] `plays/bfn456_snedronningen/piece_forstandsspillet.md` is created
- [x] `plays/bfn456_snedronningen/place_taghaven.md` is created
- [x] `plays/bfn456_snedronningen/place_slottet.md` is created
- [x] `plays/bfn456_snedronningen/place_floden.md` is created
- [x] `plays/bfn456_snedronningen/process_forfrysning.md` is created
- [x] `plays/bfn456_snedronningen/process_optoening.md` is created
- [x] `plays/bfn456_snedronningen/plan_gerdas_soegning.md` is created and linked to `persona_gerda.md`
- [x] `plays/bfn456_snedronningen/plan_snedronningens_spil.md` is created and linked to `persona_snedronningen.md`
- [x] `plays/bfn456_snedronningen/pitch_kontrast.md` is created
- [x] `plays/bfn456_snedronningen/plot_spejlet.md` is created and casts company elements
- [x] `plays/bfn456_snedronningen/plot_bortfoerelsen.md` is created and casts company elements
- [x] `plays/bfn456_snedronningen/plot_rejsen.md` is created and casts company elements
- [x] `plays/bfn456_snedronningen/plot_ispaladset.md` is created and casts company elements
- [x] The local validation tests (`npm test`) run successfully with zero errors
