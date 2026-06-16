---
khai: order
title: "Stage BFN 269"
language: english
license: CC-BY-NC-SA-4.0
stamp:
  owner: KAI HACKS AI
  version: v0.0.1
  date: "2026-06-16"
---

# Order: Stage BFN 269

## Direction

The house must stage BFN 269 to establish the first production in the H.C. Andersen house. The production must be a faithful systemic representation of the original Danish fairytale, focusing on sensitivity as the core royal detection mechanism, and satisfying all local conformance and language gates.

## Orders

1. The Playwright (Hans Christian Andersen) must author the play definition, the three core personas, the royal and stranger positions, the castle place, the sensitivity test process, the pea and bed pieces, and the two plots.
2. The Theatre Manager (Edvard Collin) must verify the local registry, ensure correct versioning, check formatting, and validate that the entire cast conforms to the canon.
3. The Roadie (Vilhelm Pedersen) must set the stage, verify the local test suite is green, and prepare the files for packaging.

## Implementation

The play files must be placed in `plays/bfn269_prinsessen_paa_aerten/` and follow the house language policy:

- Structural elements and frontmatter in English.
- Narrative prose, projections, actions, shadows, tells, and staging notes in Danish.

## Targets

- [x] `plays/bfn269_prinsessen_paa_aerten/play_prinsessen.md` is created and lists the complete company
- [x] `plays/bfn269_prinsessen_paa_aerten/persona_prinsessen.md` is created and links to `position_fremmed.md`
- [x] `plays/bfn269_prinsessen_paa_aerten/persona_dronningen.md` is created and links to `position_kongelig.md`
- [x] `plays/bfn269_prinsessen_paa_aerten/persona_prinsen.md` is created and links to `position_kongelig.md`
- [x] `plays/bfn269_prinsessen_paa_aerten/position_kongelig.md` is created
- [x] `plays/bfn269_prinsessen_paa_aerten/position_fremmed.md` is created
- [x] `plays/bfn269_prinsessen_paa_aerten/piece_aerten.md` is created
- [x] `plays/bfn269_prinsessen_paa_aerten/piece_sengen.md` is created
- [x] `plays/bfn269_prinsessen_paa_aerten/place_slottet.md` is created
- [x] `plays/bfn269_prinsessen_paa_aerten/process_proeven.md` is created
- [x] `plays/bfn269_prinsessen_paa_aerten/plot_soegning.md` is created and casts company elements
- [x] `plays/bfn269_prinsessen_paa_aerten/plot_proevelse.md` is created and casts company elements
- [x] The local validation tests (`npm test`) run successfully with zero errors
