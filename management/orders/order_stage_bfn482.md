---
khai: order
title: "Stage BFN 482"
language: english
license: CC-BY-NC-SA-4.0
stamp:
  owner: KAI HACKS AI
  version: v0.0.1
  date: "2026-06-21"
---

# Order: Stage BFN 482

## Direction

The house must stage BFN 482 (_Stoppenaalen_) to establish the thirty-third production in the H.C. Andersen house. The production must model Stoppenaalen, Flasketuden, the positions (Hovmodig, Ydmyget), the piece (Lak), the environments (Køkkenet, Rendestenen), the knæk and pral processes, and the plots leading to their realization. It must be written in authentic Danish for all prose sections.

## Orders

1. The Playwright (Hans Christian Andersen) must author the play definition, the two personas, the two positions, the piece, the two places, the two processes, the in-world plan, the pitch of Satire og Stolthed, and the four plots.
2. The Theatre Manager (Edvard Collin) must verify the local registry, ensure correct versioning, check formatting, and validate that the entire cast conforms to the canon.
3. The Roadie (Vilhelm Pedersen) must set the stage, verify the local test suite is green, and prepare the files for packaging.

## Implementation

The play files must be placed in `plays/bfn482_stoppenaalen/` and follow the house language policy:

- Structural elements and frontmatter in English.
- Narrative prose, projections, actions, shadows, tells, and staging notes in Danish.

## Targets

- [x] `plays/bfn482_stoppenaalen/play_stoppenaalen.md` is created and lists the complete company
- [x] `plays/bfn482_stoppenaalen/persona_stoppenaalen.md` is created and links to `position_hovmodig.md`
- [x] `plays/bfn482_stoppenaalen/persona_flasketuden.md` is created and links to `position_ydmyget.md`
- [x] `plays/bfn482_stoppenaalen/position_hovmodig.md` is created
- [x] `plays/bfn482_stoppenaalen/position_ydmyget.md` is created
- [x] `plays/bfn482_stoppenaalen/piece_lak.md` is created
- [x] `plays/bfn482_stoppenaalen/place_koekkenet.md` is created
- [x] `plays/bfn482_stoppenaalen/place_rendestenen.md` is created
- [x] `plays/bfn482_stoppenaalen/process_knaek.md` is created
- [x] `plays/bfn482_stoppenaalen/process_pral.md` is created
- [x] `plays/bfn482_stoppenaalen/plan_stoppenaal_stolthed.md` is created and linked to `persona_stoppenaalen.md`
- [x] `plays/bfn482_stoppenaalen/pitch_satire_stolthed.md` is created
- [x] `plays/bfn482_stoppenaalen/plot_køkken.md` is created and casts company elements
- [x] `plays/bfn482_stoppenaalen/plot_rendesten.md` is created and casts company elements
- [x] `plays/bfn482_stoppenaalen/plot_drengene.md` is created and casts company elements
- [x] `plays/bfn482_stoppenaalen/plot_afslutningen.md` is created and casts company elements
- [x] The local validation tests (`npm test`) run successfully with zero errors
