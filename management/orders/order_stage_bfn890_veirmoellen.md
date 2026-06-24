---
khai: order
title: "Stage BFN 890 Veirmoellen"
language: english
license: CC-BY-NC-SA-4.0
stamp:
  owner: KAI HACKS AI
  version: v0.0.1
  date: "2026-06-24"
---

# Order: Stage BFN 890 Veirmoellen

## Direction

The house must stage BFN 890 (_Veirmøllen_) to establish the ninety-fourth production in the H.C. Andersen house. The production must model Mølle, Møller, the positions (Stolt, Styrende), the piece (Vinge), the environments (Bakke, Indre), the formaling and nedbrydning processes, and the plots leading to their realization. It must be written in authentic Danish for all prose sections.

## Orders

1. The Playwright (Hans Christian Andersen) must author the play definition, the two personas, the two positions, the piece, the two places, the two processes, the two in-world plans, the pitch of Forgængelighed, and the four plots.
2. The Theatre Manager (Edvard Collin) must verify the local registry, ensure correct versioning, check formatting, and validate that the cast conforms to the canon.
3. The Roadie (Vilhelm Pedersen) must set the stage, verify the local test suite is green, and prepare the files for packaging.

## Implementation

The play files must be placed in `plays/bfn890_veirmoellen/` and follow the house language policy:

- Structural elements and frontmatter in English.
- Narrative prose, projections, actions, shadows, tells, and staging notes in Danish.

## Targets

- [x] `plays/bfn890_veirmoellen/play_veirmoellen.md` is created and lists the complete company
- [x] `plays/bfn890_veirmoellen/persona_moelle.md` is created and links to `position_stolt.md`
- [x] `plays/bfn890_veirmoellen/persona_moeller.md` is created and links to `position_styrende.md`
- [x] `plays/bfn890_veirmoellen/position_stolt.md` is created
- [x] `plays/bfn890_veirmoellen/position_styrende.md` is created
- [x] `plays/bfn890_veirmoellen/piece_vinge.md` is created
- [x] `plays/bfn890_veirmoellen/place_bakke.md` is created
- [x] `plays/bfn890_veirmoellen/place_indre.md` is created
- [x] `plays/bfn890_veirmoellen/process_formaling.md` is created
- [x] `plays/bfn890_veirmoellen/process_nedbrydning.md` is created
- [x] `plays/bfn890_veirmoellen/plan_arbejde.md` is created and linked to `persona_moelle.md`
- [x] `plays/bfn890_veirmoellen/plan_pleje.md` is created and linked to `persona_moeller.md`
- [x] `plays/bfn890_veirmoellen/pitch_forgaengelighed.md` is created
- [x] `plays/bfn890_veirmoellen/plot_virksomheden.md` is created and casts company elements
- [x] `plays/bfn890_veirmoellen/plot_selvforstaaelsen.md` is created and casts company elements
- [x] `plays/bfn890_veirmoellen/plot_branden.md` is created and casts company elements
- [x] `plays/bfn890_veirmoellen/plot_genopbygningen.md` is created and casts company elements
- [x] The local validation tests (`npm test`) run successfully with zero errors
