---
khai: order
title: "Stage BFN 1011 Spoerg Amagermoer"
language: english
license: CC-BY-NC-SA-4.0
stamp:
  owner: KAI HACKS AI
  version: v0.0.1
  date: "2026-06-25"
---

# Order: Stage BFN 1011 Spoerg Amagermoer

## Direction

The house must stage BFN 1011 (_Spørg Amagermo'er!_) to establish the hundred and twenty-third production in the H.C. Andersen house. The production must model Guleroden (the old carrot) and Bruden (the young carrot bride), their positions (Bejler, Modvillig), the pieces representing the dew (Dug) and the soup tureen (Suppe), the environments of Amager and the garden (Haven), the processes of wedding (Vielse) and splitting (Revnen), their plans of marriage (Aegteskab) and liberation (Frigoerelse), the surrealist pitch, and the plots representing the vegetable wedding and the old carrot's dance and demise. It must be written in authentic Danish for all prose sections.

## Orders

1. The Playwright (Hans Christian Andersen) must author the play definition, the two personas, the two positions, the two pieces, the two places, the two processes, the two in-world plans, the pitch of Surrealistisk, and the two plots.
2. The Theatre Manager (Edvard Collin) must verify the local registry, ensure correct versioning, check formatting, and validate that the cast conforms to the canon.
3. The Roadie (Vilhelm Pedersen) must set the stage, verify the local test suite is green, and prepare the files for packaging.

## Implementation

The play files must be placed in `plays/bfn1011_spoerg_amagermoer/` and follow the house language policy:

- Structural elements and frontmatter in English.
- Narrative prose, projections, actions, shadows, tells, and staging notes in Danish.

## Targets

- [x] `plays/bfn1011_spoerg_amagermoer/play_spoerg_amagermoer.md` is created and lists the complete company
- [x] `plays/bfn1011_spoerg_amagermoer/persona_guleroden.md` is created and links to `position_bejler.md`
- [x] `plays/bfn1011_spoerg_amagermoer/persona_bruden.md` is created and links to `position_modvillig.md`
- [x] `plays/bfn1011_spoerg_amagermoer/position_bejler.md` is created
- [x] `plays/bfn1011_spoerg_amagermoer/position_modvillig.md` is created
- [x] `plays/bfn1011_spoerg_amagermoer/piece_dug.md` is created
- [x] `plays/bfn1011_spoerg_amagermoer/piece_suppe.md` is created
- [x] `plays/bfn1011_spoerg_amagermoer/place_amager.md` is created
- [x] `plays/bfn1011_spoerg_amagermoer/place_haven.md` is created
- [x] `plays/bfn1011_spoerg_amagermoer/process_vielse.md` is created
- [x] `plays/bfn1011_spoerg_amagermoer/process_revnen.md` is created
- [x] `plays/bfn1011_spoerg_amagermoer/plan_aegteskab.md` is created and linked to `persona_guleroden.md`
- [x] `plays/bfn1011_spoerg_amagermoer/plan_frigoerelse.md` is created and linked to `persona_bruden.md`
- [x] `plays/bfn1011_spoerg_amagermoer/pitch_surrealistisk.md` is created
- [x] `plays/bfn1011_spoerg_amagermoer/plot_brylluppet.md` is created and casts company elements
- [x] `plays/bfn1011_spoerg_amagermoer/plot_revnen.md` is created and casts company elements
- [x] The local validation tests (`npm test`) run successfully with zero errors
