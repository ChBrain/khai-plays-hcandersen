---
khai: order
title: "Stage BFN 817 Skarnbassen"
language: english
license: CC-BY-NC-SA-4.0
stamp:
  owner: KAI HACKS AI
  version: v0.0.1
  date: "2026-06-24"
---

# Order: Stage BFN 817 Skarnbassen

## Direction

The house must stage BFN 817 (_Skarnbassen_) to establish the seventy-ninth production in the H.C. Andersen house. The production must model Skarnbasse, Kejserhest, the positions (Hovmodig, Indsigtsfuld), the piece (Guldsko), the environments (Stald, Have), the rejse and ydmygelse processes, and the plots leading to their realization. It must be written in authentic Danish for all prose sections.

## Orders

1. The Playwright (Hans Christian Andersen) must author the play definition, the two personas, the two positions, the piece, the two places, the two processes, the two in-world plans, the pitch of Satire, and the four plots.
2. The Theatre Manager (Edvard Collin) must verify the local registry, ensure correct versioning, check formatting, and validate that the entire cast conforms to the canon.
3. The Roadie (Vilhelm Pedersen) must set the stage, verify the local test suite is green, and prepare the files for packaging.

## Implementation

The play files must be placed in `plays/bfn817_skarnbassen/` and follow the house language policy:

- Structural elements and frontmatter in English.
- Narrative prose, projections, actions, shadows, tells, and staging notes in Danish.

## Targets

- [x] `plays/bfn817_skarnbassen/play_skarnbassen.md` is created and lists the complete company
- [x] `plays/bfn817_skarnbassen/persona_skarnbasse.md` is created and links to `position_hovmodig.md`
- [x] `plays/bfn817_skarnbassen/persona_kejserhest.md` is created and links to `position_indsigtsfuld.md`
- [x] `plays/bfn817_skarnbassen/position_hovmodig.md` is created
- [x] `plays/bfn817_skarnbassen/position_indsigtsfuld.md` is created
- [x] `plays/bfn817_skarnbassen/piece_guldsko.md` is created
- [x] `plays/bfn817_skarnbassen/place_stald.md` is created
- [x] `plays/bfn817_skarnbassen/place_have.md` is created
- [x] `plays/bfn817_skarnbassen/process_rejse.md` is created
- [x] `plays/bfn817_skarnbassen/process_ydmygelse.md` is created
- [x] `plays/bfn817_skarnbassen/plan_selvhaevelse.md` is created and linked to `persona_skarnbasse.md`
- [x] `plays/bfn817_skarnbassen/plan_tjeneste.md` is created and linked to `persona_kejserhest.md`
- [x] `plays/bfn817_skarnbassen/pitch_satire.md` is created
- [x] `plays/bfn817_skarnbassen/plot_afvisningen.md` is created and casts company elements
- [x] `plays/bfn817_skarnbassen/plot_udvandringen.md` is created and casts company elements
- [x] `plays/bfn817_skarnbassen/plot_modgangen.md` is created and casts company elements
- [x] `plays/bfn817_skarnbassen/plot_hjemkomsten.md` is created and casts company elements
- [x] The local validation tests (`npm test`) run successfully with zero errors
