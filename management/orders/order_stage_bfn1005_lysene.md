---
khai: order
title: "Stage BFN 1005 Lysene"
language: english
license: CC-BY-NC-SA-4.0
stamp:
  owner: KAI HACKS AI
  version: v0.0.1
  date: "2026-06-25"
---

# Order: Stage BFN 1005 Lysene

## Direction

The house must stage BFN 1005 (_Lysene_) to establish the hundred and twentieth production in the H.C. Andersen house. The production must model the comparison of the two candles, Vokslyset and Tællelyset. It must model their positions (Stolt, Taknemmelig), the pieces representing the chandelier (Lysekrone) and the small candle holder (Stump), the environments of the parlor (Stuen) and the cottage (Hytten), the processes of burning/illumination (Belysning) and social differentiation (Forskel), their plans of boasting (Pral) and spreading joy (Glaede), the moralizing pitch, and the plots representing each candle's service. It must be written in authentic Danish for all prose sections.

## Orders

1. The Playwright (Hans Christian Andersen) must author the play definition, the two personas, the two positions, the two pieces, the two places, the two processes, the two in-world plans, the pitch of Moraliserende, and the two plots.
2. The Theatre Manager (Edvard Collin) must verify the local registry, ensure correct versioning, check formatting, and validate that the cast conforms to the canon.
3. The Roadie (Vilhelm Pedersen) must set the stage, verify the local test suite is green, and prepare the files for packaging.

## Implementation

The play files must be placed in `plays/bfn1005_lysene/` and follow the house language policy:

- Structural elements and frontmatter in English.
- Narrative prose, projections, actions, shadows, tells, and staging notes in Danish.

## Targets

- [x] `plays/bfn1005_lysene/play_lysene.md` is created and lists the complete company
- [x] `plays/bfn1005_lysene/persona_vokslyset.md` is created and links to `position_stolt.md`
- [x] `plays/bfn1005_lysene/persona_taellelyset.md` is created and links to `position_taknemmelig.md`
- [x] `plays/bfn1005_lysene/position_stolt.md` is created
- [x] `plays/bfn1005_lysene/position_taknemmelig.md` is created
- [x] `plays/bfn1005_lysene/piece_lysekrone.md` is created
- [x] `plays/bfn1005_lysene/piece_stump.md` is created
- [x] `plays/bfn1005_lysene/place_stuen.md` is created
- [x] `plays/bfn1005_lysene/place_hytten.md` is created
- [x] `plays/bfn1005_lysene/process_belysning.md` is created
- [x] `plays/bfn1005_lysene/process_forskel.md` is created
- [x] `plays/bfn1005_lysene/plan_pral.md` is created and linked to `persona_vokslyset.md`
- [x] `plays/bfn1005_lysene/plan_glaede.md` is created and linked to `persona_taellelyset.md`
- [x] `plays/bfn1005_lysene/pitch_moraliserende.md` is created
- [x] `plays/bfn1005_lysene/plot_vokslyset.md` is created and casts company elements
- [x] `plays/bfn1005_lysene/plot_taellelyset.md` is created and casts company elements
- [x] The local validation tests (`npm test`) run successfully with zero errors
