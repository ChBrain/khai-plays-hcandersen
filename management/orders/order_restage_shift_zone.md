---
khai: order
title: "Restage the Shift-Zone Evenings"
language: english
license: CC-BY-NC-SA-4.0
stamp:
  owner: KAI HACKS AI
  version: v0.0.1
  date: "2026-07-19"
---

# Order: Restage the Shift-Zone Evenings

## Direction

Campaign 3's final batch, and the close of the Billedbog restage program.
Sourcing the complete Hersholt text evening by evening exposed a
systematic defect across the boards for the twenty-first through the
thirtieth evening: they were built from a translation numbered one ahead of
Hersholt's, so each board staged its next evening's genuine content. This
is not invention but a consistent off-by-one, and it explains the
sdu069/sdu086 collision resolved earlier, its tail. Each board is realigned
to the verified text of its own declared evening.

Because the shift left some boards staging the wrong evening faithfully,
the provenance moves are mixed, and the order states each honestly:

- free to sourced: `sdu046` (24th, Thorvaldsen), `sdu053` (26th, the
  chimney sweep), `sdu055` (29th, Vreta church), `sdu056` (30th, the inn
  and the wandering musicians).
- unverified to sourced: `sdu049` (27th, the China temple), `sdu052`
  (23rd, the Tyrol nunnery).
- fidelity correction within sourced: `sdu047` (22nd, the girl and the
  doll), `sdu048` (25th, Frankfurt and Rothschild's mother), `sdu051`
  (21st, the Fezzan caravan), `sdu054` (28th, the lone swan).

Two docket items from `order_rule_the_docket.md` close here:

1. `sdu052` was held as a candidate redeclaration to the twenty-fourth
   evening's Copenhagen flashback. The question dissolves: the twenty-third
   is its own Tyrol text, and the twenty-fourth's Copenhagen boy is the
   genuine Thorvaldsen story now staged at `sdu046`.
2. The `sdu056` tail is the same shift that produced the sdu069/sdu086
   evening-numbering collision; realigning `sdu056` to the thirtieth
   evening completes that resolution.

## Orders

1. The Playwright (Hans Christian Andersen) must realign the ten boards to
   their own declared evenings from the verified text, each built to its
   source's scale: the chimney sweep runs to nine files, the three-setting
   Thorvaldsen evening to sixteen, and each play's Stakes chapter justifies
   its shape.
2. The Theatre Manager (Edvard Collin) must verify each board's fidelity to
   its declared evening and confirm each provenance move is declared per
   file, holding the fidelity corrections at sourced and moving the rest.
3. The Roadie (Vilhelm Pedersen) must rebuild the registry through its
   single writer and ship the batch as a `patch` changeset at the standing
   count.

## Implementation

One `play/` pull request carrying this order and the ten realigned boards
(`sdu046`, `sdu047`, `sdu048`, `sdu049`, `sdu051`, `sdu052`, `sdu053`,
`sdu054`, `sdu055`, `sdu056`); the wrong-evening content is removed; every
link resolves; each reference warrant records the Billedbog origin at the
declared evening's own page. With this batch all thirty-three evenings of
Billedbog uden Billeder are sourced.

## Targets

- [x] Each of the ten boards stages its own declared evening's verified text and no shifted content remains
- [x] Every content file declares its provenance move, honestly per file (free to sourced, unverified to sourced, or fidelity correction within sourced)
- [x] Each board's file count varies with its source and its shape is justified in the play's Stakes
- [x] The two docket items (sdu052 candidate-redeclaration, the sdu056 collision tail) are recorded as closed
- [x] The registry is rebuilt by its single writer and the suite is green
