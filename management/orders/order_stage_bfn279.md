---
khai: order
title: "Stage BFN 279"
language: english
license: CC-BY-NC-SA-4.0
stamp:
  owner: KAI HACKS AI
  version: v0.0.1
  date: "2026-06-17"
---

# Order: Stage BFN 279

## Direction

The house must stage BFN 279 (_Rejsekammeraten_) to establish the seventh production in the H.C. Andersen house. The production must model Johannes, the traveling companion, the princess, the troll, the environments (the King's Castle and the Troll's Cave), the dead body, swan wings, and troll's head pieces, the secret pursuit and liberation processes, and the plots leading to the breaking of the spell. It must be written in authentic Danish for all prose sections.

## Orders

1. The Playwright (Hans Christian Andersen) must author the play definition, the four personas, the four positions, the three pieces, the two places, the two processes, the two in-world plans, and the four plots.
2. The Theatre Manager (Edvard Collin) must verify the local registry, ensure correct versioning, check formatting, and validate that the entire cast conforms to the canon.
3. The Roadie (Vilhelm Pedersen) must set the stage, verify the local test suite is green, and prepare the files for packaging.

## Implementation

The play files must be placed in `plays/bfn279_rejsekammeraten/` and follow the house language policy:

- Structural elements and frontmatter in English.
- Narrative prose, projections, actions, shadows, tells, and staging notes in Danish.

## Targets

- [x] `plays/bfn279_rejsekammeraten/play_rejsekammeraten.md` is created and lists the complete company
- [x] `plays/bfn279_rejsekammeraten/persona_johannes.md` is created and links to `position_vandrer.md`
- [x] `plays/bfn279_rejsekammeraten/persona_rejsekammeraten.md` is created and links to `position_hjaelper.md`
- [x] `plays/bfn279_rejsekammeraten/persona_prinsessen.md` is created and links to `position_fange.md`
- [x] `plays/bfn279_rejsekammeraten/persona_trolden.md` is created and links to `position_fangevogter.md`
- [x] `plays/bfn279_rejsekammeraten/position_vandrer.md` is created
- [x] `plays/bfn279_rejsekammeraten/position_hjaelper.md` is created
- [x] `plays/bfn279_rejsekammeraten/position_fange.md` is created
- [x] `plays/bfn279_rejsekammeraten/position_fangevogter.md` is created
- [x] `plays/bfn279_rejsekammeraten/piece_doed_krop.md` is created
- [x] `plays/bfn279_rejsekammeraten/piece_svanevinger.md` is created
- [x] `plays/bfn279_rejsekammeraten/piece_troldhoved.md` is created
- [x] `plays/bfn279_rejsekammeraten/place_kongens_slot.md` is created
- [x] `plays/bfn279_rejsekammeraten/place_troldens_hule.md` is created
- [x] `plays/bfn279_rejsekammeraten/process_forfoegelse.md` is created
- [x] `plays/bfn279_rejsekammeraten/process_befrielse.md` is created
- [x] `plays/bfn279_rejsekammeraten/plan_johannes_plan.md` is created and linked to `persona_johannes.md`
- [x] `plays/bfn279_rejsekammeraten/plan_rejsekammeratens_plan.md` is created and linked to `persona_rejsekammeraten.md`
- [x] `plays/bfn279_rejsekammeraten/plot_den_doede_mand.md` is created and casts company elements
- [x] `plays/bfn279_rejsekammeraten/plot_moedet.md` is created and casts company elements
- [x] `plays/bfn279_rejsekammeraten/plot_gaaderne.md` is created and casts company elements
- [x] `plays/bfn279_rejsekammeraten/plot_brylluppet.md` is created and casts company elements
- [x] The local validation tests (`npm test`) run successfully with zero errors
