---
khai: order
title: "Stage BFN 1007 Marionetspilleren"
language: english
license: CC-BY-NC-SA-4.0
stamp:
  owner: KAI HACKS AI
  version: v0.0.1
  date: "2026-06-26"
---

# Order: Stage BFN 1007 Marionetspilleren

## Direction

The house must stage BFN 1007 (_Marionetspilleren_) to establish a production in the H.C. Andersen house. The production must model spilleren, dukken, the positions (mester, levende), the pieces (marionet, teater), the environments (scenen, kufferten), the styring and frigoerelse processes, and the plots representing forestillingen and oproeret. It must be written in authentic Danish for all prose sections.

## Orders

1. The Playwright (Hans Christian Andersen) must author the play definition, the 2 personas, the 2 positions, the 2 pieces, the 2 places, the 2 processes, the 2 in-world plans, the pitch of satirisk, and the 2 plots.
2. The Theatre Manager (Edvard Collin) must verify the local registry, ensure correct versioning, check formatting, and validate that the cast conforms to the canon.
3. The Roadie (Vilhelm Pedersen) must set the stage, verify the local test suite is green, and prepare the files for packaging.

## Implementation

The play files must be placed in `plays/bfn1007_marionetspilleren/` and follow the house language policy:

- Structural elements and frontmatter in English.
- Narrative prose, projections, actions, shadows, tells, and staging notes in Danish.

## Targets

- [x] `plays/bfn1007_marionetspilleren/play__marionetspilleren.md` is created and lists the complete company
- [x] `plays/bfn1007_marionetspilleren/persona_spilleren.md` is created and links to `position_mester.md`
- [x] `plays/bfn1007_marionetspilleren/persona_dukken.md` is created and links to `position_levende.md`
- [x] `plays/bfn1007_marionetspilleren/position_mester.md` is created
- [x] `plays/bfn1007_marionetspilleren/position_levende.md` is created
- [x] `plays/bfn1007_marionetspilleren/piece_marionet.md` is created
- [x] `plays/bfn1007_marionetspilleren/piece_teater.md` is created
- [x] `plays/bfn1007_marionetspilleren/place_scenen.md` is created
- [x] `plays/bfn1007_marionetspilleren/place_kufferten.md` is created
- [x] `plays/bfn1007_marionetspilleren/process_styring.md` is created
- [x] `plays/bfn1007_marionetspilleren/process_frigoerelse.md` is created
- [x] `plays/bfn1007_marionetspilleren/plan_succes.md` is created and linked to `persona_spilleren.md`
- [x] `plays/bfn1007_marionetspilleren/plan_frihed.md` is created and linked to `persona_dukken.md`
- [x] `plays/bfn1007_marionetspilleren/pitch_satirisk.md` is created
- [x] `plays/bfn1007_marionetspilleren/plot_forestillingen.md` is created and casts company elements
- [x] `plays/bfn1007_marionetspilleren/plot_oproeret.md` is created and casts company elements
- [x] The local validation tests (`npm test`) run successfully with zero errors
