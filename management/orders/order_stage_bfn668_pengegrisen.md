---
khai: order
title: "Stage BFN 668 Pengegrisen"
language: english
license: CC-BY-NC-SA-4.0
stamp:
  owner: KAI HACKS AI
  version: v0.0.1
  date: "2026-06-23"
---

# Order: Stage BFN 668 Pengegrisen

## Direction

The house must stage BFN 668 (_Pengegrisen_) to establish the sixty-second production in the H.C. Andersen house. The production must model Pengegris, Legetoej, the positions (Hovmodig, Legefuld), the piece (Moent), the environments (Skab, Gulv), the opsparing and fald processes, and the plots leading to their realization. It must be written in authentic Danish for all prose sections.

## Orders

1. The Playwright (Hans Christian Andersen) must author the play definition, the two personas, the two positions, the piece, the two places, the two processes, the two in-world plans, the pitch of Satire, and the four plots.
2. The Theatre Manager (Edvard Collin) must verify the local registry, ensure correct versioning, check formatting, and validate that the entire cast conforms to the canon.
3. The Roadie (Vilhelm Pedersen) must set the stage, verify the local test suite is green, and prepare the files for packaging.

## Implementation

The play files must be placed in `plays/bfn668_pengegrisen/` and follow the house language policy:

- Structural elements and frontmatter in English.
- Narrative prose, projections, actions, shadows, tells, and staging notes in Danish.

## Targets

- [x] `plays/bfn668_pengegrisen/play_pengegrisen.md` is created and lists the complete company
- [x] `plays/bfn668_pengegrisen/persona_pengegris.md` is created and links to `position_hovmodig.md`
- [x] `plays/bfn668_pengegrisen/persona_legetoej.md` is created and links to `position_legefuld.md`
- [x] `plays/bfn668_pengegrisen/position_hovmodig.md` is created
- [x] `plays/bfn668_pengegrisen/position_legefuld.md` is created
- [x] `plays/bfn668_pengegrisen/piece_moent.md` is created
- [x] `plays/bfn668_pengegrisen/place_skab.md` is created
- [x] `plays/bfn668_pengegrisen/place_gulv.md` is created
- [x] `plays/bfn668_pengegrisen/process_opsparing.md` is created
- [x] `plays/bfn668_pengegrisen/process_fald.md` is created
- [x] `plays/bfn668_pengegrisen/plan_bevarelse.md` is created and linked to `persona_pengegris.md`
- [x] `plays/bfn668_pengegrisen/plan_underholdning.md` is created and linked to `persona_legetoej.md`
- [x] `plays/bfn668_pengegrisen/pitch_satire.md` is created
- [x] `plays/bfn668_pengegrisen/plot_overskud.md` is created and casts company elements
- [x] `plays/bfn668_pengegrisen/plot_komedie.md` is created and casts company elements
- [x] `plays/bfn668_pengegrisen/plot_fald.md` is created and casts company elements
- [x] `plays/bfn668_pengegrisen/plot_nybegyndelse.md` is created and casts company elements
- [x] The local validation tests (`npm test`) run successfully with zero errors
