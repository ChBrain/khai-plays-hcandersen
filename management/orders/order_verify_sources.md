---
khai: order
title: "Verify the Sources"
language: english
license: CC-BY-NC-SA-4.0
stamp:
  owner: KAI HACKS AI
  version: v0.0.1
  date: "2026-07-18"
---

# Order: Verify the Sources

## Direction

Campaign 4 of the content-quality treatment charter
(`order_treat_content_quality_review.md`): the thirty-nine productions whose
declared sources the review could not confirm have been verified against the
SDU H.C. Andersen Centre register, the Hersholt translation index, kb.dk, and
theatre-history sources. The campaign produces verdicts, not edits; the record
lives at `audit/source-verification/`. Every verdict carries a board-shape
recommendation sized to the actual source, because the house is done with
template boards: a production's file count and khai types must vary with the
source material - a two-page sketch is not a three-act singspiel.

## Orders

1. The Theatre Manager (Edvard Collin) must record the verdicts and route
   them: the restage verdicts join campaign 2's queue with their board shapes
   attached; the redeclare verdicts are corrected declarations, not rebuilds;
   the keep verdicts close their review findings.
2. The Choregos (Nicias and Pericles) must rule on the unresolved docket: the
   evenings whose Hersholt content stayed out of reach, the German-source
   'Smaastykker' pair, the thin juvenilia, and the one production whose
   declared work does not exist (`sdu645_truth`) - staging from a confirmed
   source, deeper sourcing, or retirement.
3. The Playwright (Hans Christian Andersen) must, in every restaging this
   campaign feeds, build the board to the source's scale and genre per the
   recorded board shape - never to the fifteen-file template.
4. The Roadie (Vilhelm Pedersen) must keep the record advisory: this campaign
   ships no play content and no release.

## Implementation

One governance pull request carrying this order and the verification record.
The verdicts against `Billedbog uden Billeder` evenings are anchored to the
Hersholt numbering the register uses; any future pass must not trust
cross-translation evening numbers (Howitt and Hersholt split the vignettes
differently). A deeper full-text pass becomes possible if the environment's
network policy later allows the edition hosts.

## Targets

- [x] All 39 productions of section F4 carry a recorded verdict in `audit/source-verification/findings.json`
- [x] Every verdict names its evidence (register entry, edition, or the actual content found) and an owner for the next step
- [x] Every verdict carries a board-shape recommendation sized to the actual source, honoring the no-template rule
- [x] The restage queue additions, redeclarations, keeps, and the Choregos docket are tabulated in `audit/source-verification/log.md`
- [x] The cross-translation evening-numbering trap is recorded for future verification passes
