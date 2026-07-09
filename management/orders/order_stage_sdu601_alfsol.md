---
khai: order
title: "Stage SDU 601"
language: english
license: CC-BY-NC-SA-4.0
stamp:
  owner: KAI HACKS AI
  version: v0.0.1
  date: "2026-07-09"
---

# Order: Stage SDU 601

## Direction

The house must stage SDU 601 (_Alfsol_) to establish the first work in the "Drama" genre. The production must model the early romantic tragedy in five acts, featuring the tragic princess Alfsol, the invading Swedish king Sigurd Ring, and the malicious blind Bolvise. It must model the temple altar, the battlefield, the fatal altar cup, the prophesy and sacrifice processes, and the tragic outcome. All staging, prose, projections, actions, shadows, and tells must be authored in authentic Danish.

## Orders

1. The Playwright (Hans Christian Andersen) must author the play definition, the three personas (Alfsol, SigurdRing, Bolvise), the two positions (helt, skaebne), the one piece (alterbaeger), the two places (templet, slagmarken), the two processes (spaadom, ofring), the in-world plan (erobring), the pitch (tragisk), and the three plots.
2. The Theatre Manager (Edvard Collin) must verify the local registry, ensure correct versioning, check formatting, and validate that the entire cast conforms to the canon.
3. The Roadie (Vilhelm Pedersen) must set the stage, verify the local test suite is green, and prepare the files for packaging.

## Implementation

The play files must be placed in `plays/sdu601_alfsol/` and follow the house language policy:

- Structural elements and frontmatter in English.
- Narrative prose, projections, actions, shadows, tells, and staging notes in Danish.

## Targets

- [x] `plays/sdu601_alfsol/play_alfsol.md` is created and lists the complete company
- [x] `plays/sdu601_alfsol/persona_alfsol.md` is created and links to `position_skaebne.md` or rather has its own role
- [x] `plays/sdu601_alfsol/persona_sigurd_ring.md` is created and links to `position_helt.md`
- [x] `plays/sdu601_alfsol/persona_bolvise.md` is created and links to `position_skaebne.md`
- [x] `plays/sdu601_alfsol/position_helt.md` is created
- [x] `plays/sdu601_alfsol/position_skaebne.md` is created
- [x] `plays/sdu601_alfsol/piece_alterbaeger.md` is created
- [x] `plays/sdu601_alfsol/place_templet.md` is created
- [x] `plays/sdu601_alfsol/place_slagmarken.md` is created
- [x] `plays/sdu601_alfsol/process_spaadom.md` is created
- [x] `plays/sdu601_alfsol/process_ofring.md` is created
- [x] `plays/sdu601_alfsol/plan_erobring.md` is created
- [x] `plays/sdu601_alfsol/pitch_tragisk.md` is created
- [x] `plays/sdu601_alfsol/plot_spaadommen.md` is created and casts company elements
- [x] `plays/sdu601_alfsol/plot_erobringen.md` is created and casts company elements
- [x] `plays/sdu601_alfsol/plot_ofringen.md` is created and casts company elements
- [x] The local validation tests (`npm test`) run successfully with zero errors
