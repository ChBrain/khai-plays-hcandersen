---
khai: order
title: "Stage BFN 985 Lykken kan ligge i en Pind"
language: english
license: CC-BY-NC-SA-4.0
stamp:
  owner: KAI HACKS AI
  version: v0.0.1
  date: "2026-06-25"
---

# Order: Stage BFN 985 Lykken kan ligge i en Pind

## Direction

The house must stage BFN 985 (_Lykken kan ligge i en Pind_) to establish the hundred and thirteenth production in the H.C. Andersen house. The production must model Drejer and Kone, the positions (Flittig, Støttende, Lykkelig), the pieces (Pæretræ, Pind), the environments (Værksted, Haven), the drejning and berigelse processes, and the plots representing the storm, the crafting of umbrella pins, and finding luck in a simple peg. It must be written in authentic Danish for all prose sections.

## Orders

1. The Playwright (Hans Christian Andersen) must author the play definition, the two personas, the three positions, the two pieces, the two places, the two processes, the two in-world plans, the pitch of Nøjsomhed, and the three plots.
2. The Theatre Manager (Edvard Collin) must verify the local registry, ensure correct versioning, check formatting, and validate that the cast conforms to the canon.
3. The Roadie (Vilhelm Pedersen) must set the stage, verify the local test suite is green, and prepare the files for packaging.

## Implementation

The play files must be placed in `plays/bfn985_lykken_kan_ligge_i_en_pind/` and follow the house language policy:

- Structural elements and frontmatter in English.
- Narrative prose, projections, actions, shadows, tells, and staging notes in Danish.

## Targets

- [x] `plays/bfn985_lykken_kan_ligge_i_en_pind/play_lykken_kan_ligge_i_en_pind.md` is created and lists the complete company
- [x] `plays/bfn985_lykken_kan_ligge_i_en_pind/persona_drejer.md` is created and links to `position_flittig.md`
- [x] `plays/bfn985_lykken_kan_ligge_i_en_pind/persona_kone.md` is created and links to `position_stoettende.md`
- [x] `plays/bfn985_lykken_kan_ligge_i_en_pind/position_flittig.md` is created
- [x] `plays/bfn985_lykken_kan_ligge_i_en_pind/position_stoettende.md` is created
- [x] `plays/bfn985_lykken_kan_ligge_i_en_pind/position_lykkelig.md` is created
- [x] `plays/bfn985_lykken_kan_ligge_i_en_pind/piece_paeretaer.md` is created
- [x] `plays/bfn985_lykken_kan_ligge_i_en_pind/piece_pind.md` is created
- [x] `plays/bfn985_lykken_kan_ligge_i_en_pind/place_vaerksted.md` is created
- [x] `plays/bfn985_lykken_kan_ligge_i_en_pind/place_haven.md` is created
- [x] `plays/bfn985_lykken_kan_ligge_i_en_pind/process_drejning.md` is created
- [x] `plays/bfn985_lykken_kan_ligge_i_en_pind/process_berigelse.md` is created
- [x] `plays/bfn985_lykken_kan_ligge_i_en_pind/plan_overlevelse.md` is created and linked to `persona_drejer.md`
- [x] `plays/bfn985_lykken_kan_ligge_i_en_pind/plan_opfindsomhed.md` is created and linked to `persona_drejer.md`
- [x] `plays/bfn985_lykken_kan_ligge_i_en_pind/pitch_nojsomhed.md` is created
- [x] `plays/bfn985_lykken_kan_ligge_i_en_pind/plot_stormen.md` is created and casts company elements
- [x] `plays/bfn985_lykken_kan_ligge_i_en_pind/plot_drejningen.md` is created and casts company elements
- [x] `plays/bfn985_lykken_kan_ligge_i_en_pind/plot_lykken.md` is created and casts company elements
- [x] The local validation tests (`npm test`) run successfully with zero errors
