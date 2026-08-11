# Repository Boundary

**Repository:** Structural Representation Research
**Repository Name:** `structural-representation-research`
**Document Status:** v1.0
**Architecture Layer:** Repository Architecture

---

# Purpose of This Document

This document defines the architectural boundary of the **Structural Representation Research Repository**.

The purpose of the boundary is to clarify:

* which research responsibilities belong inside this repository;
* which responsibilities remain outside the repository;
* which external assets may be referenced without being owned;
* how the repository interacts with the Hub Repository;
* and how future assets should be evaluated before placement.

The repository boundary is defined by **research responsibility**, not by file location, file volume, or operational convenience.

---

# Boundary Principle

The primary boundary principle is:

> **Repository follows Research Domain.**

An asset belongs in this repository when its primary responsibility participates directly in the Structural Representation Research lifecycle:

```text
Research Object
        ↓
Structural Representation
        ↓
Canonical Structural Representation
        ↓
Comparative Research
        ↓
Cross-case Synthesis
        ↓
Research Outputs
```

Assets that define the broader Research Program, generic methodologies, program-level governance, or unrelated operational activities remain outside this repository.

---

# Boundary Model

The repository boundary can be represented as:

```text
                         RESEARCH PROGRAM
                               │
              ┌────────────────┴────────────────┐
              │                                 │
       HUB REPOSITORY                  STRUCTURAL REPRESENTATION
              │                         RESEARCH REPOSITORY
              │                                 │
 Research Architecture                 Structural Representations
 Methodologies                                  ↓
 Program Governance                  Canonical Structural Assets
 Operational Coordination                       ↓
 Generic Role Resources                 Comparative Research
                                                ↓
                                       Cross-case Synthesis
                                                ↓
                                         Research Outputs
```

The two repositories remain architecturally related while maintaining distinct responsibilities.

---

# IN — Assets Within the Repository Boundary

The following asset classes belong within the Structural Representation Research Repository.

## 1. Structural Representation Assets

Assets produced as part of the structural externalization of identifiable research objects belong inside the repository.

These may include:

* Structural Skeleton
* Layer Map
* Module Map
* Dependency Map
* Architecture Matrix
* Concept Network
* Structural Topology
* Structural Summary
* Representation Validation
* Structural Design History
* Representation-specific Roadmaps

These assets are organized primarily under:

`10-structural-representations/`

---

## 2. Canonical Structural Representations

Canonical Structural Representations belong inside the repository.

They remain within the directory of the research object from which they were developed.

For example:

```text
10-structural-representations/
└── [research-object]/
    └── 07-canonical-structural-representation.md
```

Canonical Structural Representations should not be duplicated into a separate top-level canonical asset directory.

The governing principle is:

> **One Canonical Asset — One Canonical Location**

Other research activities may reference the Canonical Structural Representation, but the original representation remains authoritative.

---

## 3. Representation-Specific Reference and Provenance Assets

Reference materials directly associated with the development, validation, or provenance of a particular Structural Representation may remain within the corresponding research-object directory.

Typical placement:

```text
10-structural-representations/
└── [research-object]/
    └── reference/
```

These materials belong inside the repository when their primary function is to support traceability, reproducibility, validation, or interpretation of that Structural Representation.

Their presence does not make the repository a general-purpose source archive.

---

## 4. Comparative Research Assets

Research activities that use Structural Representations as inputs for comparison belong inside this repository.

These may include:

* Structural Correspondence
* Functional Correspondence
* Hierarchical Projection
* Difference Observation
* Comparative Observation
* Observation Notes
* Comparative Summary
* other Case-specific comparative assets

These assets are organized primarily under:

`20-comparative-research/`

Comparative Research should remain Case-centered where practical.

---

## 5. Historical Case Markers

Historical markers may remain within the Comparative Research layer when they preserve the developmental continuity of the research sequence.

Cases that predate the emergence of Comparative Research may therefore be retained when they provide:

* historical continuity;
* Case-number continuity;
* migration traceability;
* or evidence of the transition from Structural Representation to Comparative Research.

Such directories should be explicitly identified as historical markers and should not be misrepresented as completed Comparative Research cases.

---

## 6. Cross-Case Synthesis

Research assets that synthesize observations across multiple Comparative Research cases belong inside:

`30-cross-case-synthesis/`

This layer is intended for research that cannot be adequately represented as the result of a single comparison case.

Cross-case Synthesis may identify recurring:

* structural patterns;
* differences;
* correspondences;
* relationships;
* research questions;
* or higher-order observations.

---

## 7. Domain-Specific Research Outputs

Research outputs derived substantially from the Structural Representation Research domain may be maintained under:

`40-research-outputs/`

Such outputs may include research-oriented:

* papers;
* reports;
* synthesis documents;
* figures;
* or other formal research artifacts.

Placement should be determined by primary responsibility.

An output should not be placed here merely because it mentions Structural Representation.

---

# OUT — Assets Outside the Repository Boundary

The following responsibilities should normally remain outside the Structural Representation Research Repository.

## 1. Structural Representation Methodology

The **Structural Representation Methodology** remains in the Hub Repository.

This is a fundamental boundary.

The distinction is:

```text
Structural Representation Methodology
        =
How Structural Representation is performed

Structural Representation Research Repository
        =
Research activities and assets developed through
Structural Representation and downstream research
```

The repository may reference the methodology.

It does not own, duplicate, or replace it.

---

## 2. Research Program Architecture

Program-level Research Architecture remains outside this repository.

This includes architecture defining:

* the overall Research Program;
* relationships among major research domains;
* program-wide developmental stages;
* or responsibilities extending beyond Structural Representation Research.

This repository defines its own internal architecture but does not redefine the Research Program.

---

## 3. Methodological Emergence

Records documenting the emergence, stabilization, or evolution of reusable methodologies remain primarily within the methodological or emergence layers of the Hub Repository.

Research observations produced here may contribute evidence to methodological development.

However:

> **Evidence for methodology does not automatically belong to the methodology repository.**

The research asset and the methodological interpretation of that asset may therefore reside in different repositories.

---

## 4. Generic Role Packages

Generic Role Definitions, reusable Task Prompts, generic Handover Packages, and program-level Role resources should normally remain outside this repository.

Mission-specific operational documentation may be retained when it is necessary for provenance or reconstruction of a particular research activity.

The determining question is whether the resource describes:

**a reusable Role**

or

**a specific research execution.**

Reusable Role architecture remains outside.

Research-specific execution evidence may remain inside.

---

## 5. Program-Level Governance

Governance applying to the entire Research Program remains outside this repository.

The `90-governance/` layer in this repository is limited to governance required specifically for Structural Representation Research.

Examples may include:

* Canonical Asset integrity;
* representation traceability;
* Comparative Research traceability;
* cross-repository reference rules;
* repository-specific migration principles.

Repository governance must not silently override program-level governance.

---

## 6. General Operational Resources

Resources whose primary purpose is GitHub operation, general project administration, publication management, outreach, communication, or unrelated workflow coordination remain outside this repository unless they constitute necessary research provenance.

The repository should not become a general operational archive.

---

## 7. Society-Facing Communication Assets

Medium articles, X posts, presentation materials, outreach packages, and other society-facing communication assets do not belong here solely because they communicate findings from Structural Representation Research.

Where the Research Program maintains a separate Projection or Communication Architecture, those assets should remain within the appropriate communication environment.

Research outputs may serve as inputs to those environments without transferring the communication layer into this repository.

---

# REFERENCED — External Assets Used Without Ownership

Some assets may be essential to research performed within this repository while remaining architecturally external.

Typical examples include:

* Structural Representation Methodology;
* external source materials;
* original papers;
* official architecture documentation;
* external theoretical resources;
* Research Program architecture documents;
* cross-repository governance;
* society-facing communication assets.

The principle is:

> **Dependency does not imply ownership.**

An external asset may be referenced extensively without requiring physical relocation into this repository.

---

# Cross-Repository Responsibility

When an asset participates in more than one research domain, repository placement should follow **primary responsibility**.

Cross-repository links should be preferred over unnecessary duplication.

Conceptually:

```text
Hub Repository
     │
     │ Methodology / Architecture
     ▼
Structural Representation Research
     │
     │ Research Assets / Findings
     ▼
Other Research or Projection Environments
```

Each repository should preserve its own responsibility while allowing explicit relationships with other repositories.

---

# Boundary Decision Test

When the placement of a future asset is unclear, the following questions should be applied.

## Question 1

Is the asset itself a Structural Representation or part of developing one?

**Yes → normally IN**

---

## Question 2

Does the asset use Structural Representations as research inputs for comparison or synthesis?

**Yes → normally IN**

---

## Question 3

Does the asset define how Structural Representation should generally be performed across cases?

**Yes → normally OUT / Methodology**

---

## Question 4

Does the asset define the architecture or governance of the overall Research Program?

**Yes → normally OUT / Hub**

---

## Question 5

Is the asset primarily a society-facing transformation or communication artifact?

**Yes → normally OUT / appropriate Projection or Communication environment**

---

## Question 6

Is the asset needed only as evidence, provenance, or reference for a specific Structural Representation?

**Yes → IN may be appropriate as associated reference material**

---

## Question 7

Would moving the asset create a second authoritative copy?

**Yes → do not duplicate; REFERENCE the Canonical Source**

---

# Migration Boundary

Repository migration does not require every related asset to be physically moved.

For any asset originating in another repository, the appropriate action may be:

```text
MOVE
COPY
REFERENCE
REMAIN
```

The decision should preserve:

* Canonical Source integrity;
* provenance;
* research history;
* Case continuity;
* cross-repository traceability;
* and architectural responsibility.

Operational convenience alone is not sufficient justification for relocation.

---

# Boundary Stability

The repository boundary should remain stable as the number of Structural Representations and Comparative Research cases increases.

For example, adding future research objects should normally require only the addition of new research-object directories:

```text
10-structural-representations/
├── 000-ai-textbook/
├── 001-soar/
├── 002-acim/
├── 003-world-model/
├── 004-[future-object]/
└── ...
```

Likewise, new Comparative Research cases should not require redesign of the repository boundary.

Growth in asset volume alone is not evidence that a new repository boundary is required.

---

# Boundary Change Principle

The repository boundary may be reconsidered only when a research activity develops sufficient architectural independence to establish its own:

* research object;
* responsibility;
* lifecycle;
* governance requirements;
* reusable asset structure;
* and long-term developmental trajectory.

Repository separation should therefore follow **architectural independence**, not organizational convenience.

---

# Status

**Repository Boundary: Defined**

This document defines the responsibility boundary of the Structural Representation Research Repository.

Cross-repository relationships are specified in greater detail in:

`02-repository-relationship-map.md`

Repository-specific governance principles are defined in:

`03-governance-principles.md`

The historical development of this boundary is documented in:

`04-architecture-design-history.md`
