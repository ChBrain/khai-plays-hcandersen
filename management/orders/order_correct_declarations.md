---
khai: order
title: "Correct the Declarations"
language: english
license: CC-BY-NC-SA-4.0
stamp:
  owner: KAI HACKS AI
  version: v0.0.1
  date: "2026-07-18"
---

# Order: Correct the Declarations

## Direction

The redeclaration queue from the source-verification campaign and the docket
ruling (`order_verify_sources.md`, `order_rule_the_docket.md`): six
productions whose declarations misstate their source. Two declared titles are
mangled and are corrected to the works' real titles; two are the German-source
booklet pieces, redeclared with Andersen's own subtitle and marked free
adaptations; two stage content beyond what their genuine but modest sources
contain, and their descriptions now say so honestly. Corrected declarations,
never rebuilds: no file moves, no board changes. The `sdu069` redeclaration is
excluded - its evening-numbering collision with `sdu086` resolves in campaign
3 once the Hersholt text is sourced.

## Orders

1. The Theatre Manager (Edvard Collin) must correct the declarations:
   `sdu615` to "Mikkels Kjærlighedshistorier i Paris", `sdu618` to "Vandring
   gjennem Opera-Galleriet", `sdu211` and `sdu212` to their titles with
   Andersen's subtitle "Smaastykker efter det Tydske" and descriptions marked
   as free adaptations, `sdu639` and `sdu651` with descriptions marked "fri
   bearbejdelse" of their genuine sources.
2. The Theatre Manager (Edvard Collin) must correct the `sdu212` sibling
   contradiction in the same touch: Hans and Grethe are rival neighbors in
   every prose line, no longer 'brothers'; the position name "Nabobroder"
   keeps its file identity until the docket's board shrink retires it.
3. The Roadie (Vilhelm Pedersen) must rebuild the registry through its single
   writer and ship the batch as a `patch` changeset at the standing count.

## Implementation

One `play/` pull request carrying this order and the six corrected plays. The
edits touch frontmatter declarations, descriptions, and the `sdu212` prose
only; every filename, link, and board structure is unchanged.

## Targets

- [x] `sdu615` and `sdu618` declare their works' real titles
- [x] `sdu211` and `sdu212` declare the "Smaastykker efter det Tydske" subtitle and describe themselves as free adaptations
- [x] `sdu639` and `sdu651` describe themselves as free adaptations of their genuine sources
- [x] No prose line in `sdu212` calls Hans and Grethe brothers
- [x] No filenames, links, or board structures changed
- [x] The registry is rebuilt by its single writer and the suite is green
