---
khai: order
title: "Stage SDU 210 Vor gamle Skolemester"
language: english
license: CC-BY-NC-SA-4.0
stamp:
  owner: KAI HACKS AI
  version: v0.0.1
  date: "2026-06-26"
---

# Order: Stage SDU 210 Vor gamle Skolemester

## Direction

The house must stage SDU 210 (_Vor gamle Skolemester_) to establish a production in the H.C. Andersen house. The production must model skolemesteren, eleven, the positions (underviser, modtager), the pieces (skolebog, tavle), the environments (skolestuen, katedret), the undervisning and erindring processes, and the plots representing undervisningen and erindringen. It must be written in authentic Danish for all prose sections.

## Orders

1. The Playwright (Hans Christian Andersen) must author the play definition, the 2 personas, the 2 positions, the 2 pieces, the 2 places, the 2 processes, the 1 in-world plans, the pitch of nostalgi, and the 2 plots.
2. The Theatre Manager (Edvard Collin) must verify the local registry, ensure correct versioning, check formatting, and validate that the cast conforms to the canon.
3. The Roadie (Vilhelm Pedersen) must set the stage, verify the local test suite is green, and prepare the files for packaging.

## Implementation

The play files must be placed in `plays/sdu210_vor_gamle_skolemester/` and follow the house language policy:

- Structural elements and frontmatter in English.
- Narrative prose, projections, actions, shadows, tells, and staging notes in Danish.

## Targets

- [x] `plays/sdu210_vor_gamle_skolemester/play_vor_gamle_skolemester.md` is created and lists the complete company
- [x] `plays/sdu210_vor_gamle_skolemester/persona_skolemesteren.md` is created and links to `position_underviser.md`
- [x] `plays/sdu210_vor_gamle_skolemester/persona_eleven.md` is created and links to `position_modtager.md`
- [x] `plays/sdu210_vor_gamle_skolemester/position_underviser.md` is created
- [x] `plays/sdu210_vor_gamle_skolemester/position_modtager.md` is created
- [x] `plays/sdu210_vor_gamle_skolemester/piece_skolebog.md` is created
- [x] `plays/sdu210_vor_gamle_skolemester/piece_tavle.md` is created
- [x] `plays/sdu210_vor_gamle_skolemester/place_skolestuen.md` is created
- [x] `plays/sdu210_vor_gamle_skolemester/place_katedret.md` is created
- [x] `plays/sdu210_vor_gamle_skolemester/process_undervisning.md` is created
- [x] `plays/sdu210_vor_gamle_skolemester/process_erindring.md` is created
- [x] `plays/sdu210_vor_gamle_skolemester/plan_dannelse.md` is created and linked to `persona_skolemesteren.md`
- [x] `plays/sdu210_vor_gamle_skolemester/pitch_nostalgi.md` is created
- [x] `plays/sdu210_vor_gamle_skolemester/plot_undervisningen.md` is created and casts company elements
- [x] `plays/sdu210_vor_gamle_skolemester/plot_erindringen.md` is created and casts company elements
- [x] The local validation tests (`npm test`) run successfully with zero errors
