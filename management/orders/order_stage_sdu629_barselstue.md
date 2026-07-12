---
khai: order
title: "Stage SDU 629"
language: english
license: CC-BY-NC-SA-4.0
stamp:
  owner: KAI HACKS AI
  version: v0.0.1
  date: "2026-07-12"
---

# Order: Stage SDU 629

## Direction

The house must stage SDU 629 (_Den nye Barselstue_) to establish the twenty-ninth work in the "Drama" genre. The production must model the satirical, Holberg-style dialogues of Jespersen, Dr. Wendel, and Christine. It must model Jespersen's parlor room place, the manuscript piece representing _Den nye Romeo_, the processes representing the congratulatory visitations and the exposure of plagiarism, Jespersen's plan for literary fame, the satirical lystspil tone, and the three plots. All staging, prose, projections, actions, shadows, and tells must be authored in authentic Danish.

## Orders

1. The Playwright (Hans Christian Andersen) must author the play definition, the three personas (jespersen, wendel, christine), the three positions (plagiator, forfatter, soester), the one piece (manuskript), the one place (stue), the two processes (lykonskning, afsloering), the in-world plan (haeder), the pitch (holberg), and the three plots.
2. The Theatre Manager (Edvard Collin) must verify the local registry, ensure correct versioning, check formatting, and validate that the entire cast conforms to the canon.
3. The Roadie (Vilhelm Pedersen) must set the stage, verify the local test suite is green, and prepare the files for packaging.

## Implementation

The play files must be placed in `plays/sdu629_barselstue/` and follow the house language policy:

- Structural elements and frontmatter in English.
- Narrative prose, projections, actions, shadows, tells, and staging notes in Danish.

## Targets

- [x] `plays/sdu629_barselstue/play_barselstue.md` is created and lists the complete company
- [x] `plays/sdu629_barselstue/persona_jespersen.md` is created and links to `position_plagiator.md`
- [x] `plays/sdu629_barselstue/persona_wendel.md` is created and links to `position_forfatter.md`
- [x] `plays/sdu629_barselstue/persona_christine.md` is created and links to `position_soester.md`
- [x] `plays/sdu629_barselstue/position_plagiator.md` is created
- [x] `plays/sdu629_barselstue/position_forfatter.md` is created
- [x] `plays/sdu629_barselstue/position_soester.md` is created
- [x] `plays/sdu629_barselstue/piece_manuskript.md` is created
- [x] `plays/sdu629_barselstue/place_stue.md` is created
- [x] `plays/sdu629_barselstue/process_lykonskning.md` is created
- [x] `plays/sdu629_barselstue/process_afsloering.md` is created
- [x] `plays/sdu629_barselstue/plan_haeder.md` is created
- [x] `plays/sdu629_barselstue/pitch_holberg.md` is created
- [x] `plays/sdu629_barselstue/plot_barselsvisit.md` is created and casts company elements
- [x] `plays/sdu629_barselstue/plot_hjemkomst.md` is created and casts company elements
- [x] `plays/sdu629_barselstue/plot_forsoning.md` is created and casts company elements
- [x] The local validation tests (`npm test`) run successfully with zero errors
