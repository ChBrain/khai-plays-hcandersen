---
khai: order
title: "Stage BFN 957 Peiter Peter og Peer"
language: english
license: CC-BY-NC-SA-4.0
stamp:
  owner: KAI HACKS AI
  version: v0.0.1
  date: "2026-06-25"
---

# Order: Stage BFN 957 Peiter Peter og Peer

## Direction

The house must stage BFN 957 (_Peiter, Peter og Peer_) to establish the hundred and sixth production in the H.C. Andersen house. The production must model Peiter, Peter, and Peer, the positions (Ældst, Mellem, Yngst), the pieces (Storkenæb, Svøb), the environments (Storkereden, Barnekammeret), the fødsel and opdragelse processes, and the plots representing the stork, the birth, the growth, and the journey. It must be written in authentic Danish for all prose sections.

## Orders

1. The Playwright (Hans Christian Andersen) must author the play definition, the three personas, the three positions, the two pieces, the two places, the two processes, the two in-world plans, the pitch of Livets begyndelse, and the four plots.
2. The Theatre Manager (Edvard Collin) must verify the local registry, ensure correct versioning, check formatting, and validate that the cast conforms to the canon.
3. The Roadie (Vilhelm Pedersen) must set the stage, verify the local test suite is green, and prepare the files for packaging.

## Implementation

The play files must be placed in `plays/bfn957_peiter_peter_og_peer/` and follow the house language policy:

- Structural elements and frontmatter in English.
- Narrative prose, projections, actions, shadows, tells, and staging notes in Danish.

## Targets

- [x] `plays/bfn957_peiter_peter_og_peer/play_peiter_peter_og_peer.md` is created and lists the complete company
- [x] `plays/bfn957_peiter_peter_og_peer/persona_peiter.md` is created and links to `position_aeldst.md`
- [x] `plays/bfn957_peiter_peter_og_peer/persona_peter.md` is created and links to `position_mellem.md`
- [x] `plays/bfn957_peiter_peter_og_peer/persona_peer.md` is created and links to `position_yngst.md`
- [x] `plays/bfn957_peiter_peter_og_peer/position_aeldst.md` is created
- [x] `plays/bfn957_peiter_peter_og_peer/position_mellem.md` is created
- [x] `plays/bfn957_peiter_peter_og_peer/position_yngst.md` is created
- [x] `plays/bfn957_peiter_peter_og_peer/piece_storkenaeb.md` is created
- [x] `plays/bfn957_peiter_peter_og_peer/piece_svoeb.md` is created
- [x] `plays/bfn957_peiter_peter_og_peer/place_storkereden.md` is created
- [x] `plays/bfn957_peiter_peter_og_peer/place_barnekammeret.md` is created
- [x] `plays/bfn957_peiter_peter_og_peer/process_foedsel.md` is created
- [x] `plays/bfn957_peiter_peter_og_peer/process_opdragelse.md` is created
- [x] `plays/bfn957_peiter_peter_og_peer/plan_livsvej.md` is created and linked to `persona_peiter.md`
- [x] `plays/bfn957_peiter_peter_og_peer/plan_livskraft.md` is created and linked to `persona_peer.md`
- [x] `plays/bfn957_peiter_peter_og_peer/pitch_livets_begyndelse.md` is created
- [x] `plays/bfn957_peiter_peter_og_peer/plot_storken.md` is created and casts company elements
- [x] `plays/bfn957_peiter_peter_og_peer/plot_foedslen.md` is created and casts company elements
- [x] `plays/bfn957_peiter_peter_og_peer/plot_opdragelsen.md` is created and casts company elements
- [x] `plays/bfn957_peiter_peter_og_peer/plot_rejsen.md` is created and casts company elements
- [x] The local validation tests (`npm test`) run successfully with zero errors
