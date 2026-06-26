---
khai: order
title: "Stage BFN 749 Jødepigen"
language: english
license: CC-BY-NC-SA-4.0
stamp:
  owner: KAI HACKS AI
  version: v0.0.1
  date: "2026-06-26"
---

# Order: Stage BFN 749 Jødepigen

## Direction

The house must stage BFN 749 (_Jødepigen_) to establish a production in the H.C. Andersen house. The production must model sarah, moderen, the positions (loeftetro, troende), the pieces (bibel, salme), the environments (skolen, kirken), the indre_kamp and forloesning processes, and the plots representing loeftet and doeden. It must be written in authentic Danish for all prose sections.

## Orders

1. The Playwright (Hans Christian Andersen) must author the play definition, the 2 personas, the 2 positions, the 2 pieces, the 2 places, the 2 processes, the 2 in-world plans, the pitch of religioes, and the 2 plots.
2. The Theatre Manager (Edvard Collin) must verify the local registry, ensure correct versioning, check formatting, and validate that the cast conforms to the canon.
3. The Roadie (Vilhelm Pedersen) must set the stage, verify the local test suite is green, and prepare the files for packaging.

## Implementation

The play files must be placed in `plays/bfn749_joedepigen/` and follow the house language policy:

- Structural elements and frontmatter in English.
- Narrative prose, projections, actions, shadows, tells, and staging notes in Danish.

## Targets

- [x] `plays/bfn749_joedepigen/play_joedepigen.md` is created and lists the complete company
- [x] `plays/bfn749_joedepigen/persona_sarah.md` is created and links to `position_loeftetro.md`
- [x] `plays/bfn749_joedepigen/persona_moderen.md` is created and links to `position_troende.md`
- [x] `plays/bfn749_joedepigen/position_loeftetro.md` is created
- [x] `plays/bfn749_joedepigen/position_troende.md` is created
- [x] `plays/bfn749_joedepigen/piece_bibel.md` is created
- [x] `plays/bfn749_joedepigen/piece_salme.md` is created
- [x] `plays/bfn749_joedepigen/place_skolen.md` is created
- [x] `plays/bfn749_joedepigen/place_kirken.md` is created
- [x] `plays/bfn749_joedepigen/process_indre_kamp.md` is created
- [x] `plays/bfn749_joedepigen/process_forloesning.md` is created
- [x] `plays/bfn749_joedepigen/plan_loefte.md` is created and linked to `persona_sarah.md`
- [x] `plays/bfn749_joedepigen/plan_frelse.md` is created and linked to `persona_sarah.md`
- [x] `plays/bfn749_joedepigen/pitch_religioes.md` is created
- [x] `plays/bfn749_joedepigen/plot_loeftet.md` is created and casts company elements
- [x] `plays/bfn749_joedepigen/plot_doeden.md` is created and casts company elements
- [x] The local validation tests (`npm test`) run successfully with zero errors
