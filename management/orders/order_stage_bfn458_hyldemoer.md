---
khai: order
title: "Stage BFN 458 Hyldemoer"
language: english
license: CC-BY-NC-SA-4.0
stamp:
  owner: KAI HACKS AI
  version: v0.0.1
  date: "2026-06-26"
---

# Order: Stage BFN 458 Hyldemoer

## Direction

The house must stage BFN 458 (_Hyldemoer_) to establish a production in the H.C. Andersen house. The production must model drengen, hyldemor, bedstefar, the positions (lytter, fortaeller, erindrende), the pieces (thekande, hyldeblomst), the environments (stuen, haven), the erindring and helbredelse processes, and the plots representing thekanden and livsrejsen. It must be written in authentic Danish for all prose sections.

## Orders

1. The Playwright (Hans Christian Andersen) must author the play definition, the 3 personas, the 3 positions, the 2 pieces, the 2 places, the 2 processes, the 2 in-world plans, the pitch of hjertevarm, and the 2 plots.
2. The Theatre Manager (Edvard Collin) must verify the local registry, ensure correct versioning, check formatting, and validate that the cast conforms to the canon.
3. The Roadie (Vilhelm Pedersen) must set the stage, verify the local test suite is green, and prepare the files for packaging.

## Implementation

The play files must be placed in `plays/bfn458_hyldemoer/` and follow the house language policy:

- Structural elements and frontmatter in English.
- Narrative prose, projections, actions, shadows, tells, and staging notes in Danish.

## Targets

- [x] `plays/bfn458_hyldemoer/play_hyldemoer.md` is created and lists the complete company
- [x] `plays/bfn458_hyldemoer/persona_drengen.md` is created and links to `position_lytter.md`
- [x] `plays/bfn458_hyldemoer/persona_hyldemor.md` is created and links to `position_fortaeller.md`
- [x] `plays/bfn458_hyldemoer/persona_bedstefar.md` is created and links to `position_erindrende.md`
- [x] `plays/bfn458_hyldemoer/position_lytter.md` is created
- [x] `plays/bfn458_hyldemoer/position_fortaeller.md` is created
- [x] `plays/bfn458_hyldemoer/position_erindrende.md` is created
- [x] `plays/bfn458_hyldemoer/piece_thekande.md` is created
- [x] `plays/bfn458_hyldemoer/piece_hyldeblomst.md` is created
- [x] `plays/bfn458_hyldemoer/place_stuen.md` is created
- [x] `plays/bfn458_hyldemoer/place_haven.md` is created
- [x] `plays/bfn458_hyldemoer/process_erindring.md` is created
- [x] `plays/bfn458_hyldemoer/process_helbredelse.md` is created
- [x] `plays/bfn458_hyldemoer/plan_fantasi.md` is created and linked to `persona_drengen.md`
- [x] `plays/bfn458_hyldemoer/plan_erindring.md` is created and linked to `persona_bedstefar.md`
- [x] `plays/bfn458_hyldemoer/pitch_hjertevarm.md` is created
- [x] `plays/bfn458_hyldemoer/plot_thekanden.md` is created and casts company elements
- [x] `plays/bfn458_hyldemoer/plot_livsrejsen.md` is created and casts company elements
- [x] The local validation tests (`npm test`) run successfully with zero errors
