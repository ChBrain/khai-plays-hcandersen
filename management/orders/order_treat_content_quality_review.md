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
over-compression — section F5 of the log) are not a campaign: each rides the
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

## Targets

- [ ] The 110 calque files enumerated in `findings.json` read as idiomatic Danish, with no English 'to' for 'til' remaining under `plays/**`
- [ ] The garbled tokens ('sua', 'mij') and the F3 false friends are gone from `plays/**`
- [ ] `sdu061_venskabs_pagten` is restaged from the tale or re-declared a free adaptation, per the Choregos' ruling
- [ ] `sdu096_en_historie` is restaged from the tale or re-declared, per the ruling
- [ ] `sdu098_svinene` is restaged from the sketch or re-declared, per the ruling
- [ ] `sdu115_et_blad_fra_himlen` is restaged from the tale or re-declared, per the ruling
- [ ] `sdu130_abc_bogen` is restaged from the satire or re-declared, per the ruling
- [ ] `sdu132_hurtigloeberne` is restaged from the jury satire or re-declared, per the ruling
- [ ] `sdu133_de_vises_steen` is restaged from the tale or re-declared, per the ruling
- [ ] `sdu174_peiter_peter_og_peer` keeps its faithful stork-myth frame and regains the source's satire
- [ ] `sdu184_hvad_man_kan_hitte_paa` regains the source's ending or is re-declared, per the ruling
- [ ] `sdu185_hvad_tidselen_oplevede` is restaged from the tale or re-declared, per the ruling
- [ ] `sdu197_portner_noeglen` is restaged from the tale or re-declared, per the ruling
- [ ] `sdu611_skilles` is restaged from 'Skilles og mødes' or re-declared under 'Den Usynlige paa Sprogø'
- [ ] `sdu621_lykkens_blomst` is restaged from the 1845 play or re-declared, per the ruling
- [ ] Every `*_aften` production stages its actual evening from _Billedbog uden Billeder_
- [ ] The moon-and-listener frame lives on one series-level board, not per evening
- [ ] The 39 F4 productions carry a verified source or a recorded verdict against the review
- [ ] `sdu645_truth` and `sdu212_hans_og_grethe` have a Choregos ruling on staging or retirement
- [ ] The test suite is green after every campaign batch
