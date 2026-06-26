---
khai: order
title: "Stage BFN 295 Det er Dig, Fabelen sigter til!"
language: english
license: CC-BY-NC-SA-4.0
stamp:
  owner: KAI HACKS AI
  version: v0.0.1
  date: "2026-06-26"
---

# Order: Stage BFN 295 Det er Dig, Fabelen sigter til!

## Direction

The house must stage BFN 295 (_Det er Dig, Fabelen sigter til!_) to establish a production in the H.C. Andersen house. The production must model fabelen, mennesket, the positions (spejl, forfaengelig), the pieces (spejl, fjer), the environments (stuen, skoven), the afsloering and laere processes, and the plots representing historien and erkendelsen. It must be written in authentic Danish for all prose sections.

## Orders

1. The Playwright (Hans Christian Andersen) must author the play definition, the 2 personas, the 2 positions, the 2 pieces, the 2 places, the 2 processes, the 1 in-world plans, the pitch of satirisk, and the 2 plots.
2. The Theatre Manager (Edvard Collin) must verify the local registry, ensure correct versioning, check formatting, and validate that the cast conforms to the canon.
3. The Roadie (Vilhelm Pedersen) must set the stage, verify the local test suite is green, and prepare the files for packaging.

## Implementation

The play files must be placed in `plays/bfn295_det_er_dig_fabelen_sigter_til/` and follow the house language policy:

- Structural elements and frontmatter in English.
- Narrative prose, projections, actions, shadows, tells, and staging notes in Danish.

## Targets

- [x] `plays/bfn295_det_er_dig_fabelen_sigter_til/play_det_er_dig_fabelen_sigter_til.md` is created and lists the complete company
- [x] `plays/bfn295_det_er_dig_fabelen_sigter_til/persona_fabelen.md` is created and links to `position_spejl.md`
- [x] `plays/bfn295_det_er_dig_fabelen_sigter_til/persona_mennesket.md` is created and links to `position_forfaengelig.md`
- [x] `plays/bfn295_det_er_dig_fabelen_sigter_til/position_spejl.md` is created
- [x] `plays/bfn295_det_er_dig_fabelen_sigter_til/position_forfaengelig.md` is created
- [x] `plays/bfn295_det_er_dig_fabelen_sigter_til/piece_spejl.md` is created
- [x] `plays/bfn295_det_er_dig_fabelen_sigter_til/piece_fjer.md` is created
- [x] `plays/bfn295_det_er_dig_fabelen_sigter_til/place_stuen.md` is created
- [x] `plays/bfn295_det_er_dig_fabelen_sigter_til/place_skoven.md` is created
- [x] `plays/bfn295_det_er_dig_fabelen_sigter_til/process_afsloering.md` is created
- [x] `plays/bfn295_det_er_dig_fabelen_sigter_til/process_laere.md` is created
- [x] `plays/bfn295_det_er_dig_fabelen_sigter_til/plan_vaekning.md` is created and linked to `persona_fabelen.md`
- [x] `plays/bfn295_det_er_dig_fabelen_sigter_til/pitch_satirisk.md` is created
- [x] `plays/bfn295_det_er_dig_fabelen_sigter_til/plot_historien.md` is created and casts company elements
- [x] `plays/bfn295_det_er_dig_fabelen_sigter_til/plot_erkendelsen.md` is created and casts company elements
- [x] The local validation tests (`npm test`) run successfully with zero errors
