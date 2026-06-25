---
khai: order
title: "Stage BFN 910 Skrubtudsen"
language: english
license: CC-BY-NC-SA-4.0
stamp:
  owner: KAI HACKS AI
  version: v0.0.1
  date: "2026-06-25"
---

# Order: Stage BFN 910 Skrubtudsen

## Direction

The house must stage BFN 910 (_Skrubtudsen_) to establish the one-hundred-and-second production in the H.C. Andersen house. The production must model Skrubtudsen, Tudsemor, Stork, and Frø, the positions (Stræbende, Moderlig, Farlig, Tilfreds), the pieces (Ædelsten, Vandspand), the environments (Brønd, Have), the længsel and opstigning processes, and the plots depicting well life, bucket escape, garden exploration, and the encounter with the stork. It must be written in authentic Danish for all prose sections.

## Orders

1. The Playwright (Hans Christian Andersen) must author the play definition, the four personas, the four positions, the two pieces, the two places, the two processes, the two in-world plans, the pitch of Laengsel, and the four plots.
2. The Theatre Manager (Edvard Collin) must verify the local registry, ensure correct versioning, check formatting, and validate that the cast conforms to the canon.
3. The Roadie (Vilhelm Pedersen) must set the stage, verify the local test suite is green, and prepare the files for packaging.

## Implementation

The play files must be placed in `plays/bfn910_skrubtudsen/` and follow the house language policy:

- Structural elements and frontmatter in English.
- Narrative prose, projections, actions, shadows, tells, and staging notes in Danish.

## Targets

- [x] `plays/bfn910_skrubtudsen/play_skrubtudsen.md` is created and lists the complete company
- [x] `plays/bfn910_skrubtudsen/persona_skrubtudse.md` is created and links to `position_straebende.md`
- [x] `plays/bfn910_skrubtudsen/persona_tudsemor.md` is created and links to `position_moderlig.md`
- [x] `plays/bfn910_skrubtudsen/persona_stork.md` is created and links to `position_farlig.md`
- [x] `plays/bfn910_skrubtudsen/persona_froe.md` is created and links to `position_tilfreds.md`
- [x] `plays/bfn910_skrubtudsen/position_straebende.md` is created
- [x] `plays/bfn910_skrubtudsen/position_moderlig.md` is created
- [x] `plays/bfn910_skrubtudsen/position_farlig.md` is created
- [x] `plays/bfn910_skrubtudsen/position_tilfreds.md` is created
- [x] `plays/bfn910_skrubtudsen/piece_aedelsten.md` is created
- [x] `plays/bfn910_skrubtudsen/piece_vandspand.md` is created
- [x] `plays/bfn910_skrubtudsen/place_broend.md` is created
- [x] `plays/bfn910_skrubtudsen/place_have.md` is created
- [x] `plays/bfn910_skrubtudsen/process_laengsel.md` is created
- [x] `plays/bfn910_skrubtudsen/process_opstigning.md` is created
- [x] `plays/bfn910_skrubtudsen/plan_udgang.md` is created and linked to `persona_skrubtudse.md`
- [x] `plays/bfn910_skrubtudsen/plan_rejse.md` is created and linked to `persona_stork.md`
- [x] `plays/bfn910_skrubtudsen/pitch_laengsel.md` is created
- [x] `plays/bfn910_skrubtudsen/plot_broendlivet.md` is created and casts company elements
- [x] `plays/bfn910_skrubtudsen/plot_spanden.md` is created and casts company elements
- [x] `plays/bfn910_skrubtudsen/plot_haven.md` is created and casts company elements
- [x] `plays/bfn910_skrubtudsen/plot_storken.md` is created and casts company elements
- [x] The local validation tests (`npm test`) run successfully with zero errors
