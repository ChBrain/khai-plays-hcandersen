---
khai: order
title: "Stage BFN 1024 Hvad gamle Johanne fortalte"
language: english
license: CC-BY-NC-SA-4.0
stamp:
  owner: KAI HACKS AI
  version: v0.0.1
  date: "2026-06-25"
---

# Order: Stage BFN 1024 Hvad gamle Johanne fortalte

## Direction

The house must stage BFN 1024 (_Hvad gamle Johanne fortalte_) to establish the hundred and twenty-seventh production in the H.C. Andersen house. The production must model Rasmus (sølle Rasmus) and Johanne, their positions (Modloes, Trofast), the pieces representing the old willow tree (Piletrae) and the tailor's house (Skraedderhus), the environments of the village (Landsbyen) and the outside world (Verden), the processes of decay (Forfald) and care/concern (Omsorg), their plans of passivity (Passivitet) and holding onto memories (Erindring), the melancholic pitch, and the plots representing their childhood and the final decay and care. It must be written in authentic Danish for all prose sections.

## Orders

1. The Playwright (Hans Christian Andersen) must author the play definition, the two personas, the two positions, the two pieces, the two places, the two processes, the two in-world plans, the pitch of Melankolsk, and the two plots.
2. The Theatre Manager (Edvard Collin) must verify the local registry, ensure correct versioning, check formatting, and validate that the cast conforms to the canon.
3. The Roadie (Vilhelm Pedersen) must set the stage, verify the local test suite is green, and prepare the files for packaging.

## Implementation

The play files must be placed in `plays/bfn1024_hvad_gamle_johanne_fortalte/` and follow the house language policy:

- Structural elements and frontmatter in English.
- Narrative prose, projections, actions, shadows, tells, and staging notes in Danish.

## Targets

- [x] `plays/bfn1024_hvad_gamle_johanne_fortalte/play_hvad_gamle_johanne_fortalte.md` is created and lists the complete company
- [x] `plays/bfn1024_hvad_gamle_johanne_fortalte/persona_rasmus.md` is created and links to `position_modloes.md`
- [x] `plays/bfn1024_hvad_gamle_johanne_fortalte/persona_johanne.md` is created and links to `position_trofast.md`
- [x] `plays/bfn1024_hvad_gamle_johanne_fortalte/position_modloes.md` is created
- [x] `plays/bfn1024_hvad_gamle_johanne_fortalte/position_trofast.md` is created
- [x] `plays/bfn1024_hvad_gamle_johanne_fortalte/piece_piletrae.md` is created
- [x] `plays/bfn1024_hvad_gamle_johanne_fortalte/piece_skraedderhus.md` is created
- [x] `plays/bfn1024_hvad_gamle_johanne_fortalte/place_landsbyen.md` is created
- [x] `plays/bfn1024_hvad_gamle_johanne_fortalte/place_verden.md` is created
- [x] `plays/bfn1024_hvad_gamle_johanne_fortalte/process_forfald.md` is created
- [x] `plays/bfn1024_hvad_gamle_johanne_fortalte/process_omsorg.md` is created
- [x] `plays/bfn1024_hvad_gamle_johanne_fortalte/plan_passivitet.md` is created and linked to `persona_rasmus.md`
- [x] `plays/bfn1024_hvad_gamle_johanne_fortalte/plan_erindring.md` is created and linked to `persona_johanne.md`
- [x] `plays/bfn1024_hvad_gamle_johanne_fortalte/pitch_melankolsk.md` is created
- [x] `plays/bfn1024_hvad_gamle_johanne_fortalte/plot_barndommen.md` is created and casts company elements
- [x] `plays/bfn1024_hvad_gamle_johanne_fortalte/plot_forfaldet.md` is created and casts company elements
- [x] The local validation tests (`npm test`) run successfully with zero errors
