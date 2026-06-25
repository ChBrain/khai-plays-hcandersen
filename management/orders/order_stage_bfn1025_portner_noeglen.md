---
khai: order
title: "Stage BFN 1025 Portner Noeglen"
language: english
license: CC-BY-NC-SA-4.0
stamp:
  owner: KAI HACKS AI
  version: v0.0.1
  date: "2026-06-25"
---

# Order: Stage BFN 1025 Portner Noeglen

## Direction

The house must stage BFN 1025 (_Portner-nøglen_) to establish the hundred and twenty-eighth production in the H.C. Andersen house. The production must model Kammerraaden (the councilor) and Lene (Lotte-Lene, his wife), their positions (Soegende, Praktisk), the pieces representing the gate key (Portnoeglen) and the key's answers/guidance (Viser), the environments of the parlor (Stuen) and the street (Gaden), the processes of seeking/consultation (Snoeren) and wedding/marriage (Aegteskab), their plans of guidance (Vejledning) and domestic life (Huslighed), the ironic pitch, and the plots representing the consulting of the key and the councilor's wedding. It must be written in authentic Danish for all prose sections.

## Orders

1. The Playwright (Hans Christian Andersen) must author the play definition, the two personas, the two positions, the two pieces, the two places, the two processes, the two in-world plans, the pitch of Ironisk, and the two plots.
2. The Theatre Manager (Edvard Collin) must verify the local registry, ensure correct versioning, check formatting, and validate that the cast conforms to the canon.
3. The Roadie (Vilhelm Pedersen) must set the stage, verify the local test suite is green, and prepare the files for packaging.

## Implementation

The play files must be placed in `plays/bfn1025_portner_noeglen/` and follow the house language policy:

- Structural elements and frontmatter in English.
- Narrative prose, projections, actions, shadows, tells, and staging notes in Danish.

## Targets

- [x] `plays/bfn1025_portner_noeglen/play_portner_noeglen.md` is created and lists the complete company
- [x] `plays/bfn1025_portner_noeglen/persona_kammerraaden.md` is created and links to `position_soegende.md`
- [x] `plays/bfn1025_portner_noeglen/persona_lene.md` is created and links to `position_praktisk.md`
- [x] `plays/bfn1025_portner_noeglen/position_soegende.md` is created
- [x] `plays/bfn1025_portner_noeglen/position_praktisk.md` is created
- [x] `plays/bfn1025_portner_noeglen/piece_portnoeglen.md` is created
- [x] `plays/bfn1025_portner_noeglen/piece_viser.md` is created
- [x] `plays/bfn1025_portner_noeglen/place_stuen.md` is created
- [x] `plays/bfn1025_portner_noeglen/place_gaden.md` is created
- [x] `plays/bfn1025_portner_noeglen/process_snoeren.md` is created
- [x] `plays/bfn1025_portner_noeglen/process_aegteskab.md` is created
- [x] `plays/bfn1025_portner_noeglen/plan_vejledning.md` is created and linked to `persona_kammerraaden.md`
- [x] `plays/bfn1025_portner_noeglen/plan_huslighed.md` is created and linked to `persona_lene.md`
- [x] `plays/bfn1025_portner_noeglen/pitch_ironisk.md` is created
- [x] `plays/bfn1025_portner_noeglen/plot_snoeren.md` is created and casts company elements
- [x] `plays/bfn1025_portner_noeglen/plot_brylluppet.md` is created and casts company elements
- [x] The local validation tests (`npm test`) run successfully with zero errors
