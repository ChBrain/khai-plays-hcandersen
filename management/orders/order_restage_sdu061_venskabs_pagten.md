---
khai: order
title: "Restage SDU 061 Venskabspagten"
language: english
license: CC-BY-NC-SA-4.0
stamp:
  owner: KAI HACKS AI
  version: v0.0.1
  date: "2026-07-19"
---

# Order: Restage SDU 061 Venskabspagten

## Direction

Campaign 2 of the content-quality treatment charter: the review found the
former board garbled - a gender-swapped 'Anastasius', invented 'Elena' and
'Apoli', a blood-signed pact letter, and an inverted tragic ending. The
production is restaged from the actual "Venskabspagten" (1842, En Digters
Bazar): the narrator and Aphtanides both love Anastasia; the church bond of
friendship joins the two men; Aphtanides renounces, and the tale resolves in
the narrator's happy wedding with Anastasia. The board is sized to the
source per the no-template rule: three personas and four plots, with no
piece and no plan, because nothing but the three hearts and the sworn oath
moves the story.

## Orders

1. The Playwright (Hans Christian Andersen) must author the restaged board:
   personas Fortaelleren, Aphtanides, Anastasia; positions Brudgommen,
   Broderen, Vidnet; places Delfi, Bugten, Kirken; processes Kaerligheden,
   Pagten; pitch Forsoning; plots barndommen, afskeden, hjemkomsten,
   brylluppet; in authentic Danish.
2. The Theatre Manager (Edvard Collin) must verify fidelity to the 1842
   tale, the restored names, and the happy ending.
3. The Roadie (Vilhelm Pedersen) must rebuild the registry through its
   single writer and ship as a `patch` changeset at the standing count.

## Implementation

One `play/` pull request carrying this order and the restaged
`plays/sdu061_venskabs_pagten/` board; the garbled files are removed; every
link resolves.

## Targets

- [x] The Arc restores the narrator, Aphtanides, and Anastasia with the renunciation resolving into the happy wedding
- [x] The board carries no piece and no plan, with the shape justified in the Stakes
- [x] The garbled former board is fully removed with no orphan files
- [x] The registry is rebuilt by its single writer and the suite is green
