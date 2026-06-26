---
khai: order
title: "Stage BFN 162 Alferne paa Heden"
language: english
license: CC-BY-NC-SA-4.0
stamp:
  owner: KAI HACKS AI
  version: v0.0.1
  date: "2026-06-26"
---

# Order: Stage BFN 162 Alferne paa Heden

## Direction

The house must stage BFN 162 (_Alferne paa Heden_) to establish a production in the H.C. Andersen house. The production must model alfekongen, hyrden, the positions (leder, iagttager), the pieces (dugperler, floejte), the environments (heden, hyrdehuset), the dans and beskyttelse processes, and the plots representing natten and moerke. It must be written in authentic Danish for all prose sections.

## Orders

1. The Playwright (Hans Christian Andersen) must author the play definition, the 2 personas, the 2 positions, the 2 pieces, the 2 places, the 2 processes, the 1 in-world plans, the pitch of poetisk, and the 2 plots.
2. The Theatre Manager (Edvard Collin) must verify the local registry, ensure correct versioning, check formatting, and validate that the cast conforms to the canon.
3. The Roadie (Vilhelm Pedersen) must set the stage, verify the local test suite is green, and prepare the files for packaging.

## Implementation

The play files must be placed in `plays/bfn162_alferne_paa_heden/` and follow the house language policy:

- Structural elements and frontmatter in English.
- Narrative prose, projections, actions, shadows, tells, and staging notes in Danish.

## Targets

- [x] `plays/bfn162_alferne_paa_heden/play_alferne_paa_heden.md` is created and lists the complete company
- [x] `plays/bfn162_alferne_paa_heden/persona_alfekongen.md` is created and links to `position_leder.md`
- [x] `plays/bfn162_alferne_paa_heden/persona_hyrden.md` is created and links to `position_iagttager.md`
- [x] `plays/bfn162_alferne_paa_heden/position_leder.md` is created
- [x] `plays/bfn162_alferne_paa_heden/position_iagttager.md` is created
- [x] `plays/bfn162_alferne_paa_heden/piece_dugperler.md` is created
- [x] `plays/bfn162_alferne_paa_heden/piece_floejte.md` is created
- [x] `plays/bfn162_alferne_paa_heden/place_heden.md` is created
- [x] `plays/bfn162_alferne_paa_heden/place_hyrdehuset.md` is created
- [x] `plays/bfn162_alferne_paa_heden/process_dans.md` is created
- [x] `plays/bfn162_alferne_paa_heden/process_beskyttelse.md` is created
- [x] `plays/bfn162_alferne_paa_heden/plan_dans.md` is created and linked to `persona_alfekongen.md`
- [x] `plays/bfn162_alferne_paa_heden/pitch_poetisk.md` is created
- [x] `plays/bfn162_alferne_paa_heden/plot_natten.md` is created and casts company elements
- [x] `plays/bfn162_alferne_paa_heden/plot_moerke.md` is created and casts company elements
- [x] The local validation tests (`npm test`) run successfully with zero errors
