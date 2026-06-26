---
khai: order
title: "Stage BFN 417 Metalsvinet"
language: english
license: CC-BY-NC-SA-4.0
stamp:
  owner: KAI HACKS AI
  version: v0.0.1
  date: "2026-06-26"
---

# Order: Stage BFN 417 Metalsvinet

## Direction

The house must stage BFN 417 (_Metalsvinet_) to establish a production in the H.C. Andersen house. The production must model drengen, metalsvinet, the positions (droemmer, baerer), the pieces (tegning, bronzesvin), the environments (firenze, galleriet), the kunstudvikling and droemmejagt processes, and the plots representing natten and vaerkstedet. It must be written in authentic Danish for all prose sections.

## Orders

1. The Playwright (Hans Christian Andersen) must author the play definition, the 2 personas, the 2 positions, the 2 pieces, the 2 places, the 2 processes, the 2 in-world plans, the pitch of poetisk, and the 2 plots.
2. The Theatre Manager (Edvard Collin) must verify the local registry, ensure correct versioning, check formatting, and validate that the cast conforms to the canon.
3. The Roadie (Vilhelm Pedersen) must set the stage, verify the local test suite is green, and prepare the files for packaging.

## Implementation

The play files must be placed in `plays/bfn417_metalsvinet/` and follow the house language policy:

- Structural elements and frontmatter in English.
- Narrative prose, projections, actions, shadows, tells, and staging notes in Danish.

## Targets

- [x] `plays/bfn417_metalsvinet/play_metalsvinet.md` is created and lists the complete company
- [x] `plays/bfn417_metalsvinet/persona_drengen.md` is created and links to `position_droemmer.md`
- [x] `plays/bfn417_metalsvinet/persona_metalsvinet.md` is created and links to `position_baerer.md`
- [x] `plays/bfn417_metalsvinet/position_droemmer.md` is created
- [x] `plays/bfn417_metalsvinet/position_baerer.md` is created
- [x] `plays/bfn417_metalsvinet/piece_tegning.md` is created
- [x] `plays/bfn417_metalsvinet/piece_bronzesvin.md` is created
- [x] `plays/bfn417_metalsvinet/place_firenze.md` is created
- [x] `plays/bfn417_metalsvinet/place_galleriet.md` is created
- [x] `plays/bfn417_metalsvinet/process_kunstudvikling.md` is created
- [x] `plays/bfn417_metalsvinet/process_droemmejagt.md` is created
- [x] `plays/bfn417_metalsvinet/plan_kunst.md` is created and linked to `persona_drengen.md`
- [x] `plays/bfn417_metalsvinet/plan_frihed.md` is created and linked to `persona_drengen.md`
- [x] `plays/bfn417_metalsvinet/pitch_poetisk.md` is created
- [x] `plays/bfn417_metalsvinet/plot_natten.md` is created and casts company elements
- [x] `plays/bfn417_metalsvinet/plot_vaerkstedet.md` is created and casts company elements
- [x] The local validation tests (`npm test`) run successfully with zero errors
