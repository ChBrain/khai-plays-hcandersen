---
khai: order
title: "Treat the Content-Quality Review"
language: english
license: CC-BY-NC-SA-4.0
stamp:
  owner: KAI HACKS AI
  version: v0.0.1
  date: "2026-07-18"
---

# Order: Treat the Content-Quality Review

## Direction

The house has reviewed all two hundred and sixty-nine productions for content
quality (`audit/content-quality-review/log.md`, with the full table in
`findings.json`). The review is advisory and edits nothing; this order turns its
findings into directed work. Four campaigns follow, in order of return: first
the mechanical cleanup of the Danish prose, then the restaging of the thirteen
productions whose boards tell a story their declared source does not contain,
then the restaging of the _Billedbog uden Billeder_ evening series, and last
the source-verification of the productions whose declared works the review
could not confirm. Moderate findings (softened endings, renamed characters,
over-compression - section F5 of the log) are not a campaign: each rides the
next touch of its play.

## Orders

1. The Theatre Manager (Edvard Collin) must run the mechanical cleanup first:
   the English calque 'to' where Danish 'til' belongs across the one hundred
   and ten files enumerated in `findings.json`, the garbled tokens ('sua',
   'mij'), and the untranslated English and false friends listed in section F3
   of the log. The cleanup changes prose only, never the board.
2. The Playwright (Hans Christian Andersen) must restage the thirteen severe
   productions named in section F2, each from its actual source, following the
   per-play treatment in the log; where the Choregos rules a board is kept as a
   free adaptation, the play must be re-declared instead of restaged.
3. The Playwright (Hans Christian Andersen) must restage the evening series
   (section F1) from the actual evenings of _Billedbog uden Billeder_, moving
   the shared moon-and-listener frame to one series-level board instead of
   re-inventing it per evening.
4. The Theatre Manager (Edvard Collin) must verify the thirty-nine productions
   of section F4 against the SDU/ADL editions before any of them is treated as
   faithful, and must bring the two suspect attributions (`sdu645_truth`,
   `sdu212_hans_og_grethe`) to the Choregos with a staging or retirement
   recommendation.
5. The Choregos (Nicias and Pericles) must rule, per severe production, between
   restaging from source and re-declaring as a free adaptation, and must
   sequence the campaigns so no lane mixes cleanup with restaging.
6. The Roadie (Vilhelm Pedersen) must keep the test suite green through every
   campaign and prepare each batch for packaging; content fixes to existing
   plays ship as `patch` changesets at the standing play count.

## Implementation

Each campaign lands as its own run of `play/` pull requests, the order riding
the first change it drives, per the branching contract:

- Campaign 1 (calque cleanup) may batch many plays per pull request; the file
  list in `audit/content-quality-review/findings.json` is exhaustive and
  mechanical.
- Campaigns 2 and 3 restage one production (or one evening cluster) per pull
  request, each carrying a `patch` changeset.
- Campaign 4 produces verdicts, not edits: its outcome is either a new entry in
  campaign 2's queue or a confirmation recorded against the review.
- The review itself stays advisory: `audit/content-quality-review/**` is never
  edited by treatment work, so the log remains the fixed record the campaigns
  answer to.
- Each campaign pull request carries its own rider order under
  `management/orders/` (as the `order_stage_*` orders ride their play), with
  targets completed by that change; this order is the charter those riders
  answer to, and its own targets close with this pull request.

## Targets

- [x] The review is recorded at `audit/content-quality-review/log.md`, with per-play scores for all 269 productions, the 15 deep-dive verdicts, and the treatment table in `findings.json`
- [x] The 110 calque files and the garbled tokens are enumerated exhaustively in `findings.json`, ready for campaign 1
- [x] The thirteen severe productions of section F2 are named with a per-play treatment for campaign 2
- [x] The evening series of section F1 is scoped for campaign 3, with the shared frame identified for a series-level board
- [x] The thirty-nine unverifiable productions of section F4 are listed for campaign 4, the two suspect attributions marked for the Choregos
- [x] The four campaigns are sequenced and assigned to positions, each future pull request to carry its own rider order
