---
khai: order
title: "Stage BFN 841 Sommergjaekken"
language: english
license: CC-BY-NC-SA-4.0
stamp:
  owner: KAI HACKS AI
  version: v0.0.1
  date: "2026-06-24"
---

# Order: Stage BFN 841 Sommergjaekken

## Direction

The house must stage BFN 841 (_Sommergjækken_) to establish the ninety-first production in the H.C. Andersen house. The production must model Blomst, Brevskriver, the positions (Bebuder, Bevarer), the piece (Bog), the environments (Sne, Sider), the spiring and presning processes, and the plots leading to their realization. It must be written in authentic Danish for all prose sections.

## Orders

1. The Playwright (Hans Christian Andersen) must author the play definition, the two personas, the two positions, the piece, the two places, the two processes, the two in-world plans, the pitch of Nostalgi, and the four plots.
2. The Theatre Manager (Edvard Collin) must verify the local registry, ensure correct versioning, check formatting, and validate that the cast conforms to the canon.
3. The Roadie (Vilhelm Pedersen) must set the stage, verify the local test suite is green, and prepare the files for packaging.

## Implementation

The play files must be placed in `plays/bfn841_sommergjaekken/` and follow the house language policy:

- Structural elements and frontmatter in English.
- Narrative prose, projections, actions, shadows, tells, and staging notes in Danish.

## Targets

- [x] `plays/bfn841_sommergjaekken/play_sommergjaekken.md` is created and lists the complete company
- [x] `plays/bfn841_sommergjaekken/persona_blomst.md` is created and links to `position_bebuder.md`
- [x] `plays/bfn841_sommergjaekken/persona_brevskriver.md` is created and links to `position_bevarer.md`
- [x] `plays/bfn841_sommergjaekken/position_bebuder.md` is created
- [x] `plays/bfn841_sommergjaekken/position_bevarer.md` is created
- [x] `plays/bfn841_sommergjaekken/piece_bog.md` is created
- [x] `plays/bfn841_sommergjaekken/place_sne.md` is created
- [x] `plays/bfn841_sommergjaekken/place_sider.md` is created
- [x] `plays/bfn841_sommergjaekken/process_spiring.md` is created
- [x] `plays/bfn841_sommergjaekken/process_presning.md` is created
- [x] `plays/bfn841_sommergjaekken/plan_overlevelse.md` is created and linked to `persona_blomst.md`
- [x] `plays/bfn841_sommergjaekken/plan_erindring.md` is created and linked to `persona_brevskriver.md`
- [x] `plays/bfn841_sommergjaekken/pitch_nostalgi.md` is created
- [x] `plays/bfn841_sommergjaekken/plot_vaekningen.md` is created and casts company elements
- [x] `plays/bfn841_sommergjaekken/plot_plukningen.md` is created and casts company elements
- [x] `plays/bfn841_sommergjaekken/plot_presningen.md` is created and casts company elements
- [x] `plays/bfn841_sommergjaekken/plot_efterlivet.md` is created and casts company elements
- [x] The local validation tests (`npm test`) run successfully with zero errors
