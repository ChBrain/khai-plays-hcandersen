---
khai: order
title: "Stage BFN 386"
language: english
license: CC-BY-NC-SA-4.0
stamp:
  owner: KAI HACKS AI
  version: v0.0.1
  date: "2026-06-19"
---

# Order: Stage BFN 386

## Direction

The house must stage BFN 386 (_Den onde Fyrste_) to establish the seventeenth production in the H.C. Andersen house. The production must model Fyrsten, Englen, Myggen, Undersåtterne, the positions (Tyran, Dommer, Undertrykt), the pieces (Luftskibet, Statuen, Blodsdråben), the environments (Riget, Himlen, Ruinerne), the conquest and invasion processes, and the plots leading to their realization. It must be written in authentic Danish for all prose sections.

## Orders

1. The Playwright (Hans Christian Andersen) must author the play definition, the four personas, the three positions, the three pieces, the three places, the two processes, the two in-world plans, the pitch of Hubris, and the three plots.
2. The Theatre Manager (Edvard Collin) must verify the local registry, ensure correct versioning, check formatting, and validate that the entire cast conforms to the canon.
3. The Roadie (Vilhelm Pedersen) must set the stage, verify the local test suite is green, and prepare the files for packaging.

## Implementation

The play files must be placed in `plays/bfn386_den_onde_fyrste/` and follow the house language policy:

- Structural elements and frontmatter in English.
- Narrative prose, projections, actions, shadows, tells, and staging notes in Danish.

## Targets

- [x] `plays/bfn386_den_onde_fyrste/play_onde_fyrste.md` is created and lists the complete company
- [x] `plays/bfn386_den_onde_fyrste/persona_fyrsten.md` is created and links to `position_tyran.md`
- [x] `plays/bfn386_den_onde_fyrste/persona_englen.md` is created and links to `position_dommer.md`
- [x] `plays/bfn386_den_onde_fyrste/persona_myggen.md` is created and links to `position_dommer.md`
- [x] `plays/bfn386_den_onde_fyrste/persona_undersaatterne.md` is created and links to `position_undertrykt.md`
- [x] `plays/bfn386_den_onde_fyrste/position_tyran.md` is created
- [x] `plays/bfn386_den_onde_fyrste/position_dommer.md` is created
- [x] `plays/bfn386_den_onde_fyrste/position_undertrykt.md` is created
- [x] `plays/bfn386_den_onde_fyrste/piece_luftskibet.md` is created
- [x] `plays/bfn386_den_onde_fyrste/piece_statuen.md` is created
- [x] `plays/bfn386_den_onde_fyrste/piece_blodsdraaben.md` is created
- [x] `plays/bfn386_den_onde_fyrste/place_riget.md` is created
- [x] `plays/bfn386_den_onde_fyrste/place_himlen.md` is created
- [x] `plays/bfn386_den_onde_fyrste/place_ruinerne.md` is created
- [x] `plays/bfn386_den_onde_fyrste/process_erobring.md` is created
- [x] `plays/bfn386_den_onde_fyrste/process_invasion.md` is created
- [x] `plays/bfn386_den_onde_fyrste/plan_fyrstens_plan.md` is created and linked to `persona_fyrsten.md`
- [x] `plays/bfn386_den_onde_fyrste/plan_guddommelig_plan.md` is created and linked to `persona_myggen.md`
- [x] `plays/bfn386_den_onde_fyrste/pitch_hubris.md` is created
- [x] `plays/bfn386_den_onde_fyrste/plot_erobringen.md` is created and casts company elements
- [x] `plays/bfn386_den_onde_fyrste/plot_luftrejsen.md` is created and casts company elements
- [x] `plays/bfn386_den_onde_fyrste/plot_myggen.md` is created and casts company elements
- [x] The local validation tests (`npm test`) run successfully with zero errors
