---
khai: order
title: "Stage BFN 772 ABC-Bogen"
language: english
license: CC-BY-NC-SA-4.0
stamp:
  owner: KAI HACKS AI
  version: v0.0.1
  date: "2026-06-26"
---

# Order: Stage BFN 772 ABC-Bogen

## Direction

The house must stage BFN 772 (_ABC-Bogen_) to establish a production in the H.C. Andersen house. The production must model a, b, c, the positions (foerste, mellemliggende, sidste), the pieces (abc_bog, blaek), the environments (skolestuen, skuffen), the stavning and strid processes, and the plots representing striden and samarbejdet. It must be written in authentic Danish for all prose sections.

## Orders

1. The Playwright (Hans Christian Andersen) must author the play definition, the 3 personas, the 3 positions, the 2 pieces, the 2 places, the 2 processes, the 2 in-world plans, the pitch of laererik, and the 2 plots.
2. The Theatre Manager (Edvard Collin) must verify the local registry, ensure correct versioning, check formatting, and validate that the cast conforms to the canon.
3. The Roadie (Vilhelm Pedersen) must set the stage, verify the local test suite is green, and prepare the files for packaging.

## Implementation

The play files must be placed in `plays/bfn772_abc_bogen/` and follow the house language policy:

- Structural elements and frontmatter in English.
- Narrative prose, projections, actions, shadows, tells, and staging notes in Danish.

## Targets

- [x] `plays/bfn772_abc_bogen/play_abc_bogen.md` is created and lists the complete company
- [x] `plays/bfn772_abc_bogen/persona_a.md` is created and links to `position_foerste.md`
- [x] `plays/bfn772_abc_bogen/persona_b.md` is created and links to `position_mellemliggende.md`
- [x] `plays/bfn772_abc_bogen/persona_c.md` is created and links to `position_sidste.md`
- [x] `plays/bfn772_abc_bogen/position_foerste.md` is created
- [x] `plays/bfn772_abc_bogen/position_mellemliggende.md` is created
- [x] `plays/bfn772_abc_bogen/position_sidste.md` is created
- [x] `plays/bfn772_abc_bogen/piece_abc_bog.md` is created
- [x] `plays/bfn772_abc_bogen/piece_blaek.md` is created
- [x] `plays/bfn772_abc_bogen/place_skolestuen.md` is created
- [x] `plays/bfn772_abc_bogen/place_skuffen.md` is created
- [x] `plays/bfn772_abc_bogen/process_stavning.md` is created
- [x] `plays/bfn772_abc_bogen/process_strid.md` is created
- [x] `plays/bfn772_abc_bogen/plan_magt.md` is created and linked to `persona_a.md`
- [x] `plays/bfn772_abc_bogen/plan_orden.md` is created and linked to `persona_a.md`
- [x] `plays/bfn772_abc_bogen/pitch_laererik.md` is created
- [x] `plays/bfn772_abc_bogen/plot_striden.md` is created and casts company elements
- [x] `plays/bfn772_abc_bogen/plot_samarbejdet.md` is created and casts company elements
- [x] The local validation tests (`npm test`) run successfully with zero errors
