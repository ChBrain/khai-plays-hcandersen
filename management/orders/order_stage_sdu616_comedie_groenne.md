---
khai: order
title: "Stage SDU 616"
language: english
license: CC-BY-NC-SA-4.0
stamp:
  owner: KAI HACKS AI
  version: v0.0.1
  date: "2026-07-10"
---

# Order: Stage SDU 616

## Direction

The house must stage SDU 616 (_En Comedie i det Grønne_) to establish the sixteenth work in the "Drama" genre. The production must model the metatheatrical vaudeville of Dalby and Frank. It must model the open-air garden, the disguise kit piece, the processes representing role-switching and Kierkegaardian parody, the demonstration plan, the meta-theatrical tone, and the three plots. All staging, prose, projections, actions, shadows, and tells must be authored in authentic Danish.

## Orders

1. The Playwright (Hans Christian Andersen) must author the play definition, the two personas (dalby, frank), the two positions (direktoer, inspektoer), the one piece (forklaedning), the one place (groenne), the two processes (rollebytte, parodi), the in-world plan (forevisning), the pitch (metateater), and the three plots.
2. The Theatre Manager (Edvard Collin) must verify the local registry, ensure correct versioning, check formatting, and validate that the entire cast conforms to the canon.
3. The Roadie (Vilhelm Pedersen) must set the stage, verify the local test suite is green, and prepare the files for packaging.

## Implementation

The play files must be placed in `plays/sdu616_comedie_groenne/` and follow the house language policy:

- Structural elements and frontmatter in English.
- Narrative prose, projections, actions, shadows, tells, and staging notes in Danish.

## Targets

- [x] `plays/sdu616_comedie_groenne/play_comedie_groenne.md` is created and lists the complete company
- [x] `plays/sdu616_comedie_groenne/persona_dalby.md` is created and links to `position_direktoer.md`
- [x] `plays/sdu616_comedie_groenne/persona_frank.md` is created and links to `position_inspektoer.md`
- [x] `plays/sdu616_comedie_groenne/position_direktoer.md` is created
- [x] `plays/sdu616_comedie_groenne/position_inspektoer.md` is created
- [x] `plays/sdu616_comedie_groenne/piece_forklaedning.md` is created
- [x] `plays/sdu616_comedie_groenne/place_groenne.md` is created
- [x] `plays/sdu616_comedie_groenne/process_rollebytte.md` is created
- [x] `plays/sdu616_comedie_groenne/process_parodi.md` is created
- [x] `plays/sdu616_comedie_groenne/plan_forevisning.md` is created
- [x] `plays/sdu616_comedie_groenne/pitch_metateater.md` is created
- [x] `plays/sdu616_comedie_groenne/plot_konfrontationen.md` is created and casts company elements
- [x] `plays/sdu616_comedie_groenne/plot_frisoerscenen.md` is created and casts company elements
- [x] `plays/sdu616_comedie_groenne/plot_tilladelsen.md` is created and casts company elements
- [x] The local validation tests (`npm test`) run successfully with zero errors
