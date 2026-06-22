---
khai: order
title: "Stage BFN 616 Alt paa sin rette Plads"
language: english
license: CC-BY-NC-SA-4.0
stamp:
  owner: KAI HACKS AI
  version: v0.0.1
  date: "2026-06-22"
---

# Order: Stage BFN 616 Alt paa sin rette Plads

## Direction

The house must stage BFN 616 (_Alt paa sin rette Plads!_) to establish the fifty-fourth production in the H.C. Andersen house. The production must model Herremand, Gaasepige, the positions (Hovmodig, Ydmyg), the piece (Flojte), the environments (Herregaard, Gaasesti), the blaest and flytning processes, and the plots leading to their realization. It must be written in authentic Danish for all prose sections.

## Orders

1. The Playwright (Hans Christian Andersen) must author the play definition, the two personas, the two positions, the piece, the two places, the two processes, the two in-world plans, the pitch of Satire, and the four plots.
2. The Theatre Manager (Edvard Collin) must verify the local registry, ensure correct versioning, check formatting, and validate that the entire cast conforms to the canon.
3. The Roadie (Vilhelm Pedersen) must set the stage, verify the local test suite is green, and prepare the files for packaging.

## Implementation

The play files must be placed in `plays/bfn616_alt_paa_sin_rette_plads/` and follow the house language policy:

- Structural elements and frontmatter in English.
- Narrative prose, projections, actions, shadows, tells, and staging notes in Danish.

## Targets

- [x] `plays/bfn616_alt_paa_sin_rette_plads/play_alt_paa_sin_rette_plads.md` is created and lists the complete company
- [x] `plays/bfn616_alt_paa_sin_rette_plads/persona_herremand.md` is created and links to `position_hovmodig.md`
- [x] `plays/bfn616_alt_paa_sin_rette_plads/persona_gaasepige.md` is created and links to `position_ydmyg.md`
- [x] `plays/bfn616_alt_paa_sin_rette_plads/position_hovmodig.md` is created
- [x] `plays/bfn616_alt_paa_sin_rette_plads/position_ydmyg.md` is created
- [x] `plays/bfn616_alt_paa_sin_rette_plads/piece_flojte.md` is created
- [x] `plays/bfn616_alt_paa_sin_rette_plads/place_herregaard.md` is created
- [x] `plays/bfn616_alt_paa_sin_rette_plads/place_gaasesti.md` is created
- [x] `plays/bfn616_alt_paa_sin_rette_plads/process_blaest.md` is created
- [x] `plays/bfn616_alt_paa_sin_rette_plads/process_flytning.md` is created
- [x] `plays/bfn616_alt_paa_sin_rette_plads/plan_bevarelse.md` is created and linked to `persona_herremand.md`
- [x] `plays/bfn616_alt_paa_sin_rette_plads/plan_retfaerdighed.md` is created and linked to `persona_gaasepige.md`
- [x] `plays/bfn616_alt_paa_sin_rette_plads/pitch_satire.md` is created
- [x] `plays/bfn616_alt_paa_sin_rette_plads/plot_facade.md` is created and casts company elements
- [x] `plays/bfn616_alt_paa_sin_rette_plads/plot_flojtespil.md` is created and casts company elements
- [x] `plays/bfn616_alt_paa_sin_rette_plads/plot_storm.md` is created and casts company elements
- [x] `plays/bfn616_alt_paa_sin_rette_plads/plot_rette_plads.md` is created and casts company elements
- [x] The local validation tests (`npm test`) run successfully with zero errors
