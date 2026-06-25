---
khai: order
title: "Stage BFN 969 Hvem var den Lykkeligste"
language: english
license: CC-BY-NC-SA-4.0
stamp:
  owner: KAI HACKS AI
  version: v0.0.1
  date: "2026-06-25"
---

# Order: Stage BFN 969 Hvem var den Lykkeligste

## Direction

The house must stage BFN 969 (_Hvem var den Lykkeligste?_) to establish the hundred and eighth production in the H.C. Andersen house. The production must model Solskin, Dug, and Hæk, the positions (Moderlig, Nærende, Undersøgende), the pieces (Rose, Avis), the environments (Haven, Gravkammeret), the livsgivende and livsforløb processes, and the plots representing the dispute, the wind's quest, the deathbed, and the weeding woman. It must be written in authentic Danish for all prose sections.

## Orders

1. The Playwright (Hans Christian Andersen) must author the play definition, the three personas, the three positions, the two pieces, the two places, the two processes, the two in-world plans, the pitch of Forgængelighed, and the four plots.
2. The Theatre Manager (Edvard Collin) must verify the local registry, ensure correct versioning, check formatting, and validate that the cast conforms to the canon.
3. The Roadie (Vilhelm Pedersen) must set the stage, verify the local test suite is green, and prepare the files for packaging.

## Implementation

The play files must be placed in `plays/bfn969_hvem_var_den_lykkeligste/` and follow the house language policy:

- Structural elements and frontmatter in English.
- Narrative prose, projections, actions, shadows, tells, and staging notes in Danish.

## Targets

- [ ] `plays/bfn969_hvem_var_den_lykkeligste/play_hvem_var_den_lykkeligste.md` is created and lists the complete company
- [ ] `plays/bfn969_hvem_var_den_lykkeligste/persona_solskin.md` is created and links to `position_naerende.md`
- [ ] `plays/bfn969_hvem_var_den_lykkeligste/persona_dug.md` is created and links to `position_naerende.md`
- [ ] `plays/bfn969_hvem_var_den_lykkeligste/persona_haek.md` is created and links to `position_moderlig.md`
- [ ] `plays/bfn969_hvem_var_den_lykkeligste/position_moderlig.md` is created
- [ ] `plays/bfn969_hvem_var_den_lykkeligste/position_naerende.md` is created
- [ ] `plays/bfn969_hvem_var_den_lykkeligste/position_undersoegende.md` is created
- [ ] `plays/bfn969_hvem_var_den_lykkeligste/piece_rose.md` is created
- [ ] `plays/bfn969_hvem_var_den_lykkeligste/piece_avis.md` is created
- [ ] `plays/bfn969_hvem_var_den_lykkeligste/place_haven.md` is created
- [ ] `plays/bfn969_hvem_var_den_lykkeligste/place_gravkammeret.md` is created
- [ ] `plays/bfn969_hvem_var_den_lykkeligste/process_livsgivende.md` is created
- [ ] `plays/bfn969_hvem_var_den_lykkeligste/process_livsforloeb.md` is created
- [ ] `plays/bfn969_hvem_var_den_lykkeligste/plan_omsorg.md` is created and linked to `persona_haek.md`
- [ ] `plays/bfn969_hvem_var_den_lykkeligste/plan_opdrag.md` is created and linked to `position_undersoegende.md`
- [ ] `plays/bfn969_hvem_var_den_lykkeligste/pitch_forgaengelighed.md` is created
- [ ] `plays/bfn969_hvem_var_den_lykkeligste/plot_striden.md` is created and casts company elements
- [ ] `plays/bfn969_hvem_var_den_lykkeligste/plot_vinden.md` is created and casts company elements
- [ ] `plays/bfn969_hvem_var_den_lykkeligste/plot_doedslejet.md` is created and casts company elements
- [ ] `plays/bfn969_hvem_var_den_lykkeligste/plot_lugekonen.md` is created and casts company elements
- [ ] The local validation tests (`npm test`) run successfully with zero errors
