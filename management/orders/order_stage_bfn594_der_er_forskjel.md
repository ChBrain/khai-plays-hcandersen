---
khai: order
title: "Stage BFN 594 Der er Forskjel"
language: english
license: CC-BY-NC-SA-4.0
stamp:
  owner: KAI HACKS AI
  version: v0.0.1
  date: "2026-06-26"
---

# Order: Stage BFN 594 Der er Forskjel

## Direction

The house must stage BFN 594 (_"Der er Forskjel"_) to establish a production in the H.C. Andersen house. The production must model aeblegrenen, maelkeboetten, the positions (stolt, ydmyg), the pieces (vase, solstraale), the environments (stuen, groften), the vaerdisaettelse and erkendelse processes, and the plots representing vasen and erkendelsen. It must be written in authentic Danish for all prose sections.

## Orders

1. The Playwright (Hans Christian Andersen) must author the play definition, the 2 personas, the 2 positions, the 2 pieces, the 2 places, the 2 processes, the 2 in-world plans, the pitch of moraliserende, and the 2 plots.
2. The Theatre Manager (Edvard Collin) must verify the local registry, ensure correct versioning, check formatting, and validate that the cast conforms to the canon.
3. The Roadie (Vilhelm Pedersen) must set the stage, verify the local test suite is green, and prepare the files for packaging.

## Implementation

The play files must be placed in `plays/bfn594_der_er_forskjel/` and follow the house language policy:

- Structural elements and frontmatter in English.
- Narrative prose, projections, actions, shadows, tells, and staging notes in Danish.

## Targets

- [x] `plays/bfn594_der_er_forskjel/play_der_er_forskjel.md` is created and lists the complete company
- [x] `plays/bfn594_der_er_forskjel/persona_aeblegrenen.md` is created and links to `position_stolt.md`
- [x] `plays/bfn594_der_er_forskjel/persona_maelkeboetten.md` is created and links to `position_ydmyg.md`
- [x] `plays/bfn594_der_er_forskjel/position_stolt.md` is created
- [x] `plays/bfn594_der_er_forskjel/position_ydmyg.md` is created
- [x] `plays/bfn594_der_er_forskjel/piece_vase.md` is created
- [x] `plays/bfn594_der_er_forskjel/piece_solstraale.md` is created
- [x] `plays/bfn594_der_er_forskjel/place_stuen.md` is created
- [x] `plays/bfn594_der_er_forskjel/place_groften.md` is created
- [x] `plays/bfn594_der_er_forskjel/process_vaerdisaettelse.md` is created
- [x] `plays/bfn594_der_er_forskjel/process_erkendelse.md` is created
- [x] `plays/bfn594_der_er_forskjel/plan_pragt.md` is created and linked to `persona_aeblegrenen.md`
- [x] `plays/bfn594_der_er_forskjel/plan_livskraft.md` is created and linked to `persona_maelkeboetten.md`
- [x] `plays/bfn594_der_er_forskjel/pitch_moraliserende.md` is created
- [x] `plays/bfn594_der_er_forskjel/plot_vasen.md` is created and casts company elements
- [x] `plays/bfn594_der_er_forskjel/plot_erkendelsen.md` is created and casts company elements
- [x] The local validation tests (`npm test`) run successfully with zero errors
