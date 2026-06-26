---
khai: order
title: "Stage SDU 191 Danske Folkesagn"
language: english
license: CC-BY-NC-SA-4.0
stamp:
  owner: KAI HACKS AI
  version: v0.0.1
  date: "2026-06-26"
---

# Order: Stage SDU 191 Danske Folkesagn

## Direction

The house must stage SDU 191 (_Danske Folkesagn_) to establish a production in the H.C. Andersen house. The production must model fortaelleren, aamanden, the positions (samler, vaesen), the pieces (sagn, vand), the environments (danmark, aaen), the fortaelling and overlevering processes, and the plots representing sagnene and aaen. It must be written in authentic Danish for all prose sections.

## Orders

1. The Playwright (Hans Christian Andersen) must author the play definition, the 2 personas, the 2 positions, the 2 pieces, the 2 places, the 2 processes, the 1 in-world plans, the pitch of historisk, and the 2 plots.
2. The Theatre Manager (Edvard Collin) must verify the local registry, ensure correct versioning, check formatting, and validate that the cast conforms to the canon.
3. The Roadie (Vilhelm Pedersen) must set the stage, verify the local test suite is green, and prepare the files for packaging.

## Implementation

The play files must be placed in `plays/sdu191_danske_folkesagn/` and follow the house language policy:

- Structural elements and frontmatter in English.
- Narrative prose, projections, actions, shadows, tells, and staging notes in Danish.

## Targets

- [x] `plays/sdu191_danske_folkesagn/play_danske_folkesagn.md` is created and lists the complete company
- [x] `plays/sdu191_danske_folkesagn/persona_fortaelleren.md` is created and links to `position_samler.md`
- [x] `plays/sdu191_danske_folkesagn/persona_aamanden.md` is created and links to `position_vaesen.md`
- [x] `plays/sdu191_danske_folkesagn/position_samler.md` is created
- [x] `plays/sdu191_danske_folkesagn/position_vaesen.md` is created
- [x] `plays/sdu191_danske_folkesagn/piece_sagn.md` is created
- [x] `plays/sdu191_danske_folkesagn/piece_vand.md` is created
- [x] `plays/sdu191_danske_folkesagn/place_danmark.md` is created
- [x] `plays/sdu191_danske_folkesagn/place_aaen.md` is created
- [x] `plays/sdu191_danske_folkesagn/process_fortaelling.md` is created
- [x] `plays/sdu191_danske_folkesagn/process_overlevering.md` is created
- [x] `plays/sdu191_danske_folkesagn/plan_bevaring.md` is created and linked to `persona_fortaelleren.md`
- [x] `plays/sdu191_danske_folkesagn/pitch_historisk.md` is created
- [x] `plays/sdu191_danske_folkesagn/plot_sagnene.md` is created and casts company elements
- [x] `plays/sdu191_danske_folkesagn/plot_aaen.md` is created and casts company elements
- [x] The local validation tests (`npm test`) run successfully with zero errors
