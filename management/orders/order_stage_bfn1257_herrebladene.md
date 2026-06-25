---
khai: order
title: "Stage BFN 1257 Herrebladene"
language: english
license: CC-BY-NC-SA-4.0
stamp:
  owner: KAI HACKS AI
  version: v0.0.1
  date: "2026-06-25"
---

# Order: Stage BFN 1257 Herrebladene

## Direction

The house must stage BFN 1257 (_Herrebladene_) to establish the hundred and twelfth production in the H.C. Andersen house. The production must model William, Hjerterknægt, and Konge, the positions (Legende, Hovmodig, Moraliserende), the pieces (Spilkort, Papirslot), the environments (Stue, Riddersal), the personificering and kritik processes, and the plots representing the castle, the cards coming to life, and the sermon on cleanliness. It must be written in authentic Danish for all prose sections.

## Orders

1. The Playwright (Hans Christian Andersen) must author the play definition, the three personas, the three positions, the two pieces, the two places, the two processes, the two in-world plans, the pitch of Hverdagsmoral, and the three plots.
2. The Theatre Manager (Edvard Collin) must verify the local registry, ensure correct versioning, check formatting, and validate that the cast conforms to the canon.
3. The Roadie (Vilhelm Pedersen) must set the stage, verify the local test suite is green, and prepare the files for packaging.

## Implementation

The play files must be placed in `plays/bfn1257_herrebladene/` and follow the house language policy:

- Structural elements and frontmatter in English.
- Narrative prose, projections, actions, shadows, tells, and staging notes in Danish.

## Targets

- [x] `plays/bfn1257_herrebladene/play_herrebladene.md` is created and lists the complete company
- [x] `plays/bfn1257_herrebladene/persona_william.md` is created and links to `position_legende.md`
- [x] `plays/bfn1257_herrebladene/persona_hjerterknaegt.md` is created and links to `position_moraliserende.md`
- [x] `plays/bfn1257_herrebladene/persona_konge.md` is created and links to `position_hovmodig.md`
- [x] `plays/bfn1257_herrebladene/position_legende.md` is created
- [x] `plays/bfn1257_herrebladene/position_hovmodig.md` is created
- [x] `plays/bfn1257_herrebladene/position_moraliserende.md` is created
- [x] `plays/bfn1257_herrebladene/piece_spilkort.md` is created
- [x] `plays/bfn1257_herrebladene/piece_papirslot.md` is created
- [x] `plays/bfn1257_herrebladene/place_stue.md` is created
- [x] `plays/bfn1257_herrebladene/place_riddersal.md` is created
- [x] `plays/bfn1257_herrebladene/process_personificering.md` is created
- [x] `plays/bfn1257_herrebladene/process_kritik.md` is created
- [x] `plays/bfn1257_herrebladene/plan_leg.md` is created and linked to `persona_william.md`
- [x] `plays/bfn1257_herrebladene/plan_moral.md` is created and linked to `persona_hjerterknaegt.md`
- [x] `plays/bfn1257_herrebladene/pitch_hverdagsmoral.md` is created
- [x] `plays/bfn1257_herrebladene/plot_slottet.md` is created and casts company elements
- [x] `plays/bfn1257_herrebladene/plot_livet.md` is created and casts company elements
- [x] `plays/bfn1257_herrebladene/plot_praeken.md` is created and casts company elements
- [x] The local validation tests (`npm test`) run successfully with zero errors
