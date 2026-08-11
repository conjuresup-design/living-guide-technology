# Living Guide Technology (LGT)

**A framework for Continuity Intelligence, accountable observation,
evidence-based understanding, governed memory, and responsible
member-facing reflection.**

Living Guide Technology (LGT) is an architectural framework for building
persistent, person-centered intelligent systems that develop
understanding through continuity rather than isolated interactions.

The Living Guide is designed as an **accountable observer**, not an
authority, oracle, or therapist. It develops and revises its
understanding from accumulated evidence while preserving uncertainty,
provenance, correction, member agency, and the distinction between
observation and interpretation.

**Current framework publication:** LGT v1.2.0\
**Reference architecture:** LGT-ARCH-001 v1.0.0\
**Reference implementation:** ConjuresUp

------------------------------------------------------------------------

## Core Principles

-   Understanding is earned through observation rather than assumption.
-   The member's lived journey is the primary source of truth.
-   Conclusions remain probabilistic, confidence-aware, and revisable.
-   Memory exists to provide continuity that enables learning,
    adaptation, and trust.
-   Evidence retains provenance and temporal context.
-   New evidence may strengthen, weaken, contradict, or replace previous
    interpretations.
-   The Guide remains loyal to evidence rather than defending earlier
    conclusions.
-   Recommendations and reflections should be traceable to accumulated
    evidence where their consequence requires it.
-   The Guide should remember what a person became through experience,
    not merely what they clicked.
-   Member agency, correction, privacy, and accountable boundaries
    remain architectural concerns rather than optional interface
    features.

## Publication Family

### Framework Publications

  ------------------------------------------------------------------------------------
  Publication             Version                              Role
  ----------------------- ------------------------------------ -----------------------
  **Living Guide          v1.0.0                               Foundational framework
  Technology ---                                               baseline and
  Foundations**                                                constitutional starting
                                                               point

  **Living Guide          [v1.1.0](publications/LGT/v1.1.0/)   Constitutional,
  Technology**                                                 ethical, and
                                                               architectural evolution

  **Living Guide          [v1.2.0](publications/LGT/v1.2.0/)   Current published
  Technology**                                                 framework evolution
  ------------------------------------------------------------------------------------

The original v1.0.0 Foundations artifacts remain at the repository root
as part of the project's publication lineage.

### Normative Architecture Publications

  ---------------------------------------------------------------------------------------------
  Publication             Version                                       Scope
  ----------------------- --------------------------------------------- -----------------------
  **LGT-ARCH-001 ---      [v1.0.0](publications/LGT-ARCH-001/v1.0.0/)   System-level
  Reference                                                             architectural
  Architecture**                                                        responsibilities,
                                                                        boundaries, flows,
                                                                        conformance,
                                                                        operations, profiles,
                                                                        and extension model

  **LGT-CIN-001 ---       [v1.0.0](publications/LGT-CIN-001/v1.0.0/)    Continuity Intelligence
  Continuity                                                            across a person's lived
  Intelligence**                                                        experiences over time

  **LGT-CMP-001 ---       [v1.0.0](publications/LGT-CMP-001/v1.0.0/)    Companion relationship
  Companion Before Oracle**                                             formation, relational
                                                                        continuity, familiarity,
                                                                        adaptation, member
                                                                        agency, anti-coercion,
                                                                        contextual permission,
                                                                        failure and recovery,
                                                                        portability, reset,
                                                                        and termination

  **LGT-OBS-001 ---       [v1.0.0](publications/LGT-OBS-001/v1.0.0/)    Observation boundaries,
  Accountable                                                           provenance,
  Observation**                                                         uncertainty,
                                                                        accountability, and
                                                                        responsible
                                                                        interpretation

  **LGT-EVD-001 ---       [v1.0.0](publications/LGT-EVD-001/v1.0.0/)    Evidentiary
  Evidence Architecture**                                               contribution,
                                                                        sufficiency,
                                                                        contradiction,
                                                                        independence,
                                                                        uncertainty, and
                                                                        confidence

  **LGT-MEM-001 ---       [v1.0.0](publications/LGT-MEM-001/v1.0.0/)    Memory eligibility,
  Memory Architecture**                                                 provenance, temporal
                                                                        context, correction,
                                                                        authorization,
                                                                        retention, and
                                                                        retrieval

  **LGT-MIR-001 ---       [v1.0.0](publications/LGT-MIR-001/v1.0.0/)    Responsible reflection
  Member-Facing                                                         of accumulated
  Reflection**                                                          understanding back to
                                                                        the member
  ---------------------------------------------------------------------------------------------

## How the Publications Relate

The framework establishes the governing concepts and constitutional
direction. Specialized publications define bounded architectural
responsibilities in greater detail. **LGT-ARCH-001** connects those
responsibilities at the system level without making a particular
software stack, model provider, hosting platform, or product
implementation mandatory.

## Continuity Intelligence

**Continuity Intelligence** is a defining concept of Living Guide
Technology: the capability to preserve meaningful continuity across a
person's experiences so accountable observations, themes, patterns,
synthesis, and reflections can emerge over time.

Continuity is not merely storage. LGT distinguishes evidence from
interpretation, preserves relevant provenance and context, accommodates
contradiction and correction, and keeps understanding revisable as new
evidence emerges.

## Reference Implementation

**ConjuresUp** is the first reference implementation of Living Guide
Technology.

It demonstrates how LGT concepts can be applied to a persistent
personalized guide whose understanding develops through member
experiences, practices, reflections, journal activity, outcomes,
patterns, and accumulated continuity.

ConjuresUp does **not** define the only valid implementation of LGT. The
Reference Architecture permits independent implementations, different
interfaces, models, infrastructure, domains, and future software or
hardware integrations while preserving the framework's constitutional
and normative responsibilities.

## Normative Status

**Normative publications** define requirements, responsibilities,
boundaries, or conformance expectations for Living Guide Technology.

**Foundational and alignment documents** preserve principles and
reasoning from which the architecture developed.

**Release, decision, verification, and supporting records** document
publication history, architectural decisions, QA state, and
specification evolution.

A document's own manifest and publication metadata should be used to
determine its authoritative version and status.

## Versioning and Publication History

Stable publication artifacts are preserved by version rather than
silently overwritten. Changes to normative architecture should occur
through explicit future versions so the meaning of an earlier stable
release remains inspectable.

The Git repository additionally preserves commit and pull-request
history for the public publication process. A newer publication does not
retroactively change the content or meaning of an earlier version.

## Repository Structure

``` text
living-guide-technology/
├── publications/
│   ├── LGT/
│   │   ├── v1.1.0/
│   │   └── v1.2.0/
│   ├── LGT-ARCH-001/v1.0.0/
│   ├── LGT-CIN-001/v1.0.0/
│   ├── LGT-CMP-001/v1.0.0/
│   ├── LGT-OBS-001/v1.0.0/
│   ├── LGT-EVD-001/v1.0.0/
│   ├── LGT-MEM-001/v1.0.0/
│   └── LGT-MIR-001/v1.0.0/
├── LGT-CONSTITUTION.md
├── LGT-SPEC-v1.0.0.md
├── LGT-SPEC-v1.0.0.pdf
├── LGT-SPEC-v1.0.0.docx
├── FOUNDATIONAL_ALIGNMENT.md
├── DECISIONS.md
└── README.md
```

## Navigating the Repository

For system architecture and implementation boundaries, begin with
**LGT-ARCH-001**.

For continuity across lived experience, continue with **LGT-CIN-001**.

For the companion relationship layer—including formation, relational
continuity, familiarity, adaptation, agency, permission, failure and
recovery, portability, reset, and termination—continue with
**LGT-CMP-001**.

For the observation-to-understanding pipeline, **LGT-OBS-001 →
LGT-EVD-001 → LGT-MEM-001 → LGT-MIR-001** follows the progression from
accountable observation through evidence and governed memory to
responsible reflection.

## Development and Conformance Philosophy

LGT is intended to remain stable enough to preserve shared meaning
across implementations while remaining open enough to support
implementations its original authors did not predict.

Technology choice alone does not establish LGT conformance. Model
capability, generic AI benchmarks, documentation, security
certification, or similarity to ConjuresUp do not substitute for
satisfying applicable normative responsibilities.

Product-specific features likewise should not automatically become LGT
requirements merely because a reference implementation uses them.

## Publication Integrity

The stable publications in this repository were developed through
incremental revision and human QA before promotion to the public `main`
branch. Git history records the publication commits and pull requests
used to promote those stable artifacts.

Future revisions should preserve this principle: **change the
architecture when evidence demonstrates a reason to change it, not
merely because another version can be created.**

## Project Status

The repository currently contains the foundational LGT publication
lineage through **v1.2.0**, the first stable **LGT Reference
Architecture v1.0.0**, and specialized v1.0.0 publications for
Continuity Intelligence, Companion Before Oracle, Accountable Observation,
Evidence Architecture, Memory Architecture, and Member-Facing Reflection.

Further evolution should occur through explicit versioned publications
and repository history rather than modification of already published
stable artifacts.

## Attribution

Living Guide Technology is developed and published through the
ConjuresUp project.

**Author:** Adam Holt\
**Reference implementation:** ConjuresUp

Licensing, citation, and contribution policies should be read from the
repository's applicable governance files once formally published.
