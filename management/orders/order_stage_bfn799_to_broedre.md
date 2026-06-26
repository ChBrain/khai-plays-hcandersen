---
khai: order
title: "Stage BFN 799 To Brødre"
language: english
license: CC-BY-NC-SA-4.0
stamp:
  owner: KAI HACKS AI
  version: v0.0.1
  date: "2026-06-26"
---

# Order: Stage BFN 799 To Brødre

## Direction

The house must stage BFN 799 (_To Brødre_) to establish a production in the H.C. Andersen house. The production must model broder_a, broder_b, the positions (videnskabsmand, lovkyndig), the pieces (batteri, lovbog), the environments (laboratoriet, retten), the opdagelse and retfaerdiggoerelse processes, and the plots representing opdagelsen and samfundet. It must be written in authentic Danish for all prose sections.

## Orders

1. The Playwright (Hans Christian Andersen) must author the play definition, the 2 personas, the 2 positions, the 2 pieces, the 2 places, the 2 processes, the 2 in-world plans, the pitch of hyldende, and the 2 plots.
2. The Theatre Manager (Edvard Collin) must verify the local registry, ensure correct versioning, check formatting, and validate that the cast conforms to the canon.
3. The Roadie (Vilhelm Pedersen) must set the stage, verify the local test suite is green, and prepare the files for packaging.

## Implementation

The play files must be placed in `plays/bfn799_to_broedre/` and follow the house language policy:

- Structural elements and frontmatter in English.
- Narrative prose, projections, actions, shadows, tells, and staging notes in Danish.

## Targets

- [x] `plays/bfn799_to_broedre/play_to_broedre.md` is created and lists the complete company
- [x] `plays/bfn799_to_broedre/persona_broder_a.md` is created and links to `position_videnskabsmand.md`
- [x] `plays/bfn799_to_broedre/persona_broder_b.md` is created and links to `position_lovkyndig.md`
- [x] `plays/bfn799_to_broedre/position_videnskabsmand.md` is created
- [x] `plays/bfn799_to_broedre/position_lovkyndig.md` is created
- [x] `plays/bfn799_to_broedre/piece_batteri.md` is created
- [x] `plays/bfn799_to_broedre/piece_lovbog.md` is created
- [x] `plays/bfn799_to_broedre/place_laboratoriet.md` is created
- [x] `plays/bfn799_to_broedre/place_retten.md` is created
- [x] `plays/bfn799_to_broedre/process_opdagelse.md` is created
- [x] `plays/bfn799_to_broedre/process_retfaerdiggoerelse.md` is created
- [x] `plays/bfn799_to_broedre/plan_sandhed.md` is created and linked to `persona_broder_a.md`
- [x] `plays/bfn799_to_broedre/plan_orden.md` is created and linked to `persona_broder_b.md`
- [x] `plays/bfn799_to_broedre/pitch_hyldende.md` is created
- [x] `plays/bfn799_to_broedre/plot_opdagelsen.md` is created and casts company elements
- [x] `plays/bfn799_to_broedre/plot_samfundet.md` is created and casts company elements
- [x] The local validation tests (`npm test`) run successfully with zero errors
