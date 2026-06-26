---
khai: order
title: "Stage BFN 761 Klokkedybet"
language: english
license: CC-BY-NC-SA-4.0
stamp:
  owner: KAI HACKS AI
  version: v0.0.1
  date: "2026-06-26"
---

# Order: Stage BFN 761 Klokkedybet

## Direction

The house must stage BFN 761 (_Klokkedybet_) to establish a production in the H.C. Andersen house. The production must model aamanden, klokken, the positions (lyttende, klingende), the pieces (kirkeklokke, vand), the environments (odense_aa, taarnet), the klingning and historie processes, and the plots representing faldet and dybet. It must be written in authentic Danish for all prose sections.

## Orders

1. The Playwright (Hans Christian Andersen) must author the play definition, the 2 personas, the 2 positions, the 2 pieces, the 2 places, the 2 processes, the 2 in-world plans, the pitch of mystisk, and the 2 plots.
2. The Theatre Manager (Edvard Collin) must verify the local registry, ensure correct versioning, check formatting, and validate that the cast conforms to the canon.
3. The Roadie (Vilhelm Pedersen) must set the stage, verify the local test suite is green, and prepare the files for packaging.

## Implementation

The play files must be placed in `plays/bfn761_klokkedybet/` and follow the house language policy:

- Structural elements and frontmatter in English.
- Narrative prose, projections, actions, shadows, tells, and staging notes in Danish.

## Targets

- [x] `plays/bfn761_klokkedybet/play_klokkedybet.md` is created and lists the complete company
- [x] `plays/bfn761_klokkedybet/persona_aamanden.md` is created and links to `position_lyttende.md`
- [x] `plays/bfn761_klokkedybet/persona_klokken.md` is created and links to `position_klingende.md`
- [x] `plays/bfn761_klokkedybet/position_lyttende.md` is created
- [x] `plays/bfn761_klokkedybet/position_klingende.md` is created
- [x] `plays/bfn761_klokkedybet/piece_kirkeklokke.md` is created
- [x] `plays/bfn761_klokkedybet/piece_vand.md` is created
- [x] `plays/bfn761_klokkedybet/place_odense_aa.md` is created
- [x] `plays/bfn761_klokkedybet/place_taarnet.md` is created
- [x] `plays/bfn761_klokkedybet/process_klingning.md` is created
- [x] `plays/bfn761_klokkedybet/process_historie.md` is created
- [x] `plays/bfn761_klokkedybet/plan_erindring.md` is created and linked to `persona_klokken.md`
- [x] `plays/bfn761_klokkedybet/plan_tavshed.md` is created and linked to `persona_aamanden.md`
- [x] `plays/bfn761_klokkedybet/pitch_mystisk.md` is created
- [x] `plays/bfn761_klokkedybet/plot_faldet.md` is created and casts company elements
- [x] `plays/bfn761_klokkedybet/plot_dybet.md` is created and casts company elements
- [x] The local validation tests (`npm test`) run successfully with zero errors
