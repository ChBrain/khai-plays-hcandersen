---
khai: order
title: "Correct the SDU 004 Fidelity"
language: english
license: CC-BY-NC-SA-4.0
stamp:
  owner: KAI HACKS AI
  version: v0.0.1
  date: "2026-07-20"
---

# Order: Correct the SDU 004 Fidelity

## Direction

The docket held `sdu004_et_boerneeventyr` quarantined, to be resolved at
the SDU register once the text was reachable (`order_rule_the_docket.md`).
The full text of _Et Børneeventyr_, the fourth chapter of _Skyggebilleder_
(1831), has now been read at the Centre's own edition page
(andersen.sdu.dk/vaerk/etboerneeventyr/, register vid 4), and the board was
independently reviewed against it. The board is faithful in the main, the
Braunschweig frame, the visiting-cards bonfire, the trusting silver-grey
King's wager, the Prince's nine years, the pining, the King's restless
ghost and its release, but the review caught the same defect class treated
in `sdu045`: invention declared sourced.

The Prince's two lies are the source's most concrete images, and the board
had replaced them with invented ones: a kale leaf "covering a whole square"
and a barn "too vast to see end to end," in place of the source's kale leaf
under whose every blade a regiment of soldiers can stand and the barn where
a swallow nested and hatched its young inside a falling axe-head before it
struck the ground. And the narrator was staged leaving "midt i akten," a
Western-drama convention the source pointedly denies, saying the melodrama
was divided "not into acts, but into Days." Both are corrected to the
source; the board keeps its sourced class, now earned.

## Orders

1. The Theatre Manager (Edvard Collin) must restore the Prince's two lies
   to the source's images (the regiment under each kale leaf, the swallow
   in the falling axe-head) wherever they are staged, and replace the "akt"
   exit with the source's Days; the board stays sourced.
2. The Theatre Manager must record the confirmed source in the reference
   warrant: the Centre's edition page and register vid 4.
3. The Roadie (Vilhelm Pedersen) must rebuild the registry through its
   single writer and ship the correction as a `patch` changeset at the
   standing count.

## Implementation

One `play/` pull request carrying this order and the corrected
`sdu004_et_boerneeventyr` board. The edits touch the Prince's lie-imagery
in three files, the "akt" wording in two, and the reference warrant; no
filename, link, or board structure changes. The source-verification record
is reconciled on its own governance pull request.

## Targets

- [x] The Prince's lies stage the source's images (a regiment under each kale leaf, a swallow hatched in the falling axe-head), not the invented square-leaf and unseeable barn
- [x] No file stages the melodrama in "acts"; the narrator leaves after the source's Days
- [x] The reference warrant cites the Centre's edition page and register vid 4
- [x] The board keeps its sourced class, now earned against the verified text
- [x] The registry is rebuilt by its single writer and the suite is green
