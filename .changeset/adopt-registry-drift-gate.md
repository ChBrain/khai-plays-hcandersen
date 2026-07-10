---
"@chbrain/khai-plays-hcandersen": patch
---

Adopt the registry build-drift gate: bump `@chbrain/khai-tests` to `^0.1.27` and rebuild `registry.json` from source. The rebuild reconciles the registry to a fresh build (adding the `kind` discriminator each entry lacked) so the new conformance gate — which asserts the committed `registry.json` equals a fresh build — passes. Mechanical reconciliation; no content changes.
