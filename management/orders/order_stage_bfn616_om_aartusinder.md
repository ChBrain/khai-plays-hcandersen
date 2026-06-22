---
khai: order
title: "Stage BFN 616 Om Aartusinder"
language: english
license: CC-BY-NC-SA-4.0
stamp:
  owner: KAI HACKS AI
  version: v0.0.1
  date: "2026-06-22"
---

# Order: Stage BFN 616 Om Aartusinder

## Direction

The house must stage BFN 616 (_Om Aartusinder_) to establish the fifty-sixth production in the H.C. Andersen house. The production must model Rejsende, Europa, the positions (Hastig, Forfalden), the piece (Luftskib), the environments (Himmel, Ruin), the luftfart and sightseeing processes, and the plots leading to their realization. It must be written in authentic Danish for all prose sections.

## Orders

1. The Playwright (Hans Christian Andersen) must author the play definition, the two personas, the two positions, the piece, the two places, the two processes, the two in-world plans, the pitch of Refleksion, and the four plots.
2. The Theatre Manager (Edvard Collin) must verify the local registry, ensure correct versioning, check formatting, and validate that the entire cast conforms to the canon.
3. The Roadie (Vilhelm Pedersen) must set the stage, verify the local test suite is green, and prepare the files for packaging.

## Implementation

The play files must be placed in `plays/bfn616_om_aartusinder/` and follow the house language policy:

- Structural elements and frontmatter in English.
- Narrative prose, projections, actions, shadows, tells, and staging notes in Danish.

## Targets

- [x] `plays/bfn616_om_aartusinder/play_om_aartusinder.md` is created and lists the complete company
- [x] `plays/bfn616_om_aartusinder/persona_rejsende.md` is created and links to `position_hastig.md`
- [x] `plays/bfn616_om_aartusinder/persona_europa.md` is created and links to `position_forfalden.md`
- [x] `plays/bfn616_om_aartusinder/position_hastig.md` is created
- [x] `plays/bfn616_om_aartusinder/position_forfalden.md` is created
- [x] `plays/bfn616_om_aartusinder/piece_luftskib.md` is created
- [x] `plays/bfn616_om_aartusinder/place_himmel.md` is created
- [x] `plays/bfn616_om_aartusinder/place_ruin.md` is created
- [x] `plays/bfn616_om_aartusinder/process_luftfart.md` is created
- [x] `plays/bfn616_om_aartusinder/process_sightseeing.md` is created
- [x] `plays/bfn616_om_aartusinder/plan_rundrejse.md` is created and linked to `persona_rejsende.md`
- [x] `plays/bfn616_om_aartusinder/plan_bevaring.md` is created and linked to `persona_europa.md`
- [x] `plays/bfn616_om_aartusinder/pitch_refleksion.md` is created
- [x] `plays/bfn616_om_aartusinder/plot_overfart.md` is created and casts company elements
- [x] `plays/bfn616_om_aartusinder/plot_ruinerne.md` is created and casts company elements
- [x] `plays/bfn616_om_aartusinder/plot_danmark.md` is created and casts company elements
- [x] `plays/bfn616_om_aartusinder/plot_fremtid.md` is created and casts company elements
- [x] The local validation tests (`npm test`) run successfully with zero errors
