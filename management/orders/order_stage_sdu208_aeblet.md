---
khai: order
title: "Stage SDU 208 Æblet"
language: english
license: CC-BY-NC-SA-4.0
stamp:
  owner: KAI HACKS AI
  version: v0.0.1
  date: "2026-06-26"
---

# Order: Stage SDU 208 Æblet

## Direction

The house must stage SDU 208 (_Æblet_) to establish a production in the H.C. Andersen house. The production must model aeblet, vinden, the positions (frugt, naturkraft), the pieces (gren, have), the environments (traeet, haven), the modning and fald processes, and the plots representing modningen and faldet. It must be written in authentic Danish for all prose sections.

## Orders

1. The Playwright (Hans Christian Andersen) must author the play definition, the 2 personas, the 2 positions, the 2 pieces, the 2 places, the 2 processes, the 1 in-world plans, the pitch of poetisk, and the 2 plots.
2. The Theatre Manager (Edvard Collin) must verify the local registry, ensure correct versioning, check formatting, and validate that the cast conforms to the canon.
3. The Roadie (Vilhelm Pedersen) must set the stage, verify the local test suite is green, and prepare the files for packaging.

## Implementation

The play files must be placed in `plays/sdu208_aeblet/` and follow the house language policy:

- Structural elements and frontmatter in English.
- Narrative prose, projections, actions, shadows, tells, and staging notes in Danish.

## Targets

- [x] `plays/sdu208_aeblet/play_aeblet.md` is created and lists the complete company
- [x] `plays/sdu208_aeblet/persona_aeblet.md` is created and links to `position_frugt.md`
- [x] `plays/sdu208_aeblet/persona_vinden.md` is created and links to `position_naturkraft.md`
- [x] `plays/sdu208_aeblet/position_frugt.md` is created
- [x] `plays/sdu208_aeblet/position_naturkraft.md` is created
- [x] `plays/sdu208_aeblet/piece_gren.md` is created
- [x] `plays/sdu208_aeblet/piece_have.md` is created
- [x] `plays/sdu208_aeblet/place_traeet.md` is created
- [x] `plays/sdu208_aeblet/place_haven.md` is created
- [x] `plays/sdu208_aeblet/process_modning.md` is created
- [x] `plays/sdu208_aeblet/process_fald.md` is created
- [x] `plays/sdu208_aeblet/plan_forvandling.md` is created and linked to `persona_aeblet.md`
- [x] `plays/sdu208_aeblet/pitch_poetisk.md` is created
- [x] `plays/sdu208_aeblet/plot_modningen.md` is created and casts company elements
- [x] `plays/sdu208_aeblet/plot_faldet.md` is created and casts company elements
- [x] The local validation tests (`npm test`) run successfully with zero errors
