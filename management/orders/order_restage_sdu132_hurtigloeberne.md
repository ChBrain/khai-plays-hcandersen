---
khai: order
title: "Restage SDU 132 Hurtigloeberne"
language: english
license: CC-BY-NC-SA-4.0
stamp:
  owner: KAI HACKS AI
  version: v0.0.1
  date: "2026-07-19"
---

# Order: Restage SDU 132 Hurtigloeberne

## Direction

Campaign 2 of the content-quality treatment charter: the review found the
former board retelling Aesop's hare-and-tortoise race in place of Andersen's
actual satire, in which no race is run at all. The production is restaged
from the actual "Hurtigloeberne" (1858): a jury of animals deliberates a
speed prize, awards the hare first and the snail second for diligence, while
the swallow, fastest of all, is disqualified for absence. The board is sized
to the source per the no-template rule: a committee-satire ensemble, the
largest board of the batch because the source is genuinely many-voiced.

## Orders

1. The Playwright (Hans Christian Andersen) must author the restaged board:
   six personas (haren, sneglen, svalen, muldyret, milepaelen, talsmanden),
   three criteria positions (hurtighed, raekkefoelge, flid), two prize
   pieces, two places (forsamlingen, taersklen), the deliberation process,
   one plan for the sole scheming juror (stamtavlen), one satirisk pitch,
   three plots (bekendtgoerelsen, raadslagningen, dommen), in authentic
   Danish, with no race staged anywhere.
2. The Theatre Manager (Edvard Collin) must verify fidelity to the 1858
   satire and canon conformance.
3. The Roadie (Vilhelm Pedersen) must rebuild the registry through its
   single writer and ship as a `patch` changeset at the standing count.

## Implementation

One `play/` pull request carrying this order and the restaged
`plays/sdu132_hurtigloeberne/` board; the Aesop-race files are removed;
every link resolves.

## Targets

- [x] The Arc stages the jury deliberation and award, with no race run
- [x] The board is sized to the source: an ensemble, with the one earned plan, shape justified in the Stakes
- [x] The former Aesop-race board is fully removed with no orphan files
- [x] The registry is rebuilt by its single writer and the suite is green
