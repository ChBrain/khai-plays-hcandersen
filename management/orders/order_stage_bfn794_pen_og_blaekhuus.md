---
khai: order
title: "Stage BFN 794 Pen og Blaekhuus"
language: english
license: CC-BY-NC-SA-4.0
stamp:
  owner: KAI HACKS AI
  version: v0.0.1
  date: "2026-06-23"
---

# Order: Stage BFN 794 Pen og Blaekhuus

## Direction

The house must stage BFN 794 (_Pen og Blækhuus_) to establish the seventy-fifth production in the H.C. Andersen house. The production must model Pen, Blaekhuus, the positions (Skabende, Beholder), the piece (Blaek), the environments (Skrivebord, Papir), the inspiration and udfoerelse processes, and the plots leading to their realization. It must be written in authentic Danish for all prose sections.

## Orders

1. The Playwright (Hans Christian Andersen) must author the play definition, the two personas, the two positions, the piece, the two places, the two processes, the two in-world plans, the pitch of Ironi, and the four plots.
2. The Theatre Manager (Edvard Collin) must verify the local registry, ensure correct versioning, check formatting, and validate that the entire cast conforms to the canon.
3. The Roadie (Vilhelm Pedersen) must set the stage, verify the local test suite is green, and prepare the files for packaging.

## Implementation

The play files must be placed in `plays/bfn794_pen_og_blaekhuus/` and follow the house language policy:

- Structural elements and frontmatter in English.
- Narrative prose, projections, actions, shadows, tells, and staging notes in Danish.

## Targets

- [x] `plays/bfn794_pen_og_blaekhuus/play_pen_og_blaekhuus.md` is created and lists the complete company
- [x] `plays/bfn794_pen_og_blaekhuus/persona_pen.md` is created and links to `position_skabende.md`
- [x] `plays/bfn794_pen_og_blaekhuus/persona_blaekhuus.md` is created and links to `position_beholder.md`
- [x] `plays/bfn794_pen_og_blaekhuus/position_skabende.md` is created
- [x] `plays/bfn794_pen_og_blaekhuus/position_beholder.md` is created
- [x] `plays/bfn794_pen_og_blaekhuus/piece_blaek.md` is created
- [x] `plays/bfn794_pen_og_blaekhuus/place_skrivebord.md` is created
- [x] `plays/bfn794_pen_og_blaekhuus/place_papir.md` is created
- [x] `plays/bfn794_pen_og_blaekhuus/process_inspiration.md` is created
- [x] `plays/bfn794_pen_og_blaekhuus/process_udfoerelse.md` is created
- [x] `plays/bfn794_pen_og_blaekhuus/plan_selvros.md` is created and linked to `persona_pen.md`
- [x] `plays/bfn794_pen_og_blaekhuus/plan_indholdshyldest.md` is created and linked to `persona_blaekhuus.md`
- [x] `plays/bfn794_pen_og_blaekhuus/pitch_ironi.md` is created
- [x] `plays/bfn794_pen_og_blaekhuus/plot_skrivebordet.md` is created and casts company elements
- [x] `plays/bfn794_pen_og_blaekhuus/plot_digtningen.md` is created and casts company elements
- [x] `plays/bfn794_pen_og_blaekhuus/plot_striden.md` is created and casts company elements
- [x] `plays/bfn794_pen_og_blaekhuus/plot_natten.md` is created and casts company elements
- [x] The local validation tests (`npm test`) run successfully with zero errors
