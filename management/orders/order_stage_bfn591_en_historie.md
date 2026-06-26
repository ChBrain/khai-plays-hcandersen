---
khai: order
title: "Stage BFN 591 En Historie"
language: english
license: CC-BY-NC-SA-4.0
stamp:
  owner: KAI HACKS AI
  version: v0.0.1
  date: "2026-06-26"
---

# Order: Stage BFN 591 En Historie

## Direction

The house must stage BFN 591 (_En Historie_) to establish a production in the H.C. Andersen house. The production must model digteren, verden, the positions (soegende, dommer), the pieces (skrift, lys), the environments (kammeret, markedet), the sogning and afsløring processes, and the plots representing skabelsen and dommen. It must be written in authentic Danish for all prose sections.

## Orders

1. The Playwright (Hans Christian Andersen) must author the play definition, the 2 personas, the 2 positions, the 2 pieces, the 2 places, the 2 processes, the 2 in-world plans, the pitch of filosofisk, and the 2 plots.
2. The Theatre Manager (Edvard Collin) must verify the local registry, ensure correct versioning, check formatting, and validate that the cast conforms to the canon.
3. The Roadie (Vilhelm Pedersen) must set the stage, verify the local test suite is green, and prepare the files for packaging.

## Implementation

The play files must be placed in `plays/bfn591_en_historie/` and follow the house language policy:

- Structural elements and frontmatter in English.
- Narrative prose, projections, actions, shadows, tells, and staging notes in Danish.

## Targets

- [x] `plays/bfn591_en_historie/play_en_historie.md` is created and lists the complete company
- [x] `plays/bfn591_en_historie/persona_digteren.md` is created and links to `position_soegende.md`
- [x] `plays/bfn591_en_historie/persona_verden.md` is created and links to `position_dommer.md`
- [x] `plays/bfn591_en_historie/position_soegende.md` is created
- [x] `plays/bfn591_en_historie/position_dommer.md` is created
- [x] `plays/bfn591_en_historie/piece_skrift.md` is created
- [x] `plays/bfn591_en_historie/piece_lys.md` is created
- [x] `plays/bfn591_en_historie/place_kammeret.md` is created
- [x] `plays/bfn591_en_historie/place_markedet.md` is created
- [x] `plays/bfn591_en_historie/process_sogning.md` is created
- [x] `plays/bfn591_en_historie/process_afsløring.md` is created
- [x] `plays/bfn591_en_historie/plan_sandhed.md` is created and linked to `persona_digteren.md`
- [x] `plays/bfn591_en_historie/plan_anerkendelse.md` is created and linked to `persona_digteren.md`
- [x] `plays/bfn591_en_historie/pitch_filosofisk.md` is created
- [x] `plays/bfn591_en_historie/plot_skabelsen.md` is created and casts company elements
- [x] `plays/bfn591_en_historie/plot_dommen.md` is created and casts company elements
- [x] The local validation tests (`npm test`) run successfully with zero errors
