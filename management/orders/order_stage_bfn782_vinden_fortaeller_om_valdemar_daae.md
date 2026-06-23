---
khai: order
title: "Stage BFN 782 Vinden fortaeller om Valdemar Daae og hans Doettre"
language: english
license: CC-BY-NC-SA-4.0
stamp:
  owner: KAI HACKS AI
  version: v0.0.1
  date: "2026-06-23"
---

# Order: Stage BFN 782 Vinden fortaeller om Valdemar Daae og hans Doettre

## Direction

The house must stage BFN 782 (_Vinden fortæller om Valdemar Daae og hans Døttre_) to establish the sixty-eighth production in the H.C. Andersen house. The production must model Daae, Vind, the positions (Alkymist, Fortaeller), the piece (Guld), the environments (Herregaard, Laboratorium), the alkymi and forfald processes, and the plots leading to their realization. It must be written in authentic Danish for all prose sections.

## Orders

1. The Playwright (Hans Christian Andersen) must author the play definition, the two personas, the two positions, the piece, the two places, the two processes, the two in-world plans, the pitch of Melankoli, and the four plots.
2. The Theatre Manager (Edvard Collin) must verify the local registry, ensure correct versioning, check formatting, and validate that the entire cast conforms to the canon.
3. The Roadie (Vilhelm Pedersen) must set the stage, verify the local test suite is green, and prepare the files for packaging.

## Implementation

The play files must be placed in `plays/bfn782_vinden_fortaeller_om_valdemar_daae/` and follow the house language policy:

- Structural elements and frontmatter in English.
- Narrative prose, projections, actions, shadows, tells, and staging notes in Danish.

## Targets

- [x] `plays/bfn782_vinden_fortaeller_om_valdemar_daae/play_vinden_fortaeller_om_valdemar_daae.md` is created and lists the complete company
- [x] `plays/bfn782_vinden_fortaeller_om_valdemar_daae/persona_daae.md` is created and links to `position_alkymist.md`
- [x] `plays/bfn782_vinden_fortaeller_om_valdemar_daae/persona_vind.md` is created and links to `position_fortaeller.md`
- [x] `plays/bfn782_vinden_fortaeller_om_valdemar_daae/position_alkymist.md` is created
- [x] `plays/bfn782_vinden_fortaeller_om_valdemar_daae/position_fortaeller.md` is created
- [x] `plays/bfn782_vinden_fortaeller_om_valdemar_daae/piece_guld.md` is created
- [x] `plays/bfn782_vinden_fortaeller_om_valdemar_daae/place_herregaard.md` is created
- [x] `plays/bfn782_vinden_fortaeller_om_valdemar_daae/place_laboratorium.md` is created
- [x] `plays/bfn782_vinden_fortaeller_om_valdemar_daae/process_alkymi.md` is created
- [x] `plays/bfn782_vinden_fortaeller_om_valdemar_daae/process_forfald.md` is created
- [x] `plays/bfn782_vinden_fortaeller_om_valdemar_daae/plan_rigdom.md` is created and linked to `persona_daae.md`
- [x] `plays/bfn782_vinden_fortaeller_om_valdemar_daae/plan_observation.md` is created and linked to `persona_vind.md`
- [x] `plays/bfn782_vinden_fortaeller_om_valdemar_daae/pitch_melankoli.md` is created
- [x] `plays/bfn782_vinden_fortaeller_om_valdemar_daae/plot_rigdom_soegen.md` is created and casts company elements
- [x] `plays/bfn782_vinden_fortaeller_om_valdemar_daae/plot_vindens_sang.md` is created and casts company elements
- [x] `plays/bfn782_vinden_fortaeller_om_valdemar_daae/plot_fallit.md` is created and casts company elements
- [x] `plays/bfn782_vinden_fortaeller_om_valdemar_daae/plot_forgaengelighed.md` is created and casts company elements
- [x] The local validation tests (`npm test`) run successfully with zero errors
