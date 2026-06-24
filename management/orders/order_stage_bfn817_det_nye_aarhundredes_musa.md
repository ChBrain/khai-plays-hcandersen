---
khai: order
title: "Stage BFN 817 Det nye Aarhundredes Musa"
language: english
license: CC-BY-NC-SA-4.0
stamp:
  owner: KAI HACKS AI
  version: v0.0.1
  date: "2026-06-24"
---

# Order: Stage BFN 817 Det nye Aarhundredes Musa

## Direction

The house must stage BFN 817 (_Det nye Aarhundredes Musa_) to establish the eighty-sixth production in the H.C. Andersen house. The production must model Musa, Digter, the positions (Bebuder, Modtager), the piece (Gnist), the environments (Nutid, Fremtid), the gennembrud and oplysning processes, and the plots leading to their realization. It must be written in authentic Danish for all prose sections.

## Orders

1. The Playwright (Hans Christian Andersen) must author the play definition, the two personas, the two positions, the piece, the two places, the two processes, the two in-world plans, the pitch of Vision, and the four plots.
2. The Theatre Manager (Edvard Collin) must verify the local registry, ensure correct versioning, check formatting, and validate that the cast conforms to the canon.
3. The Roadie (Vilhelm Pedersen) must set the stage, verify the local test suite is green, and prepare the files for packaging.

## Implementation

The play files must be placed in `plays/bfn817_det_nye_aarhundredes_musa/` and follow the house language policy:

- Structural elements and frontmatter in English.
- Narrative prose, projections, actions, shadows, tells, and staging notes in Danish.

## Targets

- [x] `plays/bfn817_det_nye_aarhundredes_musa/play_det_nye_aarhundredes_musa.md` is created and lists the complete company
- [x] `plays/bfn817_det_nye_aarhundredes_musa/persona_musa.md` is created and links to `position_bebuder.md`
- [x] `plays/bfn817_det_nye_aarhundredes_musa/persona_digter.md` is created and links to `position_modtager.md`
- [x] `plays/bfn817_det_nye_aarhundredes_musa/position_bebuder.md` is created
- [x] `plays/bfn817_det_nye_aarhundredes_musa/position_modtager.md` is created
- [x] `plays/bfn817_det_nye_aarhundredes_musa/piece_gnist.md` is created
- [x] `plays/bfn817_det_nye_aarhundredes_musa/place_nutid.md` is created
- [x] `plays/bfn817_det_nye_aarhundredes_musa/place_fremtid.md` is created
- [x] `plays/bfn817_det_nye_aarhundredes_musa/process_gennembrud.md` is created
- [x] `plays/bfn817_det_nye_aarhundredes_musa/process_oplysning.md` is created
- [x] `plays/bfn817_det_nye_aarhundredes_musa/plan_forvandling.md` is created and linked to `persona_musa.md`
- [x] `plays/bfn817_det_nye_aarhundredes_musa/plan_lytning.md` is created and linked to `persona_digter.md`
- [x] `plays/bfn817_det_nye_aarhundredes_musa/pitch_vision.md` is created
- [x] `plays/bfn817_det_nye_aarhundredes_musa/plot_kaldet.md` is created and casts company elements
- [x] `plays/bfn817_det_nye_aarhundredes_musa/plot_rejsen.md` is created and casts company elements
- [x] `plays/bfn817_det_nye_aarhundredes_musa/plot_moedet.md` is created and casts company elements
- [x] `plays/bfn817_det_nye_aarhundredes_musa/plot_aabenbaringen.md` is created and casts company elements
- [x] The local validation tests (`npm test`) run successfully with zero errors
