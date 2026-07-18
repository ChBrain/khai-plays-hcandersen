---
khai: order
title: "Clean the Calques"
language: english
license: CC-BY-NC-SA-4.0
stamp:
  owner: KAI HACKS AI
  version: v0.0.1
  date: "2026-07-18"
---

# Order: Clean the Calques

## Direction

Campaign 1 of the content-quality treatment charter
(`order_treat_content_quality_review.md`): the machine-translation artifacts
enumerated in `audit/content-quality-review/findings.json` (section F3 of the
review log) must be repaired across the plays. The repair is prose-only and
mechanical: the English preposition 'to' where Danish 'til' (or 'at') belongs,
untranslated English words in Danish sentences, and garbled tokens. The board
is never touched: no file, persona, position, or declared name changes, so no
link moves. Genuine Danish numerals ('de to elskende', 'to ben') and English
structural titles ('Not to Be') stay as they are; every occurrence was
classified in context before repair, not pattern-replaced blind.

## Orders

1. The Theatre Manager (Edvard Collin) must repair the enumerated calques and
   tokens in place, verifying each ambiguous occurrence against its sentence
   before changing it, and must leave every numeral and every English
   structural field untouched.
2. The Roadie (Vilhelm Pedersen) must confirm the suite stays green and the
   diff stays prose-only, and prepare the batch for packaging with a `patch`
   changeset at the standing play count.

## Implementation

One `play/` pull request carrying this order and the repaired plays. The fix
list is exact: the calque contexts and garbled tokens recorded in
`findings.json`, extended by an exhaustive in-context sweep of every remaining
' to ' in `plays/**`. Board-vocabulary leakage in prose is out of scope; it
belongs to the restaging campaigns of the charter.

## Targets

- [x] No English 'to' remains where Danish 'til' or 'at' belongs anywhere under `plays/**`; every remaining ' to ' is a Danish numeral or an English structural field
- [x] The garbled tokens of section F3 ('sua', 'mij', 'fremmet', 'hegdet', 'Metens', 'uregistrerde', 'begrnsning', 'ombøde', 'Troser', 'søer') are repaired
- [x] The untranslated English function words and leaks in Danish prose ('they', 'is', 'in', 'of', 'and', 'where', 'by', 'with', 'house', 'gliding', 'stands', 'dandelions', 'Here', 'a', 'Rags') are translated in place; Danish homographs ('is' the ice, 'and' the duck, 'from' the pious) and English structural fields stay untouched
- [x] The false friends are repaired ('kejsersnit' to 'kejserhof', 'museet' to 'musen', 'hvisker ud' to 'visker ud')
- [x] The diff is prose-only: no filenames, links, declared names, or board structure changed
- [x] The test suite is green
