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

- 744e366: Adopt the registry build-drift gate: bump `@chbrain/khai-tests` to `^0.1.27` and rebuild `registry.json` from source. The rebuild reconciles the registry to a fresh build (adding the `kind` discriminator each entry lacked) so the new conformance gate — which asserts the committed `registry.json` equals a fresh build — passes. Mechanical reconciliation; no content changes.
- 4ece9a6: Stage SDU 801 siboni-first-patron plot, depicting H.C. Andersen's audition at Giuseppe Siboni's dinner party and C.E.F. Weyse's collection in 1819.
- a05aaf6: Stage SDU 801 leaves-odense plot, depicting H.C. Andersen's departure from Odense in 1819.
- ed19a43: Fix trigger and company structure for SDU 629 (Den nye Barselstue).
- 4de2073: Restore H.C. Andersen authenticity to SDU 207-212 and resolve structural trigger warnings across 43 plays.
- 40ab5f5: Play: correct SDU 801 — the Grimm reconciliation happened in Copenhagen (Aug 1844), not Weimar. Replace the Weimar plot/place with Copenhagen (Grimm arriving in travelling dress at the trunk-packing), replace the textually-unsupported nightcap with the dedicated volume of tales, refine the Berlin scene to the memoir's wording, and add the Dec 1845 Berlin Christmas plot (reading to both Grimm brothers).

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
