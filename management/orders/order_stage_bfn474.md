---
khai: order
title: "Stage BFN 474"
language: english
license: CC-BY-NC-SA-4.0
stamp:
  owner: KAI HACKS AI
  version: v0.0.1
  date: "2026-06-21"
---

# Order: Stage BFN 474

## Direction

The house must stage BFN 474 (_Klokken_) to establish the thirty-second production in the H.C. Andersen house. The production must model Kongesønnen, Fattigdrengen, the position (Søgende), the piece (Klokken), the environments (Byen, Skoven, Klippen), the søgning and åbenbaring processes, and the plots leading to their realization. It must be written in authentic Danish for all prose sections.

## Orders

1. The Playwright (Hans Christian Andersen) must author the play definition, the two personas, the position, the piece, the three places, the two processes, the two in-world plans, the pitch of Panteisme, and the four plots.
2. The Theatre Manager (Edvard Collin) must verify the local registry, ensure correct versioning, check formatting, and validate that the entire cast conforms to the canon.
3. The Roadie (Vilhelm Pedersen) must set the stage, verify the local test suite is green, and prepare the files for packaging.

## Implementation

The play files must be placed in `plays/bfn474_klokken/` and follow the house language policy:

- Structural elements and frontmatter in English.
- Narrative prose, projections, actions, shadows, tells, and staging notes in Danish.

## Targets

- [x] `plays/bfn474_klokken/play_klokken.md` is created and lists the complete company
- [x] `plays/bfn474_klokken/persona_kongesoennen.md` is created and links to `position_soegende.md`
- [x] `plays/bfn474_klokken/persona_fattigdrengen.md` is created and links to `position_soegende.md`
- [x] `plays/bfn474_klokken/position_soegende.md` is created
- [x] `plays/bfn474_klokken/piece_klokken.md` is created
- [x] `plays/bfn474_klokken/place_byen.md` is created
- [x] `plays/bfn474_klokken/place_skoven.md` is created
- [x] `plays/bfn474_klokken/place_klippen.md` is created
- [x] `plays/bfn474_klokken/process_soegning.md` is created
- [x] `plays/bfn474_klokken/process_aabenbaring.md` is created
- [x] `plays/bfn474_klokken/plan_klokkesoegning.md` is created and linked to the seekers
- [x] `plays/bfn474_klokken/pitch_panteisme.md` is created
- [x] `plays/bfn474_klokken/plot_lyden.md` is created and casts company elements
- [x] `plays/bfn474_klokken/plot_afveje.md` is created and casts company elements
- [x] `plays/bfn474_klokken/plot_skovvandring.md` is created and casts company elements
- [x] `plays/bfn474_klokken/plot_moedet.md` is created and casts company elements
- [x] The local validation tests (`npm test`) run successfully with zero errors
