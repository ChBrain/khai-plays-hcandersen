---
khai: order
title: "Stage BFN 606 Et Billede fra Kastelsvolden"
language: english
license: CC-BY-NC-SA-4.0
stamp:
  owner: KAI HACKS AI
  version: v0.0.1
  date: "2026-06-22"
---

# Order: Stage BFN 606 Et Billede fra Kastelsvolden

## Direction

The house must stage BFN 606 (_Et Billede fra Kastelsvolden_) to establish the forty-eighth production in the H.C. Andersen house. The production must model Veteran, Barn, the positions (Reflekterende, Legende), the piece (Erindring), the environments (Volden, Historie), the erindring and kontrast processes, and the plots leading to their realization. It must be written in authentic Danish for all prose sections.

## Orders

1. The Playwright (Hans Christian Andersen) must author the play definition, the two personas, the two positions, the piece, the two places, the two processes, the two in-world plans, the pitch of Refleksion, and the four plots.
2. The Theatre Manager (Edvard Collin) must verify the local registry, ensure correct versioning, check formatting, and validate that the entire cast conforms to the canon.
3. The Roadie (Vilhelm Pedersen) must set the stage, verify the local test suite is green, and prepare the files for packaging.

## Implementation

The play files must be placed in `plays/bfn606_et_billede_fra_kastelsvolden/` and follow the house language policy:

- Structural elements and frontmatter in English.
- Narrative prose, projections, actions, shadows, tells, and staging notes in Danish.

## Targets

- [x] `plays/bfn606_et_billede_fra_kastelsvolden/play_et_billede_fra_kastelsvolden.md` is created and lists the complete company
- [x] `plays/bfn606_et_billede_fra_kastelsvolden/persona_veteran.md` is created and links to `position_reflekterende.md`
- [x] `plays/bfn606_et_billede_fra_kastelsvolden/persona_barn.md` is created and links to `position_legende.md`
- [x] `plays/bfn606_et_billede_fra_kastelsvolden/position_reflekterende.md` is created
- [x] `plays/bfn606_et_billede_fra_kastelsvolden/position_legende.md` is created
- [x] `plays/bfn606_et_billede_fra_kastelsvolden/piece_erindring.md` is created
- [x] `plays/bfn606_et_billede_fra_kastelsvolden/place_volden.md` is created
- [x] `plays/bfn606_et_billede_fra_kastelsvolden/place_historie.md` is created
- [x] `plays/bfn606_et_billede_fra_kastelsvolden/process_erindring.md` is created
- [x] `plays/bfn606_et_billede_fra_kastelsvolden/process_kontrast.md` is created
- [x] `plays/bfn606_et_billede_fra_kastelsvolden/plan_tilbageblik.md` is created and linked to `persona_veteran.md`
- [x] `plays/bfn606_et_billede_fra_kastelsvolden/plan_nutid.md` is created and linked to `persona_barn.md`
- [x] `plays/bfn606_et_billede_fra_kastelsvolden/pitch_refleksion.md` is created
- [x] `plays/bfn606_et_billede_fra_kastelsvolden/plot_volden.md` is created and casts company elements
- [x] `plays/bfn606_et_billede_fra_kastelsvolden/plot_leg.md` is created and casts company elements
- [x] `plays/bfn606_et_billede_fra_kastelsvolden/plot_erindring.md` is created and casts company elements
- [x] `plays/bfn606_et_billede_fra_kastelsvolden/plot_forgaengelighed.md` is created and casts company elements
- [x] The local validation tests (`npm test`) run successfully with zero errors
