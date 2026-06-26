---
khai: order
title: "Stage SDU 212 Hans og Grethe"
language: english
license: CC-BY-NC-SA-4.0
stamp:
  owner: KAI HACKS AI
  version: v0.0.1
  date: "2026-06-26"
---

# Order: Stage SDU 212 Hans og Grethe

## Direction

The house must stage SDU 212 (_Hans og Grethe_) to establish a production in the H.C. Andersen house. The production must model hans, grethe, the positions (broder, soester), the pieces (broedkrumme, hvid_sten), the environments (skoven, stien), the vandring and overlevelse processes, and the plots representing skoven and vejen. It must be written in authentic Danish for all prose sections.

## Orders

1. The Playwright (Hans Christian Andersen) must author the play definition, the 2 personas, the 2 positions, the 2 pieces, the 2 places, the 2 processes, the 1 in-world plans, the pitch of dramatisk, and the 2 plots.
2. The Theatre Manager (Edvard Collin) must verify the local registry, ensure correct versioning, check formatting, and validate that the cast conforms to the canon.
3. The Roadie (Vilhelm Pedersen) must set the stage, verify the local test suite is green, and prepare the files for packaging.

## Implementation

The play files must be placed in `plays/sdu212_hans_og_grethe/` and follow the house language policy:

- Structural elements and frontmatter in English.
- Narrative prose, projections, actions, shadows, tells, and staging notes in Danish.

## Targets

- [x] `plays/sdu212_hans_og_grethe/play_hans_og_grethe.md` is created and lists the complete company
- [x] `plays/sdu212_hans_og_grethe/persona_hans.md` is created and links to `position_broder.md`
- [x] `plays/sdu212_hans_og_grethe/persona_grethe.md` is created and links to `position_soester.md`
- [x] `plays/sdu212_hans_og_grethe/position_broder.md` is created
- [x] `plays/sdu212_hans_og_grethe/position_soester.md` is created
- [x] `plays/sdu212_hans_og_grethe/piece_broedkrumme.md` is created
- [x] `plays/sdu212_hans_og_grethe/piece_hvid_sten.md` is created
- [x] `plays/sdu212_hans_og_grethe/place_skoven.md` is created
- [x] `plays/sdu212_hans_og_grethe/place_stien.md` is created
- [x] `plays/sdu212_hans_og_grethe/process_vandring.md` is created
- [x] `plays/sdu212_hans_og_grethe/process_overlevelse.md` is created
- [x] `plays/sdu212_hans_og_grethe/plan_redning.md` is created and linked to `persona_hans.md`
- [x] `plays/sdu212_hans_og_grethe/pitch_dramatisk.md` is created
- [x] `plays/sdu212_hans_og_grethe/plot_skoven.md` is created and casts company elements
- [x] `plays/sdu212_hans_og_grethe/plot_vejen.md` is created and casts company elements
- [x] The local validation tests (`npm test`) run successfully with zero errors
