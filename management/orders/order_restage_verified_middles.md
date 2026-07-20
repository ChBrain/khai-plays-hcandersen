---
khai: order
title: "Restage the Verified Middle Evenings"
language: english
license: CC-BY-NC-SA-4.0
stamp:
  owner: KAI HACKS AI
  version: v0.0.1
  date: "2026-07-19"
---

# Order: Restage the Verified Middle Evenings

## Direction

Campaign 3 continues: the second sourced batch of Billedbog uden Billeder,
five evenings whose complete Hersholt text was sourced at the register's
own pages. These boards had staged invention with no basis in Andersen: a
soldier on the ramparts, a desert traveler, an old woman at a grave, a
fisherman's boat, a painter's farewell. Each is restaged from its verified
evening and sized to that evening, never to the fifteen-file template. By
this order their provenance class moves to sourced, declared per file.

The verified content, per evening:

- Fourteenth (`sdu039`): two farmhouses by the forest path, the stork's
  nest on the sawed-off oak, brother and sister debating where the baby
  comes from, the neighbor woman calling them to the little brother.
- Sixteenth (`sdu041`): Punchinello, the richly gifted soul in a
  deformed body, who loved Columbine; her marriage to Harlequin, her
  death, and his doubly merry burial-day performance, then his vigil on
  her grave.
- Seventeenth (`sdu042`): the four-year-old in her new blue dress and
  rose bonnet, stiff as a doll with joy, asking what the dogs will think
  of her finery.
- Eighteenth (`sdu043`): Venice, the phantom city, the ocean's widow's
  veil, the Piazza's pigeons, the bound-winged lion, the Bridge of Sighs,
  the wedding ring cast from the Bucentaur.
- Thirty-third (`sdu087`): the curtainless nursery window, the four-year-
  old at her Lord's Prayer, adding "with plenty of butter on it."

## Orders

1. The Playwright (Hans Christian Andersen) must author the five restaged
   boards from the verified evenings, each built to its source's scale:
   the shortest seventeenth runs to ten files, the image-dense eighteenth
   and the years-spanning sixteenth run larger, and each play's Stakes
   chapter justifies its shape.
2. The Theatre Manager (Edvard Collin) must verify each board's fidelity
   to its verified evening and confirm the class move to sourced is
   declared in every file.
3. The Roadie (Vilhelm Pedersen) must rebuild the registry through its
   single writer and ship the batch as a `patch` changeset at the standing
   count.

## Implementation

One `play/` pull request carrying this order and the five restaged boards
(`sdu039`, `sdu041`, `sdu042`, `sdu043`, `sdu087`); the invented files are
removed; every link resolves; each reference warrant records the Billedbog
origin at the evening's own page.

## Targets

- [x] Each of the five boards stages its verified evening and no invented content remains
- [x] Every content file declares provenance sourced, moving each board's class by this order
- [x] Each board's file count varies with its source and its shape is justified in the play's Stakes
- [x] The former invented boards are fully removed with no orphan files
- [x] The registry is rebuilt by its single writer and the suite is green
