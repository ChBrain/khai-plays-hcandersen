---
khai: order
title: "Stage BFN 766 Flaskehalsen"
language: english
license: CC-BY-NC-SA-4.0
stamp:
  owner: KAI HACKS AI
  version: v0.0.1
  date: "2026-06-23"
---

# Order: Stage BFN 766 Flaskehalsen

## Direction

The house must stage BFN 766 (_Flaskehalsen_) to establish the sixty-third production in the H.C. Andersen house. The production must model Flaske, Ejer, the positions (Vidne, Brugt), the piece (Hals), the environments (Glastilvirkning, Hygge), the kredsloeb and brud processes, and the plots leading to their realization. It must be written in authentic Danish for all prose sections.

## Orders

1. The Playwright (Hans Christian Andersen) must author the play definition, the two personas, the two positions, the piece, the two places, the two processes, the two in-world plans, the pitch of Nostalgi, and the four plots.
2. The Theatre Manager (Edvard Collin) must verify the local registry, ensure correct versioning, check formatting, and validate that the entire cast conforms to the canon.
3. The Roadie (Vilhelm Pedersen) must set the stage, verify the local test suite is green, and prepare the files for packaging.

## Implementation

The play files must be placed in `plays/bfn766_flaskehalsen/` and follow the house language policy:

- Structural elements and frontmatter in English.
- Narrative prose, projections, actions, shadows, tells, and staging notes in Danish.

## Targets

- [x] `plays/bfn766_flaskehalsen/play_flaskehalsen.md` is created and lists the complete company
- [x] `plays/bfn766_flaskehalsen/persona_flaske.md` is created and links to `position_vidne.md`
- [x] `plays/bfn766_flaskehalsen/persona_ejer.md` is created and links to `position_brugt.md`
- [x] `plays/bfn766_flaskehalsen/position_vidne.md` is created
- [x] `plays/bfn766_flaskehalsen/position_brugt.md` is created
- [x] `plays/bfn766_flaskehalsen/piece_hals.md` is created
- [x] `plays/bfn766_flaskehalsen/place_glastilvirkning.md` is created
- [x] `plays/bfn766_flaskehalsen/place_hygge.md` is created
- [x] `plays/bfn766_flaskehalsen/process_kredsloeb.md` is created
- [x] `plays/bfn766_flaskehalsen/process_brud.md` is created
- [x] `plays/bfn766_flaskehalsen/plan_erindring.md` is created and linked to `persona_flaske.md`
- [x] `plays/bfn766_flaskehalsen/plan_observation.md` is created and linked to `persona_flaske.md`
- [x] `plays/bfn766_flaskehalsen/pitch_nostalgi.md` is created
- [x] `plays/bfn766_flaskehalsen/plot_livscyklus.md` is created and casts company elements
- [x] `plays/bfn766_flaskehalsen/plot_observation.md` is created and casts company elements
- [x] `plays/bfn766_flaskehalsen/plot_reduktion.md` is created and casts company elements
- [x] `plays/bfn766_flaskehalsen/plot_erindring.md` is created and casts company elements
- [x] The local validation tests (`npm test`) run successfully with zero errors
