---
khai: order
title: "Stage SDU 207 Kartoflerne"
language: english
license: CC-BY-NC-SA-4.0
stamp:
  owner: KAI HACKS AI
  version: v0.0.1
  date: "2026-06-26"
---

# Order: Stage SDU 207 Kartoflerne

## Direction

The house must stage SDU 207 (_Kartoflerne_) to establish a production in the H.C. Andersen house. The production must model kartoflen, kokken, the positions (vaekst, tilbereder), the pieces (jord, gryde), the environments (marken, koekkenet), the dyrkning and kogning processes, and the plots representing dyrkningen and koekkenet. It must be written in authentic Danish for all prose sections.

## Orders

1. The Playwright (Hans Christian Andersen) must author the play definition, the 2 personas, the 2 positions, the 2 pieces, the 2 places, the 2 processes, the 1 in-world plans, the pitch of folkelig, and the 2 plots.
2. The Theatre Manager (Edvard Collin) must verify the local registry, ensure correct versioning, check formatting, and validate that the cast conforms to the canon.
3. The Roadie (Vilhelm Pedersen) must set the stage, verify the local test suite is green, and prepare the files for packaging.

## Implementation

The play files must be placed in `plays/sdu207_kartoflerne/` and follow the house language policy:

- Structural elements and frontmatter in English.
- Narrative prose, projections, actions, shadows, tells, and staging notes in Danish.

## Targets

- [x] `plays/sdu207_kartoflerne/play_kartoflerne.md` is created and lists the complete company
- [x] `plays/sdu207_kartoflerne/persona_kartoflen.md` is created and links to `position_vaekst.md`
- [x] `plays/sdu207_kartoflerne/persona_kokken.md` is created and links to `position_tilbereder.md`
- [x] `plays/sdu207_kartoflerne/position_vaekst.md` is created
- [x] `plays/sdu207_kartoflerne/position_tilbereder.md` is created
- [x] `plays/sdu207_kartoflerne/piece_jord.md` is created
- [x] `plays/sdu207_kartoflerne/piece_gryde.md` is created
- [x] `plays/sdu207_kartoflerne/place_marken.md` is created
- [x] `plays/sdu207_kartoflerne/place_koekkenet.md` is created
- [x] `plays/sdu207_kartoflerne/process_dyrkning.md` is created
- [x] `plays/sdu207_kartoflerne/process_kogning.md` is created
- [x] `plays/sdu207_kartoflerne/plan_naering.md` is created and linked to `persona_kartoflen.md`
- [x] `plays/sdu207_kartoflerne/pitch_folkelig.md` is created
- [x] `plays/sdu207_kartoflerne/plot_dyrkningen.md` is created and casts company elements
- [x] `plays/sdu207_kartoflerne/plot_koekkenet.md` is created and casts company elements
- [x] The local validation tests (`npm test`) run successfully with zero errors
