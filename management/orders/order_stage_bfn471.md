---
khai: order
title: "Stage BFN 471"
language: english
license: CC-BY-NC-SA-4.0
stamp:
  owner: KAI HACKS AI
  version: v0.0.1
  date: "2026-06-21"
---

# Order: Stage BFN 471

## Direction

The house must stage BFN 471 (_Hyrdinden og Skorstensfejeren_) to establish the thirtieth production in the H.C. Andersen house. The production must model Hyrdinden, Skorstensfejeren, Gedebukkebenen, the positions (Elskende, Tyrand), the pieces (Kineser), the environments (Stuen, Skorstenen, Verden), the flugt and kapitulation processes, and the plots leading to their realization. It must be written in authentic Danish for all prose sections.

## Orders

1. The Playwright (Hans Christian Andersen) must author the play definition, the three personas, the two positions, the piece, the three places, the two processes, the two in-world plans, the pitch of Porcelæn, and the four plots.
2. The Theatre Manager (Edvard Collin) must verify the local registry, ensure correct versioning, check formatting, and validate that the entire cast conforms to the canon.
3. The Roadie (Vilhelm Pedersen) must set the stage, verify the local test suite is green, and prepare the files for packaging.

## Implementation

The play files must be placed in `plays/bfn471_hyrdinden/` and follow the house language policy:

- Structural elements and frontmatter in English.
- Narrative prose, projections, actions, shadows, tells, and staging notes in Danish.

## Targets

- [x] `plays/bfn471_hyrdinden/play_hyrdinden.md` is created and lists the complete company
- [x] `plays/bfn471_hyrdinden/persona_hyrdinden.md` is created and links to `position_elskende.md`
- [x] `plays/bfn471_hyrdinden/persona_skorstensfejeren.md` is created and links to `position_elskende.md`
- [x] `plays/bfn471_hyrdinden/persona_gedebukkebeens_overkrigs_generals_krigs_seere.md` is created and links to `position_tyrand.md`
- [x] `plays/bfn471_hyrdinden/position_elskende.md` is created
- [x] `plays/bfn471_hyrdinden/position_tyrand.md` is created
- [x] `plays/bfn471_hyrdinden/piece_kineser.md` is created
- [x] `plays/bfn471_hyrdinden/place_stuen.md` is created
- [x] `plays/bfn471_hyrdinden/place_skorstenen.md` is created
- [x] `plays/bfn471_hyrdinden/place_verden.md` is created
- [x] `plays/bfn471_hyrdinden/process_flugt.md` is created
- [x] `plays/bfn471_hyrdinden/process_kapitulation.md` is created
- [x] `plays/bfn471_hyrdinden/plan_hyrdindens_flugt.md` is created and linked to `persona_hyrdinden.md`
- [x] `plays/bfn471_hyrdinden/plan_gedebukkens_bryllup.md` is created and linked to `persona_gedebukkebeens_overkrigs_generals_krigs_seere.md`
- [x] `plays/bfn471_hyrdinden/pitch_porcelaen.md` is created
- [x] `plays/bfn471_hyrdinden/plot_aftalen.md` is created and casts company elements
- [x] `plays/bfn471_hyrdinden/plot_opstigningen.md` is created and casts company elements
- [x] `plays/bfn471_hyrdinden/plot_taget.md` is created and casts company elements
- [x] `plays/bfn471_hyrdinden/plot_hjemkomsten.md` is created and casts company elements
- [x] The local validation tests (`npm test`) run successfully with zero errors
