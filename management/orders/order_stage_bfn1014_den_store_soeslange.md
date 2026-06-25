---
khai: order
title: "Stage BFN 1014 Den store Soeslange"
language: english
license: CC-BY-NC-SA-4.0
stamp:
  owner: KAI HACKS AI
  version: v0.0.1
  date: "2026-06-25"
---

# Order: Stage BFN 1014 Den store Soeslange

## Direction

The house must stage BFN 1014 (_Den store Søslange_) to establish the hundred and twenty-fifth production in the H.C. Andersen house. The production must model Havfisken (the curious fish) and Havkoen (the skeptic sea cow), their positions (Undrende, Skeptisk), the pieces representing the telegraph cable (Telegrafkabel) and the deep ocean (Dybhavet), the environments of the Atlantic floor (Atlantens bund) and the surface (Overfladen), the processes of signal transmission (Telegrafering) and confusion/panic (Forvirring), their plans of communication (Kommunikation) and avoidance (Undvigelse), the allegorical pitch, and the plots representing the lowering of the cable and the debate among the sea creatures. It must be written in authentic Danish for all prose sections.

## Orders

1. The Playwright (Hans Christian Andersen) must author the play definition, the two personas, the two positions, the two pieces, the two places, the two processes, the two in-world plans, the pitch of Allegorisk, and the two plots.
2. The Theatre Manager (Edvard Collin) must verify the local registry, ensure correct versioning, check formatting, and validate that the cast conforms to the canon.
3. The Roadie (Vilhelm Pedersen) must set the stage, verify the local test suite is green, and prepare the files for packaging.

## Implementation

The play files must be placed in `plays/bfn1014_den_store_soeslange/` and follow the house language policy:

- Structural elements and frontmatter in English.
- Narrative prose, projections, actions, shadows, tells, and staging notes in Danish.

## Targets

- [x] `plays/bfn1014_den_store_soeslange/play_den_store_soeslange.md` is created and lists the complete company
- [x] `plays/bfn1014_den_store_soeslange/persona_havfisken.md` is created and links to `position_undrende.md`
- [x] `plays/bfn1014_den_store_soeslange/persona_havkoen.md` is created and links to `position_skeptisk.md`
- [x] `plays/bfn1014_den_store_soeslange/position_undrende.md` is created
- [x] `plays/bfn1014_den_store_soeslange/position_skeptisk.md` is created
- [x] `plays/bfn1014_den_store_soeslange/piece_telegrafkabel.md` is created
- [x] `plays/bfn1014_den_store_soeslange/piece_dybhavet.md` is created
- [x] `plays/bfn1014_den_store_soeslange/place_atlantens_bund.md` is created
- [x] `plays/bfn1014_den_store_soeslange/place_overfladen.md` is created
- [x] `plays/bfn1014_den_store_soeslange/process_telegrafering.md` is created
- [x] `plays/bfn1014_den_store_soeslange/process_forvirring.md` is created
- [x] `plays/bfn1014_den_store_soeslange/plan_kommunikation.md` is created and linked to `persona_havfisken.md`
- [x] `plays/bfn1014_den_store_soeslange/plan_undvigelse.md` is created and linked to `persona_havkoen.md`
- [x] `plays/bfn1014_den_store_soeslange/pitch_allegorisk.md` is created
- [x] `plays/bfn1014_den_store_soeslange/plot_nedlaeggelsen.md` is created and casts company elements
- [x] `plays/bfn1014_den_store_soeslange/plot_debatten.md` is created and casts company elements
- [x] The local validation tests (`npm test`) run successfully with zero errors
