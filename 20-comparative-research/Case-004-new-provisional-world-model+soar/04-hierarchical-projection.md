# Hierarchical Projection

**Case:** Case 004 — World Model × SOAR  
**Artifact:** `04-hierarchical-projection.md`  
**Comparison Objects:** Frozen Projection A — World Model × Frozen Projection B — SOAR  
**Projection Source:** Restabilized Comparative Judgment  
**Status:** Restabilized Hierarchical / Architectural Projection  
**Language:** Japanese Human Observation Interface

---

# 1. Purpose

本Artifactの目的は、World ModelとSOARについて独立形成・Freezeされた二つのStructural Projectionを、

- Layer
- Vertical Organization
- Hierarchical Relation
- Cross-Level Relation
- Architectural Position
- Responsibility Distribution
- Architectural Scope
- Responsibility Granularity
- Boundary Position
- Closure Position

という観点から比較し、そのHierarchical / Architectural Relationを外在化することである。

本Artifactは、

> **二つのRepresentationを一つの共通Hierarchyへ配置すること**

を目的としない。

また、

> **どちらが上位Architectureで、どちらが下位Architectureかを判定すること**

も目的としない。

比較の中心は、

```text
Hierarchical / Layer Organization in Frozen A
                       ↕
Hierarchical / Layer Organization in Frozen B
```

である。

---

# 2. Artifact Responsibility

`04-hierarchical-projection.md`のPrimary Responsibilityは、

> **Layer / Hierarchy / Vertical Responsibility / Architectural Positionの比較**

である。

具体的には、

- 各RepresentationがどのようなLayerを持つか
- LayerがどのResponsibilityを組織するか
- UnitがLayer内部でどのPositionを持つか
- Layer間Relationがどのように形成されるか
- Vertical OrganizationがHierarchyを意味するか
- Cross-Level RelationがDependencyと同一か
- 両Architectureを共通Abstraction Scaleへ置けるか
- Architectural ScopeとResponsibility Granularityがどう異なるか

を扱う。

一方、本ArtifactはDetailed Functional Comparisonそのものを再実行しない。

それは、

> `03-functional-correspondence.md`

の責任である。

---

# 3. Governing Hierarchical Principle

本Artifactでは、以下の区別を保持する。

> **Layer ≠ Module**

> **Layer ≠ Concept**

> **Hierarchy ≠ Dependency**

> **Hierarchy ≠ Sequence**

> **Hierarchy ≠ Execution Flow**

> **Topology ≠ Hierarchy**

> **Vertical Position ≠ Functional Superiority**

> **Architectural Scope ≠ Capability Rank**

これらをCollapseすると、両Representationの異なるOrganization Axisが一つの共通Hierarchyへ強制変換される。

したがって、本Artifactでは、

> **Hierarchyを発見する前に、各Representationが何をLayerとして組織しているかを確認する。**

---

# 4. Hierarchical Projection Is Not Ranking

本Artifactにおける`Hierarchical Projection`は、

```text
Higher
  ↑
A
  ↓
B
Lower
```

というRankingを意味しない。

また、

```text
Abstract
  ↑
World Model
  ↓
SOAR
Concrete
```

という単一Scaleを前提としない。

ここでのProjectionとは、

> **各Representation内部のLayer / Vertical Responsibility / Architectural Positionを保持したまま、両者のRelationを比較可能なObservation Surfaceへ投影すること**

である。

---

# 5. Why Hierarchy Requires Separate Treatment

World ModelとSOARはともにLayered Organizationを持つ。

このため表面的には、

> **Both are layered architectures**

というCorrespondenceが見える。

しかしLayer CountまたはVertical Arrangementだけでは十分ではない。

重要なのは、

> **What does each layer organize?**

である。

同数のLayerが存在しても、

- classification axis
- responsibility
- unit membership
- boundary relation
- dependency relation
- topological role

が異なれば、同一Hierarchyとは言えない。

---

# 6. World Model Layer Organization

Frozen Projection Aでは、World Modelは主として以下のLayer Organizationを持つ。

```text
Conceptual Layer
        ↓
Cognitive Function Layer
        ↓
Architectural Extension Layer
```

ただし、このVertical Representationを、

> **strict execution hierarchy**

として読まない。

各Layerは異なるArchitectural Responsibilityを持つ。

---

# 7. World Model — Conceptual Layer

Conceptual Layerには、

- World
- Representation

が位置づけられる。

このLayerは、

> **WorldとそのInternal Representationという基本的Conceptual Organization**

を担う。

ただしWorldとRepresentationは同じStructural Statusを持たない。

`World`はCore Concept / External Referenceである。

`Representation`は、

- Core Concept
- Conceptual Layer member
- Representation Module
- Conceptual Anchor
- Dependency Origin
- Topological Center

という複数Coordinatesを持つ。

したがってConceptual Layer内部にもStructural Asymmetryが存在する。

---

# 8. World Model — Cognitive Function Layer

Cognitive Function Layerには、

- Understanding
- Prediction

が位置づけられる。

このLayerは、

> **Representationに基づくCognitive Organization**

を担う。

UnderstandingはRepresentationに依存する。

PredictionはRepresentationとUnderstandingに依存する。

したがって、

```text
Conceptual Layer
        ↓
Cognitive Function Layer
```

というVertical RelationにはDependencyとの重なりが存在する。

しかしLayer RelationそのものをDependency Relationと同一視しない。

---

# 9. World Model — Architectural Extension Layer

Architectural Extension Layerには、

- Search
- Planning
- Decision-Making
- Action

等のCandidate Functionsが関係する。

重要なのは、これらがStable Core Modulesとして確定されていないことである。

したがってこのLayerは、

> **established downstream layer**

ではない。

より正確には、

> **candidate architectural extension region**

として扱う。

---

# 10. World Model Layer Sequence

World ModelのLayer Sequenceは、

```text
Conceptual
    ↓
Cognitive Function
    ↓
Architectural Extension
```

と表現できる。

しかしFrozen Projection Aは、このSequenceを、

- strict hierarchy
- execution order
- temporal order
- control hierarchy
- implementation stack

として確定していない。

したがって、

> **Layer Sequence is observational organization, not confirmed execution hierarchy.**

---

# 11. World Model Stable Vertical Region

World Modelで最も安定したVertical Organizationは、

```text
Conceptual Responsibility
        ↓
Cognitive Responsibility
```

である。

具体的には、

```text
World / Representation
        ↓
Understanding / Prediction
```

となる。

その先は、

```text
Candidate Architectural Extension
```

としてOpenである。

したがってWorld ModelのVertical Architectureは、

> **Stable Vertical Core + Open Extension Region**

として特徴づけられる。

---

# 12. World Model Vertical Boundary

PredictionはStable Coreのdownstream boundary-facing positionを形成する。

その先に、

> **Open Architectural Boundary**

が存在する。

したがってWorld ModelのVertical Organizationは、

```text
Stable Conceptual Region
        ↓
Stable Cognitive Region
        ↓
Boundary-Facing Prediction Position
        ↓
Open Architectural Extension
```

として理解できる。

これはArchitecture全体がPredictionで終了することを意味しない。

---

# 13. World Model Hierarchical Caution

World Modelについて以下を主張しない。

```text
World
  ↓
Representation
  ↓
Understanding
  ↓
Prediction
```

が、

> **four-level strict hierarchy**

であるとは判断しない。

このChainには、

- conceptual relation
- functional relation
- dependency relation
- topological relation

が重なっている。

したがって一種類のHierarchyへCollapseしない。

---

# 14. SOAR Layer Organization

Frozen Projection Bでは、SOARは主として以下のLayer Organizationを持つ。

```text
External Interaction Layer
        ↓
Internal Representation Layer
        ↓
Cognitive Organization Layer
```

ただし、SOAR Architecture全体はこのVertical Layer Mapだけでは完結しない。

ActionからEnvironmentへのReturnによってCyclic Topologyを形成するためである。

---

# 15. SOAR — External Interaction Layer

External Interaction Layerには、

- Environment
- Perception
- Action

が関係する。

このLayerは、

> **ArchitectureとExternal Environmentのinteraction responsibility**

を組織する。

PerceptionはExternal-to-Internal ingressを担う。

ActionはInternal-to-External egress / returnを担う。

EnvironmentはInteraction Contextであり、Cycleのorigin / destinationでもある。

---

# 16. SOAR — Internal Representation Layer

Internal Representation Layerの中心は、

> **Working Memory**

である。

Working Memoryは、

- Internal Representational State
- Primary Representational Workspace
- Explicit Module
- Dependency Hub
- Network Center
- Topological Center

として機能する。

したがってInternal Representation Layerは、World Model Conceptual Layerと同じLayer Responsibilityではない。

---

# 17. SOAR — Cognitive Organization Layer

Cognitive Organization Layerには、

- Decision
- Operator

が位置づけられる。

DecisionはWorking Memoryに依存し、Behavioral Transitionをorganizeする。

OperatorはDecisionに依存し、Selected Cognitive OrganizationをActionへ接続する。

したがってこのLayerは、

> **behavior-oriented cognitive organization**

を担う。

---

# 18. SOAR Action Position

ActionはExternal Interaction Layerに属しながら、Cognitive Organizationのdownstreamに位置する。

この点はSOARのLayer Organizationを理解するうえで重要である。

Actionは、

```text
Cognitive Organization
        ↓
Action
        ↓
Environment
```

というRelationを持つ一方で、Layer ClassificationではExternal Interaction Responsibilityを担う。

したがって、

> **Layer Membership ≠ Linear Position**

である。

---

# 19. SOAR Environment Position

Environmentも単純な「最上位」または「最下位」Unitではない。

SOARではEnvironmentが、

```text
Environment
    ↓
Perception
    ↓
...
    ↓
Action
    ↓
Environment
```

としてCycleの両端に現れる。

これはEnvironmentが二つ存在することを意味しない。

同じExternal Environmentが、

- interaction origin
- interaction return destination

というTopological Responsibilityを持つ。

---

# 20. SOAR Vertical Organization

SOARをVertical Responsibilityとして圧縮すると、

```text
External Interaction
        ↓
Internal Representation
        ↓
Cognitive Organization
        ↓
Behavioral Execution
        ↓
External Interaction
```

となる。

したがってSOARのVertical Projectionは、

> **linear descent**

ではなく、

> **vertical differentiation embedded in cyclic topology**

として理解する必要がある。

---

# 21. SOAR Layer Sequence Is Not Execution Sequence

SOARのLayerを、

```text
External
   ↓
Internal Representation
   ↓
Cognitive Organization
```

と記述しても、それをcomplete execution timingとして扱わない。

Frozen Projection Bが支持するのはOrganizational Responsibilityである。

したがって、

> **Layer Sequence ≠ Temporal Execution Sequence**

を保持する。

---

# 22. Initial Layer-Level Similarity

World ModelとSOARは双方とも複数Layerを持つ。

そのため表面的には、

```text
WORLD MODEL                  SOAR

Conceptual                 External Interaction
    ↓                            ↓
Cognitive                  Internal Representation
    ↓                            ↓
Extension                  Cognitive Organization
```

のような三層比較が可能に見える。

しかし、このParallel DescriptionからLayer Correspondenceを導いてはならない。

LayerのResponsibility Axisが異なるためである。

---

# 23. Layer Count Is Not Hierarchical Correspondence

仮に両者が同数の主要Layerへ整理できても、

> **same layer count ≠ same hierarchy**

である。

Layer Correspondenceを判断するには、

- What is classified?
- By what axis?
- What responsibility is separated?
- What relation exists across layers?
- Is the layer stable or candidate?
- How does the layer relate to topology?

を見る必要がある。

---

# 24. Different Classification Axes

World ModelのLayer Organizationは、

> **Conceptual → Cognitive Function → Architectural Extension**

というAxisを持つ。

SOARは、

> **External Interaction → Internal Representation → Cognitive Organization**

というAxisを持つ。

したがって両者は同じ分類軸を使用していない。

World ModelではConceptual / Cognitive / Extension Statusが主要区別となる。

SOARではExternal Interaction / Internal Representation / Cognitive OrganizationというArchitectural Responsibilityが主要区別となる。

---

## Judgment

**Different Layer Classification Responsibility**

---

# 25. Representation Position across Layers

World Model RepresentationとSOAR Working MemoryはFunctional Correspondenceを持つが、Layer Positionは異なる。

World Model Representation：

> **Conceptual Layer**

SOAR Working Memory：

> **Internal Representation Layer**

である。

この差は単なるLabel Differenceではない。

World Model RepresentationはConceptual AnchorとしてWorldとのrelationを組織しながら、Module / Dependency / Topological Centerでもある。

SOAR Working MemoryはEnvironment-coupled Architecture内部のExplicit Representational Workspaceである。

---

# 26. Representation ↔ Working Memory at Hierarchical Level

したがって、

> **Representation ↔ Working Memory**

について、

- Functional Centrality Correspondence
- Partial Structural Correspondence

は支持される。

しかし、

> **same hierarchical position**

というClaimは強く支持されない。

両者はそれぞれのArchitecture内部でCentral Positionを持つが、そのCentralityをLayer Axis上の同一Coordinateへ置くことはできない。

---

## Judgment

**Positional Proximity without Hierarchical Identity**

---

# 27. World ↔ Environment at Hierarchical Level

World ModelのWorldはConceptual Layerに属する。

SOARのEnvironmentはExternal Interaction Layerに属する。

双方はExternal Referenceとして限定的に比較可能である。

しかし、

- Conceptual reference
- interaction context
- return destination
- module status
- cyclic role

が異なる。

したがって、

> **World ↔ Environment**

をsame hierarchical levelとして扱わない。

---

## Judgment

**Limited Positional Correspondence / Different Layer Responsibility**

---

# 28. Understanding ↔ Decision at Hierarchical Level

UnderstandingとDecisionは、それぞれRepresentational Centerよりdownstreamに位置する。

しかし、

World Model Understanding：

> Cognitive Function Layer

SOAR Decision：

> Cognitive Organization Layer

である。

Layer Labelは似て見えるが、Responsibilityは異なる。

UnderstandingはSemantic / Cognitive Mediationを担う。

DecisionはBehavioral Transition Organizationを担う。

したがって、

> **same downstream vertical position does not establish hierarchical correspondence.**

---

## Judgment

**No justified direct hierarchical mapping**

---

# 29. Prediction ↔ Operator at Hierarchical Level

PredictionとOperatorもdownstream positionを持つ。

しかし、

Prediction：

> Cognitive Function Layer / Stable Core boundary-facing downstream position

Operator：

> Cognitive Organization Layer / Decision-to-Action mediation

である。

したがって、

> **Prediction ↔ Operator**

というHierarchical Mappingは支持されない。

---

## Judgment

**Hierarchical Non-Correspondence**

---

# 30. Prediction ↔ Action at Hierarchical Level

PredictionとActionはさらに異なる。

PredictionはWorld Model Cognitive Function Layerに属する。

ActionはSOAR External Interaction Layerに属し、OperatorのdownstreamでEnvironmentへのReturnを担う。

したがって、

> **Prediction ↔ Action**

はLayer、Responsibility、Boundary Positionのいずれにおいてもdirect correspondenceを形成しない。

---

## Judgment

**Strong Hierarchical / Positional Non-Correspondence**

---

# 31. World Model Action ↔ SOAR Action

同一Vocabularyである`Action`についてもHierarchical Positionは異なる。

World Model Action：

> Candidate Architectural Extension

SOAR Action：

> Explicit External Interaction Module / Cycle Return participant

である。

したがって、

```text
Action
  ↕
Action
```

というLabel Matchは、

> **same layer position**

を意味しない。

---

## Judgment

**Vocabulary Identity without Hierarchical Correspondence**

---

# 32. Cross-Level Relation — World Model

World Modelでは、

```text
Conceptual Layer
        ↓
Cognitive Function Layer
```

の間にMeaningful Cross-Level Relationが存在する。

RepresentationはUnderstandingを支え、Representation + UnderstandingはPredictionを支える。

したがってCross-Level RelationにはDependencyとの重なりがある。

しかし、

> **Cross-Level Relation = Dependency**

ではない。

LayerはClassification Responsibilityであり、DependencyはStructural Relianceである。

---

# 33. Cross-Level Relation — SOAR

SOARでは、

```text
External Interaction
        ↓
Internal Representation
        ↓
Cognitive Organization
        ↓
External Interaction
```

というCross-Level Relationが存在する。

PerceptionはExternal InteractionからWorking Memoryへ接続する。

Working MemoryはDecisionを支える。

Decision / OperatorはActionへ接続する。

ActionはExternal Environmentへ戻る。

したがってCross-Level RelationがCyclic Topologyへ組み込まれる。

---

# 34. Cross-Level Comparison

双方ともLayer間Relationを持つ。

しかしそのCross-Level Organizationは異なる。

World Model：

> **Stable conceptual-to-cognitive organization followed by open extension**

SOAR：

> **external-to-internal-to-cognitive-to-external organizational return**

である。

したがって、

> **Cross-Level Organization exists in both**

という抽象的Correspondenceは認められる。

しかしCross-Level Architectureは同一ではない。

---

## Judgment

**Abstract Cross-Level Correspondence with Material Organizational Divergence**

---

# 35. Vertical Direction

両RepresentationにはVertical Directionを描くことができる。

しかしVertical Directionは同一種類のRelationではない。

World Modelでは、

```text
World / Representation
        ↓
Understanding / Prediction
        ↓
Open Extension
```

である。

SOARでは、

```text
Environment / Perception
        ↓
Working Memory
        ↓
Decision / Operator
        ↓
Action / Environment
```

である。

したがって、

> **shared vertical readability does not establish shared hierarchy.**

---

# 36. Hierarchy and Dependency

本ComparisonではHierarchyとDependencyを分離する。

World ModelではPredictionがRepresentation + Understandingに依存する。

しかしPredictionが「Hierarchy Level 3」であると自動的に結論しない。

SOARではActionがOperatorに依存する。

しかしActionが「lower cognitive level」であるとは判断しない。

Dependencyは、

> **what relies on what**

を示す。

Hierarchyは、

> **how architectural responsibility is vertically organized**

を示す。

---

# 37. Hierarchy and Function

Layer PositionはFunctionと関連するが同一ではない。

たとえばWorld Model UnderstandingがCognitive Function Layerに属することは、そのFunctionを理解するために重要である。

しかし、

> **Cognitive Function Layer membership**

だけでUnderstandingの全Responsibilityを定義できない。

同様にSOAR DecisionがCognitive Organization Layerに属することだけでDecision Function全体を定義できない。

---

# 38. Hierarchy and Topology

TopologyはHierarchyより広いGlobal Connection Patternを扱う。

World ModelではLayered Organizationが、

> **Stable Core + Open Architectural Boundary**

というTopologyへ組み込まれる。

SOARではLayered Organizationが、

> **Closed Environment-Coupled Organizational Cycle**

へ組み込まれる。

したがって、

> **similar layerability can coexist with different global topology.**

---

# 39. World Model Topological Effect on Hierarchy

World ModelのOpen Architectural Boundaryは、Vertical Organizationを閉じない。

そのため、

```text
Conceptual
    ↓
Cognitive
    ↓
Extension
```

を固定されたcomplete hierarchyとして扱えない。

Architectural Extension Layer自体がCandidate Regionであるため、

> **Vertical Closure remains open.**

---

# 40. SOAR Topological Effect on Hierarchy

SOARではVertical OrganizationがAction / Environment ReturnによってCycleへ戻る。

したがって、

```text
External
    ↓
Internal
    ↓
Cognitive
    ↓
External
```

となる。

この構造ではVertical Differentiationが存在しても、Global Topologyは単純なTop-down Hierarchyではない。

---

# 41. Open Vertical Boundary versus Cyclic Return

この差を圧縮すると、

```text
WORLD MODEL

Conceptual
    ↓
Cognitive
    ↓
Open Extension
```

に対して、

```text
SOAR

External Interaction
    ↓
Internal Representation
    ↓
Cognitive Organization
    ↓
External Interaction
    ↺
```

となる。

したがってGlobal Hierarchical Projectionは、

> **Open Vertical Extension versus Cyclic Cross-Level Return**

というNon-Correspondenceを示す。

---

# 42. Stable Layer versus Candidate Layer

World ModelではConceptual LayerとCognitive Function LayerがStable Coreに強く結びつく。

Architectural Extension LayerはCandidate Regionを含む。

したがって、すべてのLayerが同じObservation Statusを持つわけではない。

この点はSOARと異なる。

SOARの主要LayerはIntegrated CycleのOrganizationとして表現される。

---

# 43. Observation Status as Architectural Coordinate

World Modelでは、

- Stable
- Candidate
- Unresolved

というObservation StatusがArchitectural Organizationに関与する。

これは単なるConfidence Labelではない。

何がStable Coreに属し、何がOpen Extensionに属するかを分離する。

したがって、

> **Observation Status participates in hierarchical organization.**

---

# 44. SOAR Integrated Layer Status

SOARではEnvironment、Perception、Working Memory、Decision、Operator、ActionがIntegrated Organizational CycleとしてFrozen Projection Bに保持される。

World Model型の、

> Stable Core / Candidate Extension

という同一Status Architectureは観察されない。

したがって、

> **Status-based hierarchical organization**

にもNon-Correspondenceが存在する。

---

## Judgment

**Different Architectural Organization**

---

# 45. Boundary Position — World Model

World ModelではBoundaryがStable Coreのdownstream側に現れる。

Predictionは、

> **stable-core boundary-facing position**

を持つ。

その先のSearch / Planning / Decision-Making / Action等はCandidate Extensionとして保持される。

したがってBoundaryはVertical Architectureの外縁を形成する。

---

# 46. Boundary Position — SOAR

SOARではBoundaryは一方向の末端に限定されない。

PerceptionとActionがExternal / Internal interactionをmediatedするため、

```text
Environment
   ↓
Perception
   ↓
Internal Organization
   ↓
Action
   ↓
Environment
```

としてBoundary RelationがArchitectureの両側に分布する。

したがってSOAR Boundaryは、

> **distributed interaction boundary**

として理解できる。

---

# 47. Boundary Position Comparison

World Model：

> **downstream open architectural boundary**

SOAR：

> **distributed external/internal interaction boundary**

である。

この差はBoundaryの位置だけでなく、Boundary Responsibilityの差でもある。

---

## Judgment

**Different Boundary Position and Responsibility**

---

# 48. Closure Position — World Model

World ModelではStable CoreのVertical OrganizationがPredictionまで確立される。

しかしその先をOpen Boundaryとして保持する。

したがって、

> **Vertical Architecture does not close through a represented return relation.**

---

# 49. Closure Position — SOAR

SOARではActionからEnvironmentへのReturnによってGlobal Organizationが閉じる。

したがってClosureは、

> **vertical differentiationの末端からexternal interaction levelへreturnするtopological relation**

として形成される。

---

# 50. Closure Position Comparison

World Model：

```text
Stable Vertical Core
        ↓
Open Boundary
```

SOAR：

```text
Vertical Differentiation
        ↓
Action
        ↓
Environment
        ↺
```

となる。

したがってClosure PositionにはStrong Non-Correspondenceが存在する。

---

## Judgment

**Strong Hierarchical / Topological Non-Correspondence**

---

# 51. Architectural Scale — Initial Temptation

両Representationを比較すると、

- World ModelはWorld / Representation / Understanding / Prediction
- SOARはEnvironment / Perception / Working Memory / Decision / Operator / Action

を持つため、

> **World Model is more abstract; SOAR is more concrete**

と読みたくなる。

しかしBounded Recursive Verificationでは、この単一Scale Interpretationは十分に支持されないと判断された。

---

# 52. Why a Single Abstraction Scale Is Unsafe

単一Abstraction Scaleを採用すると、

```text
World Model
      ↓
More Detailed
      ↓
SOAR
```

という関係を暗黙的に形成する。

すると、

- SOAR Perception
- SOAR Decision
- SOAR Operator
- SOAR Action

をWorld Modelの「より詳細な下位Component」として読むRiskが生じる。

Frozen A/Bはこの関係を支持しない。

---

# 53. Different Architectural Scope

より安全なJudgmentは、

> **Different Architectural Scope**

である。

World Modelは、

> **World → Representation → Understanding → Prediction**

というStable Coreを中心にArchitectureを形成し、その先をOpen Extensionとして保持する。

SOARは、

> **Environment → Perception → Working Memory → Decision → Operator → Action → Environment**

というIntegrated Organizational Cycleを形成する。

両者は何をArchitectureとして確定するかのScopeが異なる。

---

# 54. Different Responsibility Granularity

さらに、

> **Different Responsibility Granularity**

を保持する。

SOARでは、

- Perception
- Working Memory
- Decision
- Operator
- Action

が比較的明示的にResponsibility-separatedされる。

World Modelでは、

- Representation
- Understanding
- Prediction

がStable Coreを形成し、その先のFunctionsをCandidateとして保持する。

この差をDetail Levelの上下だけに還元しない。

---

# 55. Scope versus Granularity

`Scope`と`Granularity`も同一ではない。

Scope：

> **What architectural responsibility is included within the represented object?**

Granularity：

> **How finely are responsibilities differentiated within that scope?**

である。

したがって、

> **Different Scope**

と、

> **Different Granularity**

を分離して保持する。

---

# 56. No Vertical Ranking

本Comparisonから、

```text
World Model
      ↑
Higher Level
      ↓
SOAR
```

または、

```text
SOAR
      ↑
More Complete
      ↓
World Model
```

というVertical Rankingを導かない。

Architectural ScopeとResponsibility Granularityの差は、

> **hierarchical superiority / inferiority**

を意味しない。

---

# 57. No Completion Hierarchy

SOARをWorld ModelのOpen Extensionの「下位階層」として使用しない。

たとえば、

```text
World Model Prediction
        ↓
SOAR Decision
        ↓
SOAR Operator
        ↓
SOAR Action
```

というCombined Hierarchyは支持されない。

これは二つのFrozen ObjectsをCross-Framingして第三のArchitectureを生成することになる。

---

# 58. No Reduction Hierarchy

逆にWorld ModelをSOARのHigh-Level Summaryとして扱わない。

たとえば、

```text
SOAR Working Memory
        ↓
abstracted as Representation

SOAR Decision / Operator
        ↓
abstracted as Understanding

SOAR Action
        ↓
abstracted as Prediction
```

というReductionも支持されない。

Frozen A/BのResponsibility Distributionを失うためである。

---

# 59. No Shared Universal Hierarchy

両者の部分的Correspondenceから、

> **External World → Internal Representation → Cognition → Action**

というUniversal Cognitive Hierarchyを導かない。

SOARではAction Returnが明示されるが、World Model Stable CoreではActionはCandidateである。

したがって、Universal HierarchyをCurrent Evidenceから形成しない。

---

# 60. Vertical Correspondence Region

両者に最も限定的に認められるVertical Correspondenceは、

> **External / Internal distinction**

と、

> **Internal Representational Organizationからsubsequent cognitive responsibilityへのrelation**

である。

概念的には、

```text
External Domain
      ↓
Internal Representation
      ↓
Subsequent Cognitive Organization
```

という抽象的Vertical Formである。

---

# 61. Limits of the Vertical Correspondence

このAbstract Formを具体化すると差異が現れる。

World Model：

```text
World
  ↓
Representation
  ↓
Understanding
  ↓
Prediction
```

SOAR：

```text
Environment
    ↓
Perception
    ↓
Working Memory
    ↓
Decision
    ↓
Operator
    ↓
Action
    ↓
Environment
```

したがって、

> **abstract vertical correspondence weakens as architectural responsibility becomes more specific.**

---

# 62. Hierarchical Localization of Correspondence

Structural / Functional Comparisonと同様に、Hierarchical CorrespondenceもArchitecture全体へ均等に分布しない。

Correspondenceは、

> **External / Internal differentiation**

および、

> **Representational Centrality**

付近に集中する。

その後、

- Layer Responsibility
- Downstream Position
- Boundary
- Closure
- Extension Status

でDivergenceが増大する。

---

# 63. Hierarchical Divergence after Representational Center

Representational Center以降をVertical Projectionすると、

```text
                REPRESENTATIONAL CENTER
                         │
            ┌────────────┴────────────┐
            │                         │
       WORLD MODEL                   SOAR
            │                         │
      Understanding                Decision
            │                         │
       Prediction                  Operator
            │                         │
      Open Boundary                Action
                                      │
                                 Environment
                                      ↺
```

となる。

このDiagramは1:1 Mappingを示さない。

むしろ、

> **the hierarchical / architectural paths diverge after their respective representational centers**

ことを示す。

---

# 64. Hierarchical Correspondence Matrix

| Hierarchical Coordinate | World Model | SOAR | Judgment |
|---|---|---|---|
| External-side organization | World / Conceptual Layer | Environment / External Interaction Layer | Limited Positional Correspondence |
| Internal representation | Representation / Conceptual Layer | Working Memory / Internal Representation Layer | Positional Proximity without Hierarchical Identity |
| Immediate downstream cognitive region | Understanding | Decision | No justified direct mapping |
| Further downstream region | Prediction | Operator | Hierarchical Non-Correspondence |
| Behavioral execution position | Candidate / unresolved | Action explicit | Non-Correspondence |
| Boundary position | Open downstream boundary | Distributed interaction boundary | Different |
| Closure position | Open | Environment return | Strong Non-Correspondence |
| Extension status | Candidate region | Integrated cycle | Different Architectural Organization |
| Layer classification axis | Conceptual / Cognitive / Extension | External / Representation / Cognitive Organization | Different |
| Common abstraction scale | Not established | Not established | Undetermined / Unsupported |

---

# 65. Layer Responsibility Matrix

| Layer Responsibility | World Model | SOAR |
|---|---|---|
| External / reference organization | Conceptual World | External Environment |
| Internal representational organization | Representation within Conceptual Layer | Working Memory within Internal Representation Layer |
| Cognitive organization | Understanding / Prediction | Decision / Operator |
| Behavioral execution | Candidate / unresolved | Action explicit |
| Environmental return | Not established in Stable Core | Explicit |
| Architectural extension | Explicitly open / candidate | No direct counterpart |
| Cycle closure | No | Yes, organizationally represented |

このMatrixはCommon Layer Hierarchyを形成するものではない。

それぞれのArchitectureがどのResponsibilityをどこに配置しているかを比較するためのObservation Surfaceである。

---

# 66. Surface Layer Correspondence

以下のようなSurface Correspondenceは認められる。

- both distinguish multiple architectural regions
- both separate representational responsibility from at least some downstream cognitive responsibility
- both allow vertical reading
- both organize heterogeneous responsibilities rather than one undifferentiated block

しかし、これらは、

> **same hierarchy**

を支持しない。

---

# 67. Material Hierarchical Non-Correspondence

Material Non-Correspondenceは以下に存在する。

1. Layer classification axis
2. Representation layer position
3. downstream responsibility distribution
4. candidate versus integrated downstream organization
5. boundary placement
6. closure placement
7. cyclic return
8. observation-status organization
9. architectural scope
10. responsibility granularity

したがってGlobal Hierarchical Isomorphismは支持されない。

---

# 68. Layer Correspondence versus Functional Correspondence

RepresentationとWorking Memoryには強いFunctional Correspondenceが存在する。

しかしLayer Correspondenceは弱い。

これは重要である。

```text
Strong Functional Correspondence
        ≠
Same Layer Position
```

したがって、Functional ComparisonとHierarchical Comparisonは独立Dimensionとして保持する必要がある。

---

# 69. Layer Correspondence versus Structural Correspondence

同様にPartial Structural Correspondenceが存在しても、

> **same layer membership**

は導かれない。

Structural CentralityとLayer Positionは異なるCoordinatesである。

RepresentationとWorking MemoryがともにTopological Centerであっても、それぞれが属するLayer Responsibilityは異なる。

---

# 70. Cross-Level Correspondence versus Cross-Level Identity

双方にCross-Level Relationが存在する。

しかし、

World Model：

> Conceptual → Cognitive → Open Extension

SOAR：

> External Interaction → Internal Representation → Cognitive Organization → External Interaction

である。

したがって、

> **Cross-Level Correspondence exists only at a highly abstract organizational level.**

具体的Cross-Level Architectureは異なる。

---

# 71. Hierarchical Invariants

本Artifactでは以下を保持する。

> **Layer ≠ Module**

---

> **Layer ≠ Concept**

---

> **Hierarchy ≠ Dependency**

---

> **Hierarchy ≠ Sequence**

---

> **Hierarchy ≠ Execution Flow**

---

> **Topology ≠ Hierarchy**

---

> **Layer Count ≠ Hierarchical Correspondence**

---

> **Vertical Readability ≠ Shared Hierarchy**

---

> **Same Layer Label ≠ Same Layer Responsibility**

---

> **Same Vertical Position ≠ Same Functional Responsibility**

---

> **Centrality ≠ Hierarchical Identity**

---

> **Different Scope ≠ Higher / Lower Abstraction Rank**

---

> **Different Granularity ≠ Higher / Lower Capability**

---

> **Open Vertical Boundary ≠ Incomplete Hierarchy**

---

> **Cyclic Return ≠ Complete Hierarchy**

---

# 72. Strongly Supported Hierarchical Findings

Frozen A/BおよびVerification後に強く保持されるHierarchical Findingsは以下である。

1. 両RepresentationはLayered / regionally differentiated organizationを持つ。
2. Layer Classification Axisは異なる。
3. RepresentationとWorking MemoryはCentralityを共有するが、same layer positionではない。
4. Representational Center以降のVertical Responsibilityは分岐する。
5. World ModelはStable CoreからOpen Extensionへ向かう。
6. SOARはVertical DifferentiationをCyclic Returnへ組み込む。
7. Global Hierarchical / Topological Organizationは同型ではない。
8. 両者を一つのAbstraction Scaleへ安全に配置できない。
9. Different Architectural Scope and Responsibility Granularityとして扱うべきである。

---

# 73. Partially Supported Hierarchical Findings

以下は限定的に支持される。

1. External / Internal differentiation
2. Internal Representationからsubsequent cognitive organizationへのvertical relation
3. Multiple responsibility regionsの存在
4. Representational Centrality周辺のpositional proximity

しかしこれらは、

> **Global Hierarchical Correspondence**

を支持しない。

---

# 74. Hierarchical Non-Correspondences

主要Non-Correspondenceは、

- Conceptual Layer ↔ External Interaction Layer
- Representation Layer Position ↔ Working Memory Layer Position
- Understanding ↔ Decision
- Prediction ↔ Operator
- Prediction ↔ Action
- Candidate Action ↔ Explicit Action
- Open Extension ↔ Closed Cycle
- downstream boundary ↔ distributed interaction boundary
- Stable / Candidate organization ↔ Integrated cycle organization

である。

---

# 75. Undetermined Hierarchical Relations

Frozen A/Bだけでは以下を確定できない。

## 75.1 Common Abstraction Level

World ModelとSOARを同一Abstraction Scale上で正確に位置づけられるか。

**Status:** Unsupported / Undetermined

---

## 75.2 Universal Cognitive Hierarchy

両者が共通するUniversal Cognitive Hierarchyを表しているか。

**Status:** Insufficient Evidence

---

## 75.3 Complete Cross-Level Mapping

各Layerを1:1で対応させられるか。

**Status:** Not Supported

---

## 75.4 Shared Control Hierarchy

両者が同一Control Hierarchyを持つか。

**Status:** Insufficient Evidence

---

# 76. Evidence Boundary

本Artifactから以下を主張しない。

- World Model and SOAR have the same hierarchy
- both have equivalent three-layer architectures
- World Model Conceptual Layer equals SOAR External Interaction Layer
- World Model Representation Layer position equals SOAR Working Memory Layer position
- Understanding equals Decision
- Prediction equals Operator
- Prediction equals Action
- World Model Action equals SOAR Action
- SOAR is a lower-level implementation of World Model
- World Model is a higher-level abstraction of SOAR
- SOAR fills World Model's lower hierarchy
- World Model summarizes SOAR's hierarchy
- both instantiate a universal cognitive hierarchy
- SOAR's cycle proves a feedback hierarchy
- World Model's open boundary proves hierarchical incompleteness
- SOAR's closure proves hierarchical completeness

---

# 77. No Layer Completion across Models

World ModelのArchitectural Extension LayerがOpenであることを理由として、SOARのDecision / Operator / Actionをその内部へ配置しない。

以下は支持されない。

```text
WORLD MODEL

Conceptual
    ↓
Cognitive
    ↓
Prediction
    ↓
SOAR Decision
    ↓
SOAR Operator
    ↓
SOAR Action
```

これはComparative ObservationではなくCross-Model Architecture Constructionである。

---

# 78. No Hierarchical Reduction

逆方向にも、

```text
SOAR
Environment
    ↓
Working Memory
    ↓
Decision / Operator
    ↓
Action

        reduced to

WORLD MODEL
World
    ↓
Representation
    ↓
Understanding
    ↓
Prediction
```

とは扱わない。

このReductionはResponsibility Differencesを消去する。

---

# 79. No Missing-Layer Interpretation

一方に明示Layerがあり他方に直接Counterpartがない場合、

> **missing layer**

とは判断しない。

たとえばSOARのExternal Interaction Layerに対するWorld Model側の完全Counterpartがないとしても、

> World Model lacks an interaction layer

というTheory-level Claimへ進まない。

Frozen Representation上で同種のLayer Responsibilityが確立されていないというObservationに限定する。

---

# 80. No Higher/Lower Intelligence Interpretation

Layer Count、Hierarchy Depth、Cyclic Closure等から、

- more intelligent
- more advanced
- more autonomous
- more complete

というJudgmentを導かない。

Hierarchical ProjectionはCapability Evaluationではない。

---

# 81. Unexpected Hierarchical Observation

Comparisonを通じて重要だったObservationは、

> **Layered Organizationそのものは両者に存在するが、Layerの責任軸が異なるため、表面的なLayer Correspondenceが最も誤読を生みやすい**

ことである。

「両方とも3層程度に整理できる」というObservationは、それ自体では弱い。

重要なのは、

> **何を分離するためのLayerなのか**

である。

---

# 82. Second Unexpected Observation

もう一つ重要なのは、

> **Representational CentralityのCorrespondenceはHierarchical IdentityよりもFunctional Correspondenceとして強い**

ことである。

RepresentationとWorking MemoryはArchitecture内部で中心的である。

しかしそのLayer Positionは異なる。

したがって、

```text
Functional Centrality Correspondence
            >
Hierarchical Position Correspondence
```

という非対称性が存在する。

これは数量的大小を意味せず、Evidence Strengthの方向を示す。

---

# 83. Third Unexpected Observation

SOARではLayered Differentiationが存在するにもかかわらず、Global ArchitectureはHierarchyとして閉じず、CycleとしてEnvironmentへ戻る。

したがって、

> **Layered Architecture can be cyclic without being a simple hierarchy.**

これは、

> **Layer ≠ Topology**

を明確に示す。

---

# 84. Fourth Unexpected Observation

World ModelではVertical Layer Organizationが存在するが、その下流はOpen Architectural Boundaryへ向かう。

したがって、

> **Layered Architecture can remain architecturally open.**

このことから、

> **Layered ≠ Closed**

であることも確認される。

---

# 85. Hierarchical Comparison and Global Topology

両者を最も圧縮して比較すると、

```text
WORLD MODEL

Conceptual Responsibility
        ↓
Cognitive Responsibility
        ↓
Stable-Core Boundary
        ↓
Open Architectural Extension
```

に対して、

```text
SOAR

External Interaction
        ↓
Internal Representation
        ↓
Cognitive Organization
        ↓
Behavioral Execution
        ↓
External Interaction
        ↺
```

となる。

ここにGlobal Hierarchical / Architectural Divergenceが最も明確に現れる。

---

# 86. Architectural Position Map

```text
WORLD MODEL                           SOAR

World                               Environment
│                                   │
├─ Conceptual Layer                 ├─ External Interaction
│                                   │
Representation                      Perception
│                                   │
├─ Conceptual Layer                 Working Memory
│                                   │
│                                   ├─ Internal Representation
│                                   │
Understanding                       Decision
│                                   │
├─ Cognitive Function              ├─ Cognitive Organization
│                                   │
Prediction                          Operator
│                                   │
├─ Cognitive Function              ├─ Cognitive Organization
│                                   │
Open Architectural Boundary        Action
│                                   │
Candidate Extension                ├─ External Interaction
                                    │
                                    Environment
                                    ↺
```

このMapは横方向の1:1 Correspondenceを示さない。

各UnitのArchitectural Positionを並置し、Position Responsibilityの差を観察するためのProjectionである。

---

# 87. Responsibility Distribution Map

より抽象化すると、

```text
WORLD MODEL

[Conceptual Responsibility]
          │
          ▼
[Cognitive Responsibility]
          │
          ▼
[Open Extension Responsibility]
```

に対して、

```text
SOAR

[External Interaction Responsibility]
          │
          ▼
[Internal Representation Responsibility]
          │
          ▼
[Cognitive Organization Responsibility]
          │
          ▼
[External Interaction Responsibility]
          ↺
```

となる。

この差は単なるLayer Count Differenceではない。

> **Responsibility Distribution Architecture**

そのものが異なる。

---

# 88. Restabilized Hierarchical Judgment

本Artifactで保持されるRestabilized Hierarchical Judgmentは次の通りである。

> **World ModelとSOARはともに複数のArchitectural Region / Layerを区別し、Internal Representational Organizationを後続Cognitive Responsibilityと区別するという限定されたVertical Correspondenceを持つ。Representational Centrality周辺にはPositional Proximityも存在する。**
>
> **しかし、両者のLayer Classification Axisは異なる。World ModelはConceptual Layer、Cognitive Function Layer、Architectural ExtensionというOrganizationを持ち、Stable CoreからOpen Architectural Boundaryへ向かう。一方、SOARはExternal Interaction、Internal Representation、Cognitive Organizationを区別し、それらをBehavioral ExecutionからEnvironmentへのReturnを含むClosed Organizational Cycleへ組み込む。**
>
> **したがって、Representation ↔ Working MemoryのFunctional Centrality Correspondenceはsame hierarchical positionを意味せず、Understanding ↔ Decision、Prediction ↔ Operator、Prediction ↔ Action、World Model Action ↔ SOAR Actionというdirect hierarchical mappingも支持されない。**
>
> **また、両者を単一のAbstract-to-Concrete Scaleへ配置することも支持されない。より適切なのは、Different Architectural Scope and Responsibility Granularityとして保持することである。**
>
> **この比較が支持するのはGlobal Hierarchical Isomorphismではなく、Representational Centrality周辺の限定されたVertical / Positional Correspondenceと、Layer Responsibility、Boundary、Closure、Architectural ScopeにおけるGlobal Hierarchical Divergenceの併存である。**

最も圧縮したFormは、

> **Limited Vertical Correspondence around Representational Centrality × Global Divergence in Layer Responsibility, Boundary, and Closure**

である。

---

# 89. Relationship to Structural Correspondence

`02-structural-correspondence.md`は、

> **Structural Units / Relations / Dependency / Topology / Boundary / Closure**

をPrimary Comparison Surfaceとする。

本Artifactはそのうち、

> **Layer / Vertical Responsibility / Architectural Position**

を独立してProjectionする。

したがって02のTopology Judgmentを単純に再記述するものではない。

---

# 90. Relationship to Functional Correspondence

`03-functional-correspondence.md`では、

> **what each structure does**

を比較した。

本Artifactでは、

> **where those responsibilities are architecturally organized**

を比較する。

したがって、

```text
Function
    ≠
Hierarchical Position
```

である。

Representation ↔ Working Memoryがその代表例である。

---

# 91. Relationship to Observation Notes

Initial Comparisonでの、

- Layer similarity
- Architectural Scale
- Cross-level interpretation

等がVerificationによってどのようにQUALIFY / RECLASSIFYされたかという履歴は、

> `05-observation-notes.md`

の責任である。

本ArtifactではRestabilizedされたHierarchical Judgmentを保持する。

---

# 92. Relationship to Comparative Summary

本Artifactの主要Hierarchical Findingsは、

> `06-comparative-summary.md`

でCase-level Judgmentへ圧縮される。

06は本Artifactの詳細なLayer / Position Analysisを置き換えない。

---

# 93. Final Hierarchical Orientation

本Comparisonで重要なのは、

> **両Architectureに何層あるか**

ではない。

重要なのは、

> **各Layerが何を分離し、どのResponsibilityを担い、Architecture全体のどこに位置するか**

である。

この問いに対してWorld ModelとSOARは異なる答えを持つ。

World Modelは、

```text
Conceptual
    ↓
Cognitive
    ↓
Open Extension
```

というResponsibility Organizationを持つ。

SOARは、

```text
External Interaction
    ↓
Internal Representation
    ↓
Cognitive Organization
    ↓
External Interaction
    ↺
```

というResponsibility Organizationを持つ。

したがって両者のLayered Characterは比較可能であるが、

> **same hierarchy**

とは判断できない。

---

# 94. Artifact Boundary

本Artifactの責任は、

> **Layer / Hierarchy / Vertical Responsibility / Cross-Level Relation / Architectural Position / Scope / Responsibility Granularityの保持**

である。

本Artifactでは、

- New Comparative Analysisを追加しない
- Frozen A/Bを修正しない
- LayerをModuleへCollapseしない
- HierarchyをDependencyへCollapseしない
- Vertical DirectionをExecution Flowへ変換しない
- Layer CountからCorrespondenceを導かない
- Architectural ScopeをCapability Rankingへ変換しない
- SOARをWorld Modelのlower-level completionとして扱わない
- World ModelをSOARのhigher-level abstractionとして扱わない
- Legacy Case 004を参照しない

というBoundaryを維持する。

---

# Status

**Artifact:** `04-hierarchical-projection.md`  
**Case:** Case 004 — World Model × SOAR  
**Projection Source:** Restabilized Comparative Judgment  
**Artifact Responsibility:** Hierarchical / Layer / Architectural Position Comparison  
**Layer Responsibility:** Preserved  
**Vertical Responsibility:** Preserved  
**Cross-Level Relation:** Preserved  
**Architectural Position:** Preserved  
**Different Architectural Scope:** Preserved  
**Different Responsibility Granularity:** Preserved  
**Hierarchical Non-Correspondence:** Preserved  
**Capability Boundary:** Preserved  
**Evidence Boundary:** Preserved  
**Frozen A/B Revision:** None  
**New Comparative Analysis:** None Added  
**Old Case 004:** Withheld  
**Repository Projection Status:** Artifact 04 Complete  
**Next Artifact:** Not Started
