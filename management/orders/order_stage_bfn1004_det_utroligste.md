---
khai: order
title: "Stage BFN 1004 Det Utroligste"
language: english
license: CC-BY-NC-SA-4.0
stamp:
  owner: KAI HACKS AI
  version: v0.0.1
  date: "2026-06-25"
---

# Order: Stage BFN 1004 Det Utroligste

## Direction

The house must stage BFN 1004 (_Det Utroligste_) to establish the hundred and twenty-second production in the H.C. Andersen house. The production must model the tension between the creative force of Kunstneren and the destructive force of Kraftkarlen. It must model their positions (Skaber, Oedelaegger), the pieces representing the mechanical clock (Stueur) and the axe (Oekse), the environments of the exhibition hall (Salen) and the town (Byen), the processes of creation (Skabelse) and destruction (Destruktion), the plans of making art (Skaben) and historical/biblical memory (Hukommelse), the allegorical pitch, and the plots representing the exhibition contest and the destruction followed by the clock's spiritual triumph. It must be written in authentic Danish for all prose sections.

## Orders

1. The Playwright (Hans Christian Andersen) must author the play definition, the two personas, the two positions, the two pieces, the two places, the two processes, the two in-world plans, the pitch of Allegorisk, and the two plots.
2. The Theatre Manager (Edvard Collin) must verify the local registry, ensure correct versioning, check formatting, and validate that the cast conforms to the canon.
3. The Roadie (Vilhelm Pedersen) must set the stage, verify the local test suite is green, and prepare the files for packaging.

## Implementation

The play files must be placed in `plays/bfn1004_det_utroligste/` and follow the house language policy:

- Structural elements and frontmatter in English.
- Narrative prose, projections, actions, shadows, tells, and staging notes in Danish.

## Targets

- [x] `plays/bfn1004_det_utroligste/play_det_utroligste.md` is created and lists the complete company
- [x] `plays/bfn1004_det_utroligste/persona_kunstneren.md` is created and links to `position_skaber.md`
- [x] `plays/bfn1004_det_utroligste/persona_kraftkarlen.md` is created and links to `position_oedelaegger.md`
- [x] `plays/bfn1004_det_utroligste/position_skaber.md` is created
- [x] `plays/bfn1004_det_utroligste/position_oedelaegger.md` is created
- [x] `plays/bfn1004_det_utroligste/piece_stueur.md` is created
- [x] `plays/bfn1004_det_utroligste/piece_oekse.md` is created
- [x] `plays/bfn1004_det_utroligste/place_salen.md` is created
- [x] `plays/bfn1004_det_utroligste/place_byen.md` is created
- [x] `plays/bfn1004_det_utroligste/process_skabelse.md` is created
- [x] `plays/bfn1004_det_utroligste/process_destruktion.md` is created
- [x] `plays/bfn1004_det_utroligste/plan_skaben.md` is created and linked to `persona_kunstneren.md`
- [x] `plays/bfn1004_det_utroligste/plan_hukommelse.md` is created and linked to `persona_kunstneren.md`
- [x] `plays/bfn1004_det_utroligste/pitch_allegorisk.md` is created
- [x] `plays/bfn1004_det_utroligste/plot_konkurrencen.md` is created and casts company elements
- [x] `plays/bfn1004_det_utroligste/plot_oedelaeggelsen.md` is created and casts company elements
- [x] The local validation tests (`npm test`) run successfully with zero errors
