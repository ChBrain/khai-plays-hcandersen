---
khai: order
title: "Stage BFN 638 Den sidste Perle"
language: english
license: CC-BY-NC-SA-4.0
stamp:
  owner: KAI HACKS AI
  version: v0.0.1
  date: "2026-06-23"
---

# Order: Stage BFN 638 Den sidste Perle

## Direction

The house must stage BFN 638 (_Den sidste Perle_) to establish the fifty-eighth production in the H.C. Andersen house. The production must model Engel, Moder, the positions (Vaernende, Lidende), the piece (Vugge), the environments (Stue, Himmel), the foedsel and sorg processes, and the plots leading to their realization. It must be written in authentic Danish for all prose sections.

## Orders

1. The Playwright (Hans Christian Andersen) must author the play definition, the two personas, the two positions, the piece, the two places, the two processes, the two in-world plans, the pitch of Andagt, and the four plots.
2. The Theatre Manager (Edvard Collin) must verify the local registry, ensure correct versioning, check formatting, and validate that the entire cast conforms to the canon.
3. The Roadie (Vilhelm Pedersen) must set the stage, verify the local test suite is green, and prepare the files for packaging.

## Implementation

The play files must be placed in `plays/bfn638_den_sidste_perle/` and follow the house language policy:

- Structural elements and frontmatter in English.
- Narrative prose, projections, actions, shadows, tells, and staging notes in Danish.

## Targets

- [x] `plays/bfn638_den_sidste_perle/play_den_sidste_perle.md` is created and lists the complete company
- [x] `plays/bfn638_den_sidste_perle/persona_engel.md` is created and links to `position_vaernende.md`
- [x] `plays/bfn638_den_sidste_perle/persona_moder.md` is created and links to `position_lidende.md`
- [x] `plays/bfn638_den_sidste_perle/position_vaernende.md` is created
- [x] `plays/bfn638_den_sidste_perle/position_lidende.md` is created
- [x] `plays/bfn638_den_sidste_perle/piece_vugge.md` is created
- [x] `plays/bfn638_den_sidste_perle/place_stue.md` is created
- [x] `plays/bfn638_den_sidste_perle/place_himmel.md` is created
- [x] `plays/bfn638_den_sidste_perle/process_foedsel.md` is created
- [x] `plays/bfn638_den_sidste_perle/process_sorg.md` is created
- [x] `plays/bfn638_den_sidste_perle/plan_velsignelse.md` is created and linked to `persona_engel.md`
- [x] `plays/bfn638_den_sidste_perle/plan_accept.md` is created and linked to `persona_moder.md`
- [x] `plays/bfn638_den_sidste_perle/pitch_andagt.md` is created
- [x] `plays/bfn638_den_sidste_perle/plot_foedsel.md` is created and casts company elements
- [x] `plays/bfn638_den_sidste_perle/plot_velsignelse.md` is created and casts company elements
- [x] `plays/bfn638_den_sidste_perle/plot_mangel.md` is created and casts company elements
- [x] `plays/bfn638_den_sidste_perle/plot_fuldendelse.md` is created and casts company elements
- [x] The local validation tests (`npm test`) run successfully with zero errors
