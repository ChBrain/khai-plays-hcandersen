---
"@chbrain/khai-plays-hcandersen": patch
---

Declare `@chbrain/khai-engine-spine` as a runtime dependency. Every house runs on the spine — the neutral collaboration contract, the architecture seam, and the per-host setup plan — so it belongs in the production dependency graph, the single source of truth from which the zip bundler derives the engines a house carries (no hardcoded list). Adds a conformance guard that requires the spine engine and fails if any `@chbrain/khai-engine-*` is stranded in devDependencies.
