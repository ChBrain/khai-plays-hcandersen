---
khai: order
title: "Reconcile the Evening Audit"
language: english
license: CC-BY-NC-SA-4.0
stamp:
  owner: KAI HACKS AI
  version: v0.0.1
  date: "2026-07-19"
---

# Order: Reconcile the Evening Audit

## Direction

A post-merge review of the sourced Billedbog evenings closes the paper
trail. The source-verification campaign (`order_verify_sources.md`) sent
ten items to the Choregos with an honest `exists-content-unknown` verdict,
because the network policy blocked the editions at the time. Six of those
ten, the six evenings the docket held as campaign 3 stock (`sdu039`,
`sdu042`, `sdu043`, `sdu045`, `sdu049`, `sdu052`), have since been sourced
and restaged, so their audit rows now misstate the record as unresolved.

Each of the six merged boards was independently re-checked against its
verified evening; five verified clean, and the sixth surfaced a real defect
in `sdu045` (two contradictory, unmarked invented motives for the
un-pulled bell-rope, and a miscited register number) that is corrected on
its own play pull request. This order records the reconciliation; it ships
no play content and cuts no release.

## Orders

1. The Theatre Manager (Edvard Collin) must reconcile the audit record: the
   six evening verdicts in `audit/source-verification/findings.json` move
   to verified and restaged, each carrying a resolution that preserves the
   original network-blocked evidence; the log gains a resolution section;
   and the matching `audit/content-quality-review/findings.json` entries
   are unflagged with a resolution noted.
2. The Theatre Manager must keep the four remaining Choregos items honest:
   `sdu004` and `sdu645` stay quarantined at the register, and the German-
   source pair `sdu211`/`sdu212` keep their redeclaration with content still
   unverified.
3. The Roadie (Vilhelm Pedersen) must ship this as an empty changeset: the
   reconciliation ships nothing outside the package files and cuts no
   release.

## Implementation

One governance pull request carrying this order and the reconciled audit
records. The `sdu045` fidelity and citation fix rides its own play pull
request (`order_correct_sdu045_fidelity.md`), because it changes package
content and this does not.

## Targets

- [x] The six resolved evenings read verified and restaged in the source-verification record, with their original evidence preserved and a resolution added
- [x] The source-verification log carries a resolution section naming each evening, its verified content, and its pull request
- [x] The six matching content-quality-review entries are unflagged with a resolution noted
- [x] The four still-open Choregos items are left honest and unchanged
- [x] The change ships no play content and rides an empty changeset
