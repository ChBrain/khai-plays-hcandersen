---
khai: order
title: "Stage BFN 890 Lygtemaendene"
language: english
license: CC-BY-NC-SA-4.0
stamp:
  owner: KAI HACKS AI
  version: v0.0.1
  date: "2026-06-24"
---

# Order: Stage BFN 890 Lygtemaendene

## Direction

The house must stage BFN 890 (_Lygtemændene ere i Byen, sagde Mosekonen_) to establish the ninety-third production in the H.C. Andersen house. The production must model Mosekone, Mand, the positions (Bryggende, Søgende), the piece (Lygte), the environments (Mose, By), the brygning and bedrag processes, and the plots leading to their realization. It must be written in authentic Danish for all prose sections.

## Orders

1. The Playwright (Hans Christian Andersen) must author the play definition, the two personas, the two positions, the piece, the two places, the two processes, the two in-world plans, the pitch of Vildfarelse, and the four plots.
2. The Theatre Manager (Edvard Collin) must verify the local registry, ensure correct versioning, check formatting, and validate that the cast conforms to the canon.
3. The Roadie (Vilhelm Pedersen) must set the stage, verify the local test suite is green, and prepare the files for packaging.

## Implementation

The play files must be placed in `plays/bfn890_lygtemaendene/` and follow the house language policy:

- Structural elements and frontmatter in English.
- Narrative prose, projections, actions, shadows, tells, and staging notes in Danish.

## Targets

- [x] `plays/bfn890_lygtemaendene/play_lygtemaendene.md` is created and lists the complete company
- [x] `plays/bfn890_lygtemaendene/persona_mosekone.md` is created and links to `position_bryggende.md`
- [x] `plays/bfn890_lygtemaendene/persona_mand.md` is created and links to `position_soegende.md`
- [x] `plays/bfn890_lygtemaendene/position_bryggende.md` is created
- [x] `plays/bfn890_lygtemaendene/position_soegende.md` is created
- [x] `plays/bfn890_lygtemaendene/piece_lygte.md` is created
- [x] `plays/bfn890_lygtemaendene/place_mose.md` is created
- [x] `plays/bfn890_lygtemaendene/place_by.md` is created
- [x] `plays/bfn890_lygtemaendene/process_brygning.md` is created
- [x] `plays/bfn890_lygtemaendene/process_bedrag.md` is created
- [x] `plays/bfn890_lygtemaendene/plan_mosebryg.md` is created and linked to `persona_mosekone.md`
- [x] `plays/bfn890_lygtemaendene/plan_optegnelse.md` is created and linked to `persona_mand.md`
- [x] `plays/bfn890_lygtemaendene/pitch_vildfarelse.md` is created
- [x] `plays/bfn890_lygtemaendene/plot_moedet.md` is created and casts company elements
- [x] `plays/bfn890_lygtemaendene/plot_mosekonens_fortaelling.md` is created and casts company elements
- [x] `plays/bfn890_lygtemaendene/plot_lygtemaendenes_tog.md` is created and casts company elements
- [x] `plays/bfn890_lygtemaendene/plot_tvivlen.md` is created and casts company elements
- [x] The local validation tests (`npm test`) run successfully with zero errors
