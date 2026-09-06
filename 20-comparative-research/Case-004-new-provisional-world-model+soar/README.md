# Case 004 — World Model × SOAR

**Repository Area:** `20-comparative-research/`  
**Case:** Case 004  
**Comparison:** World Model Structural Representation × SOAR Structural Representation  
**Status:** Repository Projection Complete / Freeze Pending  
**Language:** Japanese Human Observation Interface

---

# 1. Purpose

このDirectoryは、

> **World Model Structural Representation × SOAR Structural Representation**

について実施したIndependent Structural Comparisonを保存するCase Packageである。

本Caseでは、World ModelとSOARを直接比較する前に、それぞれのRepresentation PackageからIndependent Structural Projectionを形成した。

その後、Human InspectionとFreezeを経た二つのProjectionだけをComparison Objectsとして使用した。

本Caseの目的は、

> **二つのFrozen Structural Representationの間で、どこにCorrespondenceが成立し、どこにNon-Correspondenceが存在し、どのRelationがCurrent EvidenceではUndeterminedとして残るかを観察すること**

である。

本Caseは、

- Theory correctnessの評価
- Implementation Comparison
- Capability Comparison
- Performance Comparison
- Theory Integration

を目的としない。

詳細なComparison Resultは`02`–`06`に分離して保存する。

---

# 2. Case Identity — Independent Re-Challenge

本Caseは、

> **Case 004 — World Model × SOAR**

のIndependent Re-Challengeである。

Repositoryには以前形成された旧Case 004が存在する。

```text
20-comparative-research/
│
├── Case-004-provisional-world-model+soar/
│
└── Case-004-new-provisional-world-model+soar/
```

しかし、新Case形成中、旧Caseは、

> **Bracketed Legacy Observation**

としてWithholdされた。

旧Caseを、

- Answer Key
- Expected Result
- Terminology Source
- Correspondence Map
- Validation Target

として使用していない。

したがって、このPackageは旧CaseのRevisionではない。

また、旧CaseのConclusionを再現することを目的としたReplicationでもない。

同じComparison Targetに対して、

> **Independent ProjectionからComparisonを再実行した新しいComparative Package**

として位置づける。

---

# 3. Comparison Objects

本Caseで直接比較されたObjectは、World Model Theory全体とSOAR Theory全体ではない。

Comparison Objectsは、

> **Frozen Independent Structural Projection A — World Model**

および、

> **Frozen Independent Structural Projection B — SOAR**

である。

Primary SourceとなったRepresentation Packagesは、

```text
10-structural-representations/
│
├── 001-soar/
│
└── 003-world-model/
```

である。

Comparison開始前に、それぞれのPackageを独立してStructural Objectとして再構成した。

その結果、

```text
World Model
    ↓
Independent Structural Projection A
    ↓
Human Inspection
    ↓
FREEZE A


SOAR
    ↓
Independent Structural Projection B
    ↓
Human Inspection
    ↓
FREEZE B
```

という二つのFrozen Objectsが形成された。

Comparisonは、

```text
Frozen Projection A
        ×
Frozen Projection B
```

に対してのみ実施された。

---

# 4. Governing Principle

本Caseを統治したPrimary Principleは、

> **Independent Structural Projection before Comparative Observation**

である。

このPrincipleにより、

> **AをBによって再構成しない**

かつ、

> **BをAによって再構成しない**

というIndependence Conditionを維持した。

Comparisonでは、

> **Relation-before-Description**

を採用した。

単に同じVocabularyや似たPositionを探すのではなく、

> **どのStructural / Functional Responsibility間に、どの程度のRelationがEvidenceとして支持されるか**

を観察した。

また、

```text
Correspondence
Non-Correspondence
Undetermined
```

をすべて正当なComparative Resultとして扱った。

したがって、

> **Correspondenceを発見すること自体**

をComparisonの成功条件とはしていない。

---

# 5. Comparison Process

本Caseは以下の順序で形成された。

```text
Controlled Intake
      ↓
Independent Projection A
      ↓
Human Inspection
      ↓
FREEZE A
      ↓
Independent Projection B
      ↓
Human Inspection
      ↓
FREEZE B
      ↓
Restabilization
      ↓
Initial Structural Comparative Observation
      ↓
Human Freeze
      ↓
Bounded Recursive Verification
      ↓
Restabilized Comparative Judgment
      ↓
Repository Projection
```

Initial Comparative Observationの後には、

> **Bounded Recursive Verification**

を実施した。

VerificationではExternal Evidenceを追加せず、Frozen A / Bへ戻ってInitial Observationを再確認した。

Observationは必要に応じて、

- PRESERVE
- QUALIFY
- REVISE
- RECLASSIFY
- WITHDRAW
- UNDETERMINED

として処理された。

その結果を経てRestabilized Comparative Judgmentを形成し、その後にのみRepository Projectionへ進んだ。

したがって、

> **Repository Writing ≠ New Comparative Analysis**

である。

---

# 6. Primary Comparative Judgment

本CaseのRestabilized Comparative Judgmentを最も短く表すと、

> **Local Correspondence around Representational Centrality × Global Divergence in Architectural Responsibility and Closure**

である。

より厳密には、

> **Local Functional / Partial Structural Correspondence around Representational Centrality × Global Structural and Functional Divergence in Downstream Responsibility, Topology, Boundary, and Closure**

である。

最も強いCorrespondenceは、

> **World Model Representation ↔ SOAR Working Memory**

周辺に存在する。

双方ともInternal Representational Organizationとして高いCentralityを持ち、その後のCognitive Organizationを可能にする。

したがって、

> **Strong Functional Correspondence / Partial Structural Correspondence**

が支持される。

ただし、

> **Representation = Working Memory**

とは判断しない。

これは、

> **Functional Correspondence without Structural Identity**

として保持される。

Representational Center以降では両ArchitectureのResponsibilityが分岐する。

```text
WORLD MODEL

Representation
    ↓
Understanding
    ↓
Prediction
    ↓
Open Architectural Boundary


SOAR

Working Memory
    ↓
Decision
    ↓
Operator
    ↓
Action
    ↓
Environment
    ↺
```

したがって、

- Understanding ↔ Decision
- Prediction ↔ Operator
- Prediction ↔ Action

のDirect Mappingは支持されない。

Global Topologyも異なる。

World Model：

> **Stable Core + Open Architectural Boundary**

SOAR：

> **Closed Environment-Coupled Organizational Cycle**

である。

このため、

> **Local Correspondence ≠ Global Isomorphism**

をCurrent Judgmentとして維持する。

なお、以下はCurrent EvidenceではUndeterminedとして残る。

- Generative Correspondence
- Object-level Flow Correspondence
- Specific Feedback Mechanism
- Formal Recursion

これらをCase Closureのために強制解決しない。

---

# 7. Repository Structure

本Directoryは以下のArtifactsで構成される。

```text
Case-004-new-provisional-world-model+soar/
│
├── README.md
├── 01-representation-package-overview.md
├── 02-structural-correspondence.md
├── 03-functional-correspondence.md
├── 04-hierarchical-projection.md
├── 05-observation-notes.md
└── 06-comparative-summary.md
```

各Artifactは一つのRestabilized Comparative Objectを異なるResponsibilityからRepositoryへProjectionする。

したがって、`02`–`06`は互いに独立した新しいComparisonではない。

```text
Restabilized Comparative Judgment
                ↓
       Repository Projection
                ↓
     ┌──────────┼──────────┐
     │          │          │
 Structural  Functional  Hierarchical
     │          │          │
     └──────┬───┴──────┬───┘
            │          │
       Observation   Summary
```

READMEはこのPackageへのEntry / Navigationを担当する。

---

# 8. Artifact Responsibilities

| Artifact | Primary Responsibility |
|---|---|
| `01-representation-package-overview.md` | Comparison Foundation |
| `02-structural-correspondence.md` | Structural Correspondence / Non-Correspondence |
| `03-functional-correspondence.md` | Functional Responsibility Comparison |
| `04-hierarchical-projection.md` | Layer / Hierarchy / Architectural Position |
| `05-observation-notes.md` | Observation / Verification History |
| `06-comparative-summary.md` | Restabilized Case-Level Comparative Judgment |
| `README.md` | Case Entry / Navigation / Boundary Orientation |

### `01-representation-package-overview.md`

Comparison Objects、Source Boundary、Freeze、Independence、Comparison Processなど、Case全体のFoundationを確認する。

### `02-structural-correspondence.md`

Structural Units、Dependency、Transformation、Topology、Boundary、ClosureなどのStructural Correspondence / Non-Correspondenceを確認する。

### `03-functional-correspondence.md`

Functional Correspondence without Structural Identity、Representational Enabling、Downstream Functional Divergenceなどを確認する。

### `04-hierarchical-projection.md`

Layer、Vertical Responsibility、Architectural Position、Architectural Scope、Responsibility Granularityを確認する。

### `05-observation-notes.md`

Unexpected Observation、Alternative Reading、VerificationによるQualification / Revision / Reclassification / Withdrawal / Undeterminedを確認する。

### `06-comparative-summary.md`

Restabilized Comparative Judgment全体をCase-levelで確認する。

---

# 9. Recommended Reading Path

## Standard Reading Path

Case形成過程とResultを順番に確認する場合、

```text
README
   ↓
01 — Representation Package Overview
   ↓
02 — Structural Correspondence
   ↓
03 — Functional Correspondence
   ↓
04 — Hierarchical Projection
   ↓
05 — Observation Notes
   ↓
06 — Comparative Summary
```

を推奨する。

## Minimum Reading Path

Caseの目的とPrimary Judgmentを短時間で確認する場合、

```text
README
   ↓
01 — Comparison Foundation
   ↓
06 — Comparative Summary
```

をMinimum Reading Pathとする。

必要に応じて、

```text
Structural Detail
→ 02

Functional Detail
→ 03

Hierarchical Detail
→ 04

Verification History
→ 05
```

へ進む。

`06`は02–05の代替ではない。

02–05はJudgmentを支えるResponsibility-separated Projectionであり、06はそのRestabilized Judgmentを圧縮したArtifactである。

---

# 10. Evidence Boundary

本CaseのJudgmentはFrozen Representation Packagesが支持する範囲に限定される。

Comparison形成時に、

- External Web Search
- Additional Literature
- Unrelated Repository Materials
- Legacy Case 004 substantive contents

をEvidenceとして追加していない。

また、本Packageから以下を主張しない。

```text
Structural Correspondence
        ≠
Theory Equivalence

Functional Correspondence
        ≠
Mechanism Identity

Positional Similarity
        ≠
Same Responsibility

Vocabulary Identity
        ≠
Structural Identity

Local Correspondence
        ≠
Global Isomorphism

Open Boundary
        ≠
Deficiency

Structural Closure
        ≠
Epistemic Completeness

Cycle
        ≠
Feedback
        ≠
Formal Recursion

Different Responsibility
        ≠
Different Capability
```

特に、World ModelのCandidate RegionをSOARのExplicit Modulesで補完しない。

> **SOAR does not complete the World Model.**

また、SOARをWorld ModelのDetailed Version、World ModelをSOARのAbstract Versionとして扱わない。

Verification後の表現は、

> **Different Architectural Scope and Responsibility Granularity**

である。

本CaseはStructural Representation Comparisonであり、

- Theory Correctness
- Scientific Superiority
- Implementation Equivalence
- Capability Ranking
- Shared Ontology
- Universal Cognitive Architecture

を判定しない。

---

# 11. Legacy Case Boundary

旧Case 004：

```text
20-comparative-research/
└── Case-004-provisional-world-model+soar/
```

は、New Case形成中、

> **Bracketed Legacy Observation**

としてWithholdされた。

New CaseのCurrent Judgmentは、旧Caseの内容を参照せず形成されている。

したがって現段階では、

- New Case reproduced Old Case
- New Case contradicted Old Case
- New Case improved Old Case
- Old Case anticipated New Case

のいずれも判断しない。

New Case Freeze後にOld Caseを開く場合、

> **Old Case × Independently Formed New Case**

のObservationはSeparate Comparative Responsibilityとして扱う。

Old Caseを開いた後に得られたObservationによって、Freeze済みNew CaseをRetroactively Rewriteしない。

---

# 12. Current Status and Freeze Gate

現在、New Case 004のRepository Artifact Setは、

```text
README
01-representation-package-overview.md
02-structural-correspondence.md
03-functional-correspondence.md
04-hierarchical-projection.md
05-observation-notes.md
06-comparative-summary.md
```

まで形成されている。

したがって、

> **Repository Projection is complete.**

ただし、

> **Artifact Completion ≠ Case Freeze**

である。

Final Freeze前に、

1. Full Artifact SetのHuman Review
2. Cross-MD Responsibility Check
3. Evidence Boundary Check
4. Verification Result Preservation Check
5. Legacy Case Withholding Check
6. 必要なAuthorized Correction

を確認する。

その後、Humanが明示的に、

> **NEW CASE 004 — FREEZE**

を宣言した時点でCurrent New CaseをFreezeする。

---

## Final Orientation

このPackageは、

> **World ModelとSOARが似ていることを示すPackage**

でも、

> **両者が異なることを示すPackage**

でもない。

そのResponsibilityは、

> **どこでMeaningful Correspondenceが成立し、どこからArchitectural Responsibilityが分岐し、どのRelationがCurrent EvidenceではUndeterminedとして残るかを保存すること**

である。

Current Evidenceが最も安定して支持するJudgmentは、

> **Local Correspondence around Representational Centrality × Global Divergence in Architectural Responsibility and Closure**

である。

---

# Status

**Case:** Case 004 — World Model × SOAR  
**Artifact:** `README.md`  
**Artifact Responsibility:** Case Entry / Navigation / Boundary Orientation  
**Comparison Objects:** Frozen Projection A × Frozen Projection B  
**Independent Projection Condition:** Preserved  
**Restabilized Comparative Judgment:** Preserved  
**Evidence Boundary:** Preserved  
**Undetermined Findings:** Preserved  
**Frozen A/B Revision:** None  
**New Comparative Analysis:** None Added  
**Legacy Case 004:** Withheld  
**Repository Artifact Set:** 01–06 + README Complete  
**Repository Projection:** Complete  
**Case Freeze:** Pending Human Authorization  
**Next Gate:** Cross-MD / Evidence-Boundary Final Review → Human `NEW CASE 004 — FREEZE`
