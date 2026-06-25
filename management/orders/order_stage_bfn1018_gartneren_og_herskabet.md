---
khai: order
title: "Stage BFN 1018 Gartneren og Herskabet"
language: english
license: CC-BY-NC-SA-4.0
stamp:
  owner: KAI HACKS AI
  version: v0.0.1
  date: "2026-06-25"
---

# Order: Stage BFN 1018 Gartneren og Herskabet

## Direction

The house must stage BFN 1018 (_Gartneren og Herskabet_) to establish the hundred and twenty-sixth production in the H.C. Andersen house. The production must model gartner Larsen and the noble family (Herskabet), their positions (Gartner, Herre), the pieces representing the prized fruit (Frugt) and the old rook trees (Raegetraeer), the environments of the manor garden (Herregaardshaven) and the outside world (Verden), the processes of cultivation (Dyrkning) and denial (Fornaegtelse), their plans of improvement (Forbedring) and conservation (Konservering), the satirical pitch, and the plots representing the garden labor, the external recognition with internal denial, and the storm blowing down the rook trees. It must be written in authentic Danish for all prose sections.

## Orders

1. The Playwright (Hans Christian Andersen) must author the play definition, the two personas, the two positions, the two pieces, the two places, the two processes, the two in-world plans, the pitch of Satirisk, and the three plots.
2. The Theatre Manager (Edvard Collin) must verify the local registry, ensure correct versioning, check formatting, and validate that the cast conforms to the canon.
3. The Roadie (Vilhelm Pedersen) must set the stage, verify the local test suite is green, and prepare the files for packaging.

## Implementation

The play files must be placed in `plays/bfn1018_gartneren_og_herskabet/` and follow the house language policy:

- Structural elements and frontmatter in English.
- Narrative prose, projections, actions, shadows, tells, and staging notes in Danish.

## Targets

- [x] `plays/bfn1018_gartneren_og_herskabet/play_gartneren_og_herskabet.md` is created and lists the complete company
- [x] `plays/bfn1018_gartneren_og_herskabet/persona_larsen.md` is created and links to `position_gartner.md`
- [x] `plays/bfn1018_gartneren_og_herskabet/persona_herskabet.md` is created and links to `position_herre.md`
- [x] `plays/bfn1018_gartneren_og_herskabet/position_gartner.md` is created
- [x] `plays/bfn1018_gartneren_og_herskabet/position_herre.md` is created
- [x] `plays/bfn1018_gartneren_og_herskabet/piece_frugt.md` is created
- [x] `plays/bfn1018_gartneren_og_herskabet/piece_raegetraeer.md` is created
- [x] `plays/bfn1018_gartneren_og_herskabet/place_herregaardshaven.md` is created
- [x] `plays/bfn1018_gartneren_og_herskabet/place_verden.md` is created
- [x] `plays/bfn1018_gartneren_og_herskabet/process_dyrkning.md` is created
- [x] `plays/bfn1018_gartneren_og_herskabet/process_fornaegtelse.md` is created
- [x] `plays/bfn1018_gartneren_og_herskabet/plan_forbedring.md` is created and linked to `persona_larsen.md`
- [x] `plays/bfn1018_gartneren_og_herskabet/plan_konservering.md` is created and linked to `persona_herskabet.md`
- [x] `plays/bfn1018_gartneren_og_herskabet/pitch_satirisk.md` is created
- [x] `plays/bfn1018_gartneren_og_herskabet/plot_haven.md` is created and casts company elements
- [x] `plays/bfn1018_gartneren_og_herskabet/plot_anerkendelsen.md` is created and casts company elements
- [x] `plays/bfn1018_gartneren_og_herskabet/plot_stormen.md` is created and casts company elements
- [x] The local validation tests (`npm test`) run successfully with zero errors
