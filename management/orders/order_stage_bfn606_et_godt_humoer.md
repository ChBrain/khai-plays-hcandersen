---
khai: order
title: "Stage BFN 606 Et godt Humør"
language: english
license: CC-BY-NC-SA-4.0
stamp:
  owner: KAI HACKS AI
  version: v0.0.1
  date: "2026-06-22"
---

# Order: Stage BFN 606 Et godt Humør

## Direction

The house must stage BFN 606 (_Et godt Humør_) to establish the fifty-second production in the H.C. Andersen house. The production must model Humorist, Borgerskab, the positions (Munter, Dyster), the piece (Vid), the environments (Gade, Kirkegaard), the observation and latter processes, and the plots leading to their realization. It must be written in authentic Danish for all prose sections.

## Orders

1. The Playwright (Hans Christian Andersen) must author the play definition, the two personas, the two positions, the piece, the two places, the two processes, the two in-world plans, the pitch of Humor, and the four plots.
2. The Theatre Manager (Edvard Collin) must verify the local registry, ensure correct versioning, check formatting, and validate that the entire cast conforms to the canon.
3. The Roadie (Vilhelm Pedersen) must set the stage, verify the local test suite is green, and prepare the files for packaging.

## Implementation

The play files must be placed in `plays/bfn606_et_godt_humoer/` and follow the house language policy:

- Structural elements and frontmatter in English.
- Narrative prose, projections, actions, shadows, tells, and staging notes in Danish.

## Targets

- [x] `plays/bfn606_et_godt_humoer/play_et_godt_humoer.md` is created and lists the complete company
- [x] `plays/bfn606_et_godt_humoer/persona_humorist.md` is created and links to `position_munter.md`
- [x] `plays/bfn606_et_godt_humoer/persona_borgerskab.md` is created and links to `position_dyster.md`
- [x] `plays/bfn606_et_godt_humoer/position_munter.md` is created
- [x] `plays/bfn606_et_godt_humoer/position_dyster.md` is created
- [x] `plays/bfn606_et_godt_humoer/piece_vid.md` is created
- [x] `plays/bfn606_et_godt_humoer/place_gade.md` is created
- [x] `plays/bfn606_et_godt_humoer/place_kirkegaard.md` is created
- [x] `plays/bfn606_et_godt_humoer/process_observation.md` is created
- [x] `plays/bfn606_et_godt_humoer/process_latter.md` is created
- [x] `plays/bfn606_et_godt_humoer/plan_livsglaede.md` is created and linked to `persona_humorist.md`
- [x] `plays/bfn606_et_godt_humoer/plan_kritik.md` is created and linked to `persona_borgerskab.md`
- [x] `plays/bfn606_et_godt_humoer/pitch_humor.md` is created
- [x] `plays/bfn606_et_godt_humoer/plot_arv.md` is created and casts company elements
- [x] `plays/bfn606_et_godt_humoer/plot_gaden.md` is created and casts company elements
- [x] `plays/bfn606_et_godt_humoer/plot_kirkegaarden.md` is created and casts company elements
- [x] `plays/bfn606_et_godt_humoer/plot_latter.md` is created and casts company elements
- [x] The local validation tests (`npm test`) run successfully with zero errors
