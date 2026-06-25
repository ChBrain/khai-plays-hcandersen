---
khai: order
title: "Stage BFN 990 Kometen"
language: english
license: CC-BY-NC-SA-4.0
stamp:
  owner: KAI HACKS AI
  version: v0.0.1
  date: "2026-06-25"
---

# Order: Stage BFN 990 Kometen

## Direction

The house must stage BFN 990 (_Kometen_) to establish the hundred and fourteenth production in the H.C. Andersen house. The production must model Dreng and Komet, the positions (Undrende, Evig, Forgængelig), the pieces (Sæbeboble, Kikkert), the environments (Haven, Verdensrummet), the kredsløb and aldring processes, and the plots representing the child viewing the comet, the passing of decades, and the old man's final farewell. It must be written in authentic Danish for all prose sections.

## Orders

1. The Playwright (Hans Christian Andersen) must author the play definition, the two personas, the three positions, the two pieces, the two places, the two processes, the two in-world plans, the pitch of Evighed, and the three plots.
2. The Theatre Manager (Edvard Collin) must verify the local registry, ensure correct versioning, check formatting, and validate that the cast conforms to the canon.
3. The Roadie (Vilhelm Pedersen) must set the stage, verify the local test suite is green, and prepare the files for packaging.

## Implementation

The play files must be placed in `plays/bfn990_kometen/` and follow the house language policy:

- Structural elements and frontmatter in English.
- Narrative prose, projections, actions, shadows, tells, and staging notes in Danish.

## Targets

- [x] `plays/bfn990_kometen/play_kometen.md` is created and lists the complete company
- [x] `plays/bfn990_kometen/persona_dreng.md` is created and links to `position_undrende.md`
- [x] `plays/bfn990_kometen/persona_komet.md` is created and links to `position_evig.md`
- [x] `plays/bfn990_kometen/position_undrende.md` is created
- [x] `plays/bfn990_kometen/position_evig.md` is created
- [x] `plays/bfn990_kometen/position_forgaengelig.md` is created
- [x] `plays/bfn990_kometen/piece_saebeboble.md` is created
- [x] `plays/bfn990_kometen/piece_kikkert.md` is created
- [x] `plays/bfn990_kometen/place_haven.md` is created
- [x] `plays/bfn990_kometen/place_verdensrummet.md` is created
- [x] `plays/bfn990_kometen/process_kredsloeb.md` is created
- [x] `plays/bfn990_kometen/process_aldring.md` is created
- [x] `plays/bfn990_kometen/plan_iagttagelse.md` is created and linked to `persona_dreng.md`
- [x] `plays/bfn990_kometen/plan_leg.md` is created and linked to `persona_dreng.md`
- [x] `plays/bfn990_kometen/pitch_evighed.md` is created
- [x] `plays/bfn990_kometen/plot_barnet.md` is created and casts company elements
- [x] `plays/bfn990_kometen/plot_tiden.md` is created and casts company elements
- [x] `plays/bfn990_kometen/plot_afsked.md` is created and casts company elements
- [x] The local validation tests (`npm test`) run successfully with zero errors
