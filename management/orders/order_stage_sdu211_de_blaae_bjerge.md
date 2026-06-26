---
khai: order
title: "Stage SDU 211 De blaae Bjerge"
language: english
license: CC-BY-NC-SA-4.0
stamp:
  owner: KAI HACKS AI
  version: v0.0.1
  date: "2026-06-26"
---

# Order: Stage SDU 211 De blaae Bjerge

## Direction

The house must stage SDU 211 (_De blaae Bjerge_) to establish a production in the H.C. Andersen house. The production must model laengsleren, maaneskinnet, the positions (soegende, vejviser), the pieces (vandrestav, stjerne), the environments (dalen, bjerget), the vandring and laengsel processes, and the plots representing laengslen and rejsen. It must be written in authentic Danish for all prose sections.

## Orders

1. The Playwright (Hans Christian Andersen) must author the play definition, the 2 personas, the 2 positions, the 2 pieces, the 2 places, the 2 processes, the 1 in-world plans, the pitch of eventyrlig, and the 2 plots.
2. The Theatre Manager (Edvard Collin) must verify the local registry, ensure correct versioning, check formatting, and validate that the cast conforms to the canon.
3. The Roadie (Vilhelm Pedersen) must set the stage, verify the local test suite is green, and prepare the files for packaging.

## Implementation

The play files must be placed in `plays/sdu211_de_blaae_bjerge/` and follow the house language policy:

- Structural elements and frontmatter in English.
- Narrative prose, projections, actions, shadows, tells, and staging notes in Danish.

## Targets

- [x] `plays/sdu211_de_blaae_bjerge/play_de_blaae_bjerge.md` is created and lists the complete company
- [x] `plays/sdu211_de_blaae_bjerge/persona_laengsleren.md` is created and links to `position_soegende.md`
- [x] `plays/sdu211_de_blaae_bjerge/persona_maaneskinnet.md` is created and links to `position_vejviser.md`
- [x] `plays/sdu211_de_blaae_bjerge/position_soegende.md` is created
- [x] `plays/sdu211_de_blaae_bjerge/position_vejviser.md` is created
- [x] `plays/sdu211_de_blaae_bjerge/piece_vandrestav.md` is created
- [x] `plays/sdu211_de_blaae_bjerge/piece_stjerne.md` is created
- [x] `plays/sdu211_de_blaae_bjerge/place_dalen.md` is created
- [x] `plays/sdu211_de_blaae_bjerge/place_bjerget.md` is created
- [x] `plays/sdu211_de_blaae_bjerge/process_vandring.md` is created
- [x] `plays/sdu211_de_blaae_bjerge/process_laengsel.md` is created
- [x] `plays/sdu211_de_blaae_bjerge/plan_rejsen.md` is created and linked to `persona_laengsleren.md`
- [x] `plays/sdu211_de_blaae_bjerge/pitch_eventyrlig.md` is created
- [x] `plays/sdu211_de_blaae_bjerge/plot_laengslen.md` is created and casts company elements
- [x] `plays/sdu211_de_blaae_bjerge/plot_rejsen.md` is created and casts company elements
- [x] The local validation tests (`npm test`) run successfully with zero errors
