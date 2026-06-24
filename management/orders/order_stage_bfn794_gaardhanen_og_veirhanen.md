---
khai: order
title: "Stage BFN 794 Gaardhanen og Veirhanen"
language: english
license: CC-BY-NC-SA-4.0
stamp:
  owner: KAI HACKS AI
  version: v0.0.1
  date: "2026-06-23"
---

# Order: Stage BFN 794 Gaardhanen og Veirhanen

## Direction

The house must stage BFN 794 (_Gaardhanen og Veirhanen_) to establish the seventy-fourth production in the H.C. Andersen house. The production must model Gaardhane, Veirhane, the positions (Privilegeret, Ustadig), the piece (Korn), the environments (Gaard, Tag), the hovmod and forfald processes, and the plots leading to their realization. It must be written in authentic Danish for all prose sections.

## Orders

1. The Playwright (Hans Christian Andersen) must author the play definition, the two personas, the two positions, the piece, the two places, the two processes, the two in-world plans, the pitch of Satire, and the four plots.
2. The Theatre Manager (Edvard Collin) must verify the local registry, ensure correct versioning, check formatting, and validate that the entire cast conforms to the canon.
3. The Roadie (Vilhelm Pedersen) must set the stage, verify the local test suite is green, and prepare the files for packaging.

## Implementation

The play files must be placed in `plays/bfn794_gaardhanen_og_veirhanen/` and follow the house language policy:

- Structural elements and frontmatter in English.
- Narrative prose, projections, actions, shadows, tells, and staging notes in Danish.

## Targets

- [x] `plays/bfn794_gaardhanen_og_veirhanen/play_gaardhanen_og_veirhanen.md` is created and lists the complete company
- [x] `plays/bfn794_gaardhanen_og_veirhanen/persona_gaardhane.md` is created and links to `position_privilegeret.md`
- [x] `plays/bfn794_gaardhanen_og_veirhanen/persona_veirhane.md` is created and links to `position_ustadig.md`
- [x] `plays/bfn794_gaardhanen_og_veirhanen/position_privilegeret.md` is created
- [x] `plays/bfn794_gaardhanen_og_veirhanen/position_ustadig.md` is created
- [x] `plays/bfn794_gaardhanen_og_veirhanen/piece_korn.md` is created
- [x] `plays/bfn794_gaardhanen_og_veirhanen/place_gaard.md` is created
- [x] `plays/bfn794_gaardhanen_og_veirhanen/place_tag.md` is created
- [x] `plays/bfn794_gaardhanen_og_veirhanen/process_hovmod.md` is created
- [x] `plays/bfn794_gaardhanen_og_veirhanen/process_forfald.md` is created
- [x] `plays/bfn794_gaardhanen_og_veirhanen/plan_selvforherligelse.md` is created and linked to `persona_gaardhane.md`
- [x] `plays/bfn794_gaardhanen_og_veirhanen/plan_retningsskifte.md` is created and linked to `persona_veirhane.md`
- [x] `plays/bfn794_gaardhanen_og_veirhanen/pitch_satire.md` is created
- [x] `plays/bfn794_gaardhanen_og_veirhanen/plot_pladsen.md` is created and casts company elements
- [x] `plays/bfn794_gaardhanen_og_veirhanen/plot_blaesten.md` is created and casts company elements
- [x] `plays/bfn794_gaardhanen_og_veirhanen/plot_striden.md` is created and casts company elements
- [x] `plays/bfn794_gaardhanen_og_veirhanen/plot_forgaengelsen.md` is created and casts company elements
- [x] The local validation tests (`npm test`) run successfully with zero errors
