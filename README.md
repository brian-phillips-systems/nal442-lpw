# LPW — Canonical Corpus Deposit

## Purpose

This repository contains the canonical LPW corpus deposit.

It is a stable, text-first archive layer intended for:

- deterministic storage
- reproducible reference
- layer-separated integration into downstream systems

This repository is not a viewer, pipeline, or interpretive engine.

It is a corpus authority layer.


---

## Current State (Canonical Surface v0)

The present corpus:

- Preserves canonical textual units
- Maintains deterministic filenames
- Avoids embedded runtime dependencies
- Avoids UI binding
- Avoids enforced positional (POS) coupling

The repository intentionally prioritizes:

- stability
- clarity
- auditability
- minimalism


---

## Architectural Position

LPW occupies the **corpus layer** in a multi-layer manuscript system.

It is intentionally separated from:

- visual navigation substrates (e.g., static viewers)
- positional alignment engines
- interpretive layers
- transformation pipelines

This separation preserves evidentiary integrity and future flexibility.


---

## Column-Level Evolution (Structured Flexibility)

The current structure allows for future refinement at the column level.

Possible future enhancements may include:

- deterministic column subdivision
- column-level manifest anchoring
- structural metadata binding
- checksum anchoring of column units
- alignment scaffolding for positional systems

Any such enhancement will:

- respect canonical freeze points
- preserve backward compatibility where possible
- require explicit version signaling

No silent structural migration will occur.


---

## Versioning Philosophy

This repository is:

- stable
- incrementally improvable
- version-declarable when structural changes occur

Future structural enhancements will be reflected via:

- semantic version tags
- documented change logs
- explicit migration notes

Immutability of declared canonical units is prioritized.


---

## Non-Goals

This repository does not:

- interpret manuscript meaning
- normalize textual variants
- embed runtime UI components
- bind permanently to positional scaffolding
- collapse layers into a monolithic tool


---

## Governance

Changes to canonical textual units require explicit declaration.

Structural refinements must:

- preserve deterministic file architecture
- maintain auditability
- avoid silent mutation

This repository models reproducible digital humanities infrastructure with strict layer separation and controlled evolution.
