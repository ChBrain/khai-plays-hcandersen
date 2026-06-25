---
khai: order
title: "Stage BFN 992 Hvad man kan hitte paa"
language: english
license: CC-BY-NC-SA-4.0
stamp:
  owner: KAI HACKS AI
  version: v0.0.1
  date: "2026-06-25"
---

# Order: Stage BFN 992 Hvad man kan hitte paa

## Direction

The house must stage BFN 992 (_Hvad man kan hitte paa_) to establish the hundred and sixteenth production in the H.C. Andersen house. The production must model Digter and Kone, the positions (Søgende, Indviet, Kritisk), the pieces (Briller, Bog), the environments (Hytten, Skoven), the digtning and inspiration processes, and the plots representing the writer's block, meeting the wise woman, and finding poetry in a simple object. It must be written in authentic Danish for all prose sections.

## Orders

1. The Playwright (Hans Christian Andersen) must author the play definition, the two personas, the three positions, the two pieces, the two places, the two processes, the two in-world plans, the pitch of Satirisk, and the three plots.
2. The Theatre Manager (Edvard Collin) must verify the local registry, ensure correct versioning, check formatting, and validate that the cast conforms to the canon.
3. The Roadie (Vilhelm Pedersen) must set the stage, verify the local test suite is green, and prepare the files for packaging.

## Implementation

The play files must be placed in `plays/bfn992_hvad_man_kan_hitte_paa/` and follow the house language policy:

- Structural elements and frontmatter in English.
- Narrative prose, projections, actions, shadows, tells, and staging notes in Danish.

## Targets

- [x] `plays/bfn992_hvad_man_kan_hitte_paa/play_hvad_man_kan_hitte_paa.md` is created and lists the complete company
- [x] `plays/bfn992_hvad_man_kan_hitte_paa/persona_digter.md` is created and links to `position_soegende.md`
- [x] `plays/bfn992_hvad_man_kan_hitte_paa/persona_kone.md` is created and links to `position_indviet.md`
- [x] `plays/bfn992_hvad_man_kan_hitte_paa/position_soegende.md` is created
- [x] `plays/bfn992_hvad_man_kan_hitte_paa/position_indviet.md` is created
- [x] `plays/bfn992_hvad_man_kan_hitte_paa/position_kritisk.md` is created
- [x] `plays/bfn992_hvad_man_kan_hitte_paa/piece_briller.md` is created
- [x] `plays/bfn992_hvad_man_kan_hitte_paa/piece_bog.md` is created
- [x] `plays/bfn992_hvad_man_kan_hitte_paa/place_hytten.md` is created
- [x] `plays/bfn992_hvad_man_kan_hitte_paa/place_skoven.md` is created
- [x] `plays/bfn992_hvad_man_kan_hitte_paa/process_digtning.md` is created
- [x] `plays/bfn992_hvad_man_kan_hitte_paa/process_inspiration.md` is created
- [x] `plays/bfn992_hvad_man_kan_hitte_paa/plan_soegning.md` is created and linked to `persona_digter.md`
- [x] `plays/bfn992_hvad_man_kan_hitte_paa/plan_undervisning.md` is created and linked to `persona_kone.md`
- [x] `plays/bfn992_hvad_man_kan_hitte_paa/pitch_satirisk.md` is created
- [x] `plays/bfn992_hvad_man_kan_hitte_paa/plot_blokaden.md` is created and casts company elements
- [x] `plays/bfn992_hvad_man_kan_hitte_paa/plot_moedet.md` is created and casts company elements
- [x] `plays/bfn992_hvad_man_kan_hitte_paa/plot_paafundet.md` is created and casts company elements
- [x] The local validation tests (`npm test`) run successfully with zero errors
