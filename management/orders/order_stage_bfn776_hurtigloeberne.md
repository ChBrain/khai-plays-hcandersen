---
khai: order
title: "Stage BFN 776 Hurtigløberne"
language: english
license: CC-BY-NC-SA-4.0
stamp:
  owner: KAI HACKS AI
  version: v0.0.1
  date: "2026-06-26"
---

# Order: Stage BFN 776 Hurtigløberne

## Direction

The house must stage BFN 776 (_Hurtigløberne_) to establish a production in the H.C. Andersen house. The production must model haren, sneglen, uglen, the positions (hurtig, langsom, dommer), the pieces (pris, bane), the environments (skoven, maallinjen), the loebe and bedrag processes, and the plots representing loebet and dommen. It must be written in authentic Danish for all prose sections.

## Orders

1. The Playwright (Hans Christian Andersen) must author the play definition, the 3 personas, the 3 positions, the 2 pieces, the 2 places, the 2 processes, the 2 in-world plans, the pitch of satirisk, and the 2 plots.
2. The Theatre Manager (Edvard Collin) must verify the local registry, ensure correct versioning, check formatting, and validate that the cast conforms to the canon.
3. The Roadie (Vilhelm Pedersen) must set the stage, verify the local test suite is green, and prepare the files for packaging.

## Implementation

The play files must be placed in `plays/bfn776_hurtigloeberne/` and follow the house language policy:

- Structural elements and frontmatter in English.
- Narrative prose, projections, actions, shadows, tells, and staging notes in Danish.

## Targets

- [x] `plays/bfn776_hurtigloeberne/play_hurtigloeberne.md` is created and lists the complete company
- [x] `plays/bfn776_hurtigloeberne/persona_haren.md` is created and links to `position_hurtig.md`
- [x] `plays/bfn776_hurtigloeberne/persona_sneglen.md` is created and links to `position_langsom.md`
- [x] `plays/bfn776_hurtigloeberne/persona_uglen.md` is created and links to `position_dommer.md`
- [x] `plays/bfn776_hurtigloeberne/position_hurtig.md` is created
- [x] `plays/bfn776_hurtigloeberne/position_langsom.md` is created
- [x] `plays/bfn776_hurtigloeberne/position_dommer.md` is created
- [x] `plays/bfn776_hurtigloeberne/piece_pris.md` is created
- [x] `plays/bfn776_hurtigloeberne/piece_bane.md` is created
- [x] `plays/bfn776_hurtigloeberne/place_skoven.md` is created
- [x] `plays/bfn776_hurtigloeberne/place_maallinjen.md` is created
- [x] `plays/bfn776_hurtigloeberne/process_loebe.md` is created
- [x] `plays/bfn776_hurtigloeberne/process_bedrag.md` is created
- [x] `plays/bfn776_hurtigloeberne/plan_sejr.md` is created and linked to `persona_haren.md`
- [x] `plays/bfn776_hurtigloeberne/plan_aere.md` is created and linked to `persona_sneglen.md`
- [x] `plays/bfn776_hurtigloeberne/pitch_satirisk.md` is created
- [x] `plays/bfn776_hurtigloeberne/plot_loebet.md` is created and casts company elements
- [x] `plays/bfn776_hurtigloeberne/plot_dommen.md` is created and casts company elements
- [x] The local validation tests (`npm test`) run successfully with zero errors
