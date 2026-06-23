---
khai: order
title: "Stage BFN 794 En Historie fra Klitterne"
language: english
license: CC-BY-NC-SA-4.0
stamp:
  owner: KAI HACKS AI
  version: v0.0.1
  date: "2026-06-23"
---

# Order: Stage BFN 794 En Historie fra Klitterne

## Direction

The house must stage BFN 794 (_En Historie fra Klitterne_) to establish the seventy-seventh production in the H.C. Andersen house. The production must model Joergen, Clara, the positions (Skibbruden, Privilegeret), the piece (Skib), the environments (Klit, Kirke), the vandring and forloesning processes, and the plots leading to their realization. It must be written in authentic Danish for all prose sections.

## Orders

1. The Playwright (Hans Christian Andersen) must author the play definition, the two personas, the two positions, the piece, the two places, the two processes, the two in-world plans, the pitch of Melankoli, and the four plots.
2. The Theatre Manager (Edvard Collin) must verify the local registry, ensure correct versioning, check formatting, and validate that the entire cast conforms to the canon.
3. The Roadie (Vilhelm Pedersen) must set the stage, verify the local test suite is green, and prepare the files for packaging.

## Implementation

The play files must be placed in `plays/bfn794_en_historie_fra_klitterne/` and follow the house language policy:

- Structural elements and frontmatter in English.
- Narrative prose, projections, actions, shadows, tells, and staging notes in Danish.

## Targets

- [x] `plays/bfn794_en_historie_fra_klitterne/play_en_historie_fra_klitterne.md` is created and lists the complete company
- [x] `plays/bfn794_en_historie_fra_klitterne/persona_joergen.md` is created and links to `position_skibbruden.md`
- [x] `plays/bfn794_en_historie_fra_klitterne/persona_clara.md` is created and links to `position_privilegeret.md`
- [x] `plays/bfn794_en_historie_fra_klitterne/position_skibbruden.md` is created
- [x] `plays/bfn794_en_historie_fra_klitterne/position_privilegeret.md` is created
- [x] `plays/bfn794_en_historie_fra_klitterne/piece_skib.md` is created
- [x] `plays/bfn794_en_historie_fra_klitterne/place_klit.md` is created
- [x] `plays/bfn794_en_historie_fra_klitterne/place_kirke.md` is created
- [x] `plays/bfn794_en_historie_fra_klitterne/process_vandring.md` is created
- [x] `plays/bfn794_en_historie_fra_klitterne/process_forloesning.md` is created
- [x] `plays/bfn794_en_historie_fra_klitterne/plan_overlevelse.md` is created and linked to `persona_joergen.md`
- [x] `plays/bfn794_en_historie_fra_klitterne/plan_standsbevarelse.md` is created and linked to `persona_clara.md`
- [x] `plays/bfn794_en_historie_fra_klitterne/pitch_melankoli.md` is created
- [x] `plays/bfn794_en_historie_fra_klitterne/plot_skibbruddet.md` is created and casts company elements
- [x] `plays/bfn794_en_historie_fra_klitterne/plot_opvaeksten.md` is created and casts company elements
- [x] `plays/bfn794_en_historie_fra_klitterne/plot_tabene.md` is created and casts company elements
- [x] `plays/bfn794_en_historie_fra_klitterne/plot_stormfloden.md` is created and casts company elements
- [x] The local validation tests (`npm test`) run successfully with zero errors
