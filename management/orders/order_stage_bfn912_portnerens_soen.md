---
khai: order
title: "Stage BFN 912 Portnerens Soen"
language: english
license: CC-BY-NC-SA-4.0
stamp:
  owner: KAI HACKS AI
  version: v0.0.1
  date: "2026-06-25"
---

# Order: Stage BFN 912 Portnerens Soen

## Direction

The house must stage BFN 912 (_Portnerens Søn_) to establish the ninety-ninth production in the H.C. Andersen house. The production must model Georg and Emilie, the positions (Udviklende, Ophøjet), the pieces (Tegninger, Sadel), the environments (Kælder, FørsteSal), the uddannelse and anerkendelse processes, and the plots representing their shared childhood, the fire, and his rise to marriage. It must be written in authentic Danish for all prose sections.

## Orders

1. The Playwright (Hans Christian Andersen) must author the play definition, the two personas, the two positions, the two pieces, the two places, the two processes, the two in-world plans, the pitch of Klasserejse, and the five plots.
2. The Theatre Manager (Edvard Collin) must verify the local registry, ensure correct versioning, check formatting, and validate that the cast conforms to the canon.
3. The Roadie (Vilhelm Pedersen) must set the stage, verify the local test suite is green, and prepare the files for packaging.

## Implementation

The play files must be placed in `plays/bfn912_portnerens_soen/` and follow the house language policy:

- Structural elements and frontmatter in English.
- Narrative prose, projections, actions, shadows, tells, and staging notes in Danish.

## Targets

- [x] `plays/bfn912_portnerens_soen/play_portnerens_soen.md` is created and lists the complete company
- [x] `plays/bfn912_portnerens_soen/persona_georg.md` is created and links to `position_udviklende.md`
- [x] `plays/bfn912_portnerens_soen/persona_emilie.md` is created and links to `position_ophoejet.md`
- [x] `plays/bfn912_portnerens_soen/position_udviklende.md` is created
- [x] `plays/bfn912_portnerens_soen/position_ophoejet.md` is created
- [x] `plays/bfn912_portnerens_soen/piece_tegninger.md` is created
- [x] `plays/bfn912_portnerens_soen/piece_sadel.md` is created
- [x] `plays/bfn912_portnerens_soen/place_kaelder.md` is created
- [x] `plays/bfn912_portnerens_soen/place_foerste_sal.md` is created
- [x] `plays/bfn912_portnerens_soen/process_uddannelse.md` is created
- [x] `plays/bfn912_portnerens_soen/process_anerkendelse.md` is created
- [x] `plays/bfn912_portnerens_soen/plan_kunst.md` is created and linked to `persona_georg.md`
- [x] `plays/bfn912_portnerens_soen/plan_kaerlighed.md` is created and linked to `persona_emilie.md`
- [x] `plays/bfn912_portnerens_soen/pitch_klasserejse.md` is created
- [x] `plays/bfn912_portnerens_soen/plot_barndom.md` is created and casts company elements
- [x] `plays/bfn912_portnerens_soen/plot_ildsvaade.md` is created and casts company elements
- [x] `plays/bfn912_portnerens_soen/plot_kunsten.md` is created and casts company elements
- [x] `plays/bfn912_portnerens_soen/plot_maskebal.md` is created and casts company elements
- [x] `plays/bfn912_portnerens_soen/plot_aegteskab.md` is created and casts company elements
- [x] The local validation tests (`npm test`) run successfully with zero errors
