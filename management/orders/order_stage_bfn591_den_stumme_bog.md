---
khai: order
title: "Stage BFN 591 Den stumme Bog"
language: english
license: CC-BY-NC-SA-4.0
stamp:
  owner: KAI HACKS AI
  version: v0.0.1
  date: "2026-06-26"
---

# Order: Stage BFN 591 Den stumme Bog

## Direction

The house must stage BFN 591 (_Den stumme Bog_) to establish a production in the H.C. Andersen house. The production must model ejeren, blomsten, the positions (samler, vidne), the pieces (bogen, rose), the environments (kisten, haven), the bevaring and forgaengelighed processes, and the plots representing samlingen and graven. It must be written in authentic Danish for all prose sections.

## Orders

1. The Playwright (Hans Christian Andersen) must author the play definition, the 2 personas, the 2 positions, the 2 pieces, the 2 places, the 2 processes, the 2 in-world plans, the pitch of poetisk, and the 2 plots.
2. The Theatre Manager (Edvard Collin) must verify the local registry, ensure correct versioning, check formatting, and validate that the cast conforms to the canon.
3. The Roadie (Vilhelm Pedersen) must set the stage, verify the local test suite is green, and prepare the files for packaging.

## Implementation

The play files must be placed in `plays/bfn591_den_stumme_bog/` and follow the house language policy:

- Structural elements and frontmatter in English.
- Narrative prose, projections, actions, shadows, tells, and staging notes in Danish.

## Targets

- [x] `plays/bfn591_den_stumme_bog/play_den_stumme_bog.md` is created and lists the complete company
- [x] `plays/bfn591_den_stumme_bog/persona_ejeren.md` is created and links to `position_samler.md`
- [x] `plays/bfn591_den_stumme_bog/persona_blomsten.md` is created and links to `position_vidne.md`
- [x] `plays/bfn591_den_stumme_bog/position_samler.md` is created
- [x] `plays/bfn591_den_stumme_bog/position_vidne.md` is created
- [x] `plays/bfn591_den_stumme_bog/piece_bogen.md` is created
- [x] `plays/bfn591_den_stumme_bog/piece_rose.md` is created
- [x] `plays/bfn591_den_stumme_bog/place_kisten.md` is created
- [x] `plays/bfn591_den_stumme_bog/place_haven.md` is created
- [x] `plays/bfn591_den_stumme_bog/process_bevaring.md` is created
- [x] `plays/bfn591_den_stumme_bog/process_forgaengelighed.md` is created
- [x] `plays/bfn591_den_stumme_bog/plan_erindring.md` is created and linked to `persona_ejeren.md`
- [x] `plays/bfn591_den_stumme_bog/plan_tavshed.md` is created and linked to `persona_ejeren.md`
- [x] `plays/bfn591_den_stumme_bog/pitch_poetisk.md` is created
- [x] `plays/bfn591_den_stumme_bog/plot_samlingen.md` is created and casts company elements
- [x] `plays/bfn591_den_stumme_bog/plot_graven.md` is created and casts company elements
- [x] The local validation tests (`npm test`) run successfully with zero errors
