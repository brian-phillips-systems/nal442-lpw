# Latin Plate Witness (LPW) – Canonical Corpus Deposit

A structured, version-controlled corpus publication demonstrating
deterministic text segmentation, atomic file initialization, and strict
separation between source preservation and analytic layers.

This repository represents a canonical deposit layer for a structured
text corpus. It is intentionally minimal and text-first.

---

## Purpose

This project exists to demonstrate:

- Deterministic corpus segmentation
- Stable filename conventions
- Version-controlled canonical deposits
- Reproducible reference states
- Clear separation between source data and transformation systems

The repository does not include interpretation logic, rendering systems,
or transformation pipelines. It serves as a stable authority layer.

---

## Design Principles

**1. Atomic Files**

Each canonical unit is stored as an independent text file.
Files are never implicitly merged or dynamically generated.

**2. Deterministic Naming**

Filenames are stable and structured to preserve ordering
without relying on runtime logic.

**3. Reproducibility**

The repository is intended to produce identical checkouts
across environments. No build step is required.

**4. Layer Separation**

This corpus layer is strictly separated from:

- Parsing systems
- ETL pipelines
- UI layers
- Positional indexing systems

Downstream systems may consume this corpus, but they do not
modify its canonical surface.

**5. Explicit Versioning**

Structural changes, if any, require explicit version signaling.
No silent structural migrations occur.

---

## Repository Structure

- Individual `.txt` files represent canonical text units
- LICENSE (CC0 Public Domain dedication)
- README (this document)

The corpus is intentionally text-only and dependency-free.

---

## Intended Use Cases

This structure supports:

- Corpus indexing
- Integrity verification workflows
- Checksum anchoring
- Deterministic ETL integration
- Academic or archival reference

---

## License

CC0 1.0 Universal (Public Domain Dedication)

This repository waives copyright to the extent permitted by law.
It may be copied, modified, and redistributed without restriction.

---

## Status

Stable canonical deposit.
Future enhancements would require explicit structural versioning.
