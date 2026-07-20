---
khai: order
title: "Correct the SDU 045 Fidelity"
language: english
license: CC-BY-NC-SA-4.0
stamp:
  owner: KAI HACKS AI
  version: v0.0.1
  date: "2026-07-19"
---

# Order: Correct the SDU 045 Fidelity

## Direction

The post-merge review of the sourced Billedbog evenings caught three
defects in `sdu045_tyvende_aften`, an early restaging that predates the
tightened exemplar discipline. The board stages the verified Twentieth
Evening faithfully in the main, but carried unmarked invention and a
miscited register number, and both are corrected here without touching the
board's shape.

The Twentieth Evening gives no reason why the girl dares not pull the
bell-rope; she simply dare not, as the play's own Arc says ("tør hun ikke
trække i den"). Two files had each supplied a different invented motive,
declared sourced: the persona's Shadow blamed fear of the grandmother's
anger over the broken pitcher, and the plot's Action blamed fear of
disturbing whoever lived behind the door. Unmarked invention is the house's
cardinal defect, and two contradictory inventions on one sourced board
doubly so. Both are removed and replaced with the source's own irony, that
the child weeps over a worthless jar amid the priceless ruins she lives
among, which the campaign's ruling already named. The reference warrant is
corrected from the volume-level register number (item 313, copied from
`sdu086`) to this evening's own catalogue number, register vid 45,
matching every sibling evening.

## Orders

1. The Theatre Manager (Edvard Collin) must remove the two invented
   bell-rope motives in `persona_pigen.md` and `plot_taarerne.md`, holding
   the board sourced by restoring the source's silence on the girl's
   reason, and correct the register citation in `REFERENCES.md` to vid 45.
2. The Roadie (Vilhelm Pedersen) must rebuild the registry through its
   single writer and ship the correction as a `patch` changeset at the
   standing count.

## Implementation

One `play/` pull request carrying this order and the corrected
`sdu045_tyvende_aften` board. The edits touch two prose lines and one
citation only; every filename, link, and board structure is unchanged.

## Targets

- [x] No file in `sdu045_tyvende_aften` supplies an invented reason for the un-pulled bell-rope; the board stays sourced and faithful to the source's silence
- [x] The reference warrant cites register vid 45, not the volume-level item 313
- [x] No filenames, links, or board structure changed
- [x] The registry is rebuilt by its single writer and the suite is green
