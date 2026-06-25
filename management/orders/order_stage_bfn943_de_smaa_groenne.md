---
khai: order
title: "Stage BFN 943 De smaa Groenne"
language: english
license: CC-BY-NC-SA-4.0
stamp:
  owner: KAI HACKS AI
  version: v0.0.1
  date: "2026-06-25"
---

# Order: Stage BFN 943 De smaa Groenne

## Direction

The house must stage BFN 943 (_De smaa Grønne_) to establish the hundred and fourth production in the H.C. Andersen house. The production must model Bladlusen, Mariehønen, and Rosenbusken, the positions (Indbildsk, Fortærende, Bærende), the pieces (Rosenblad, Vingeskal), the environments (Stænglen, Haven), the udsugning and udryddelse processes, and the plots representing the rose, the regiment, the attack, and the survival. It must be written in authentic Danish for all prose sections.

## Orders

1. The Playwright (Hans Christian Andersen) must author the play definition, the three personas, the three positions, the two pieces, the two places, the two processes, the two in-world plans, the pitch of Mikrokosmos, and the four plots.
2. The Theatre Manager (Edvard Collin) must verify the local registry, ensure correct versioning, check formatting, and validate that the cast conforms to the canon.
3. The Roadie (Vilhelm Pedersen) must set the stage, verify the local test suite is green, and prepare the files for packaging.

## Implementation

The play files must be placed in `plays/bfn943_de_smaa_groenne/` and follow the house language policy:

- Structural elements and frontmatter in English.
- Narrative prose, projections, actions, shadows, tells, and staging notes in Danish.

## Targets

- [x] `plays/bfn943_de_smaa_groenne/play_de_smaa_groenne.md` is created and lists the complete company
- [x] `plays/bfn943_de_smaa_groenne/persona_bladlusen.md` is created and links to `position_indbildsk.md`
- [x] `plays/bfn943_de_smaa_groenne/persona_mariehoenen.md` is created and links to `position_fortaerende.md`
- [x] `plays/bfn943_de_smaa_groenne/persona_rosenbusken.md` is created and links to `position_baerende.md`
- [x] `plays/bfn943_de_smaa_groenne/position_indbildsk.md` is created
- [x] `plays/bfn943_de_smaa_groenne/position_fortaerende.md` is created
- [x] `plays/bfn943_de_smaa_groenne/position_baerende.md` is created
- [x] `plays/bfn943_de_smaa_groenne/piece_rosenblad.md` is created
- [x] `plays/bfn943_de_smaa_groenne/piece_vingeskal.md` is created
- [x] `plays/bfn943_de_smaa_groenne/place_staenglen.md` is created
- [x] `plays/bfn943_de_smaa_groenne/place_haven.md` is created
- [x] `plays/bfn943_de_smaa_groenne/process_udsugning.md` is created
- [x] `plays/bfn943_de_smaa_groenne/process_udryddelse.md` is created
- [x] `plays/bfn943_de_smaa_groenne/plan_overlevelse.md` is created and linked to `persona_bladlusen.md`
- [x] `plays/bfn943_de_smaa_groenne/plan_erobring.md` is created and linked to `persona_mariehoenen.md`
- [x] `plays/bfn943_de_smaa_groenne/pitch_mikrokosmos.md` is created
- [x] `plays/bfn943_de_smaa_groenne/plot_rosen.md` is created and casts company elements
- [x] `plays/bfn943_de_smaa_groenne/plot_regimentet.md` is created and casts company elements
- [x] `plays/bfn943_de_smaa_groenne/plot_angrebet.md` is created and casts company elements
- [x] `plays/bfn943_de_smaa_groenne/plot_overlevelsen.md` is created and casts company elements
- [x] The local validation tests (`npm test`) run successfully with zero errors
