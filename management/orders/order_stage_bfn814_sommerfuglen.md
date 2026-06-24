---
khai: order
title: "Stage BFN 814 Sommerfuglen"
language: english
license: CC-BY-NC-SA-4.0
stamp:
  owner: KAI HACKS AI
  version: v0.0.1
  date: "2026-06-24"
---

# Order: Stage BFN 814 Sommerfuglen

## Direction

The house must stage BFN 814 (_Sommerfuglen_) to establish the eighty-third production in the H.C. Andersen house. The production must model Sommerfugl, Blomst, the positions (Snoevsen, Ventende), the piece (Naal), the environments (Haven, Stuen), the kurmageri and fastlaasning processes, and the plots leading to their realization. It must be written in authentic Danish for all prose sections.

## Orders

1. The Playwright (Hans Christian Andersen) must author the play definition, the two personas, the two positions, the piece, the two places, the two processes, the two in-world plans, the pitch of Ironi, and the four plots.
2. The Theatre Manager (Edvard Collin) must verify the local registry, ensure correct versioning, check formatting, and validate that the cast conforms to the canon.
3. The Roadie (Vilhelm Pedersen) must set the stage, verify the local test suite is green, and prepare the files for packaging.

## Implementation

The play files must be placed in `plays/bfn814_sommerfuglen/` and follow the house language policy:

- Structural elements and frontmatter in English.
- Narrative prose, projections, actions, shadows, tells, and staging notes in Danish.

## Targets

- [x] `plays/bfn814_sommerfuglen/play_sommerfuglen.md` is created and lists the complete company
- [x] `plays/bfn814_sommerfuglen/persona_sommerfugl.md` is created and links to `position_snoevsen.md`
- [x] `plays/bfn814_sommerfuglen/persona_blomst.md` is created and links to `position_ventende.md`
- [x] `plays/bfn814_sommerfuglen/position_snoevsen.md` is created
- [x] `plays/bfn814_sommerfuglen/position_ventende.md` is created
- [x] `plays/bfn814_sommerfuglen/piece_naal.md` is created
- [x] `plays/bfn814_sommerfuglen/place_haven.md` is created
- [x] `plays/bfn814_sommerfuglen/place_stuen.md` is created
- [x] `plays/bfn814_sommerfuglen/process_kurmageri.md` is created
- [x] `plays/bfn814_sommerfuglen/process_fastlaasning.md` is created
- [x] `plays/bfn814_sommerfuglen/plan_valg.md` is created and linked to `persona_sommerfugl.md`
- [x] `plays/bfn814_sommerfuglen/plan_erindring.md` is created and linked to `persona_blomst.md`
- [x] `plays/bfn814_sommerfuglen/pitch_ironi.md` is created
- [x] `plays/bfn814_sommerfuglen/plot_foraarssmagen.md` is created and casts company elements
- [x] `plays/bfn814_sommerfuglen/plot_afvisningen.md` is created and casts company elements
- [x] `plays/bfn814_sommerfuglen/plot_efteraarsskumringen.md` is created and casts company elements
- [x] `plays/bfn814_sommerfuglen/plot_naalen.md` is created and casts company elements
- [x] The local validation tests (`npm test`) run successfully with zero errors
