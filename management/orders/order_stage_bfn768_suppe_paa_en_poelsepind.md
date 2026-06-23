---
khai: order
title: "Stage BFN 768 Suppe paa en Poelsepind"
language: english
license: CC-BY-NC-SA-4.0
stamp:
  owner: KAI HACKS AI
  version: v0.0.1
  date: "2026-06-23"
---

# Order: Stage BFN 768 Suppe paa en Poelsepind

## Direction

The house must stage BFN 768 (_Suppe paa en Pølsepind_) to establish the sixty-fourth production in the H.C. Andersen house. The production must model Musekonge, Rejsende, the positions (Soeger, Dommer), the piece (Poelsepind), the environments (Hof, Verden), the rejse and suppekogning processes, and the plots leading to their realization. It must be written in authentic Danish for all prose sections.

## Orders

1. The Playwright (Hans Christian Andersen) must author the play definition, the two personas, the two positions, the piece, the two places, the two processes, the two in-world plans, the pitch of Eventyr, and the four plots.
2. The Theatre Manager (Edvard Collin) must verify the local registry, ensure correct versioning, check formatting, and validate that the entire cast conforms to the canon.
3. The Roadie (Vilhelm Pedersen) must set the stage, verify the local test suite is green, and prepare the files for packaging.

## Implementation

The play files must be placed in `plays/bfn768_suppe_paa_en_poelsepind/` and follow the house language policy:

- Structural elements and frontmatter in English.
- Narrative prose, projections, actions, shadows, tells, and staging notes in Danish.

## Targets

- [x] `plays/bfn768_suppe_paa_en_poelsepind/play_suppe_paa_en_poelsepind.md` is created and lists the complete company
- [x] `plays/bfn768_suppe_paa_en_poelsepind/persona_musekonge.md` is created and links to `position_dommer.md`
- [x] `plays/bfn768_suppe_paa_en_poelsepind/persona_rejsende.md` is created and links to `position_soeger.md`
- [x] `plays/bfn768_suppe_paa_en_poelsepind/position_dommer.md` is created
- [x] `plays/bfn768_suppe_paa_en_poelsepind/position_soeger.md` is created
- [x] `plays/bfn768_suppe_paa_en_poelsepind/piece_poelsepind.md` is created
- [x] `plays/bfn768_suppe_paa_en_poelsepind/place_hof.md` is created
- [x] `plays/bfn768_suppe_paa_en_poelsepind/place_verden.md` is created
- [x] `plays/bfn768_suppe_paa_en_poelsepind/process_rejse.md` is created
- [x] `plays/bfn768_suppe_paa_en_poelsepind/process_suppekogning.md` is created
- [x] `plays/bfn768_suppe_paa_en_poelsepind/plan_indflydelse.md` is created and linked to `persona_rejsende.md`
- [x] `plays/bfn768_suppe_paa_en_poelsepind/plan_valg.md` is created and linked to `persona_musekonge.md`
- [x] `plays/bfn768_suppe_paa_en_poelsepind/pitch_eventyr.md` is created
- [x] `plays/bfn768_suppe_paa_en_poelsepind/plot_udfordring.md` is created and casts company elements
- [x] `plays/bfn768_suppe_paa_en_poelsepind/plot_soegen.md` is created and casts company elements
- [x] `plays/bfn768_suppe_paa_en_poelsepind/plot_gensyn.md` is created and casts company elements
- [x] `plays/bfn768_suppe_paa_en_poelsepind/plot_list.md` is created and casts company elements
- [x] The local validation tests (`npm test`) run successfully with zero errors
