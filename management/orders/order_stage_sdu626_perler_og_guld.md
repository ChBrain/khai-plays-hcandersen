---
khai: order
title: "Stage SDU 626"
language: english
license: CC-BY-NC-SA-4.0
stamp:
  owner: KAI HACKS AI
  version: v0.0.1
  date: "2026-07-11"
---

# Order: Stage SDU 626

## Direction

The house must stage SDU 626 (_Meer end Perler og Guld_) to establish the twenty-sixth work in the "Drama" genre. The production must model the fantastical, comedic dialogues of the Åndernes Konge, Elimar, Henrik, and Anna. It must model the Spirit Temple, the hot-air balloon piece, the processes representing the journey between realms and the search for truth, Elimar's quest plan, the playful eventyrkomedie tone, and the three plots. All staging, prose, projections, actions, shadows, and tells must be authored in authentic Danish.

## Orders

1. The Playwright (Hans Christian Andersen) must author the play definition, the three personas (konge, elimar, henrik, anna), the three positions (hersker, eventyr, tjener, sandhed), the one piece (ballon), the one place (aandetempel), the two processes (rejse, gaade), the in-world plan (statue), the pitch (komedie), and the three plots.
2. The Theatre Manager (Edvard Collin) must verify the local registry, ensure correct versioning, check formatting, and validate that the entire cast conforms to the canon.
3. The Roadie (Vilhelm Pedersen) must set the stage, verify the local test suite is green, and prepare the files for packaging.

## Implementation

The play files must be placed in `plays/sdu626_perler_og_guld/` and follow the house language policy:

- Structural elements and frontmatter in English.
- Narrative prose, projections, actions, shadows, tells, and staging notes in Danish.

## Targets

- [x] `plays/sdu626_perler_og_guld/play_perler_og_guld.md` is created and lists the complete company
- [x] `plays/sdu626_perler_og_guld/persona_konge.md` is created and links to `position_hersker.md`
- [x] `plays/sdu626_perler_og_guld/persona_elimar.md` is created and links to `position_eventyr.md`
- [x] `plays/sdu626_perler_og_guld/persona_henrik.md` is created and links to `position_tjener.md`
- [x] `plays/sdu626_perler_og_guld/persona_anna.md` is created and links to `position_sandhed.md`
- [x] `plays/sdu626_perler_og_guld/position_hersker.md` is created
- [x] `plays/sdu626_perler_og_guld/position_eventyr.md` is created
- [x] `plays/sdu626_perler_og_guld/position_tjener.md` is created
- [x] `plays/sdu626_perler_og_guld/position_sandhed.md` is created
- [x] `plays/sdu626_perler_og_guld/piece_ballon.md` is created
- [x] `plays/sdu626_perler_og_guld/place_aandetempel.md` is created
- [x] `plays/sdu626_perler_og_guld/process_rejse.md` is created
- [x] `plays/sdu626_perler_og_guld/process_gaade.md` is created
- [x] `plays/sdu626_perler_og_guld/plan_statue.md` is created
- [x] `plays/sdu626_perler_og_guld/pitch_komedie.md` is created
- [x] `plays/sdu626_perler_og_guld/plot_opgave.md` is created and casts company elements
- [x] `plays/sdu626_perler_og_guld/plot_ballonrejse.md` is created and casts company elements
- [x] `plays/sdu626_perler_og_guld/plot_triumf.md` is created and casts company elements
- [x] The local validation tests (`npm test`) run successfully with zero errors
