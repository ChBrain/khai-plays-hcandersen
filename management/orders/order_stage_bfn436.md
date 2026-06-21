---
khai: order
title: "Stage BFN 436"
language: english
license: CC-BY-NC-SA-4.0
stamp:
  owner: KAI HACKS AI
  version: v0.0.1
  date: "2026-06-20"
---

# Order: Stage BFN 436

## Direction

The house must stage BFN 436 (_Nattergalen_) to establish the twenty-second production in the H.C. Andersen house. The production must model Nattergalen, Kejseren, Kunstfuglen, Døden, the positions (Sanger, Hersker, Mekanisme, Gæst), the pieces (Mekanisk_Urværk, Kejserlige_Insignier, Tårerne), the environments (Skoven, Paladset, Dødslejet), the silver song and winding processes, and the plots leading to their realization. It must be written in authentic Danish for all prose sections.

## Orders

1. The Playwright (Hans Christian Andersen) must author the play definition, the four personas, the four positions, the three pieces, the three places, the two processes, the two in-world plans, the pitch of Artistic Freedom, and the four plots.
2. The Theatre Manager (Edvard Collin) must verify the local registry, ensure correct versioning, check formatting, and validate that the entire cast conforms to the canon.
3. The Roadie (Vilhelm Pedersen) must set the stage, verify the local test suite is green, and prepare the files for packaging.

## Implementation

The play files must be placed in `plays/bfn436_nattergalen/` and follow the house language policy:

- Structural elements and frontmatter in English.
- Narrative prose, projections, actions, shadows, tells, and staging notes in Danish.

## Targets

- [x] `plays/bfn436_nattergalen/play_nattergalen.md` is created and lists the complete company
- [x] `plays/bfn436_nattergalen/persona_nattergalen.md` is created and links to `position_sanger.md`
- [x] `plays/bfn436_nattergalen/persona_kejseren.md` is created and links to `position_hersker.md`
- [x] `plays/bfn436_nattergalen/persona_kunstfuglen.md` is created and links to `position_mekanisme.md`
- [x] `plays/bfn436_nattergalen/persona_doeden.md` is created and links to `position_gaest.md`
- [x] `plays/bfn436_nattergalen/position_sanger.md` is created
- [x] `plays/bfn436_nattergalen/position_hersker.md` is created
- [x] `plays/bfn436_nattergalen/position_mekanisme.md` is created
- [x] `plays/bfn436_nattergalen/position_gaest.md` is created
- [x] `plays/bfn436_nattergalen/piece_mekanisk_urvaerk.md` is created
- [x] `plays/bfn436_nattergalen/piece_kejserlige_insignier.md` is created
- [x] `plays/bfn436_nattergalen/piece_taarerne.md` is created
- [x] `plays/bfn436_nattergalen/place_skoven.md` is created
- [x] `plays/bfn436_nattergalen/place_paladset.md` is created
- [x] `plays/bfn436_nattergalen/place_doedslejet.md` is created
- [x] `plays/bfn436_nattergalen/process_soelvklang.md` is created
- [x] `plays/bfn436_nattergalen/process_optraekning.md` is created
- [x] `plays/bfn436_nattergalen/plan_nattergalens_frihed.md` is created and linked to `persona_nattergalen.md`
- [x] `plays/bfn436_nattergalen/plan_hofstatens_pragt.md` is created and linked to `persona_kunstfuglen.md`
- [x] `plays/bfn436_nattergalen/pitch_kunstnerisk_frihed.md` is created
- [x] `plays/bfn436_nattergalen/plot_skovens_stemme.md` is created and casts company elements
- [x] `plays/bfn436_nattergalen/plot_mekanisk_triumf.md` is created and casts company elements
- [x] `plays/bfn436_nattergalen/plot_doedslejet.md` is created and casts company elements
- [x] `plays/bfn436_nattergalen/plot_morgensang.md` is created and casts company elements
- [x] The local validation tests (`npm test`) run successfully with zero errors
