---
khai: order
title: "Stage BFN 804 Flyttedagen"
language: english
license: CC-BY-NC-SA-4.0
stamp:
  owner: KAI HACKS AI
  version: v0.0.1
  date: "2026-06-25"
---

# Order: Stage BFN 804 Flyttedagen

## Direction

The house must stage BFN 804 (_Flyttedagen_) to establish the one-hundredth production in the H.C. Andersen house. The production must model Ole and Fortælleren, the positions (Vagt, Besøgende), the pieces (Bimpel, Tænder, Snefnug), the environments (Taarn, Gade), the erindring and retfærdighed processes, and the plots representing the watchman's observations, the garbage cart stories, the death omnibus, and the moral warnings of historical kings. It must be written in authentic Danish for all prose sections.

## Orders

1. The Playwright (Hans Christian Andersen) must author the play definition, the two personas, the two positions, the three pieces, the two places, the two processes, the two in-world plans, the pitch of Forgængelighed, and the five plots.
2. The Theatre Manager (Edvard Collin) must verify the local registry, ensure correct versioning, check formatting, and validate that the cast conforms to the canon.
3. The Roadie (Vilhelm Pedersen) must set the stage, verify the local test suite is green, and prepare the files for packaging.

## Implementation

The play files must be placed in `plays/bfn804_flyttedagen/` and follow the house language policy:

- Structural elements and frontmatter in English.
- Narrative prose, projections, actions, shadows, tells, and staging notes in Danish.

## Targets

- [x] `plays/bfn804_flyttedagen/play_flyttedagen.md` is created and lists the complete company
- [x] `plays/bfn804_flyttedagen/persona_ole.md` is created and links to `position_vagt.md`
- [x] `plays/bfn804_flyttedagen/persona_fortaelleren.md` is created and links to `position_besoegende.md`
- [x] `plays/bfn804_flyttedagen/position_vagt.md` is created
- [x] `plays/bfn804_flyttedagen/position_besoegende.md` is created
- [x] `plays/bfn804_flyttedagen/piece_bimpel.md` is created
- [x] `plays/bfn804_flyttedagen/piece_taender.md` is created
- [x] `plays/bfn804_flyttedagen/piece_snefnug.md` is created
- [x] `plays/bfn804_flyttedagen/place_taarn.md` is created
- [x] `plays/bfn804_flyttedagen/place_gade.md` is created
- [x] `plays/bfn804_flyttedagen/process_erindring.md` is created
- [x] `plays/bfn804_flyttedagen/process_retfaerdighed.md` is created
- [x] `plays/bfn804_flyttedagen/plan_flytning.md` is created and linked to `persona_fortaelleren.md`
- [x] `plays/bfn804_flyttedagen/plan_dom.md` is created and linked to `persona_ole.md`
- [x] `plays/bfn804_flyttedagen/pitch_forgaengelighed.md` is created
- [x] `plays/bfn804_flyttedagen/plot_besoeget.md` is created and casts company elements
- [x] `plays/bfn804_flyttedagen/plot_vognen.md` is created and casts company elements
- [x] `plays/bfn804_flyttedagen/plot_omnibussen.md` is created and casts company elements
- [x] `plays/bfn804_flyttedagen/plot_ludvig.md` is created and casts company elements
- [x] `plays/bfn804_flyttedagen/plot_dommen.md` is created and casts company elements
- [x] The local validation tests (`npm test`) run successfully with zero errors
