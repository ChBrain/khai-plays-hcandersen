---
khai: order
title: "Record the Booklet Register Facts"
language: english
license: CC-BY-NC-SA-4.0
stamp:
  owner: KAI HACKS AI
  version: v0.0.1
  date: "2026-07-20"
---

# Order: Record the Booklet Register Facts

## Direction

The register pages for the German-source booklet pair (`sdu211`,
`sdu212`, vid 211 and vid 212, snapshots uploaded) confirmed both as
genuine Andersen works, register nrs 211 and 212 in the eventyr category,
each first published 23 December 1972 as a manuscript piece efter det
Tydske. The source-verification ledger already records this; this order
carries the same facts into the two boards' own reference warrants, which
still cited only the general works database. No content changes: the
register gives the identity and first print but not the text, so both
boards keep their free adaptations marked `free`, pending the 1972 printing.

## Orders

1. The Theatre Manager (Edvard Collin) must enrich the `sdu211` and
   `sdu212` reference warrants with the register facts, register vid,
   eventyr category, and the 23 December 1972 first print, noting the text
   is still absent and the boards stay free adaptations.
2. The Roadie (Vilhelm Pedersen) must rebuild the registry through its
   single writer and ship the enrichment as a `patch` changeset at the
   standing count.

## Implementation

One `play/` pull request carrying this order and the two enriched warrants.
The edits touch the `Origin` sections and source tables of the two
`REFERENCES.md` files only; no board file, provenance class, link, or
structure changes.

## Targets

- [x] The `sdu211` and `sdu212` warrants cite register vid 211/212, the eventyr category, and the 23 December 1972 first print
- [x] Both warrants note the text is still absent and the boards remain free adaptations pending the 1972 printing
- [x] No board file, provenance class, link, or structure changed
- [x] The registry is rebuilt by its single writer and the suite is green
