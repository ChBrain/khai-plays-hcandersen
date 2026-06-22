---
khai: order
title: "Stage BFN 606 Svanereden"
language: english
license: CC-BY-NC-SA-4.0
stamp:
  owner: KAI HACKS AI
  version: v0.0.1
  date: "2026-06-22"
---

# Order: Stage BFN 606 Svanereden

## Direction

The house must stage BFN 606 (_Svanereden_) to establish the fifty-first production in the H.C. Andersen house. The production must model Rede, Svaner, the positions (Moder, Flyver), the piece (Vingeslag), the environments (Hav, Himmel), the udklaekning and flyvning processes, and the plots leading to their realization. It must be written in authentic Danish for all prose sections.

## Orders

1. The Playwright (Hans Christian Andersen) must author the play definition, the two personas, the two positions, the piece, the two places, the two processes, the two in-world plans, the pitch of Heroisk, and the four plots.
2. The Theatre Manager (Edvard Collin) must verify the local registry, ensure correct versioning, check formatting, and validate that the entire cast conforms to the canon.
3. The Roadie (Vilhelm Pedersen) must set the stage, verify the local test suite is green, and prepare the files for packaging.

## Implementation

The play files must be placed in `plays/bfn606_svanereden/` and follow the house language policy:

- Structural elements and frontmatter in English.
- Narrative prose, projections, actions, shadows, tells, and staging notes in Danish.

## Targets

- [x] `plays/bfn606_svanereden/play_svanereden.md` is created and lists the complete company
- [x] `plays/bfn606_svanereden/persona_rede.md` is created and links to `position_moder.md`
- [x] `plays/bfn606_svanereden/persona_svaner.md` is created and links to `position_flyver.md`
- [x] `plays/bfn606_svanereden/position_moder.md` is created
- [x] `plays/bfn606_svanereden/position_flyver.md` is created
- [x] `plays/bfn606_svanereden/piece_vingeslag.md` is created
- [x] `plays/bfn606_svanereden/place_hav.md` is created
- [x] `plays/bfn606_svanereden/place_himmel.md` is created
- [x] `plays/bfn606_svanereden/process_udklaekning.md` is created
- [x] `plays/bfn606_svanereden/process_flyvning.md` is created
- [x] `plays/bfn606_svanereden/plan_bevaring.md` is created and linked to `persona_rede.md`
- [x] `plays/bfn606_svanereden/plan_verdensfaerd.md` is created and linked to `persona_svaner.md`
- [x] `plays/bfn606_svanereden/pitch_heroisk.md` is created
- [x] `plays/bfn606_svanereden/plot_reden.md` is created and casts company elements
- [x] `plays/bfn606_svanereden/plot_udklaekning.md` is created and casts company elements
- [x] `plays/bfn606_svanereden/plot_flugt.md` is created and casts company elements
- [x] `plays/bfn606_svanereden/plot_verdensnavn.md` is created and casts company elements
- [x] The local validation tests (`npm test`) run successfully with zero errors
