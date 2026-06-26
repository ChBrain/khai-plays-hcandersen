---
khai: order
title: "Stage BFN 760 Et stykke Perlesnor"
language: english
license: CC-BY-NC-SA-4.0
stamp:
  owner: KAI HACKS AI
  version: v0.0.1
  date: "2026-06-26"
---

# Order: Stage BFN 760 Et stykke Perlesnor

## Direction

The house must stage BFN 760 (_Et stykke Perlesnor_) to establish a production in the H.C. Andersen house. The production must model den_rejsende, toget, the positions (iagttager, forbinder), the pieces (perlesnor, billet), the environments (jernbanen, danmark), the rejse and forbindelse processes, and the plots representing afgangen and ankomsten. It must be written in authentic Danish for all prose sections.

## Orders

1. The Playwright (Hans Christian Andersen) must author the play definition, the 2 personas, the 2 positions, the 2 pieces, the 2 places, the 2 processes, the 2 in-world plans, the pitch of optimistisk, and the 2 plots.
2. The Theatre Manager (Edvard Collin) must verify the local registry, ensure correct versioning, check formatting, and validate that the cast conforms to the canon.
3. The Roadie (Vilhelm Pedersen) must set the stage, verify the local test suite is green, and prepare the files for packaging.

## Implementation

The play files must be placed in `plays/bfn760_et_stykke_perlesnor/` and follow the house language policy:

- Structural elements and frontmatter in English.
- Narrative prose, projections, actions, shadows, tells, and staging notes in Danish.

## Targets

- [x] `plays/bfn760_et_stykke_perlesnor/play_et_stykke_perlesnor.md` is created and lists the complete company
- [x] `plays/bfn760_et_stykke_perlesnor/persona_den_rejsende.md` is created and links to `position_iagttager.md`
- [x] `plays/bfn760_et_stykke_perlesnor/persona_toget.md` is created and links to `position_forbinder.md`
- [x] `plays/bfn760_et_stykke_perlesnor/position_iagttager.md` is created
- [x] `plays/bfn760_et_stykke_perlesnor/position_forbinder.md` is created
- [x] `plays/bfn760_et_stykke_perlesnor/piece_perlesnor.md` is created
- [x] `plays/bfn760_et_stykke_perlesnor/piece_billet.md` is created
- [x] `plays/bfn760_et_stykke_perlesnor/place_jernbanen.md` is created
- [x] `plays/bfn760_et_stykke_perlesnor/place_danmark.md` is created
- [x] `plays/bfn760_et_stykke_perlesnor/process_rejse.md` is created
- [x] `plays/bfn760_et_stykke_perlesnor/process_forbindelse.md` is created
- [x] `plays/bfn760_et_stykke_perlesnor/plan_erindring.md` is created and linked to `persona_den_rejsende.md`
- [x] `plays/bfn760_et_stykke_perlesnor/plan_fremskridt.md` is created and linked to `persona_den_rejsende.md`
- [x] `plays/bfn760_et_stykke_perlesnor/pitch_optimistisk.md` is created
- [x] `plays/bfn760_et_stykke_perlesnor/plot_afgangen.md` is created and casts company elements
- [x] `plays/bfn760_et_stykke_perlesnor/plot_ankomsten.md` is created and casts company elements
- [x] The local validation tests (`npm test`) run successfully with zero errors
