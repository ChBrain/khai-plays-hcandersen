---
khai: order
title: "Stage BFN 622 Hun duede ikke"
language: english
license: CC-BY-NC-SA-4.0
stamp:
  owner: KAI HACKS AI
  version: v0.0.1
  date: "2026-06-23"
---

# Order: Stage BFN 622 Hun duede ikke

## Direction

The house must stage BFN 622 (_Hun duede ikke_) to establish the sixtieth production in the H.C. Andersen house. The production must model Vaskekone, Borgmester, the positions (Traet, Doemmende), the piece (Snavsetoej), the environments (Aa, Kirke), the vask and dom processes, and the plots leading to their realization. It must be written in authentic Danish for all prose sections.

## Orders

1. The Playwright (Hans Christian Andersen) must author the play definition, the two personas, the two positions, the piece, the two places, the two processes, the two in-world plans, the pitch of Patos, and the four plots.
2. The Theatre Manager (Edvard Collin) must verify the local registry, ensure correct versioning, check formatting, and validate that the entire cast conforms to the canon.
3. The Roadie (Vilhelm Pedersen) must set the stage, verify the local test suite is green, and prepare the files for packaging.

## Implementation

The play files must be placed in `plays/bfn622_hun_duede_ikke/` and follow the house language policy:

- Structural elements and frontmatter in English.
- Narrative prose, projections, actions, shadows, tells, and staging notes in Danish.

## Targets

- [x] `plays/bfn622_hun_duede_ikke/play_hun_duede_ikke.md` is created and lists the complete company
- [x] `plays/bfn622_hun_duede_ikke/persona_vaskekone.md` is created and links to `position_traet.md`
- [x] `plays/bfn622_hun_duede_ikke/persona_borgmester.md` is created and links to `position_doemmende.md`
- [x] `plays/bfn622_hun_duede_ikke/position_traet.md` is created
- [x] `plays/bfn622_hun_duede_ikke/position_doemmende.md` is created
- [x] `plays/bfn622_hun_duede_ikke/piece_snavsetoej.md` is created
- [x] `plays/bfn622_hun_duede_ikke/place_aa.md` is created
- [x] `plays/bfn622_hun_duede_ikke/place_kirke.md` is created
- [x] `plays/bfn622_hun_duede_ikke/process_vask.md` is created
- [x] `plays/bfn622_hun_duede_ikke/process_dom.md` is created
- [x] `plays/bfn622_hun_duede_ikke/plan_overlevelse.md` is created and linked to `persona_vaskekone.md`
- [x] `plays/bfn622_hun_duede_ikke/plan_retfaerdiggoerelse.md` is created and linked to `persona_borgmester.md`
- [x] `plays/bfn622_hun_duede_ikke/pitch_patos.md` is created
- [x] `plays/bfn622_hun_duede_ikke/plot_slid.md` is created and casts company elements
- [x] `plays/bfn622_hun_duede_ikke/plot_dom.md` is created and casts company elements
- [x] `plays/bfn622_hun_duede_ikke/plot_doed.md` is created and casts company elements
- [x] `plays/bfn622_hun_duede_ikke/plot_dommedag.md` is created and casts company elements
- [x] The local validation tests (`npm test`) run successfully with zero errors
