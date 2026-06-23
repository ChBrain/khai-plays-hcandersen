---
khai: order
title: "Stage BFN 667 Ved det yderste Hav"
language: english
license: CC-BY-NC-SA-4.0
stamp:
  owner: KAI HACKS AI
  version: v0.0.1
  date: "2026-06-23"
---

# Order: Stage BFN 667 Ved det yderste Hav

## Direction

The house must stage BFN 667 (_Ved det yderste Hav_) to establish the sixty-first production in the H.C. Andersen house. The production must model Doeende, Kammerat, the positions (Hjemve, Vagt), the piece (Lys), the environments (Hytte, Hav), the rejse and droem processes, and the plots leading to their realization. It must be written in authentic Danish for all prose sections.

## Orders

1. The Playwright (Hans Christian Andersen) must author the play definition, the two personas, the two positions, the piece, the two places, the two processes, the two in-world plans, the pitch of Nostalgi, and the four plots.
2. The Theatre Manager (Edvard Collin) must verify the local registry, ensure correct versioning, check formatting, and validate that the entire cast conforms to the canon.
3. The Roadie (Vilhelm Pedersen) must set the stage, verify the local test suite is green, and prepare the files for packaging.

## Implementation

The play files must be placed in `plays/bfn667_ved_det_yderste_hav/` and follow the house language policy:

- Structural elements and frontmatter in English.
- Narrative prose, projections, actions, shadows, tells, and staging notes in Danish.

## Targets

- [x] `plays/bfn667_ved_det_yderste_hav/play_ved_det_yderste_hav.md` is created and lists the complete company
- [x] `plays/bfn667_ved_det_yderste_hav/persona_doeende.md` is created and links to `position_hjemve.md`
- [x] `plays/bfn667_ved_det_yderste_hav/persona_kammerat.md` is created and links to `position_vagt.md`
- [x] `plays/bfn667_ved_det_yderste_hav/position_hjemve.md` is created
- [x] `plays/bfn667_ved_det_yderste_hav/position_vagt.md` is created
- [x] `plays/bfn667_ved_det_yderste_hav/piece_lys.md` is created
- [x] `plays/bfn667_ved_det_yderste_hav/place_hytte.md` is created
- [x] `plays/bfn667_ved_det_yderste_hav/place_hav.md` is created
- [x] `plays/bfn667_ved_det_yderste_hav/process_rejse.md` is created
- [x] `plays/bfn667_ved_det_yderste_hav/process_droem.md` is created
- [x] `plays/bfn667_ved_det_yderste_hav/plan_erindring.md` is created and linked to `persona_doeende.md`
- [x] `plays/bfn667_ved_det_yderste_hav/plan_overgang.md` is created and linked to `persona_kammerat.md`
- [x] `plays/bfn667_ved_det_yderste_hav/pitch_nostalgi.md` is created
- [x] `plays/bfn667_ved_det_yderste_hav/plot_kulde.md` is created and casts company elements
- [x] `plays/bfn667_ved_det_yderste_hav/plot_droem.md` is created and casts company elements
- [x] `plays/bfn667_ved_det_yderste_hav/plot_doed.md` is created and casts company elements
- [x] `plays/bfn667_ved_det_yderste_hav/plot_fred.md` is created and casts company elements
- [x] The local validation tests (`npm test`) run successfully with zero errors
