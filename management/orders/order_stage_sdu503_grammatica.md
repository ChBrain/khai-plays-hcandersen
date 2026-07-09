---
khai: order
title: "Stage SDU 503"
language: english
license: CC-BY-NC-SA-4.0
stamp:
  owner: KAI HACKS AI
  version: v0.0.1
  date: "2026-07-09"
---

# Order: Stage SDU 503

## Direction

The house must stage SDU 503 (_Den skjønne Grammatica, eller Badens latinske Grammatik_) to establish the third work in the "Anden Prosa" genre. The production must model the personified Latin grammar, featuring Mama Nominativ, Genitiv, the beautiful Dativ, Akkusativ, Ablativ, Vokativ, and the active Løjtnant Amo. It must model the parlor, the syntax dictionary, the declension and conjugation processes, and the final union of verb and cases in a complete sentence. All staging, prose, projections, actions, shadows, and tells must be authored in authentic Danish.

## Orders

1. The Playwright (Hans Christian Andersen) must author the play definition, the three personas (Dativ, Amo, Nominativ), the two positions (kasus, verbum), the one piece (grammatikbogen), the two places (stuen, ordbogen), the two processes (deklinering, konjugering), the in-world plan (kaerlighed), the pitch (sentimental), and the three plots.
2. The Theatre Manager (Edvard Collin) must verify the local registry, ensure correct versioning, check formatting, and validate that the entire cast conforms to the canon.
3. The Roadie (Vilhelm Pedersen) must set the stage, verify the local test suite is green, and prepare the files for packaging.

## Implementation

The play files must be placed in `plays/sdu503_grammatica/` and follow the house language policy:

- Structural elements and frontmatter in English.
- Narrative prose, projections, actions, shadows, tells, and staging notes in Danish.

## Targets

- [x] `plays/sdu503_grammatica/play_grammatica.md` is created and lists the complete company
- [x] `plays/sdu503_grammatica/persona_dativ.md` is created and links to `position_kasus.md`
- [x] `plays/sdu503_grammatica/persona_amo.md` is created and links to `position_verbum.md`
- [x] `plays/sdu503_grammatica/persona_nominativ.md` is created and links to `position_kasus.md`
- [x] `plays/sdu503_grammatica/position_kasus.md` is created
- [x] `plays/sdu503_grammatica/position_verbum.md` is created
- [x] `plays/sdu503_grammatica/piece_grammatikbogen.md` is created
- [x] `plays/sdu503_grammatica/place_stuen.md` is created
- [x] `plays/sdu503_grammatica/place_ordbogen.md` is created
- [x] `plays/sdu503_grammatica/process_deklinering.md` is created
- [x] `plays/sdu503_grammatica/process_konjugering.md` is created
- [x] `plays/sdu503_grammatica/plan_kaerlighed.md` is created
- [x] `plays/sdu503_grammatica/pitch_sentimental.md` is created
- [x] `plays/sdu503_grammatica/plot_husspektaklet.md` is created and casts company elements
- [x] `plays/sdu503_grammatica/plot_staevnemoedet.md` is created and casts company elements
- [x] `plays/sdu503_grammatica/plot_saetningsbygningen.md` is created and casts company elements
- [x] The local validation tests (`npm test`) run successfully with zero errors
