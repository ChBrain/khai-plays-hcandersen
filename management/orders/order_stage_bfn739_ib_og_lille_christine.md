---
khai: order
title: "Stage BFN 739 Ib og lille Christine"
language: english
license: CC-BY-NC-SA-4.0
stamp:
  owner: KAI HACKS AI
  version: v0.0.1
  date: "2026-06-26"
---

# Order: Stage BFN 739 Ib og lille Christine

## Direction

The house must stage BFN 739 (_Ib og lille Christine_) to establish a production in the H.C. Andersen house. The production must model ib, christine, spaadommen, the positions (trofast, ambitioes, skaebne), the pieces (tre_noedder, guldhjerte), the environments (skoven, koebenhavn), the skilsmisse and forloesning processes, and the plots representing barndommen and skaebnen. It must be written in authentic Danish for all prose sections.

## Orders

1. The Playwright (Hans Christian Andersen) must author the play definition, the 3 personas, the 3 positions, the 2 pieces, the 2 places, the 2 processes, the 2 in-world plans, the pitch of melankolsk, and the 2 plots.
2. The Theatre Manager (Edvard Collin) must verify the local registry, ensure correct versioning, check formatting, and validate that the cast conforms to the canon.
3. The Roadie (Vilhelm Pedersen) must set the stage, verify the local test suite is green, and prepare the files for packaging.

## Implementation

The play files must be placed in `plays/bfn739_ib_og_lille_christine/` and follow the house language policy:

- Structural elements and frontmatter in English.
- Narrative prose, projections, actions, shadows, tells, and staging notes in Danish.

## Targets

- [x] `plays/bfn739_ib_og_lille_christine/play_ib_og_lille_christine.md` is created and lists the complete company
- [x] `plays/bfn739_ib_og_lille_christine/persona_ib.md` is created and links to `position_trofast.md`
- [x] `plays/bfn739_ib_og_lille_christine/persona_christine.md` is created and links to `position_ambitioes.md`
- [x] `plays/bfn739_ib_og_lille_christine/persona_spaadommen.md` is created and links to `position_skaebne.md`
- [x] `plays/bfn739_ib_og_lille_christine/position_trofast.md` is created
- [x] `plays/bfn739_ib_og_lille_christine/position_ambitioes.md` is created
- [x] `plays/bfn739_ib_og_lille_christine/position_skaebne.md` is created
- [x] `plays/bfn739_ib_og_lille_christine/piece_tre_noedder.md` is created
- [x] `plays/bfn739_ib_og_lille_christine/piece_guldhjerte.md` is created
- [x] `plays/bfn739_ib_og_lille_christine/place_skoven.md` is created
- [x] `plays/bfn739_ib_og_lille_christine/place_koebenhavn.md` is created
- [x] `plays/bfn739_ib_og_lille_christine/process_skilsmisse.md` is created
- [x] `plays/bfn739_ib_og_lille_christine/process_forloesning.md` is created
- [x] `plays/bfn739_ib_og_lille_christine/plan_kaerlighed.md` is created and linked to `persona_ib.md`
- [x] `plays/bfn739_ib_og_lille_christine/plan_lykke.md` is created and linked to `persona_christine.md`
- [x] `plays/bfn739_ib_og_lille_christine/pitch_melankolsk.md` is created
- [x] `plays/bfn739_ib_og_lille_christine/plot_barndommen.md` is created and casts company elements
- [x] `plays/bfn739_ib_og_lille_christine/plot_skaebnen.md` is created and casts company elements
- [x] The local validation tests (`npm test`) run successfully with zero errors
