---
khai: order
title: "Stage BFN 1259 Qvæk"
language: english
license: CC-BY-NC-SA-4.0
stamp:
  owner: KAI HACKS AI
  version: v0.0.1
  date: "2026-06-26"
---

# Order: Stage BFN 1259 Qvæk

## Direction

The house must stage BFN 1259 (_Qvæk_) to establish a production in the H.C. Andersen house. The production must model tudsen, drengen, the positions (sanger, iagttager), the pieces (mudder, sten), the environments (groften, vejen), the kvaekken and leg processes, and the plots representing groften and leg. It must be written in authentic Danish for all prose sections.

## Orders

1. The Playwright (Hans Christian Andersen) must author the play definition, the 2 personas, the 2 positions, the 2 pieces, the 2 places, the 2 processes, the 1 in-world plans, the pitch of satirisk, and the 2 plots.
2. The Theatre Manager (Edvard Collin) must verify the local registry, ensure correct versioning, check formatting, and validate that the cast conforms to the canon.
3. The Roadie (Vilhelm Pedersen) must set the stage, verify the local test suite is green, and prepare the files for packaging.

## Implementation

The play files must be placed in `plays/bfn1259_qvaek/` and follow the house language policy:

- Structural elements and frontmatter in English.
- Narrative prose, projections, actions, shadows, tells, and staging notes in Danish.

## Targets

- [x] `plays/bfn1259_qvaek/play_qvaek.md` is created and lists the complete company
- [x] `plays/bfn1259_qvaek/persona_tudsen.md` is created and links to `position_sanger.md`
- [x] `plays/bfn1259_qvaek/persona_drengen.md` is created and links to `position_iagttager.md`
- [x] `plays/bfn1259_qvaek/position_sanger.md` is created
- [x] `plays/bfn1259_qvaek/position_iagttager.md` is created
- [x] `plays/bfn1259_qvaek/piece_mudder.md` is created
- [x] `plays/bfn1259_qvaek/piece_sten.md` is created
- [x] `plays/bfn1259_qvaek/place_groften.md` is created
- [x] `plays/bfn1259_qvaek/place_vejen.md` is created
- [x] `plays/bfn1259_qvaek/process_kvaekken.md` is created
- [x] `plays/bfn1259_qvaek/process_leg.md` is created
- [x] `plays/bfn1259_qvaek/plan_overlevelse.md` is created and linked to `persona_tudsen.md`
- [x] `plays/bfn1259_qvaek/pitch_satirisk.md` is created
- [x] `plays/bfn1259_qvaek/plot_groften.md` is created and casts company elements
- [x] `plays/bfn1259_qvaek/plot_leg.md` is created and casts company elements
- [x] The local validation tests (`npm test`) run successfully with zero errors
