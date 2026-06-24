---
khai: order
title: "Stage BFN 890 Guldskat"
language: english
license: CC-BY-NC-SA-4.0
stamp:
  owner: KAI HACKS AI
  version: v0.0.1
  date: "2026-06-24"
---

# Order: Stage BFN 890 Guldskat

## Direction

The house must stage BFN 890 (_Guldskat_) to establish the ninety-seventh production in the H.C. Andersen house. The production must model Peter, Moder, the positions (Musiker, Kærlig), the piece (Tromme), the environments (Hjem, Krigsmark), the trommen and hjemkomst processes, and the plots leading to their realization. It must be written in authentic Danish for all prose sections.

## Orders

1. The Playwright (Hans Christian Andersen) must author the play definition, the two personas, the two positions, the piece, the two places, the two processes, the two in-world plans, the pitch of Hengivenhed, and the four plots.
2. The Theatre Manager (Edvard Collin) must verify the local registry, ensure correct versioning, check formatting, and validate that the cast conforms to the canon.
3. The Roadie (Vilhelm Pedersen) must set the stage, verify the local test suite is green, and prepare the files for packaging.

## Implementation

The play files must be placed in `plays/bfn890_guldskat/` and follow the house language policy:

- Structural elements and frontmatter in English.
- Narrative prose, projections, actions, shadows, tells, and staging notes in Danish.

## Targets

- [x] `plays/bfn890_guldskat/play_guldskat.md` is created and lists the complete company
- [x] `plays/bfn890_guldskat/persona_peter.md` is created and links to `position_musiker.md`
- [x] `plays/bfn890_guldskat/persona_moder.md` is created and links to `position_kaerlig.md`
- [x] `plays/bfn890_guldskat/position_musiker.md` is created
- [x] `plays/bfn890_guldskat/position_kaerlig.md` is created
- [x] `plays/bfn890_guldskat/piece_tromme.md` is created
- [x] `plays/bfn890_guldskat/place_hjem.md` is created
- [x] `plays/bfn890_guldskat/place_krigsmark.md` is created
- [x] `plays/bfn890_guldskat/process_trommen.md` is created
- [x] `plays/bfn890_guldskat/process_hjemkomst.md` is created
- [x] `plays/bfn890_guldskat/plan_krigstjeneste.md` is created and linked to `persona_peter.md`
- [x] `plays/bfn890_guldskat/plan_moders_boen.md` is created and linked to `persona_moder.md`
- [x] `plays/bfn890_guldskat/pitch_hengivenhed.md` is created
- [x] `plays/bfn890_guldskat/plot_barndommen.md` is created and casts company elements
- [x] `plays/bfn890_guldskat/plot_afrejsen.md` is created and casts company elements
- [x] `plays/bfn890_guldskat/plot_krigens_alvor.md` is created and casts company elements
- [x] `plays/bfn890_guldskat/plot_gensynet.md` is created and casts company elements
- [x] The local validation tests (`npm test`) run successfully with zero errors
