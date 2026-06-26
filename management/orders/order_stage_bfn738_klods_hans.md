---
khai: order
title: "Stage BFN 738 Klods-Hans"
language: english
license: CC-BY-NC-SA-4.0
stamp:
  owner: KAI HACKS AI
  version: v0.0.1
  date: "2026-06-26"
---

# Order: Stage BFN 738 Klods-Hans

## Direction

The house must stage BFN 738 (_Klods-Hans_) to establish a production in the H.C. Andersen house. The production must model klods_hans, prinsessen, broedrene, the positions (spontan, vaelgende, studerede), the pieces (gedebuk, pludder, traesko), the environments (vejen, slottet), the bejlen and forbloeffelse processes, and the plots representing vejen_til_slottet and audiensen. It must be written in authentic Danish for all prose sections.

## Orders

1. The Playwright (Hans Christian Andersen) must author the play definition, the 3 personas, the 3 positions, the 3 pieces, the 2 places, the 2 processes, the 2 in-world plans, the pitch of humoristisk, and the 2 plots.
2. The Theatre Manager (Edvard Collin) must verify the local registry, ensure correct versioning, check formatting, and validate that the cast conforms to the canon.
3. The Roadie (Vilhelm Pedersen) must set the stage, verify the local test suite is green, and prepare the files for packaging.

## Implementation

The play files must be placed in `plays/bfn738_klods_hans/` and follow the house language policy:

- Structural elements and frontmatter in English.
- Narrative prose, projections, actions, shadows, tells, and staging notes in Danish.

## Targets

- [x] `plays/bfn738_klods_hans/play_klods_hans.md` is created and lists the complete company
- [x] `plays/bfn738_klods_hans/persona_klods_hans.md` is created and links to `position_spontan.md`
- [x] `plays/bfn738_klods_hans/persona_prinsessen.md` is created and links to `position_vaelgende.md`
- [x] `plays/bfn738_klods_hans/persona_broedrene.md` is created and links to `position_studerede.md`
- [x] `plays/bfn738_klods_hans/position_spontan.md` is created
- [x] `plays/bfn738_klods_hans/position_vaelgende.md` is created
- [x] `plays/bfn738_klods_hans/position_studerede.md` is created
- [x] `plays/bfn738_klods_hans/piece_gedebuk.md` is created
- [x] `plays/bfn738_klods_hans/piece_pludder.md` is created
- [x] `plays/bfn738_klods_hans/piece_traesko.md` is created
- [x] `plays/bfn738_klods_hans/place_vejen.md` is created
- [x] `plays/bfn738_klods_hans/place_slottet.md` is created
- [x] `plays/bfn738_klods_hans/process_bejlen.md` is created
- [x] `plays/bfn738_klods_hans/process_forbloeffelse.md` is created
- [x] `plays/bfn738_klods_hans/plan_lykke.md` is created and linked to `persona_klods_hans.md`
- [x] `plays/bfn738_klods_hans/plan_stolthed.md` is created and linked to `persona_broedrene.md`
- [x] `plays/bfn738_klods_hans/pitch_humoristisk.md` is created
- [x] `plays/bfn738_klods_hans/plot_vejen_til_slottet.md` is created and casts company elements
- [x] `plays/bfn738_klods_hans/plot_audiensen.md` is created and casts company elements
- [x] The local validation tests (`npm test`) run successfully with zero errors
