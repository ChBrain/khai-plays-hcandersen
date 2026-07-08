---
khai: order
title: "Stage SDU 403"
language: english
license: CC-BY-NC-SA-4.0
stamp:
  owner: KAI HACKS AI
  version: v0.0.1
  date: "2026-07-08"
---

# Order: Stage SDU 403

## Direction

The house must stage SDU 403 (_Kun en Spillemand_) to establish the third novel-length production in the H.C. Andersen house. The production must model Christian's unappreciated musical genius and passive resignation, his violin ("Violinen"), Naomi's wild rise to the aristocracy, Steffen-Kareth's tragic shadow-side fate, their childhood in Svendborg, and Christian's lonely death. It must be written in authentic Danish for all staging and prose sections.

## Orders

1. The Playwright (Hans Christian Andersen) must author the play definition, the four personas (Christian, Naomi, Kareth, Steffen), the three positions (spillemand, adelsfrue, skyggebarn), the one piece (violinen), the three places (svendborg, koebenhavn, herregaarden), the two processes (resignation, vildskab), the in-world plan (overlevelse), the pitch (tragisk), and the three plots.
2. The Theatre Manager (Edvard Collin) must verify the local registry, ensure correct versioning, check formatting, and validate that the entire cast conforms to the canon.
3. The Roadie (Vilhelm Pedersen) must set the stage, verify the local test suite is green, and prepare the files for packaging.

## Implementation

The play files must be placed in `plays/sdu403_spillemand/` and follow the house language policy:

- Structural elements and frontmatter in English.
- Narrative prose, projections, actions, shadows, tells, and staging notes in Danish.

## Targets

- [x] `plays/sdu403_spillemand/play_spillemand.md` is created and lists the complete company
- [x] `plays/sdu403_spillemand/persona_christian.md` is created and links to `position_spillemand.md`
- [x] `plays/sdu403_spillemand/persona_naomi.md` is created and links to `position_adelsfrue.md`
- [x] `plays/sdu403_spillemand/persona_kareth.md` is created and links to `position_skyggebarn.md`
- [x] `plays/sdu403_spillemand/persona_steffen.md` is created
- [x] `plays/sdu403_spillemand/position_spillemand.md` is created
- [x] `plays/sdu403_spillemand/position_adelsfrue.md` is created
- [x] `plays/sdu403_spillemand/position_skyggebarn.md` is created
- [x] `plays/sdu403_spillemand/piece_violinen.md` is created
- [x] `plays/sdu403_spillemand/place_svendborg.md` is created
- [x] `plays/sdu403_spillemand/place_koebenhavn.md` is created
- [x] `plays/sdu403_spillemand/place_herregaarden.md` is created
- [x] `plays/sdu403_spillemand/process_resignation.md` is created
- [x] `plays/sdu403_spillemand/process_vildskab.md` is created
- [x] `plays/sdu403_spillemand/plan_overlevelse.md` is created
- [x] `plays/sdu403_spillemand/pitch_tragisk.md` is created
- [x] `plays/sdu403_spillemand/plot_barndomsdroemme.md` is created and casts company elements
- [x] `plays/sdu403_spillemand/plot_skyggeverdenen.md` is created and casts company elements
- [x] `plays/sdu403_spillemand/plot_doedsakten.md` is created and casts company elements
- [x] The local validation tests (`npm test`) run successfully with zero errors
