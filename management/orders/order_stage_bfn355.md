---
khai: order
title: "Stage BFN 355"
language: english
license: CC-BY-NC-SA-4.0
stamp:
  owner: KAI HACKS AI
  version: v0.0.1
  date: "2026-06-19"
---

# Order: Stage BFN 355

## Direction

The house must stage BFN 355 (_Storkene_) to establish the sixteenth production in the H.C. Andersen house. The production must model Storkemoderen, Storkeungerne, Drengene, Peer, the positions (Vogter, Novice, Mobber, Beskytter), the pieces (Reden, Sangen, Babyerne), the environments (Taget, Dammen, Byen), the wing practice and retribution processes, and the plots leading to their realization. It must be written in authentic Danish for all prose sections.

## Orders

1. The Playwright (Hans Christian Andersen) must author the play definition, the four personas, the four positions, the three pieces, the three places, the two processes, the two in-world plans, the pitch of Justice, and the four plots.
2. The Theatre Manager (Edvard Collin) must verify the local registry, ensure correct versioning, check formatting, and validate that the entire cast conforms to the canon.
3. The Roadie (Vilhelm Pedersen) must set the stage, verify the local test suite is green, and prepare the files for packaging.

## Implementation

The play files must be placed in `plays/bfn355_storkene/` and follow the house language policy:

- Structural elements and frontmatter in English.
- Narrative prose, projections, actions, shadows, tells, and staging notes in Danish.

## Targets

- [x] `plays/bfn355_storkene/play_storkene.md` is created and lists the complete company
- [x] `plays/bfn355_storkene/persona_storkemoderen.md` is created and links to `position_vogter.md`
- [x] `plays/bfn355_storkene/persona_storkeungerne.md` is created and links to `position_novice.md`
- [x] `plays/bfn355_storkene/persona_drengene.md` is created and links to `position_mobber.md`
- [x] `plays/bfn355_storkene/persona_peer.md` is created and links to `position_beskytter.md`
- [x] `plays/bfn355_storkene/position_vogter.md` is created
- [x] `plays/bfn355_storkene/position_novice.md` is created
- [x] `plays/bfn355_storkene/position_mobber.md` is created
- [x] `plays/bfn355_storkene/position_beskytter.md` is created
- [x] `plays/bfn355_storkene/piece_reden.md` is created
- [x] `plays/bfn355_storkene/piece_sangen.md` is created
- [x] `plays/bfn355_storkene/piece_babyer.md` is created
- [x] `plays/bfn355_storkene/place_taget.md` is created
- [x] `plays/bfn355_storkene/place_dammen.md` is created
- [x] `plays/bfn355_storkene/place_byen.md` is created
- [x] `plays/bfn355_storkene/process_vingeoevelse.md` is created
- [x] `plays/bfn355_storkene/process_gengaeldelse.md` is created
- [x] `plays/bfn355_storkene/plan_storkenes_plan.md` is created and linked to `persona_storkemoderen.md`
- [x] `plays/bfn355_storkene/plan_drengenes_plan.md` is created and linked to `persona_drengene.md`
- [x] `plays/bfn355_storkene/pitch_justice.md` is created
- [x] `plays/bfn355_storkene/plot_reden.md` is created and casts company elements
- [x] `plays/bfn355_storkene/plot_oevelsen.md` is created and casts company elements
- [x] `plays/bfn355_storkene/plot_udrejsen.md` is created and casts company elements
- [x] `plays/bfn355_storkene/plot_leveringen.md` is created and casts company elements
- [x] The local validation tests (`npm test`) run successfully with zero errors
