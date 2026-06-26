---
khai: order
title: "Stage BFN 296 Talismanen"
language: english
license: CC-BY-NC-SA-4.0
stamp:
  owner: KAI HACKS AI
  version: v0.0.1
  date: "2026-06-26"
---

# Order: Stage BFN 296 Talismanen

## Direction

The house must stage BFN 296 (_Talismanen_) to establish a production in the H.C. Andersen house. The production must model manden, konen, the positions (soegende, soegende), the pieces (talisman, ring), the environments (slottet, hytten), the soegen and indseelse processes, and the plots representing rejsen and hjemkomsten. It must be written in authentic Danish for all prose sections.

## Orders

1. The Playwright (Hans Christian Andersen) must author the play definition, the 2 personas, the 2 positions, the 2 pieces, the 2 places, the 2 processes, the 1 in-world plans, the pitch of moraliserende, and the 2 plots.
2. The Theatre Manager (Edvard Collin) must verify the local registry, ensure correct versioning, check formatting, and validate that the cast conforms to the canon.
3. The Roadie (Vilhelm Pedersen) must set the stage, verify the local test suite is green, and prepare the files for packaging.

## Implementation

The play files must be placed in `plays/bfn296_talismanen/` and follow the house language policy:

- Structural elements and frontmatter in English.
- Narrative prose, projections, actions, shadows, tells, and staging notes in Danish.

## Targets

- [x] `plays/bfn296_talismanen/play_talismanen.md` is created and lists the complete company
- [x] `plays/bfn296_talismanen/persona_manden.md` is created and links to `position_soegende.md`
- [x] `plays/bfn296_talismanen/persona_konen.md` is created and links to `position_soegende.md`
- [x] `plays/bfn296_talismanen/position_soegende.md` is created
- [x] `plays/bfn296_talismanen/position_soegende.md` is created
- [x] `plays/bfn296_talismanen/piece_talisman.md` is created
- [x] `plays/bfn296_talismanen/piece_ring.md` is created
- [x] `plays/bfn296_talismanen/place_slottet.md` is created
- [x] `plays/bfn296_talismanen/place_hytten.md` is created
- [x] `plays/bfn296_talismanen/process_soegen.md` is created
- [x] `plays/bfn296_talismanen/process_indseelse.md` is created
- [x] `plays/bfn296_talismanen/plan_lykke.md` is created and linked to `persona_manden.md`
- [x] `plays/bfn296_talismanen/pitch_moraliserende.md` is created
- [x] `plays/bfn296_talismanen/plot_rejsen.md` is created and casts company elements
- [x] `plays/bfn296_talismanen/plot_hjemkomsten.md` is created and casts company elements
- [x] The local validation tests (`npm test`) run successfully with zero errors
