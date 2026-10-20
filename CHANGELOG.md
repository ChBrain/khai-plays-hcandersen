# @chbrain/khai-plays-hcandersen

## 0.270.0

### Minor Changes

- c74b657: Play: stage SDU 609 (Agnete og Havmanden).
- 1e33e43: Play: stage SDU 610 (Festen paa Kenilworth).
- 74c44e1: Play: stage SDU 611 (Skilles og mødes).
- aa210fa: Play: stage SDU 612 (En rigtig Soldat).
- dd262ed: Play: stage SDU 613 (Den Usynlige paa Sprogø).
- 4c908fc: Play: stage SDU 614 (Mulatten).
- d6c056e: Play: stage SDU 615 (Mikkels Kjærlighedshistorier i Paris).
- d24795d: Play: stage SDU 616 (En Comedie i det Grønne).
- 271ccb7: Play: stage SDU 617 (Maurerpigen).
- 2d641e1: Play: stage SDU 618 (Vandring gjennem Opera-Galleriet).
- 7d8339e: Play: stage SDU 619 (Kongen drømmer).
- 8afb92b: Play: stage SDU 620 (Fragmenter af Ahasverus).
- bf8ab10: Play: stage SDU 621 (Lykkens Blomst).
- 156182e: Play: stage SDU 622 (Liden Kirsten).
- 34671d2: Play: stage SDU 623 (Ahasverus).
- 0cc6ab5: Play: stage SDU 624 (Kunstens Dannevirke).
- 51aebe7: Play: stage SDU 625 (Brylluppet ved Como-Søen).
- 20c96f2: Play: stage SDU 626 (Meer end Perler og Guld).
- f30a508: Play: stage SDU 627 (En Nat i Roeskilde).
- d650634: Play: stage SDU 628 (Ole Lukøie).
- cbe83fc: Play: stage SDU 629 (Den nye Barselstue).
- dbae909: Play: stage SDU 630 (Hyldemoer).
- 6506bdd: Play: stage SDU 631 (Nøkken).
- 54e57b1: Play: stage SDU 632 (Indledning til Carnevalet).
- fdf1d1d: Play: stage SDU 633 (Fuglen i Pæretræet).
- 4805747: Play: stage SDU 634 (En Landsbyhistorie).
- 5da542b: Play: stage SDU 635 (Paa Langebro).
- d960217: Play: stage SDU 636 (Han er ikke født).
- 719ea30: Play: stage SDU 637 (Da Spanierne var her).
- e1985ed: Play: stage SDU 638 (Kong Saul).
- db96c15: Play: stage SDU 639 (I Vetturinens Vogn).
- a553c10: Play: stage SDU 642 (Intermediet til Holbergs: Kilderejsen).
- 168423f: Play: stage SDU 643 (Hr. Rasmussen).
- 06eda10: Play: stage SDU 644 (Danmark).
- 5cbaf44: Play: stage SDU 645 (Truth).
- f03a943: Play: stage SDU 646 (I Maaneskin).
- 00447c5: Play: stage SDU 647 (Souffleurens Benefice).
- d6d95b0: Play: stage SDU 650 (En Oedeland).
- 871d254: Play: stage SDU 651 (Sangerinden).
- 1f7798c: Stage SDU 801: Mit eget Eventyr uden Digtning — Hans Christian Andersens selvbiografi med møderne med Jacob Grimm i Berlin og Weimar (1844).

### Patch Changes

- 57839d1: Adopt the canon-borne provenance key (khai-arch 0.1.22): every content file
  declares sourced, free, or unverified in frontmatter, per the class map
  drawn from the content-quality program's records.
- 744e366: Adopt the registry build-drift gate: bump `@chbrain/khai-tests` to `^0.1.27` and rebuild `registry.json` from source. The rebuild reconciles the registry to a fresh build (adding the `kind` discriminator each entry lacked) so the new conformance gate — which asserts the committed `registry.json` equals a fresh build — passes. Mechanical reconciliation; no content changes.
- 4ece9a6: Stage SDU 801 siboni-first-patron plot, depicting H.C. Andersen's audition at Giuseppe Siboni's dinner party and C.E.F. Weyse's collection in 1819.
- a05aaf6: Stage SDU 801 leaves-odense plot, depicting H.C. Andersen's departure from Odense in 1819.
- ae400a8: Clean the machine-translation calques across the plays: English 'to' for
  Danish 'til'/'at', untranslated English function words in Danish prose, and
  garbled tokens, per campaign 1 of the content-quality treatment order.
  Prose-only; no board, filename, or link changes.
- b6607d4: Correct six play declarations per the source-verification campaign: real
  titles for sdu615/sdu618, the German-source booklet subtitle and free-
  adaptation marking for sdu211/sdu212 (with the sibling contradiction fixed),
  and free-adaptation descriptions for sdu639/sdu651.
- c874017: Correct sdu004 Et Boerneeventyr against the now-sourced Skyggebilleder text: restore the Prince's two lies to the source's images (a regiment under each kale leaf, a swallow hatched in the falling axe-head) in place of invented ones, replace the "act" exit with the source's Days, and cite the confirmed source page and register vid 4. Quarantine lifted.
- 9a568ec: Correct sdu045 Tyvende Aften: remove two contradictory invented motives for the un-pulled bell-rope (the source gives none), restoring the board to sourced fidelity, and fix the register citation from the volume-level item 313 to vid 45.
- 595b763: Correct the sdu613 declaration to the full title "Den Usynlige paa Sprogø",
  per the redeclaration queued by the sdu611 restage ruling.
- 1877322: Stage SDU 801 thorvaldsen-rome plot, depicting H.C. Andersen's meeting and relationship with Bertel Thorvaldsen in Rome in 1833–34.
- ed19a43: Fix trigger and company structure for SDU 629 (Den nye Barselstue).
- 1d333f7: repair 13 broken intra-play links across SDU plays: prose references that dropped the `.md` extension the Company declaration carried, now caught by the resolve-any link check
- 11fecbb: Stage SDU 801 england-dickens plot, depicting H.C. Andersen's meeting with Charles Dickens at Gore House in London in 1847.
- 5d63678: Stage SDU 801 collin-stipend plot, depicting Jonas Collin securing the royal rescript from Frederik VI for H.C. Andersen's education in 1822.
- baf85ed: Stage SDU 801 orsted-prophecy plot, depicting H.C. Ørsted's prophecy that H.C. Andersen's fairy tales would make him immortal in 1835.
- ff49a47: Record the register facts in the sdu211/sdu212 warrants: both De blaae Bjerge and Hans og Grethe are confirmed genuine Andersen works (register vid 211/212, eventyr, first published 23 December 1972), their reference warrants now citing the register and first print; the boards keep their free adaptations pending the 1972 text.
- 1d333f7: author REFERENCES.md reference warrants for all 269 SDU plays, each grounded in the H.C. Andersen Centret (SDU) catalogue number and hcandersen.dk register, mapping every element file in the Encoding, so every play ships a self-contained warrant it can deploy on
- 719a23c: Repair Hvad man kan hitte paa (sdu184): restore the source's ending (no
  poetic gift, the critic's vocation), the briller/hoereroer instrument pair,
  and satirical coherence, per the docket ruling on campaign 2.
- c7d0137: Restage the sixth through tenth evenings of Billedbog uden Billeder from their verified Hersholt texts (Uppsala's poet, the coastal Viking grave, the moonless reverie, Greenland, the old maid's hearse); five invented boards move free to sourced by order.
- c45fa7c: Restage Et Boerneeventyr (sdu004) from the verified Skyggebilleder text,
  replacing the invented board and moving its provenance class to sourced.
- e503068: Restage Tolvte Aften from the verified Pompeii evening: the invented melancholy-man board is replaced by the sourced vignette (the singer in the amphitheater, the silence three minutes after), provenance moved free to sourced by order.
- b80eb3f: Restage Tyvende Aften (sdu045) from the verified Twentieth Evening (Rome,
  the shattered pitcher), moving the board's provenance to sourced.
- b828405: Restage Venskabspagten (sdu061) from the actual 1842 tale, restoring the
  narrator, Aphtanides, and Anastasia with the true ending, per campaign 2 of
  the content-quality order.
- da84c15: Restage Een og tredivte Aften (sdu069) from the settled Thirty-first
  Evening (the dancing bear), dissolving the numbering collision with sdu086
  and moving the board's provenance to sourced.
- 05934ef: Restage To og tredivte Aften (sdu086) from the settled Thirty-second
  Evening (the prisoner's farewell), completing the 31/32 settlement and
  moving the board's provenance to sourced.
- 1332826: Restage En Historie (sdu096) from Andersen's actual 1851 tale, replacing the
  invented poet-allegory board, per campaign 2 of the content-quality order.
- 006a02e: Restage Svinene (sdu098) from the actual I Sverrig travel sketch, replacing
  the invented eagle-and-sow fable, per the docket ruling on campaign 2.
- 4968d84: Restage Et Blad fra Himlen (sdu115) from the actual 1853 tale with its
  ironic ending intact, per campaign 2 of the content-quality order.
- f358dc5: Restage ABC-Bogen (sdu130) from Andersen's actual 1858 satire, replacing the
  invented letter-quarrel board, per campaign 2 of the content-quality order.
- 43e9afb: Restage Hurtigloeberne (sdu132) from Andersen's actual 1858 jury satire,
  replacing the Aesop hare-and-tortoise board, per campaign 2 of the
  content-quality order.
- bed12b7: Restage De Vises Steen (sdu133) from the actual 1858 tale, replacing the
  seeker-vs-shadow allegory and its contradictory plans, per campaign 2 of the
  content-quality order.
- 03322c1: Restage Hvad Tidselen oplevede (sdu185) from the actual 1869 tale on a
  minimal single-fable board, per campaign 2 of the content-quality order.
- a6bef92: Restage Portnoeglen (sdu197) from the actual 1872 tale, restoring the
  married household and the protegee, per campaign 2 of the content-quality
  order.
- ac9b94c: Restage Qvaek (sdu201) from the actual posthumous press satire, replacing
  the toad-stoning board, per campaign 2 of the content-quality order.
- 15a4c89: Restage Skriveren (sdu202) from the actual posthumous vanity satire,
  replacing the preserver-of-memory board, per campaign 2 of the
  content-quality order.
- 0bc69e8: Restage Den fattige Kone og den lille Canariefugl (sdu205) from the actual
  early sketch, replacing the invented caretaking board, per campaign 2 of
  the content-quality order.
- 65aff42: Restage Skilles og moedes (sdu611) from the actual 1835 two-part work,
  replacing the wrong-work Sprogoe board and correcting the truncated
  declared title, per the docket ruling on campaign 2.
- 9bb10f8: Restage Lykkens Blomst (sdu621) from the actual 1845 eventyrkomedie on a
  conservative confirmed-sources board, per campaign 2 of the content-quality
  order.
- 0b20b36: Realign the shift-zone evenings (21st through 30th of Billedbog uden Billeder): ten boards built from a translation numbered one ahead of Hersholt are corrected to their own declared evening's verified text, completing the sourcing of all 33 evenings.
- 43f1d63: Restage five verified middle evenings of Billedbog uden Billeder from their Hersholt texts (the stork and the oak, Punchinello, the child's new dress, Venice, and the butter-prayer); five invented boards move to sourced by order.
- 4de2073: Restore H.C. Andersen authenticity to SDU 207-212 and resolve structural trigger warnings across 43 plays.
- 7dbe287: Redeclare sdu645 Truth on register evidence: the work is a confirmed Andersen children's parody-comedy (BFN 1266, first printed 1940 in Eiler Høeg), not a fabrication and not retired; the board's warrant and description now record its identity while the staging stays unverified pending the 1940 text.
- 40ab5f5: Play: correct SDU 801 — the Grimm reconciliation happened in Copenhagen (Aug 1844), not Weimar. Replace the Weimar plot/place with Copenhagen (Grimm arriving in travelling dress at the trunk-packing), replace the textually-unsupported nightcap with the dedicated volume of tales, refine the Berlin scene to the memoir's wording, and add the Dec 1845 Berlin Christmas plot (reading to both Grimm brothers).
- 83dff19: Stage SDU 801 paris-heine plot, depicting H.C. Andersen's meeting with Heinrich Heine in Paris in 1833.
- 3b37221: Stage SDU 801 meisling-schooldays plot, depicting H.C. Andersen's school years and humiliation under Rector Simon Meisling.

## 0.230.0

### Minor Changes

- 6227199: Play: stage SDU 607 (Ravnen eller Broderprøven).
- 3f83df6: Play: stage SDU 608 (Dronningen paa 16 Aar).

## 0.228.0

### Minor Changes

- 609b861: Play: stage SDU 606 (Bruden fra Lammermoor).

## 0.227.0

### Minor Changes

- c6a0d58: Play: stage SDU 605 (Fornuftgiftermaalet Nr. 2).

## 0.226.0

### Minor Changes

- ec95147: Play: stage SDU 604 (Skibet).

## 0.225.0

### Minor Changes

- 93e9989: Play: stage SDU 602 (Røverne i Vissenbjerg i Fyen).
- a94d68c: Play: stage SDU 603 (Kjærlighed paa Nicolai Taarn eller Hvad siger Parterret).

## 0.223.0

### Minor Changes

- 33ea2dc: Play: stage SDU 601 (Alfsol).

## 0.222.0

### Minor Changes

- 9be3495: Play: stage SDU 503 (Den skjønne Grammatica).

## 0.221.0

### Minor Changes

- 3cbc984: Play: stage SDU 502 (Fodreise fra Holmens Canal).

## 0.220.0

### Minor Changes

- 51d9acf: Play: stage SDU 501 (Gjenfærdet ved Palnatokes Grav).

## 0.219.0

### Minor Changes

- d0026e5: Play: stage SDU 406 (Lykke-Peer).

## 0.45.1

### Patch Changes

- 5916668: Transliterate four play-element filenames from Danish characters to ASCII (ø→oe, æ→ae), matching the house's own convention (stoppenaalen, koekkenet, gadeloegten): plan_holger_danske_droem, plot_droemmen (bfn472), process_knaek (bfn482), plot_droemme (bfn517). Non-ASCII filenames break their links across platforms (NFC/NFD normalization, tooling, zip bundling). The Danish prose in the play bodies is untouched; only the filenames and the links and management orders that reference them are updated.

## 0.40.1

### Patch Changes

- 5eec50c: Declare `@chbrain/khai-engine-spine` as a runtime dependency. Every house runs on the spine — the neutral collaboration contract, the architecture seam, and the per-host setup plan — so it belongs in the production dependency graph, the single source of truth from which the zip bundler derives the engines a house carries (no hardcoded list). Adds a conformance guard that requires the spine engine and fails if any `@chbrain/khai-engine-*` is stranded in devDependencies.

## 0.19.1

### Patch Changes

- 9e3662a: Stage BFN 410 in REFERENCES.md.

## 0.14.2

### Patch Changes

- 1610977: Add a pitch (the tonal key: tenor, undertow, nerve, echo) to every H.C. Andersen play, in Danish and wired into each play's Company. 16 pitches across 14 plays.

## 0.14.1

### Patch Changes

- f686729: Converge hcandersen management onto the shared blueprint core (Order 0c). The voice layer
  and the chain-owned core (positions, shared Choregos personas, plan_stage_the_score)
  now match the blueprint verbatim; cast the house Director (Jean Hersholt) as overlay.
  Keeps its existing Roadie + touring as overlay (deferred); homes already present. The convergence gate reports 0 findings; house conformance passes.
- 0805bbe: Sync the Director position to the current blueprint: the cast named as the
  producer (the separation of two stances), and "tune the pitch" added to the
  redirect idioms. Brings the house in line with the chain canon (khai #505/#506).
- 62979db: Re-converge the Director seat to the control loop: position_director and
  plan_stage_the_score match the rewritten blueprint core (the Director runs a
  living production and captures a run, not a teller).

## 0.7.1

### Patch Changes

- ef82d17: Ship and export `registry.json`. The file exists in the repo but was excluded
  from the published package (absent from `files`, no `exports`), so consumers fell
  back to deprecated `## Arc` markdown parsing. Add `registry.json` to `files` and
  an `exports` map (`.`, `./package.json`, `./registry.json`), matching the other
  houses. Packaging fix only — no play change, so it ships at the same play count.
- 93d8025: Staging the sixth play BFN 280 (Den uartige Dreng) under plays/

## 0.5.1

### Patch Changes

- cb41a6f: Staging the fifth play BFN 278 (Tommelise) under plays/

## 0.0.1

### Patch Changes

- ce31aed: First release of the H.C. Andersen production house: raised and empty, ready to receive plays (written later in khai-playwright mode). Cuts the initial publish of the programme package; the minor stays at the play count (0).
