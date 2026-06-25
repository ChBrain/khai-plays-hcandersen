---
khai: order
title: "Stage BFN 977 Ugedagene"
language: english
license: CC-BY-NC-SA-4.0
stamp:
  owner: KAI HACKS AI
  version: v0.0.1
  date: "2026-06-25"
---

# Order: Stage BFN 977 Ugedagene

## Direction

The house must stage BFN 977 (_Ugedagene_) to establish the hundred and ninth production in the H.C. Andersen house. The production must model Søndag, Mandag, and Skuddag, the positions (Ledende, Arbejdende, Huserende), the pieces (Kappe, Maske), the environments (Kalender, Gilde), the arbejde and fejring processes, and the plots representing the daily routine, the plan, the carnival, and the farewell. It must be written in authentic Danish for all prose sections.

## Orders

1. The Playwright (Hans Christian Andersen) must author the play definition, the three personas, the three positions, the two pieces, the two places, the two processes, the two in-world plans, the pitch of Tidscyklus, and the four plots.
2. The Theatre Manager (Edvard Collin) must verify the local registry, ensure correct versioning, check formatting, and validate that the cast conforms to the canon.
3. The Roadie (Vilhelm Pedersen) must set the stage, verify the local test suite is green, and prepare the files for packaging.

## Implementation

The play files must be placed in `plays/bfn977_ugedagene/` and follow the house language policy:

- Structural elements and frontmatter in English.
- Narrative prose, projections, actions, shadows, tells, and staging notes in Danish.

## Targets

- [ ] `plays/bfn977_ugedagene/play_ugedagene.md` is created and lists the complete company
- [ ] `plays/bfn977_ugedagene/persona_soendag.md` is created and links to `position_ledende.md`
- [ ] `plays/bfn977_ugedagene/persona_mandag.md` is created and links to `position_arbejdende.md`
- [ ] `plays/bfn977_ugedagene/persona_skuddag.md` is created and links to `position_huserende.md`
- [ ] `plays/bfn977_ugedagene/position_ledende.md` is created
- [ ] `plays/bfn977_ugedagene/position_arbejdende.md` is created
- [ ] `plays/bfn977_ugedagene/position_huserende.md` is created
- [ ] `plays/bfn977_ugedagene/piece_kappe.md` is created
- [ ] `plays/bfn977_ugedagene/piece_maske.md` is created
- [ ] `plays/bfn977_ugedagene/place_kalender.md` is created
- [ ] `plays/bfn977_ugedagene/place_gilde.md` is created
- [ ] `plays/bfn977_ugedagene/process_arbejde.md` is created
- [ ] `plays/bfn977_ugedagene/process_fejring.md` is created
- [ ] `plays/bfn977_ugedagene/plan_frigoerelse.md` is created and linked to `persona_mandag.md`
- [ ] `plays/bfn977_ugedagene/plan_kammeratskab.md` is created and linked to `persona_soendag.md`
- [ ] `plays/bfn977_ugedagene/pitch_tidscyklus.md` is created
- [ ] `plays/bfn977_ugedagene/plot_hverdagen.md` is created and casts company elements
- [ ] `plays/bfn977_ugedagene/plot_planen.md` is created and casts company elements
- [ ] `plays/bfn977_ugedagene/plot_karneval.md` is created and casts company elements
- [ ] `plays/bfn977_ugedagene/plot_afsked.md` is created and casts company elements
- [ ] The local validation tests (`npm test`) run successfully with zero errors
