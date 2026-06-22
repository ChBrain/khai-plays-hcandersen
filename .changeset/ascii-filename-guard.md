---
---

Add a conformance guard that every filename is ASCII. Non-ASCII filenames break their links across platforms (macOS NFD vs Linux NFC normalization) and trip tooling and zip-bundling; the house already transliterates, and this makes it a gate. Test-only — ships no package content, so an empty changeset.
