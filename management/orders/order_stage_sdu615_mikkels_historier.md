---
khai: order
title: "Stage SDU 615"
language: english
license: CC-BY-NC-SA-4.0
stamp:
  owner: KAI HACKS AI
  version: v0.0.1
  date: "2026-07-10"
---

# Order: Stage SDU 615

## Direction

The house must stage SDU 615 (_Mikkels Kjærlighedshistorier i Paris_) to establish the fifteenth work in the "Drama" genre. The production must model the comedic vaudeville monologue of Mikkel, his off-stage Major, and the French lady in the diligence. It must model Paris, the carriage ticket piece, the processes representing language barrier and travel movement, the plan to return to Denmark, the lighthearted vaudeville tone, and the three plots. All staging, prose, projections, actions, shadows, and tells must be authored in authentic Danish.

## Orders

1. The Playwright (Hans Christian Andersen) must author the play definition, the three personas (mikkel, major, dame), the three positions (dansker, herskab, koket), the one piece (billet), the one place (paris), the two processes (sprogforvirring, rejsefeber), the in-world plan (hjemrejse), the pitch (vaudeville), and the three plots.
2. The Theatre Manager (Edvard Collin) must verify the local registry, ensure correct versioning, check formatting, and validate that the entire cast conforms to the canon.
3. The Roadie (Vilhelm Pedersen) must set the stage, verify the local test suite is green, and prepare the files for packaging.

## Implementation

The play files must be placed in `plays/sdu615_mikkels_historier/` and follow the house language policy:

- Structural elements and frontmatter in English.
- Narrative prose, projections, actions, shadows, tells, and staging notes in Danish.

## Targets

- [x] `plays/sdu615_mikkels_historier/play_mikkels_historier.md` is created and lists the complete company
- [x] `plays/sdu615_mikkels_historier/persona_mikkel.md` is created and links to `position_dansker.md`
- [x] `plays/sdu615_mikkels_historier/persona_major.md` is created and links to `position_herskab.md`
- [x] `plays/sdu615_mikkels_historier/persona_dame.md` is created and links to `position_koket.md`
- [x] `plays/sdu615_mikkels_historier/position_dansker.md` is created
- [x] `plays/sdu615_mikkels_historier/position_herskab.md` is created
- [x] `plays/sdu615_mikkels_historier/position_koket.md` is created
- [x] `plays/sdu615_mikkels_historier/piece_billet.md` is created
- [x] `plays/sdu615_mikkels_historier/place_paris.md` is created
- [x] `plays/sdu615_mikkels_historier/process_sprogforvirring.md` is created
- [x] `plays/sdu615_mikkels_historier/process_rejsefeber.md` is created
- [x] `plays/sdu615_mikkels_historier/plan_hjemrejse.md` is created
- [x] `plays/sdu615_mikkels_historier/pitch_vaudeville.md` is created
- [x] `plays/sdu615_mikkels_historier/plot_diligencen.md` is created and casts company elements
- [x] `plays/sdu615_mikkels_historier/plot_byrundturen.md` is created and casts company elements
- [x] `plays/sdu615_mikkels_historier/plot_hjemvejen.md` is created and casts company elements
- [x] The local validation tests (`npm test`) run successfully with zero errors
