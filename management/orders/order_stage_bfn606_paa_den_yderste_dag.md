---
khai: order
title: "Stage BFN 606 På den yderste Dag"
language: english
license: CC-BY-NC-SA-4.0
stamp:
  owner: KAI HACKS AI
  version: v0.0.1
  date: "2026-06-22"
---

# Order: Stage BFN 606 På den yderste Dag

## Direction

The house must stage BFN 606 (_På den yderste Dag_) to establish the forty-ninth production in the H.C. Andersen house. The production must model Sjael, Engel, the positions (Angstfuld, Mild), the piece (Tro), the environments (Doedsleje, Himlen), the doed and dom processes, and the plots leading to their realization. It must be written in authentic Danish for all prose sections.

## Orders

1. The Playwright (Hans Christian Andersen) must author the play definition, the two personas, the two positions, the piece, the two places, the two processes, the two in-world plans, the pitch of Patos, and the four plots.
2. The Theatre Manager (Edvard Collin) must verify the local registry, ensure correct versioning, check formatting, and validate that the entire cast conforms to the canon.
3. The Roadie (Vilhelm Pedersen) must set the stage, verify the local test suite is green, and prepare the files for packaging.

## Implementation

The play files must be placed in `plays/bfn606_paa_den_yderste_dag/` and follow the house language policy:

- Structural elements and frontmatter in English.
- Narrative prose, projections, actions, shadows, tells, and staging notes in Danish.

## Targets

- [x] `plays/bfn606_paa_den_yderste_dag/play_paa_den_yderste_dag.md` is created and lists the complete company
- [x] `plays/bfn606_paa_den_yderste_dag/persona_sjael.md` is created and links to `position_angstfuld.md`
- [x] `plays/bfn606_paa_den_yderste_dag/persona_engel.md` is created and links to `position_mild.md`
- [x] `plays/bfn606_paa_den_yderste_dag/position_angstfuld.md` is created
- [x] `plays/bfn606_paa_den_yderste_dag/position_mild.md` is created
- [x] `plays/bfn606_paa_den_yderste_dag/piece_tro.md` is created
- [x] `plays/bfn606_paa_den_yderste_dag/place_doedsleje.md` is created
- [x] `plays/bfn606_paa_den_yderste_dag/place_himlen.md` is created
- [x] `plays/bfn606_paa_den_yderste_dag/process_doed.md` is created
- [x] `plays/bfn606_paa_den_yderste_dag/process_dom.md` is created
- [x] `plays/bfn606_paa_den_yderste_dag/plan_opgoerelse.md` is created and linked to `persona_sjael.md`
- [x] `plays/bfn606_paa_den_yderste_dag/plan_frelse.md` is created and linked to `persona_engel.md`
- [x] `plays/bfn606_paa_den_yderste_dag/pitch_patos.md` is created
- [x] `plays/bfn606_paa_den_yderste_dag/plot_doedsleje.md` is created and casts company elements
- [x] `plays/bfn606_paa_den_yderste_dag/plot_rejsen.md` is created and casts company elements
- [x] `plays/bfn606_paa_den_yderste_dag/plot_dom.md` is created and casts company elements
- [x] `plays/bfn606_paa_den_yderste_dag/plot_frelse.md` is created and casts company elements
- [x] The local validation tests (`npm test`) run successfully with zero errors
