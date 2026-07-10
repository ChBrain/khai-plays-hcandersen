---
khai: order
title: "Stage SDU 618"
language: english
license: CC-BY-NC-SA-4.0
stamp:
  owner: KAI HACKS AI
  version: v0.0.1
  date: "2026-07-10"
---

# Order: Stage SDU 618

## Direction

The house must stage SDU 618 (_Vandring gjennem Opera-Galleriet_) to establish the eighteenth work in the "Drama" genre. The production must model the metatheatrical framework of the Guide, the Diva, and the Critic. It must model the grand opera gallery, the printed program piece, the processes representing the gallery tour and the musical collage, the guide's concert plan, the deklamatoriske framing tone, and the three plots. All staging, prose, projections, actions, shadows, and tells must be authored in authentic Danish.

## Orders

1. The Playwright (Hans Christian Andersen) must author the play definition, the three personas (guide, diva, kritiker), the three positions (rundviser, operastjerne, recensent), the one piece (program), the one place (galleriet), the two processes (vandring, kollage), the in-world plan (benefice), the pitch (rammefortaelling), and the three plots.
2. The Theatre Manager (Edvard Collin) must verify the local registry, ensure correct versioning, check formatting, and validate that the entire cast conforms to the canon.
3. The Roadie (Vilhelm Pedersen) must set the stage, verify the local test suite is green, and prepare the files for packaging.

## Implementation

The play files must be placed in `plays/sdu618_opera_galleriet/` and follow the house language policy:

- Structural elements and frontmatter in English.
- Narrative prose, projections, actions, shadows, tells, and staging notes in Danish.

## Targets

- [x] `plays/sdu618_opera_galleriet/play_opera_galleriet.md` is created and lists the complete company
- [x] `plays/sdu618_opera_galleriet/persona_guide.md` is created and links to `position_rundviser.md`
- [x] `plays/sdu618_opera_galleriet/persona_diva.md` is created and links to `position_operastjerne.md`
- [x] `plays/sdu618_opera_galleriet/persona_kritiker.md` is created and links to `position_recensent.md`
- [x] `plays/sdu618_opera_galleriet/position_rundviser.md` is created
- [x] `plays/sdu618_opera_galleriet/position_operastjerne.md` is created
- [x] `plays/sdu618_opera_galleriet/position_recensent.md` is created
- [x] `plays/sdu618_opera_galleriet/piece_program.md` is created
- [x] `plays/sdu618_opera_galleriet/place_galleriet.md` is created
- [x] `plays/sdu618_opera_galleriet/process_vandring.md` is created
- [x] `plays/sdu618_opera_galleriet/process_kollage.md` is created
- [x] `plays/sdu618_opera_galleriet/plan_benefice.md` is created
- [x] `plays/sdu618_opera_galleriet/pitch_rammefortaelling.md` is created
- [x] `plays/sdu618_opera_galleriet/plot_aabningen.md` is created and casts company elements
- [x] `plays/sdu618_opera_galleriet/plot_galleriet.md` is created and casts company elements
- [x] `plays/sdu618_opera_galleriet/plot_afslutningen.md` is created and casts company elements
- [x] The local validation tests (`npm test`) run successfully with zero errors
