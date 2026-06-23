---
khai: order
title: "Stage BFN 782 Pigen som traadte paa Broedet"
language: english
license: CC-BY-NC-SA-4.0
stamp:
  owner: KAI HACKS AI
  version: v0.0.1
  date: "2026-06-23"
---

# Order: Stage BFN 782 Pigen som traadte paa Broedet

## Direction

The house must stage BFN 782 (_Pigen, som traadte paa Brødet_) to establish the sixty-ninth production in the H.C. Andersen house. The production must model Inger, Mosekone, the positions (Hovmodig, Brygger), the piece (Broed), the environments (Mose, Himmel), the forstening and forloesning processes, and the plots leading to their realization. It must be written in authentic Danish for all prose sections.

## Orders

1. The Playwright (Hans Christian Andersen) must author the play definition, the two personas, the two positions, the piece, the two places, the two processes, the two in-world plans, the pitch of Patos, and the four plots.
2. The Theatre Manager (Edvard Collin) must verify the local registry, ensure correct versioning, check formatting, and validate that the entire cast conforms to the canon.
3. The Roadie (Vilhelm Pedersen) must set the stage, verify the local test suite is green, and prepare the files for packaging.

## Implementation

The play files must be placed in `plays/bfn782_pigen_som_traadte_paa_broedet/` and follow the house language policy:

- Structural elements and frontmatter in English.
- Narrative prose, projections, actions, shadows, tells, and staging notes in Danish.

## Targets

- [x] `plays/bfn782_pigen_som_traadte_paa_broedet/play_pigen_som_traadte_paa_broedet.md` is created and lists the complete company
- [x] `plays/bfn782_pigen_som_traadte_paa_broedet/persona_inger.md` is created and links to `position_hovmodig.md`
- [x] `plays/bfn782_pigen_som_traadte_paa_broedet/persona_mosekone.md` is created and links to `position_brygger.md`
- [x] `plays/bfn782_pigen_som_traadte_paa_broedet/position_hovmodig.md` is created
- [x] `plays/bfn782_pigen_som_traadte_paa_broedet/position_brygger.md` is created
- [x] `plays/bfn782_pigen_som_traadte_paa_broedet/piece_broed.md` is created
- [x] `plays/bfn782_pigen_som_traadte_paa_broedet/place_mose.md` is created
- [x] `plays/bfn782_pigen_som_traadte_paa_broedet/place_himmel.md` is created
- [x] `plays/bfn782_pigen_som_traadte_paa_broedet/process_forstening.md` is created
- [x] `plays/bfn782_pigen_som_traadte_paa_broedet/process_forloesning.md` is created
- [x] `plays/bfn782_pigen_som_traadte_paa_broedet/plan_selvbevarelse.md` is created and linked to `persona_inger.md`
- [x] `plays/bfn782_pigen_som_traadte_paa_broedet/plan_strafforfald.md` is created and linked to `persona_inger.md`
- [x] `plays/bfn782_pigen_som_traadte_paa_broedet/pitch_patos.md` is created
- [x] `plays/bfn782_pigen_som_traadte_paa_broedet/plot_overmod.md` is created and casts company elements
- [x] `plays/bfn782_pigen_som_traadte_paa_broedet/plot_mosen.md` is created and casts company elements
- [x] `plays/bfn782_pigen_som_traadte_paa_broedet/plot_straf.md` is created and casts company elements
- [x] `plays/bfn782_pigen_som_traadte_paa_broedet/plot_angst_og_haab.md` is created and casts company elements
- [x] The local validation tests (`npm test`) run successfully with zero errors
