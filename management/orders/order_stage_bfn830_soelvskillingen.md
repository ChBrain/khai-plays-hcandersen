---
khai: order
title: "Stage BFN 830 Soelvskillingen"
language: english
license: CC-BY-NC-SA-4.0
stamp:
  owner: KAI HACKS AI
  version: v0.0.1
  date: "2026-06-24"
---

# Order: Stage BFN 830 Soelvskillingen

## Direction

The house must stage BFN 830 (_Sølvskillingen_) to establish the ninetieth production in the H.C. Andersen house. The production must model Skilling, Rejsende, the positions (Udstoeedt, Dommer), the piece (Hul), the environments (Udland, Hjemland), the devaluering and genopretning processes, and the plots leading to their realization. It must be written in authentic Danish for all prose sections.

## Orders

1. The Playwright (Hans Christian Andersen) must author the play definition, the two personas, the two positions, the piece, the two places, the two processes, the two in-world plans, the pitch of Ironi, and the four plots.
2. The Theatre Manager (Edvard Collin) must verify the local registry, ensure correct versioning, check formatting, and validate that the cast conforms to the canon.
3. The Roadie (Vilhelm Pedersen) must set the stage, verify the local test suite is green, and prepare the files for packaging.

## Implementation

The play files must be placed in `plays/bfn830_soelvskillingen/` and follow the house language policy:

- Structural elements and frontmatter in English.
- Narrative prose, projections, actions, shadows, tells, and staging notes in Danish.

## Targets

- [x] `plays/bfn830_soelvskillingen/play_soelvskillingen.md` is created and lists the complete company
- [x] `plays/bfn830_soelvskillingen/persona_skilling.md` is created and links to `position_udstoeedt.md`
- [x] `plays/bfn830_soelvskillingen/persona_rejsende.md` is created and links to `position_dommer.md`
- [x] `plays/bfn830_soelvskillingen/position_udstoeedt.md` is created
- [x] `plays/bfn830_soelvskillingen/position_dommer.md` is created
- [x] `plays/bfn830_soelvskillingen/piece_hul.md` is created
- [x] `plays/bfn830_soelvskillingen/place_udland.md` is created
- [x] `plays/bfn830_soelvskillingen/place_hjemland.md` is created
- [x] `plays/bfn830_soelvskillingen/process_devaluering.md` is created
- [x] `plays/bfn830_soelvskillingen/process_genopretning.md` is created
- [x] `plays/bfn830_soelvskillingen/plan_rejse.md` is created and linked to `persona_skilling.md`
- [x] `plays/bfn830_soelvskillingen/plan_hjemkomst.md` is created and linked to `persona_rejsende.md`
- [x] `plays/bfn830_soelvskillingen/pitch_ironi.md` is created
- [x] `plays/bfn830_soelvskillingen/plot_udvekslingen.md` is created and casts company elements
- [x] `plays/bfn830_soelvskillingen/plot_maerkningen.md` is created and casts company elements
- [x] `plays/bfn830_soelvskillingen/plot_vildfarelsen.md` is created and casts company elements
- [x] `plays/bfn830_soelvskillingen/plot_genkendelsen.md` is created and casts company elements
- [x] The local validation tests (`npm test`) run successfully with zero errors
