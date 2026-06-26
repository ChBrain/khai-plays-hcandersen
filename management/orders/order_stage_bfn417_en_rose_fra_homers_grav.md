---
khai: order
title: "Stage BFN 417 En Rose fra Homers Grav"
language: english
license: CC-BY-NC-SA-4.0
stamp:
  owner: KAI HACKS AI
  version: v0.0.1
  date: "2026-06-26"
---

# Order: Stage BFN 417 En Rose fra Homers Grav

## Direction

The house must stage BFN 417 (_En Rose fra Homers Grav_) to establish a production in the H.C. Andersen house. The production must model rosen, sangeren, the positions (droemmer, fortaeller), the pieces (rosenblad, harpe), the environments (graven, skibet), the droem and sang processes, and the plots representing graven and rejsen. It must be written in authentic Danish for all prose sections.

## Orders

1. The Playwright (Hans Christian Andersen) must author the play definition, the 2 personas, the 2 positions, the 2 pieces, the 2 places, the 2 processes, the 1 in-world plans, the pitch of romantisk, and the 2 plots.
2. The Theatre Manager (Edvard Collin) must verify the local registry, ensure correct versioning, check formatting, and validate that the cast conforms to the canon.
3. The Roadie (Vilhelm Pedersen) must set the stage, verify the local test suite is green, and prepare the files for packaging.

## Implementation

The play files must be placed in `plays/bfn417_en_rose_fra_homers_grav/` and follow the house language policy:

- Structural elements and frontmatter in English.
- Narrative prose, projections, actions, shadows, tells, and staging notes in Danish.

## Targets

- [x] `plays/bfn417_en_rose_fra_homers_grav/play_en_rose_fra_homers_grav.md` is created and lists the complete company
- [x] `plays/bfn417_en_rose_fra_homers_grav/persona_rosen.md` is created and links to `position_droemmer.md`
- [x] `plays/bfn417_en_rose_fra_homers_grav/persona_sangeren.md` is created and links to `position_fortaeller.md`
- [x] `plays/bfn417_en_rose_fra_homers_grav/position_droemmer.md` is created
- [x] `plays/bfn417_en_rose_fra_homers_grav/position_fortaeller.md` is created
- [x] `plays/bfn417_en_rose_fra_homers_grav/piece_rosenblad.md` is created
- [x] `plays/bfn417_en_rose_fra_homers_grav/piece_harpe.md` is created
- [x] `plays/bfn417_en_rose_fra_homers_grav/place_graven.md` is created
- [x] `plays/bfn417_en_rose_fra_homers_grav/place_skibet.md` is created
- [x] `plays/bfn417_en_rose_fra_homers_grav/process_droem.md` is created
- [x] `plays/bfn417_en_rose_fra_homers_grav/process_sang.md` is created
- [x] `plays/bfn417_en_rose_fra_homers_grav/plan_erindring.md` is created and linked to `persona_rosen.md`
- [x] `plays/bfn417_en_rose_fra_homers_grav/pitch_romantisk.md` is created
- [x] `plays/bfn417_en_rose_fra_homers_grav/plot_graven.md` is created and casts company elements
- [x] `plays/bfn417_en_rose_fra_homers_grav/plot_rejsen.md` is created and casts company elements
- [x] The local validation tests (`npm test`) run successfully with zero errors
