---
khai: order
title: "Restage SDU 621 Lykkens Blomst"
language: english
license: CC-BY-NC-SA-4.0
stamp:
  owner: KAI HACKS AI
  version: v0.0.1
  date: "2026-07-19"
---

# Order: Restage SDU 621 Lykkens Blomst

## Direction

Campaign 2 of the content-quality treatment charter: the review found the
former board staging an invented jailer couple 'Tage and Elna' in a
prison-test plot foreign to Andersen's 1845 eventyrkomedie. The production
is restaged from the actual "Lykkens Blomst": the contented forester
household, the Nisse's trial with the two magic pearls, the transformations
into Johannes Ewald's life and Prins Buris's legend with Liden Kirsten,
and the return to contentment. The full 1845 script could not be located
during verification, so the board is deliberately conservative: confirmed
figures only, no invented names, and the provisional sourcing stated
honestly in the Stakes for expansion when the primary text is in hand.

## Orders

1. The Playwright (Hans Christian Andersen) must author the restaged board:
   persona Skovfogedparret (the Nisse folded into the frame), position
   Tilfredse, piece Perlerne, place Skovfogedhjem, plan Lykkeproeven with
   standing intent, pitch Tilfredshed, processes Forvandling and
   Erkendelse, plots blomsten_visner, ewalds_liv, buris_og_kirsten,
   hjemkomsten, in authentic Danish.
2. The Theatre Manager (Edvard Collin) must verify the confirmed figures
   and the honest provisional-sourcing note, and must queue a board
   expansion review for when the 1845 text becomes reachable.
3. The Roadie (Vilhelm Pedersen) must rebuild the registry through its
   single writer and ship as a `patch` changeset at the standing count.

## Implementation

One `play/` pull request carrying this order and the restaged
`plays/sdu621_lykkens_blomst/` board; the invented Tage/Elna prison files
are removed; every link resolves.

## Targets

- [x] The Arc stages the pearls trial through Ewald and Buris into the return to contentment
- [x] The board stays within confirmed sourcing, with the provisional note in the Stakes
- [x] The former invented board is fully removed with no orphan files
- [x] The registry is rebuilt by its single writer and the suite is green
