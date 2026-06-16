---
updated: "2026-01-01"
---

# H.C. Andersen House: Reference

## Line of Work

Staging the works of H.C. Andersen as **systemic systems**: modeling the mechanical, thematic, and dramatic structures of the source. The house represents these works not as conventional character tragedies, but as structured processes operating under system-wide rules.

### Staging Status

The current status of the H.C. Andersen productions within this house, cataloged by their BFN (Birger Frank Nielsen bibliography) numbers:

- [x] **BFN 267: Fyrtøjet** — Staged
- [ ] **BFN 268: Lille Claus og store Claus** — Planned
- [x] **BFN 269: Prinsessen paa Ærten** — Staged
- [ ] **BFN 270: Den lille Idas Blomster** — Planned

## Origin

The authoritative source of truth for the authentic Danish texts, titles, and publication history is the official register of the H.C. Andersen Centret at Syddansk Universitet:

| Source            | Key Work / Event                       | Scope                         |
| ----------------- | -------------------------------------- | ----------------------------- |
| **SDU Centret**   | [hcandersen.dk](https://hcandersen.dk) | Chronological works database. |
| **H.C. Andersen** | BFN 267–270                            | Canonical tales (1835).       |

## Restrictions

What the house refuses to model, and to whom it delegates.

- **Absolutism & Realism**: The house refuses to claim absolute historical or psychological realism. Elements, roles, and settings are strictly reduced to the essential load-bearing vectors of the play's systemic architecture.
- **Language Policy**: The house defines its own language policy regarding the staging prose and schema compatibility:
  - **English for Architecture & Schema**: To maintain compatibility with global validation tooling and the `khai` framework specifications, structural headings, frontmatter keys, reference warrants (`REFERENCE.md` or `REFERENCES.md`), and the house identity (`README.md`) are written in English.
  - **Danish for Prose & Staging**: All character projections, actions, shadows, tells, and staging notes are written in the source's authentic language (Danish, the language Hans Christian Andersen wrote in) to preserve its original dramatic force and historical qualities.

## Encoding

Source to constraint, per file.

- **the house ([README.md](README.md))**: The Estate identity that answers for the entire run.
- **the productions (`plays/`)**: The individual staging packages, each containing the play definition, personas, positions, pieces, places, processes, and plots.
- **the gates (`tests/`, `khai-guard.config.json`)**: The conformance and governance checks ensuring that all plays comply with the canon.
