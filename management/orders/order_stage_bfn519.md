---
khai: order
title: "Stage BFN 519"
language: english
license: CC-BY-NC-SA-4.0
stamp:
  owner: KAI HACKS AI
  version: v0.0.1
  date: "2026-06-21"
---

# Order: Stage BFN 519

## Direction

The house must stage BFN 519 (_Lille Tuk_) to establish the thirty-seventh production in the H.C. Andersen house. The production must model Lille Tuk, Byerne, the positions (Pligtopfyldende, Vejviser), the piece (Geografibogen), the environments (Kammeret, Sjaelland), the pligt and droemmeri processes, and the plots leading to their realization. It must be written in authentic Danish for all prose sections.

## Orders

1. The Playwright (Hans Christian Andersen) must author the play definition, the two personas, the two positions, the piece, the two places, the two processes, the two in-world plans, the pitch of Poesi, and the four plots.
2. The Theatre Manager (Edvard Collin) must verify the local registry, ensure correct versioning, check formatting, and validate that the entire cast conforms to the canon.
3. The Roadie (Vilhelm Pedersen) must set the stage, verify the local test suite is green, and prepare the files for packaging.

## Implementation

The play files must be placed in `plays/bfn519_lille_tuk/` and follow the house language policy:

- Structural elements and frontmatter in English.
- Narrative prose, projections, actions, shadows, tells, and staging notes in Danish.

## Targets

- [x] `plays/bfn519_lille_tuk/play_lille_tuk.md` is created and lists the complete company
- [x] `plays/bfn519_lille_tuk/persona_lille_tuk.md` is created and links to `position_pligtopfyldende.md`
- [x] `plays/bfn519_lille_tuk/persona_byerne.md` is created and links to `position_vejviser.md`
- [x] `plays/bfn519_lille_tuk/position_pligtopfyldende.md` is created
- [x] `plays/bfn519_lille_tuk/position_vejviser.md` is created
- [x] `plays/bfn519_lille_tuk/piece_geografibogen.md` is created
- [x] `plays/bfn519_lille_tuk/place_kammeret.md` is created
- [x] `plays/bfn519_lille_tuk/place_sjaelland.md` is created
- [x] `plays/bfn519_lille_tuk/process_pligt.md` is created
- [x] `plays/bfn519_lille_tuk/process_droemmeri.md` is created
- [x] `plays/bfn519_lille_tuk/plan_lektielaesning.md` is created and linked to `persona_lille_tuk.md`
- [x] `plays/bfn519_lille_tuk/plan_aandelig_rejse.md` is created and linked to `persona_byerne.md`
- [x] `plays/bfn519_lille_tuk/pitch_poesi.md` is created
- [x] `plays/bfn519_lille_tuk/plot_aften.md` is created and casts company elements
- [x] `plays/bfn519_lille_tuk/plot_soevn.md` is created and casts company elements
- [x] `plays/bfn519_lille_tuk/plot_droemmerejse.md` is created and casts company elements
- [x] `plays/bfn519_lille_tuk/plot_morgen.md` is created and casts company elements
- [x] The local validation tests (`npm test`) run successfully with zero errors
