---
khai: order
title: "Stage SDU 620"
language: english
license: CC-BY-NC-SA-4.0
stamp:
  owner: KAI HACKS AI
  version: v0.0.1
  date: "2026-07-10"
---

# Order: Stage SDU 620

## Direction

The house must stage SDU 620 (_Fragmenter af Ahasverus_) to establish the twentieth work in the "Drama" genre. The production must model the allegorical dialogues of Ahasverus, Columbus, and Lucifer. It must model the open ocean / deck of Santa Maria, the navigation chart piece, the processes representing the eternal wandering and the scientific discovery, Columbus' exploration plan, the grand allegorical tone, and the three plots. All staging, prose, projections, actions, shadows, and tells must be authored in authentic Danish.

## Orders

1. The Playwright (Hans Christian Andersen) must author the play definition, the three personas (ahasverus, columbus, lucifer), the three positions (vandrer, opdager, fristende_aand), the one piece (soekort), the one place (verdenshavet), the two processes (evig_vandring, opdagelse), the in-world plan (nyt_land), the pitch (laesedrama), and the three plots.
2. The Theatre Manager (Edvard Collin) must verify the local registry, ensure correct versioning, check formatting, and validate that the entire cast conforms to the canon.
3. The Roadie (Vilhelm Pedersen) must set the stage, verify the local test suite is green, and prepare the files for packaging.

## Implementation

The play files must be placed in `plays/sdu620_ahasverus_fragmenter/` and follow the house language policy:

- Structural elements and frontmatter in English.
- Narrative prose, projections, actions, shadows, tells, and staging notes in Danish.

## Targets

- [x] `plays/sdu620_ahasverus_fragmenter/play_ahasverus_fragmenter.md` is created and lists the complete company
- [x] `plays/sdu620_ahasverus_fragmenter/persona_ahasverus.md` is created and links to `position_vandrer.md`
- [x] `plays/sdu620_ahasverus_fragmenter/persona_columbus.md` is created and links to `position_opdager.md`
- [x] `plays/sdu620_ahasverus_fragmenter/persona_lucifer.md` is created and links to `position_fristende_aand.md`
- [x] `plays/sdu620_ahasverus_fragmenter/position_vandrer.md` is created
- [x] `plays/sdu620_ahasverus_fragmenter/position_opdager.md` is created
- [x] `plays/sdu620_ahasverus_fragmenter/position_fristende_aand.md` is created
- [x] `plays/sdu620_ahasverus_fragmenter/piece_soekort.md` is created
- [x] `plays/sdu620_ahasverus_fragmenter/place_verdenshavet.md` is created
- [x] `plays/sdu620_ahasverus_fragmenter/process_evig_vandring.md` is created
- [x] `plays/sdu620_ahasverus_fragmenter/process_opdagelse.md` is created
- [x] `plays/sdu620_ahasverus_fragmenter/plan_nyt_land.md` is created
- [x] `plays/sdu620_ahasverus_fragmenter/pitch_laesedrama.md` is created
- [x] `plays/sdu620_ahasverus_fragmenter/plot_evigheden.md` is created and casts company elements
- [x] `plays/sdu620_ahasverus_fragmenter/plot_lyset.md` is created and casts company elements
- [x] `plays/sdu620_ahasverus_fragmenter/plot_rejsen.md` is created and casts company elements
- [x] The local validation tests (`npm test`) run successfully with zero errors
