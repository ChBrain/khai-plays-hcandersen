---
khai: order
title: "Stage BFN 1018 Hvad hele Familien sagde"
language: english
license: CC-BY-NC-SA-4.0
stamp:
  owner: KAI HACKS AI
  version: v0.0.1
  date: "2026-06-25"
---

# Order: Stage BFN 1018 Hvad hele Familien sagde

## Direction

The house must stage BFN 1018 (_Hvad hele Familien sagde_) to establish the hundred and nineteenth production in the H.C. Andersen house. The production must model little Marie and Gudfader, their positions (Barn, Fortaeller), the pieces representing the birthday gift (Foedselsdagsgave) and the societal boundary (Plankevaerk), the environments of the parlor (Stuen) and the attic (Kvisten), the processes of affirming life (Livsbekraeftelse) and aging (Aldring), their plans of play (Leg) and storytelling (Fortaelling), the optimistic pitch, and the plots representing the birthday and the ultimate declaration of life as an adventure. It must be written in authentic Danish for all prose sections.

## Orders

1. The Playwright (Hans Christian Andersen) must author the play definition, the two personas, the two positions, the two pieces, the two places, the two processes, the two in-world plans, the pitch of Optimistisk, and the two plots.
2. The Theatre Manager (Edvard Collin) must verify the local registry, ensure correct versioning, check formatting, and validate that the cast conforms to the canon.
3. The Roadie (Vilhelm Pedersen) must set the stage, verify the local test suite is green, and prepare the files for packaging.

## Implementation

The play files must be placed in `plays/bfn1018_hvad_hele_familien_sagde/` and follow the house language policy:

- Structural elements and frontmatter in English.
- Narrative prose, projections, actions, shadows, tells, and staging notes in Danish.

## Targets

- [x] `plays/bfn1018_hvad_hele_familien_sagde/play_hvad_hele_familien_sagde.md` is created and lists the complete company
- [x] `plays/bfn1018_hvad_hele_familien_sagde/persona_marie.md` is created and links to `position_barn.md`
- [x] `plays/bfn1018_hvad_hele_familien_sagde/persona_gudfader.md` is created and links to `position_fortaeller.md`
- [x] `plays/bfn1018_hvad_hele_familien_sagde/position_barn.md` is created
- [x] `plays/bfn1018_hvad_hele_familien_sagde/position_fortaeller.md` is created
- [x] `plays/bfn1018_hvad_hele_familien_sagde/piece_foedselsdagsgave.md` is created
- [x] `plays/bfn1018_hvad_hele_familien_sagde/piece_plankevaerk.md` is created
- [x] `plays/bfn1018_hvad_hele_familien_sagde/place_stuen.md` is created
- [x] `plays/bfn1018_hvad_hele_familien_sagde/place_kvisten.md` is created
- [x] `plays/bfn1018_hvad_hele_familien_sagde/process_livsbekraeftelse.md` is created
- [x] `plays/bfn1018_hvad_hele_familien_sagde/process_aldring.md` is created
- [x] `plays/bfn1018_hvad_hele_familien_sagde/plan_leg.md` is created and linked to `persona_marie.md`
- [x] `plays/bfn1018_hvad_hele_familien_sagde/plan_fortaelling.md` is created and linked to `persona_gudfader.md`
- [x] `plays/bfn1018_hvad_hele_familien_sagde/pitch_optimistisk.md` is created
- [x] `plays/bfn1018_hvad_hele_familien_sagde/plot_foedselsdagen.md` is created and casts company elements
- [x] `plays/bfn1018_hvad_hele_familien_sagde/plot_livseventyret.md` is created and casts company elements
- [x] The local validation tests (`npm test`) run successfully with zero errors
