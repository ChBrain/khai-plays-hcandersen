---
khai: order
title: "Stage BFN 817 Hvad Fatter Gjoer"
language: english
license: CC-BY-NC-SA-4.0
stamp:
  owner: KAI HACKS AI
  version: v0.0.1
  date: "2026-06-24"
---

# Order: Stage BFN 817 Hvad Fatter Gjoer

## Direction

The house must stage BFN 817 (_Hvad Fatter gør, det er altid det Rigtige_) to establish the eightieth production in the H.C. Andersen house. The production must model Fatter, Mutter, the positions (Godtroende, Kaerlig), the piece (Hest), the environments (Marked, Hjem), the byttehandel and forloesning processes, and the plots leading to their realization. It must be written in authentic Danish for all prose sections.

## Orders

1. The Playwright (Hans Christian Andersen) must author the play definition, the two personas, the two positions, the piece, the two places, the two processes, the two in-world plans, the pitch of Komik, and the four plots.
2. The Theatre Manager (Edvard Collin) must verify the local registry, ensure correct versioning, check formatting, and validate that the entire cast conforms to the canon.
3. The Roadie (Vilhelm Pedersen) must set the stage, verify the local test suite is green, and prepare the files for packaging.

## Implementation

The play files must be placed in `plays/bfn817_hvad_fatter_gjoer/` and follow the house language policy:

- Structural elements and frontmatter in English.
- Narrative prose, projections, actions, shadows, tells, and staging notes in Danish.

## Targets

- [x] `plays/bfn817_hvad_fatter_gjoer/play_hvad_fatter_gjoer.md` is created and lists the complete company
- [x] `plays/bfn817_hvad_fatter_gjoer/persona_fatter.md` is created and links to `position_godtroende.md`
- [x] `plays/bfn817_hvad_fatter_gjoer/persona_mutter.md` is created and links to `position_kaerlig.md`
- [x] `plays/bfn817_hvad_fatter_gjoer/position_godtroende.md` is created
- [x] `plays/bfn817_hvad_fatter_gjoer/position_kaerlig.md` is created
- [x] `plays/bfn817_hvad_fatter_gjoer/piece_hest.md` is created
- [x] `plays/bfn817_hvad_fatter_gjoer/place_marked.md` is created
- [x] `plays/bfn817_hvad_fatter_gjoer/place_hjem.md` is created
- [x] `plays/bfn817_hvad_fatter_gjoer/process_byttehandel.md` is created
- [x] `plays/bfn817_hvad_fatter_gjoer/process_forloesning.md` is created
- [x] `plays/bfn817_hvad_fatter_gjoer/plan_bytte.md` is created and linked to `persona_fatter.md`
- [x] `plays/bfn817_hvad_fatter_gjoer/plan_modtagelse.md` is created and linked to `persona_mutter.md`
- [x] `plays/bfn817_hvad_fatter_gjoer/pitch_komik.md` is created
- [x] `plays/bfn817_hvad_fatter_gjoer/plot_udrejsen.md` is created and casts company elements
- [x] `plays/bfn817_hvad_fatter_gjoer/plot_byttehandelen.md` is created and casts company elements
- [x] `plays/bfn817_hvad_fatter_gjoer/plot_vaeddemaalet.md` is created and casts company elements
- [x] `plays/bfn817_hvad_fatter_gjoer/plot_hjemkomsten.md` is created and casts company elements
- [x] The local validation tests (`npm test`) run successfully with zero errors
