---
khai: order
title: "Stage SDU 502"
language: english
license: CC-BY-NC-SA-4.0
stamp:
  owner: KAI HACKS AI
  version: v0.0.1
  date: "2026-07-09"
---

# Order: Stage SDU 502

## Direction

The house must stage SDU 502 (_Fodreise fra Holmens Canal til Østpynten af Amager i Aarene 1828 og 1829_) to establish the second work in the "Anden Prosa" genre. The production must model the chaotic, satirical, and fantastic journey of the young narrator who is tempted by Satan to become an author. It must model the 100-mile boots borrowed from Jerusalems Skomager, the starting point at Holmens Kanal, the destination at Amager, the glimpse into Hell, and the final completion of the text. All staging, prose, projections, actions, shadows, and tells must be authored in authentic Danish.

## Orders

1. The Playwright (Hans Christian Andersen) must author the play definition, the three personas (Fortaelleren, Satan, Skomageren), the two positions (digter, frister), the one piece (milestoevler), the three places (holmens_canal, amager, helvede), the two processes (fantasirejse, fristelse), the in-world plan (fodrejse), the pitch (satirisk), and the three plots.
2. The Theatre Manager (Edvard Collin) must verify the local registry, ensure correct versioning, check formatting, and validate that the entire cast conforms to the canon.
3. The Roadie (Vilhelm Pedersen) must set the stage, verify the local test suite is green, and prepare the files for packaging.

## Implementation

The play files must be placed in `plays/sdu52_fodreise/` or rather `plays/sdu502_fodreise/` and follow the house language policy:

- Structural elements and frontmatter in English.
- Narrative prose, projections, actions, shadows, tells, and staging notes in Danish.

## Targets

- [x] `plays/sdu502_fodreise/play_fodreise.md` is created and lists the complete company
- [x] `plays/sdu502_fodreise/persona_fortaelleren.md` is created and links to `position_digter.md`
- [x] `plays/sdu502_fodreise/persona_satan.md` is created and links to `position_frister.md`
- [x] `plays/sdu502_fodreise/persona_skomageren.md` is created
- [x] `plays/sdu502_fodreise/position_digter.md` is created
- [x] `plays/sdu502_fodreise/position_frister.md` is created
- [x] `plays/sdu502_fodreise/piece_milestoevler.md` is created
- [x] `plays/sdu502_fodreise/place_holmens_canal.md` is created
- [x] `plays/sdu502_fodreise/place_amager.md` is created
- [x] `plays/sdu502_fodreise/place_helvede.md` is created
- [x] `plays/sdu502_fodreise/process_fantasirejse.md` is created
- [x] `plays/sdu502_fodreise/process_fristelse.md` is created
- [x] `plays/sdu502_fodreise/plan_fodrejse.md` is created
- [x] `plays/sdu502_fodreise/pitch_satirisk.md` is created
- [x] `plays/sdu502_fodreise/plot_nytaarsaften.md` is created and casts company elements
- [x] `plays/sdu502_fodreise/plot_stoevelrejsen.md` is created and casts company elements
- [x] `plays/sdu502_fodreise/plot_helvedessynet.md` is created and casts company elements
- [x] The local validation tests (`npm test`) run successfully with zero errors
