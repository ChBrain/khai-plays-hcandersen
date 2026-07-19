---
khai: order
title: "Correct the SDU 613 Declaration"
language: english
license: CC-BY-NC-SA-4.0
stamp:
  owner: KAI HACKS AI
  version: v0.0.1
  date: "2026-07-19"
---

# Order: Correct the SDU 613 Declaration

## Direction

The redeclaration queued by the sdu611 restage ruling: the production at
`plays/sdu613_usynlige/` declares the truncated title "Usynlige" for
Andersen's dramatic jest "Den Usynlige paa Sprogø" (1839). The declaration,
the H1, and the Name are corrected to the full title. A corrected
declaration, not a rebuild: no other file changes.

## Orders

1. The Theatre Manager (Edvard Collin) must correct the declared title, the
   H1, and the Name to "Den Usynlige paa Sprogø".
2. The Roadie (Vilhelm Pedersen) must rebuild the registry through its
   single writer and ship as a `patch` changeset at the standing count.

## Implementation

One `play/` pull request carrying this order and the one corrected hub file.

## Targets

- [x] The declaration, H1, and Name read the full "Den Usynlige paa Sprogø"
- [x] No other file is changed
- [x] The registry is rebuilt by its single writer and the suite is green
