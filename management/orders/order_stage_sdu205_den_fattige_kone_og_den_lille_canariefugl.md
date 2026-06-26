---
khai: order
title: "Stage SDU 205 Den fattige Kone og den lille Canariefugl"
language: english
license: CC-BY-NC-SA-4.0
stamp:
  owner: KAI HACKS AI
  version: v0.0.1
  date: "2026-06-26"
---

# Order: Stage SDU 205 Den fattige Kone og den lille Canariefugl

## Direction

The house must stage SDU 205 (_Den fattige Kone og den lille Canariefugl_) to establish a production in the H.C. Andersen house. The production must model konen, fuglen, the positions (plejer, sanger), the pieces (bur, hampfroe), the environments (stuen, vindueskarmen), the pleje and sang processes, and the plots representing stuen and sangen. It must be written in authentic Danish for all prose sections.

## Orders

1. The Playwright (Hans Christian Andersen) must author the play definition, the 2 personas, the 2 positions, the 2 pieces, the 2 places, the 2 processes, the 1 in-world plans, the pitch of hjertevarm, and the 2 plots.
2. The Theatre Manager (Edvard Collin) must verify the local registry, ensure correct versioning, check formatting, and validate that the cast conforms to the canon.
3. The Roadie (Vilhelm Pedersen) must set the stage, verify the local test suite is green, and prepare the files for packaging.

## Implementation

The play files must be placed in `plays/sdu205_den_fattige_kone_og_den_lille_canariefugl/` and follow the house language policy:

- Structural elements and frontmatter in English.
- Narrative prose, projections, actions, shadows, tells, and staging notes in Danish.

## Targets

- [x] `plays/sdu205_den_fattige_kone_og_den_lille_canariefugl/play_den_fattige_kone_og_den_lille_canariefugl.md` is created and lists the complete company
- [x] `plays/sdu205_den_fattige_kone_og_den_lille_canariefugl/persona_konen.md` is created and links to `position_plejer.md`
- [x] `plays/sdu205_den_fattige_kone_og_den_lille_canariefugl/persona_fuglen.md` is created and links to `position_sanger.md`
- [x] `plays/sdu205_den_fattige_kone_og_den_lille_canariefugl/position_plejer.md` is created
- [x] `plays/sdu205_den_fattige_kone_og_den_lille_canariefugl/position_sanger.md` is created
- [x] `plays/sdu205_den_fattige_kone_og_den_lille_canariefugl/piece_bur.md` is created
- [x] `plays/sdu205_den_fattige_kone_og_den_lille_canariefugl/piece_hampfroe.md` is created
- [x] `plays/sdu205_den_fattige_kone_og_den_lille_canariefugl/place_stuen.md` is created
- [x] `plays/sdu205_den_fattige_kone_og_den_lille_canariefugl/place_vindueskarmen.md` is created
- [x] `plays/sdu205_den_fattige_kone_og_den_lille_canariefugl/process_pleje.md` is created
- [x] `plays/sdu205_den_fattige_kone_og_den_lille_canariefugl/process_sang.md` is created
- [x] `plays/sdu205_den_fattige_kone_og_den_lille_canariefugl/plan_overlevelse.md` is created and linked to `persona_konen.md`
- [x] `plays/sdu205_den_fattige_kone_og_den_lille_canariefugl/pitch_hjertevarm.md` is created
- [x] `plays/sdu205_den_fattige_kone_og_den_lille_canariefugl/plot_stuen.md` is created and casts company elements
- [x] `plays/sdu205_den_fattige_kone_og_den_lille_canariefugl/plot_sangen.md` is created and casts company elements
- [x] The local validation tests (`npm test`) run successfully with zero errors
