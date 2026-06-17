---
khai: order
title: "Stage BFN 268"
language: english
license: CC-BY-NC-SA-4.0
stamp:
  owner: KAI HACKS AI
  version: v0.0.1
  date: "2026-06-17"
---

# Order: Stage BFN 268

## Direction

The house must stage BFN 268 (_Lille Claus og store Claus_) to establish the third production in the H.C. Andersen house. The production must model Lille Claus, Store Claus, the sexton (Degnen), the grandmother, the horse hide, the chest of silver, the cattle, the environments (hut, mill, and riverbank), the trade and deception processes, and the plots leading to Store Claus's demise. It must be written in authentic Danish for all prose sections.

## Orders

1. The Playwright (Hans Christian Andersen) must author the play definition, the four personas (Lille Claus, Store Claus, Degnen, Bedstemoderen), the three positions (bonde, spion, lokkedue), the three pieces (hestehuden, pengeskrappen, kvaeget), the three places (hytten, moellen, aaen), the two processes (byttehandel, bedraget), the two in-world plans (lille claus plan, store claus plan), and the four plots.
2. The Theatre Manager (Edvard Collin) must verify the local registry, ensure correct versioning, check formatting, and validate that the entire cast conforms to the canon.
3. The Roadie (Vilhelm Pedersen) must set the stage, verify the local test suite is green, and prepare the files for packaging.

## Implementation

The play files must be placed in `plays/bfn268_lille_claus_og_store_claus/` and follow the house language policy:

- Structural elements and frontmatter in English.
- Narrative prose, projections, actions, shadows, tells, and staging notes in Danish.

## Targets

- [x] `plays/bfn268_lille_claus_og_store_claus/play_lille_claus.md` is created and lists the complete company
- [x] `plays/bfn268_lille_claus_og_store_claus/persona_lille_claus.md` is created and links to `position_bonde.md`
- [x] `plays/bfn268_lille_claus_og_store_claus/persona_store_claus.md` is created and links to `position_bonde.md`
- [x] `plays/bfn268_lille_claus_og_store_claus/persona_degnen.md` is created and links to `position_spion.md`
- [x] `plays/bfn268_lille_claus_og_store_claus/persona_bedstemoderen.md` is created and links to `position_lokkedue.md`
- [x] `plays/bfn268_lille_claus_og_store_claus/position_bonde.md` is created
- [x] `plays/bfn268_lille_claus_og_store_claus/position_spion.md` is created
- [x] `plays/bfn268_lille_claus_og_store_claus/position_lokkedue.md` is created
- [x] `plays/bfn268_lille_claus_og_store_claus/piece_hestehuden.md` is created
- [x] `plays/bfn268_lille_claus_og_store_claus/piece_pengeskrappen.md` is created
- [x] `plays/bfn268_lille_claus_og_store_claus/piece_kvaeget.md` is created
- [x] `plays/bfn268_lille_claus_og_store_claus/place_hytten.md` is created
- [x] `plays/bfn268_lille_claus_og_store_claus/place_moellen.md` is created
- [x] `plays/bfn268_lille_claus_og_store_claus/place_aaen.md` is created
- [x] `plays/bfn268_lille_claus_og_store_claus/process_byttehandel.md` is created
- [x] `plays/bfn268_lille_claus_og_store_claus/process_bedraget.md` is created
- [x] `plays/bfn268_lille_claus_og_store_claus/plan_lille_claus_plan.md` is created and linked to `persona_lille_claus.md`
- [x] `plays/bfn268_lille_claus_og_store_claus/plan_store_claus_plan.md` is created and linked to `persona_store_claus.md`
- [x] `plays/bfn268_lille_claus_og_store_claus/plot_hestene.md` is created and casts company elements
- [x] `plays/bfn268_lille_claus_og_store_claus/plot_spaa_manden.md` is created and casts company elements
- [x] `plays/bfn268_lille_claus_og_store_claus/plot_bedstemoderen.md` is created and casts company elements
- [x] `plays/bfn268_lille_claus_og_store_claus/plot_aaen.md` is created and casts company elements
- [x] The local validation tests (`npm test`) run successfully with zero errors
