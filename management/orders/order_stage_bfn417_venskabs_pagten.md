---
khai: order
title: "Stage BFN 417 Venskabs-Pagten"
language: english
license: CC-BY-NC-SA-4.0
stamp:
  owner: KAI HACKS AI
  version: v0.0.1
  date: "2026-06-26"
---

# Order: Stage BFN 417 Venskabs-Pagten

## Direction

The house must stage BFN 417 (_Venskabs-Pagten_) to establish a production in the H.C. Andersen house. The production must model anastasius, apoli, elena, the positions (ven, foerer, elsket), the pieces (pagtbrev, ring), the environments (graekenland, hjemmet), the venskab and loyalitet processes, and the plots representing pagten and proeven. It must be written in authentic Danish for all prose sections.

## Orders

1. The Playwright (Hans Christian Andersen) must author the play definition, the 3 personas, the 3 positions, the 2 pieces, the 2 places, the 2 processes, the 2 in-world plans, the pitch of tragisk, and the 2 plots.
2. The Theatre Manager (Edvard Collin) must verify the local registry, ensure correct versioning, check formatting, and validate that the cast conforms to the canon.
3. The Roadie (Vilhelm Pedersen) must set the stage, verify the local test suite is green, and prepare the files for packaging.

## Implementation

The play files must be placed in `plays/bfn417_venskabs_pagten/` and follow the house language policy:

- Structural elements and frontmatter in English.
- Narrative prose, projections, actions, shadows, tells, and staging notes in Danish.

## Targets

- [x] `plays/bfn417_venskabs_pagten/play_venskabs_pagten.md` is created and lists the complete company
- [x] `plays/bfn417_venskabs_pagten/persona_anastasius.md` is created and links to `position_ven.md`
- [x] `plays/bfn417_venskabs_pagten/persona_apoli.md` is created and links to `position_foerer.md`
- [x] `plays/bfn417_venskabs_pagten/persona_elena.md` is created and links to `position_elsket.md`
- [x] `plays/bfn417_venskabs_pagten/position_ven.md` is created
- [x] `plays/bfn417_venskabs_pagten/position_foerer.md` is created
- [x] `plays/bfn417_venskabs_pagten/position_elsket.md` is created
- [x] `plays/bfn417_venskabs_pagten/piece_pagtbrev.md` is created
- [x] `plays/bfn417_venskabs_pagten/piece_ring.md` is created
- [x] `plays/bfn417_venskabs_pagten/place_graekenland.md` is created
- [x] `plays/bfn417_venskabs_pagten/place_hjemmet.md` is created
- [x] `plays/bfn417_venskabs_pagten/process_venskab.md` is created
- [x] `plays/bfn417_venskabs_pagten/process_loyalitet.md` is created
- [x] `plays/bfn417_venskabs_pagten/plan_loefte.md` is created and linked to `persona_anastasius.md`
- [x] `plays/bfn417_venskabs_pagten/plan_beskyttelse.md` is created and linked to `persona_apoli.md`
- [x] `plays/bfn417_venskabs_pagten/pitch_tragisk.md` is created
- [x] `plays/bfn417_venskabs_pagten/plot_pagten.md` is created and casts company elements
- [x] `plays/bfn417_venskabs_pagten/plot_proeven.md` is created and casts company elements
- [x] The local validation tests (`npm test`) run successfully with zero errors
