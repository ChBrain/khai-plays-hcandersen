---
khai: order
title: "Stage SDU 627"
language: english
license: CC-BY-NC-SA-4.0
stamp:
  owner: KAI HACKS AI
  version: v0.0.1
  date: "2026-07-11"
---

# Order: Stage SDU 627

## Direction

The house must stage SDU 627 (_En Nat i Roeskilde_) to establish the twenty-seventh work in the "Drama" genre. The production must model the comedic vaudeville dialogues of Rummel, Rasmus Graah, and the Pige. It must model the Roskilde kro-værelse, the will/testament letter piece, the processes representing the rolling of dice and the realization of their shared wife, the husbands' plan to escape their wife, the comedic vaudeville tone, and the three plots. All staging, prose, projections, actions, shadows, and tells must be authored in authentic Danish.

## Orders

1. The Playwright (Hans Christian Andersen) must author the play definition, the three personas (rummel, graah, pige), the three positions (urtekraemmer, gaest, pige_stilling), the one piece (testamente), the one place (krovaerelse), the two processes (rafling, forveksling), the in-world plan (kone), the pitch (vaudeville), and the three plots.
2. The Theatre Manager (Edvard Collin) must verify the local registry, ensure correct versioning, check formatting, and validate that the entire cast conforms to the canon.
3. The Roadie (Vilhelm Pedersen) must set the stage, verify the local test suite is green, and prepare the files for packaging.

## Implementation

The play files must be placed in `plays/sdu627_roeskilde/` and follow the house language policy:

- Structural elements and frontmatter in English.
- Narrative prose, projections, actions, shadows, tells, and staging notes in Danish.

## Targets

- [x] `plays/sdu627_roeskilde/play_roeskilde.md` is created and lists the complete company
- [x] `plays/sdu627_roeskilde/persona_rummel.md` is created and links to `position_urtekraemmer.md`
- [x] `plays/sdu627_roeskilde/persona_graah.md` is created and links to `position_gaest.md`
- [x] `plays/sdu627_roeskilde/persona_pige.md` is created and links to `position_pige_stilling.md`
- [x] `plays/sdu627_roeskilde/position_urtekraemmer.md` is created
- [x] `plays/sdu627_roeskilde/position_gaest.md` is created
- [x] `plays/sdu627_roeskilde/position_pige_stilling.md` is created
- [x] `plays/sdu627_roeskilde/piece_testamente.md` is created
- [x] `plays/sdu627_roeskilde/place_krovaerelse.md` is created
- [x] `plays/sdu627_roeskilde/process_rafling.md` is created
- [x] `plays/sdu627_roeskilde/process_forveksling.md` is created
- [x] `plays/sdu627_roeskilde/plan_kone.md` is created
- [x] `plays/sdu627_roeskilde/pitch_vaudeville.md` is created
- [x] `plays/sdu627_roeskilde/plot_delt_vaerelse.md` is created and casts company elements
- [x] `plays/sdu627_roeskilde/plot_terningekast.md` is created and casts company elements
- [x] `plays/sdu627_roeskilde/plot_postbudskab.md` is created and casts company elements
- [x] The local validation tests (`npm test`) run successfully with zero errors
