---
khai: order
title: "Stage BFN 815 Bispen paa Boerglum"
language: english
license: CC-BY-NC-SA-4.0
stamp:
  owner: KAI HACKS AI
  version: v0.0.1
  date: "2026-06-24"
---

# Order: Stage BFN 815 Bispen paa Boerglum

## Direction

The house must stage BFN 815 (_Bispen paa Børglum og hans Frænde_) to establish the eighty-fourth production in the H.C. Andersen house. The production must model Bisp, Fraende, the positions (Magthaver, Haevner), the piece (Vaaben), the environments (Kloster, Kirke), the undertrykkelse and afregning processes, and the plots leading to their realization. It must be written in authentic Danish for all prose sections.

## Orders

1. The Playwright (Hans Christian Andersen) must author the play definition, the two personas, the two positions, the piece, the two places, the two processes, the two in-world plans, the pitch of Alvor, and the four plots.
2. The Theatre Manager (Edvard Collin) must verify the local registry, ensure correct versioning, check formatting, and validate that the cast conforms to the canon.
3. The Roadie (Vilhelm Pedersen) must set the stage, verify the local test suite is green, and prepare the files for packaging.

## Implementation

The play files must be placed in `plays/bfn815_bispen_paa_boerglum/` and follow the house language policy:

- Structural elements and frontmatter in English.
- Narrative prose, projections, actions, shadows, tells, and staging notes in Danish.

## Targets

- [x] `plays/bfn815_bispen_paa_boerglum/play_bispen_paa_boerglum.md` is created and lists the complete company
- [x] `plays/bfn815_bispen_paa_boerglum/persona_bisp.md` is created and links to `position_magthaver.md`
- [x] `plays/bfn815_bispen_paa_boerglum/persona_fraende.md` is created and links to `position_haevner.md`
- [x] `plays/bfn815_bispen_paa_boerglum/position_magthaver.md` is created
- [x] `plays/bfn815_bispen_paa_boerglum/position_haevner.md` is created
- [x] `plays/bfn815_bispen_paa_boerglum/piece_vaaben.md` is created
- [x] `plays/bfn815_bispen_paa_boerglum/place_kloster.md` is created
- [x] `plays/bfn815_bispen_paa_boerglum/place_kirke.md` is created
- [x] `plays/bfn815_bispen_paa_boerglum/process_undertrykkelse.md` is created
- [x] `plays/bfn815_bispen_paa_boerglum/process_afregning.md` is created
- [x] `plays/bfn815_bispen_paa_boerglum/plan_plyndring.md` is created and linked to `persona_bisp.md`
- [x] `plays/bfn815_bispen_paa_boerglum/plan_forberedelse.md` is created and linked to `persona_fraende.md`
- [x] `plays/bfn815_bispen_paa_boerglum/pitch_alvor.md` is created
- [x] `plays/bfn815_bispen_paa_boerglum/plot_magtudfoldelsen.md` is created and casts company elements
- [x] `plays/bfn815_bispen_paa_boerglum/plot_striden.md` is created and casts company elements
- [x] `plays/bfn815_bispen_paa_boerglum/plot_juletiden.md` is created and casts company elements
- [x] `plays/bfn815_bispen_paa_boerglum/plot_afregningen.md` is created and casts company elements
- [x] The local validation tests (`npm test`) run successfully with zero errors
