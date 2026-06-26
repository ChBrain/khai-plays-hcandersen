---
khai: order
title: "Stage BFN 775 Dynd-Kongens Datter"
language: english
license: CC-BY-NC-SA-4.0
stamp:
  owner: KAI HACKS AI
  version: v0.0.1
  date: "2026-06-26"
---

# Order: Stage BFN 775 Dynd-Kongens Datter

## Direction

The house must stage BFN 775 (_Dynd-Kongens Datter_) to establish a production in the H.C. Andersen house. The production must model helga, dyndkongen, praesten, the positions (tvedelt, moerk, forloesende), the pieces (fjerham, lilje), the environments (mosens_dyb, vikingegaarden), the forvandling and daab processes, and the plots representing forbandelsen and forloesningen. It must be written in authentic Danish for all prose sections.

## Orders

1. The Playwright (Hans Christian Andersen) must author the play definition, the 3 personas, the 3 positions, the 2 pieces, the 2 places, the 2 processes, the 2 in-world plans, the pitch of episk, and the 2 plots.
2. The Theatre Manager (Edvard Collin) must verify the local registry, ensure correct versioning, check formatting, and validate that the cast conforms to the canon.
3. The Roadie (Vilhelm Pedersen) must set the stage, verify the local test suite is green, and prepare the files for packaging.

## Implementation

The play files must be placed in `plays/bfn775_dynd_kongens_datter/` and follow the house language policy:

- Structural elements and frontmatter in English.
- Narrative prose, projections, actions, shadows, tells, and staging notes in Danish.

## Targets

- [x] `plays/bfn775_dynd_kongens_datter/play_dynd_kongens_datter.md` is created and lists the complete company
- [x] `plays/bfn775_dynd_kongens_datter/persona_helga.md` is created and links to `position_tvedelt.md`
- [x] `plays/bfn775_dynd_kongens_datter/persona_dyndkongen.md` is created and links to `position_moerk.md`
- [x] `plays/bfn775_dynd_kongens_datter/persona_praesten.md` is created and links to `position_forloesende.md`
- [x] `plays/bfn775_dynd_kongens_datter/position_tvedelt.md` is created
- [x] `plays/bfn775_dynd_kongens_datter/position_moerk.md` is created
- [x] `plays/bfn775_dynd_kongens_datter/position_forloesende.md` is created
- [x] `plays/bfn775_dynd_kongens_datter/piece_fjerham.md` is created
- [x] `plays/bfn775_dynd_kongens_datter/piece_lilje.md` is created
- [x] `plays/bfn775_dynd_kongens_datter/place_mosens_dyb.md` is created
- [x] `plays/bfn775_dynd_kongens_datter/place_vikingegaarden.md` is created
- [x] `plays/bfn775_dynd_kongens_datter/process_forvandling.md` is created
- [x] `plays/bfn775_dynd_kongens_datter/process_daab.md` is created
- [x] `plays/bfn775_dynd_kongens_datter/plan_frihed.md` is created and linked to `persona_helga.md`
- [x] `plays/bfn775_dynd_kongens_datter/plan_frelse.md` is created and linked to `persona_helga.md`
- [x] `plays/bfn775_dynd_kongens_datter/pitch_episk.md` is created
- [x] `plays/bfn775_dynd_kongens_datter/plot_forbandelsen.md` is created and casts company elements
- [x] `plays/bfn775_dynd_kongens_datter/plot_forloesningen.md` is created and casts company elements
- [x] The local validation tests (`npm test`) run successfully with zero errors
