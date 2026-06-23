---
khai: order
title: "Stage BFN 769 Pebersvendens Nathue"
language: english
license: CC-BY-NC-SA-4.0
stamp:
  owner: KAI HACKS AI
  version: v0.0.1
  date: "2026-06-23"
---

# Order: Stage BFN 769 Pebersvendens Nathue

## Direction

The house must stage BFN 769 (_Pebersvendens Nathue_) to establish the sixty-fifth production in the H.C. Andersen house. The production must model Anton, Skygge, the positions (Isoleret, Droemmende), the piece (Nathue), the environments (Kammer, Tyskland), the erindring and forsoemmelse processes, and the plots leading to their realization. It must be written in authentic Danish for all prose sections.

## Orders

1. The Playwright (Hans Christian Andersen) must author the play definition, the two personas, the two positions, the piece, the two places, the two processes, the two in-world plans, the pitch of Melankoli, and the four plots.
2. The Theatre Manager (Edvard Collin) must verify the local registry, ensure correct versioning, check formatting, and validate that the entire cast conforms to the canon.
3. The Roadie (Vilhelm Pedersen) must set the stage, verify the local test suite is green, and prepare the files for packaging.

## Implementation

The play files must be placed in `plays/bfn769_pebersvendens_nathue/` and follow the house language policy:

- Structural elements and frontmatter in English.
- Narrative prose, projections, actions, shadows, tells, and staging notes in Danish.

## Targets

- [x] `plays/bfn769_pebersvendens_nathue/play_pebersvendens_nathue.md` is created and lists the complete company
- [x] `plays/bfn769_pebersvendens_nathue/persona_anton.md` is created and links to `position_isoleret.md`
- [x] `plays/bfn769_pebersvendens_nathue/persona_skygge.md` is created and links to `position_droemmende.md`
- [x] `plays/bfn769_pebersvendens_nathue/position_isoleret.md` is created
- [x] `plays/bfn769_pebersvendens_nathue/position_droemmende.md` is created
- [x] `plays/bfn769_pebersvendens_nathue/piece_nathue.md` is created
- [x] `plays/bfn769_pebersvendens_nathue/place_kammer.md` is created
- [x] `plays/bfn769_pebersvendens_nathue/place_tyskland.md` is created
- [x] `plays/bfn769_pebersvendens_nathue/process_erindring.md` is created
- [x] `plays/bfn769_pebersvendens_nathue/process_forsoemmelse.md` is created
- [x] `plays/bfn769_pebersvendens_nathue/plan_hjemve.md` is created and linked to `persona_anton.md`
- [x] `plays/bfn769_pebersvendens_nathue/plan_pligt.md` is created and linked to `persona_anton.md`
- [x] `plays/bfn769_pebersvendens_nathue/pitch_melankoli.md` is created
- [x] `plays/bfn769_pebersvendens_nathue/plot_hverdag.md` is created and casts company elements
- [x] `plays/bfn769_pebersvendens_nathue/plot_droem.md` is created and casts company elements
- [x] `plays/bfn769_pebersvendens_nathue/plot_doed.md` is created and casts company elements
- [x] `plays/bfn769_pebersvendens_nathue/plot_eftermaele.md` is created and casts company elements
- [x] The local validation tests (`npm test`) run successfully with zero errors
