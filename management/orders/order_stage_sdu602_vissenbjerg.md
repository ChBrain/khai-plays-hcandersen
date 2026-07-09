---
khai: order
title: "Stage SDU 602"
language: english
license: CC-BY-NC-SA-4.0
stamp:
  owner: KAI HACKS AI
  version: v0.0.1
  date: "2026-07-09"
---

# Order: Stage SDU 602

## Direction

The house must stage SDU 602 (_Røverne i Vissenbjerg i Fyen_) to establish the second work in the "Drama" genre. The production must model the early sagn- and robber drama, featuring the outlaw leader Knud Vissenberg, the disguised wooer Henning Aasum, and the superstitious robber Ulrik. It must model the robber tavern in Vissenbjerg, the wealthy estate, the magical alrune root, the robbery and superstition processes, the wooing plan, and the final raid. All staging, prose, projections, actions, shadows, and tells must be authored in authentic Danish.

## Orders

1. The Playwright (Hans Christian Andersen) must author the play definition, the three personas (Knud, Henning, Ulrik), the two positions (roever, bejler), the one piece (alrune), the two places (vissenbjerghuse, herregaarden), the two processes (roeveri, overtro), the in-world plan (bortfoerelse), the pitch (folkesagn), and the three plots.
2. The Theatre Manager (Edvard Collin) must verify the local registry, ensure correct versioning, check formatting, and validate that the entire cast conforms to the canon.
3. The Roadie (Vilhelm Pedersen) must set the stage, verify the local test suite is green, and prepare the files for packaging.

## Implementation

The play files must be placed in `plays/sdu602_vissenbjerg/` and follow the house language policy:

- Structural elements and frontmatter in English.
- Narrative prose, projections, actions, shadows, tells, and staging notes in Danish.

## Targets

- [x] `plays/sdu602_vissenbjerg/play_vissenbjerg.md` is created and lists the complete company
- [x] `plays/sdu602_vissenbjerg/persona_knud.md` is created and links to `position_roever.md`
- [x] `plays/sdu602_vissenbjerg/persona_henning.md` is created and links to `position_bejler.md`
- [x] `plays/sdu602_vissenbjerg/persona_ulrik.md` is created and links to `position_roever.md`
- [x] `plays/sdu602_vissenbjerg/position_roever.md` is created
- [x] `plays/sdu602_vissenbjerg/position_bejler.md` is created
- [x] `plays/sdu602_vissenbjerg/piece_alrune.md` is created
- [x] `plays/sdu602_vissenbjerg/place_vissenbjerghuse.md` is created
- [x] `plays/sdu602_vissenbjerg/place_herregaarden.md` is created
- [x] `plays/sdu602_vissenbjerg/process_roeveri.md` is created
- [x] `plays/sdu602_vissenbjerg/process_overtro.md` is created
- [x] `plays/sdu602_vissenbjerg/plan_bortfoerelse.md` is created
- [x] `plays/sdu602_vissenbjerg/pitch_folkesagn.md` is created
- [x] `plays/sdu602_vissenbjerg/plot_krostuen.md` is created and casts company elements
- [x] `plays/sdu602_vissenbjerg/plot_bejleriet.md` is created and casts company elements
- [x] `plays/sdu602_vissenbjerg/plot_overfaldet.md` is created and casts company elements
- [x] The local validation tests (`npm test`) run successfully with zero errors
