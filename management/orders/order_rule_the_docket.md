---
khai: order
title: "Rule the Docket"
language: english
license: CC-BY-NC-SA-4.0
stamp:
  owner: KAI HACKS AI
  version: v0.0.1
  date: "2026-07-18"
---

# Order: Rule the Docket

## Direction

The source-verification campaign (`order_verify_sources.md`,
`audit/source-verification/log.md`) left ten productions to the Choregos. The
two voices took the docket; the exchange below is the record, and the rulings
in Implementation fall out of it. A canon gap is noted for the house: the
instructions stage debates as discussion Plays in `management/discussions/`,
but the canon carries no discussion type, so this debate rides its order - the
Theatre Manager should raise the gap when the canon is next revised.

The cue: ten unresolved verdicts, one confirmed fabrication among them.

Nicias: The fabrication first. I will not retire `sdu645_truth` on a search
that could not even reach the editions. The house numbering follows the SDU
register; until someone reads what the register holds at that number, we do
not know whether "Truth" is invention or an entry we failed to find. Quarantine
it from faithful status and wait.

Pericles: Waiting is a decision too, and it leaves a board on the boards that
no one can vouch for. But I take your point about the numbering: the register
is the arbiter, and it is one lookup away once the network opens. Quarantine
now, resolve at the register, retire only on evidence. The same key unlocks
the six evenings: they are one text, not six cases. Fold them into the evening
campaign and source the Hersholt text once, instead of ruling six times on
snippets.

Nicias: Agreed on the evenings, with one carve-out: the twenty-third has a
named candidate in the twenty-fourth's Copenhagen flashback. That is a
redeclaration waiting on one confirmation, not a restage - keep it separate so
it does not sink with the rest.

Pericles: Kept. The booklet pair, then. The register confirms both as
Andersen's small pieces after the German; the content is beyond reach, but the
sourcing is not. Redeclare them as what they are - Smaastykker efter det
Tydske, free adaptations - and let their boards shrink to booklet scale when
next touched. That is honest today and costs nothing.

Nicias: And the child's tale stays where caution puts it: too thin to verify,
too thin to rebuild on a guess. Defer it with the register lookup, beside the
fabrication.

The verdict: no plan had anything left to press; the rulings below fell out.

## Orders

1. The Theatre Manager (Edvard Collin) must hold `sdu645_truth` and
   `sdu004_et_boerneeventyr` quarantined from faithful status, and resolve
   both at the SDU register (vid 645 and vid 4) as soon as the editions are
   reachable; retirement of `sdu645_truth` requires a dedicated order on
   register evidence, never on absence of search results.
2. The Theatre Manager (Edvard Collin) must redeclare `sdu211_de_blaae_bjerge`
   and `sdu212_hans_og_grethe` as free adaptations after the German
   ('Smaastykker efter det Tydske'), joining the redeclaration queue; the
   sibling-gender contradiction in `sdu212` is corrected in the same touch.
3. The Playwright (Hans Christian Andersen) must treat the six unresolved
   evenings (`sdu039`, `sdu042`, `sdu043`, `sdu045`, `sdu049`, `sdu052`) as
   campaign 3 stock: no per-play work until the campaign sources the complete
   Hersholt text, and `sdu052` is first checked against the twenty-fourth
   evening's Copenhagen flashback as a candidate redeclaration.
4. The Roadie (Vilhelm Pedersen) must request the network allowance for
   andersen.sdu.dk (or a human-provided text of Billedbog uden Billeder and
   the register entries) before campaign 3 or the quarantine resolutions are
   attempted.

## Implementation

The docket rulings, recorded against `audit/source-verification/findings.json`:

- `sdu645_truth` - quarantined; resolve at register vid 645; retire only by
  dedicated order on evidence.
- `sdu004_et_boerneeventyr` - quarantined; resolve at register vid 4.
- `sdu211_de_blaae_bjerge`, `sdu212_hans_og_grethe` - redeclare as free
  adaptations after the German; boards shrink to booklet scale (3-4 files)
  when touched.
- `sdu039`, `sdu042`, `sdu043`, `sdu045`, `sdu049` - campaign 3 stock, blocked
  on the sourced text.
- `sdu052_treogtyvende_aften` - candidate redeclaration to the twenty-fourth
  evening; confirm before redeclaring, else campaign 3 stock.

This order ships no play content; the redeclarations and campaign 3 land as
their own pull requests riding their own orders.

## Targets

- [x] All ten docket items carry a ruling with an owner and a trigger condition
- [x] The two quarantines name their register resolution points (vid 645, vid 4)
- [x] The redeclaration queue gains the booklet pair with the German-source declaration and the sdu212 correction noted
- [x] Campaign 3 gains the six evenings and the text-sourcing precondition
- [x] The discussion-type canon gap is recorded for the next canon revision
