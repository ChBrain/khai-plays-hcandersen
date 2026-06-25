---
khai: order
title: "Stage BFN 911 Gjemt er ikke glemt"
language: english
license: CC-BY-NC-SA-4.0
stamp:
  owner: KAI HACKS AI
  version: v0.0.1
  date: "2026-06-25"
---

# Order: Stage BFN 911 Gjemt er ikke glemt

## Direction

The house must stage BFN 911 (_Gjemt er ikke glemt_) to establish the ninety-eighth production in the H.C. Andersen house. The production must model Fru Mette Mogens, Drengen, and Pigen, the positions (Adelig, Trofast, Sørgende), the piece (Lænke), the environments (Gaard, Kjøkken), the erindring and retfærdighed processes, and the plots representing three historical/contemporary scenes of remembrance. It must be written in authentic Danish for all prose sections.

## Orders

1. The Playwright (Hans Christian Andersen) must author the play definition, the three personas, the three positions, the piece, the two places, the two processes, the two in-world plans, the pitch of Erindring, and the four plots.
2. The Theatre Manager (Edvard Collin) must verify the local registry, ensure correct versioning, check formatting, and validate that the cast conforms to the canon.
3. The Roadie (Vilhelm Pedersen) must set the stage, verify the local test suite is green, and prepare the files for packaging.

## Implementation

The play files must be placed in `plays/bfn911_gjemt_er_ikke_glemt/` and follow the house language policy:

- Structural elements and frontmatter in English.
- Narrative prose, projections, actions, shadows, tells, and staging notes in Danish.

## Targets

- [x] `plays/bfn911_gjemt_er_ikke_glemt/play_gjemt_er_ikke_glemt.md` is created and lists the complete company
- [x] `plays/bfn911_gjemt_er_ikke_glemt/persona_mette_mogens.md` is created and links to `position_adelig.md`
- [x] `plays/bfn911_gjemt_er_ikke_glemt/persona_drengen.md` is created and links to `position_trofast.md`
- [x] `plays/bfn911_gjemt_er_ikke_glemt/persona_pigen.md` is created and links to `position_soergende.md`
- [x] `plays/bfn911_gjemt_er_ikke_glemt/position_adelig.md` is created
- [x] `plays/bfn911_gjemt_er_ikke_glemt/position_trofast.md` is created
- [x] `plays/bfn911_gjemt_er_ikke_glemt/position_soergende.md` is created
- [x] `plays/bfn911_gjemt_er_ikke_glemt/piece_laenke.md` is created
- [x] `plays/bfn911_gjemt_er_ikke_glemt/place_gaard.md` is created
- [x] `plays/bfn911_gjemt_er_ikke_glemt/place_kjoekken.md` is created
- [x] `plays/bfn911_gjemt_er_ikke_glemt/process_erindring.md` is created
- [x] `plays/bfn911_gjemt_er_ikke_glemt/process_retfaerdighed.md` is created
- [x] `plays/bfn911_gjemt_er_ikke_glemt/plan_frelse.md` is created and linked to `persona_drengen.md`
- [x] `plays/bfn911_gjemt_er_ikke_glemt/plan_troskab.md` is created and linked to `persona_pigen.md`
- [x] `plays/bfn911_gjemt_er_ikke_glemt/pitch_erindring.md` is created
- [x] `plays/bfn911_gjemt_er_ikke_glemt/plot_roeverne.md` is created and casts company elements
- [x] `plays/bfn911_gjemt_er_ikke_glemt/plot_solskinnet.md` is created and casts company elements
- [x] `plays/bfn911_gjemt_er_ikke_glemt/plot_sorgen.md` is created and casts company elements
- [x] The local validation tests (`npm test`) run successfully with zero errors
