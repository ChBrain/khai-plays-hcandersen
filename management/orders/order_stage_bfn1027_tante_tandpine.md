---
khai: order
title: "Stage BFN 1027 Tante Tandpine"
language: english
license: CC-BY-NC-SA-4.0
stamp:
  owner: KAI HACKS AI
  version: v0.0.1
  date: "2026-06-25"
---

# Order: Stage BFN 1027 Tante Tandpine

## Direction

The house must stage BFN 1027 (_Tante Tandpine_) to establish the hundred and thirtieth production in the H.C. Andersen house. The production must model Rasmussen (the young student/poet) and Madam Tandpine (personified Toothache), their positions (Studerende, Pinefuld), the pieces representing the sugar/sweets (Sukker) and the poem (Digt), the environments of the cold chamber (Kammeret) and the confectionery parlor (Sukkerbageriet), the processes of agonizing pain (Smerte) and poetic creation (Digtning), their plans of escape/survival (Overlevelse) and artistic release (Poesi), the grotesque pitch, and the plots representing the aunt's pampering and the nightmare visitation of the toothache demon. It must be written in authentic Danish for all prose sections.

## Orders

1. The Playwright (Hans Christian Andersen) must author the play definition, the two personas, the two positions, the two pieces, the two places, the two processes, the two in-world plans, the pitch of Grotesk, and the two plots.
2. The Theatre Manager (Edvard Collin) must verify the local registry, ensure correct versioning, check formatting, and validate that the cast conforms to the canon.
3. The Roadie (Vilhelm Pedersen) must set the stage, verify the local test suite is green, and prepare the files for packaging.

## Implementation

The play files must be placed in `plays/bfn1027_tante_tandpine/` and follow the house language policy:

- Structural elements and frontmatter in English.
- Narrative prose, projections, actions, shadows, tells, and staging notes in Danish.

## Targets

- [x] `plays/bfn1027_tante_tandpine/play_tante_tandpine.md` is created and lists the complete company
- [x] `plays/bfn1027_tante_tandpine/persona_rasmussen.md` is created and links to `position_studerende.md`
- [x] `plays/bfn1027_tante_tandpine/persona_tandpinen.md` is created and links to `position_pinefuld.md`
- [x] `plays/bfn1027_tante_tandpine/position_studerende.md` is created
- [x] `plays/bfn1027_tante_tandpine/position_pinefuld.md` is created
- [x] `plays/bfn1027_tante_tandpine/piece_sukker.md` is created
- [x] `plays/bfn1027_tante_tandpine/piece_digt.md` is created
- [x] `plays/bfn1027_tante_tandpine/place_kammeret.md` is created
- [x] `plays/bfn1027_tante_tandpine/place_sukkerbageriet.md` is created
- [x] `plays/bfn1027_tante_tandpine/process_smerte.md` is created
- [x] `plays/bfn1027_tante_tandpine/process_digtning.md` is created
- [x] `plays/bfn1027_tante_tandpine/plan_overlevelse.md` is created and linked to `persona_rasmussen.md`
- [x] `plays/bfn1027_tante_tandpine/plan_poesi.md` is created and linked to `persona_tandpinen.md`
- [x] `plays/bfn1027_tante_tandpine/pitch_grotesk.md` is created
- [x] `plays/bfn1027_tante_tandpine/plot_tanten.md` is created and casts company elements
- [x] `plays/bfn1027_tante_tandpine/plot_tandpinen.md` is created and casts company elements
- [x] The local validation tests (`npm test`) run successfully with zero errors
