---
"@chbrain/khai-plays-hcandersen": patch
---

Transliterate four play-element filenames from Danish characters to ASCII (ø→oe, æ→ae), matching the house's own convention (stoppenaalen, koekkenet, gadeloegten): plan_holger_danske_droem, plot_droemmen (bfn472), process_knaek (bfn482), plot_droemme (bfn517). Non-ASCII filenames break their links across platforms (NFC/NFD normalization, tooling, zip bundling). The Danish prose in the play bodies is untouched; only the filenames and the links and management orders that reference them are updated.
