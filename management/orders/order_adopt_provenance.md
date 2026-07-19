---
khai: order
title: "Adopt the Provenance Key"
language: english
license: CC-BY-NC-SA-4.0
stamp:
  owner: KAI HACKS AI
  version: v0.0.1
  date: "2026-07-19"
---

# Order: Adopt the Provenance Key

## Direction

The canon-borne provenance vocabulary (khai-arch 0.1.22, ordered by
`order_declare_provenance.md`) is adopted: the kit is bumped and every
content file under `plays/**` declares its class in frontmatter in the same
change. The classes are drawn from the program's own records, never chosen
fresh: sourced for clean and restaged boards, free where the reviews
confirmed invention not yet restaged (the invented evening tableaux, the
divergent sketches and juvenilia, the declared adaptations, and the
lie-contest board awaiting its restage), unverified where sourcing is still
unproven (five evenings, five dramas, and the posthumous Truth sketch),
with file-level marks inside the two provisional restagings. The marks are
the honest today: each campaign 3 restage flips its board back to sourced.

## Orders

1. The Roadie (Vilhelm Pedersen) must bump `@chbrain/khai-arch` to the
   release carrying `provenanceValues` and verify the kit rejects an
   invalid token and accepts a valid one before the backfill.
2. The Theatre Manager (Edvard Collin) must apply the class map derived
   from `audit/content-quality-review/findings.json`,
   `audit/source-verification/findings.json`, the restaging ledger, and
   the recorded research settlements - one declaration per content file,
   no file left silent.
3. The Choregos (Nicias and Pericles) must own every future class move by
   order, and must flip each board back to sourced only when its restage
   lands.
4. The Playwright (Hans Christian Andersen) must declare the class in
   every future file at authoring time.

## Implementation

One `play/` pull request: the dependency bump (shared paths) and 4673
frontmatter declarations across 269 boards - 3841 sourced, 646 free, 186
unverified. Prose is untouched; the registry is rebuilt by its single
writer; ships as a `patch` changeset at the standing count.

## Targets

- [x] The kit validates the provenance enum (invalid token proven rejected, valid proven accepted)
- [x] Every content file under plays/** carries a provenance declaration
- [x] The classes match the program's records, with the file-level marks inside sdu611 and sdu621
- [x] The registry is rebuilt by its single writer and the suite is green
