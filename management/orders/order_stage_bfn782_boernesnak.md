---
khai: order
title: "Stage BFN 782 Boernesnak"
language: english
license: CC-BY-NC-SA-4.0
stamp:
  owner: KAI HACKS AI
  version: v0.0.1
  date: "2026-06-23"
---

# Order: Stage BFN 782 Boernesnak

## Direction

The house must stage BFN 782 (_Børnesnak_) to establish the seventy-second production in the H.C. Andersen house. The production must model Rig_Pige, Fattig_Dreng, the positions (Privilegeret, Straebende), the piece (Ler), the environments (Sal, Gade), the eksklusion and skabelse processes, and the plots leading to their realization. It must be written in authentic Danish for all prose sections.

## Orders

1. The Playwright (Hans Christian Andersen) must author the play definition, the two personas, the two positions, the piece, the two places, the two processes, the two in-world plans, the pitch of Ironi, and the four plots.
2. The Theatre Manager (Edvard Collin) must verify the local registry, ensure correct versioning, check formatting, and validate that the entire cast conforms to the canon.
3. The Roadie (Vilhelm Pedersen) must set the stage, verify the local test suite is green, and prepare the files for packaging.

## Implementation

The play files must be placed in `plays/bfn782_boernesnak/` and follow the house language policy:

- Structural elements and frontmatter in English.
- Narrative prose, projections, actions, shadows, tells, and staging notes in Danish.

## Targets

- [x] `plays/bfn782_boernesnak/play_boernesnak.md` is created and lists the complete company
- [x] `plays/bfn782_boernesnak/persona_rig_pige.md` is created and links to `position_privilegeret.md`
- [x] `plays/bfn782_boernesnak/persona_fattig_dreng.md` is created and links to `position_straebende.md`
- [x] `plays/bfn782_boernesnak/position_privilegeret.md` is created
- [x] `plays/bfn782_boernesnak/position_straebende.md` is created
- [x] `plays/bfn782_boernesnak/piece_ler.md` is created
- [x] `plays/bfn782_boernesnak/place_sal.md` is created
- [x] `plays/bfn782_boernesnak/place_gade.md` is created
- [x] `plays/bfn782_boernesnak/process_eksklusion.md` is created
- [x] `plays/bfn782_boernesnak/process_skabelse.md` is created
- [x] `plays/bfn782_boernesnak/plan_selvforherligelse.md` is created and linked to `persona_rig_pige.md`
- [x] `plays/bfn782_boernesnak/plan_arbejde.md` is created and linked to `persona_fattig_dreng.md`
- [x] `plays/bfn782_boernesnak/pitch_ironi.md` is created
- [x] `plays/bfn782_boernesnak/plot_boernefesten.md` is created and casts company elements
- [x] `plays/bfn782_boernesnak/plot_udstoedelsen.md` is created and casts company elements
- [x] `plays/bfn782_boernesnak/plot_arbejdsaar.md` is created and casts company elements
- [x] `plays/bfn782_boernesnak/plot_triumf.md` is created and casts company elements
- [x] The local validation tests (`npm test`) run successfully with zero errors
