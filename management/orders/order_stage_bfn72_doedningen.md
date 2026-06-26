---
khai: order
title: "Stage BFN 72 Dødningen"
language: english
license: CC-BY-NC-SA-4.0
stamp:
  owner: KAI HACKS AI
  version: v0.0.1
  date: "2026-06-26"
---

# Order: Stage BFN 72 Dødningen

## Direction

The house must stage BFN 72 (_Dødningen_) to establish a production in the H.C. Andersen house. The production must model johannes, doedningen, the positions (rejsende, hjaelper), the pieces (arvepenge, svaerd), the environments (kirken, vejen), the rejse and magi processes, and the plots representing afrejsen and hjaelpen. It must be written in authentic Danish for all prose sections.

## Orders

1. The Playwright (Hans Christian Andersen) must author the play definition, the 2 personas, the 2 positions, the 2 pieces, the 2 places, the 2 processes, the 1 in-world plans, the pitch of mystisk, and the 2 plots.
2. The Theatre Manager (Edvard Collin) must verify the local registry, ensure correct versioning, check formatting, and validate that the cast conforms to the canon.
3. The Roadie (Vilhelm Pedersen) must set the stage, verify the local test suite is green, and prepare the files for packaging.

## Implementation

The play files must be placed in `plays/bfn72_doedningen/` and follow the house language policy:

- Structural elements and frontmatter in English.
- Narrative prose, projections, actions, shadows, tells, and staging notes in Danish.

## Targets

- [x] `plays/bfn72_doedningen/play_doedningen.md` is created and lists the complete company
- [x] `plays/bfn72_doedningen/persona_johannes.md` is created and links to `position_rejsende.md`
- [x] `plays/bfn72_doedningen/persona_doedningen.md` is created and links to `position_hjaelper.md`
- [x] `plays/bfn72_doedningen/position_rejsende.md` is created
- [x] `plays/bfn72_doedningen/position_hjaelper.md` is created
- [x] `plays/bfn72_doedningen/piece_arvepenge.md` is created
- [x] `plays/bfn72_doedningen/piece_svaerd.md` is created
- [x] `plays/bfn72_doedningen/place_kirken.md` is created
- [x] `plays/bfn72_doedningen/place_vejen.md` is created
- [x] `plays/bfn72_doedningen/process_rejse.md` is created
- [x] `plays/bfn72_doedningen/process_magi.md` is created
- [x] `plays/bfn72_doedningen/plan_rejse.md` is created and linked to `persona_johannes.md`
- [x] `plays/bfn72_doedningen/pitch_mystisk.md` is created
- [x] `plays/bfn72_doedningen/plot_afrejsen.md` is created and casts company elements
- [x] `plays/bfn72_doedningen/plot_hjaelpen.md` is created and casts company elements
- [x] The local validation tests (`npm test`) run successfully with zero errors
