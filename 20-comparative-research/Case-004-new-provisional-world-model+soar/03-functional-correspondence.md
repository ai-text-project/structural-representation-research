# Functional Correspondence

**Case:** Case 004 — World Model × SOAR  
**Artifact:** `03-functional-correspondence.md`  
**Comparison Objects:** Frozen Projection A — World Model × Frozen Projection B — SOAR  
**Projection Source:** Restabilized Comparative Judgment  
**Status:** Restabilized Functional Comparison  
**Language:** Japanese Human Observation Interface

---

# 1. Purpose

本Artifactの目的は、World ModelとSOARについて独立形成・Freezeされた二つのStructural Projectionの間に観察された、

- Functional Correspondence
- Partial Functional Correspondence
- Functional Correspondence without Structural Identity
- Different Functional Responsibility
- Functional Non-Correspondence
- Different Transformation Responsibility
- Different Boundary Function
- Different Closure Responsibility
- Undetermined Functional Relation

を、Functional Responsibilityを中心として外在化することである。

本Artifactは、

> **同じように見えるComponentを対応づけること**

を目的としない。

また、

> **Structural CorrespondenceをFunctional Correspondenceへ自動変換すること**

も目的としない。

比較の中心は、

```text
Function / Responsibility in Frozen A
                ↕
Function / Responsibility in Frozen B
```

である。

したがって本Artifactでは、

> **What does this structural element do within its own represented architecture?**

を先に保持し、その後にFunctional Relationを比較する。

---

# 2. Artifact Responsibility

`03-functional-correspondence.md`のPrimary Responsibilityは、

> **Functional Responsibility Comparison**

である。

したがって本Artifactでは、

- Unitが何を担うか
- どのResponsibilityを後続Unitへ接続するか
- どのFunctional Relationが比較可能か
- どのFunctional Relationが比較不可能か
- Similar FunctionがStructural Identityを意味するか
- Different FunctionがどのArchitecture Differenceに由来するか
- Functional RelationがどこまでEvidenceによって支持されるか

を観察する。

一方、

- Global Topologyそのもの
- Detailed Structural Dependency Architecture
- Layer / Hierarchyの詳細
- Verification Change History
- Repository Formation History

は本ArtifactのPrimary Responsibilityではない。

それらは、

- `02-structural-correspondence.md`
- `04-hierarchical-projection.md`
- `05-observation-notes.md`

へResponsibility-separatedされる。

---

# 3. Governing Functional Principle

本Artifactでは、

> **Function-before-Mapping**

を保持する。

比較順序は、

```text
Function in A
      ↓
Responsibility in A
      ↓
Function in B
      ↓
Responsibility in B
      ↓
Direct Functional Relation
      ↓
Functional Judgment
```

である。

以下の順序は採用しない。

```text
Similar Label
      ↓
Similar Position
      ↓
Possible Functional Match
      ↓
Assumed Correspondence
```

したがって、

> **Vocabulary Similarity ≠ Functional Correspondence**

である。

---

# 4. Functional Correspondence Is Not Functional Identity

本ArtifactにおけるFunctional Correspondenceは、

> **二つのStructural Objects内部で、比較可能なFunctional ResponsibilityまたはFunctional Relationが存在すること**

を意味する。

これは、

> **同一Function**

を意味しない。

たとえば二つのUnitがともに後続Organizationを可能にしていても、

- Input responsibility
- Output responsibility
- Dependency responsibility
- Transformation responsibility
- Boundary responsibility
- Closure responsibility

が異なる場合がある。

したがって、

> **Functional Correspondence ≠ Functional Identity**

を保持する。

---

# 5. Functional Correspondence Is Not Structural Identity

さらに重要なのは、

> **Functional Correspondence ≠ Structural Identity**

である。

二つのUnitが類似したFunctional Responsibilityを持っていても、

- Structural Status
- Layer
- Module Status
- Dependency Position
- Topological Position
- Boundary Relation
- Architectural Scope

が異なる可能性がある。

本Caseで最も重要な例は、

> **Representation ↔ Working Memory**

である。

両者には意味のあるFunctional Correspondenceが存在する。

しかし、それによって両者を同一Structural Unitとして扱うことはできない。

---

# 6. Overall Functional Pattern

Restabilized Comparisonによって支持されるFunctional Patternは、

> **Representational Organizationを中心とする限定されたFunctional Correspondence**

と、

> **その後続ResponsibilityにおけるFunctional Divergence**

の併存である。

圧縮すると、

```text
External Domain
      ↓
Representational Organization
      ↓
Subsequent Cognitive Responsibility
      ↓
Functional Divergence
```

となる。

ただし、この図は同一Functional Pipelineを意味しない。

World ModelとSOARではRepresentational Center以降に形成されるFunctional Responsibilityが異なる。

したがって、

> **Local Functional Correspondence does not establish Global Functional Equivalence.**

---

# 7. World Model Functional Organization

Frozen Projection AにおいてStable Coreの主要Functional Organizationは、

```text
World
  ↓
Representation
  ↓
Understanding
  ↓
Prediction
```

として現れる。

ただし、このArrowは単一種類のFunctionを表すものではない。

World Modelでは概ね、

```text
External / Environmental World
        ↓
Internal Representation
        ↓
Semantic Understanding
        ↓
Possible Future States
```

というFunctional Transformationが支持される。

ここでの主要Responsibilitiesは、

- Representation — Worldを内部的に表現可能にする
- Understanding — Representationに基づくSemantic / Cognitive Organization
- Prediction — Possible Future StatesへのProjection

である。

---

# 8. SOAR Functional Organization

Frozen Projection Bにおいて主要Functional Organizationは、

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

として現れる。

よりFunctionalに圧縮すると、

```text
Environmental Interaction
        ↓
Internal Representational State
        ↓
Cognitive Organization
        ↓
Executable / Organized Behavior
        ↓
Environmental Re-engagement
```

となる。

主要Responsibilitiesは、

- Perception — EnvironmentとInternal Representationのmediating interface
- Working Memory — Internal Representational Workspace
- Decision — Behavioral Transitionのorganization
- Operator — Selected Cognitive Operationのorganization / mediation
- Action — Executable Behavior / Environmentへのexternal interface

である。

---

# 9. First Functional Correspondence Region

両者で最初に比較可能なFunctional Regionは、

> **External DomainとInternal Representational Organizationの関係**

である。

World Modelでは、

```text
World
  ↓
Representation
```

が存在する。

SOARでは、

```text
Environment
    ↓
Perception
    ↓
Working Memory
```

が存在する。

双方とも、

> **External DomainとInternal Representational OrganizationをFunctionalに区別する**

という限定されたCorrespondenceを持つ。

しかしExternal-to-Internal mediationは同一ではない。

---

# 10. External Reference Function

World Modelの`World`とSOARの`Environment`は、External Reference Functionという限定されたCoordinateで比較可能である。

World ModelのWorldは、

> **Representationが参照するExternal / Conceptual Domain**

として機能する。

SOARのEnvironmentは、

> **Perceptionのsource contextであり、Actionのreturn destinationでもあるExternal Interaction Domain**

として機能する。

したがって、External ReferenceというFunctional LevelではCorrespondenceが存在する。

しかしSOAR EnvironmentにはWorld Model Worldに確立されていないAdditional Responsibilityがある。

---

## Judgment

**Limited Functional Correspondence**

+

**Different Functional Responsibility**

---

# 11. Perceptual Mediation

SOARには、

> **Perception**

という明示的Functional Responsibilityが存在する。

Perceptionは、

```text
Environment
    ↓
Perception
    ↓
Working Memory
```

においてExternal-to-Internal mediationを担う。

World Model Stable Coreでは、

```text
World
  ↓
Representation
```

の間に同種の明示的Perceptual Functionは確立されていない。

したがって、

> **Perceptionに対するdirect functional counterpartはFrozen World Model Stable Coreでは支持されない。**

これはWorld ModelにPerception Capabilityが存在しないことを意味しない。

単にFrozen Projection Aに同じFunctional Responsibilityが独立Unitとして確立されていないことを意味する。

---

## Judgment

**Functional Non-Correspondence at explicit perceptual-mediation level**

---

# 12. Representation Function

World Modelの`Representation`は、Architecture内部で極めて高いFunctional Densityを持つ。

Representationは、

- Worldに対するInternal Representational Organization
- UnderstandingのFunctional Foundation
- PredictionのDependency Foundation
- Stable CoreのConceptual Anchor
- downstream cognitive organizationのenabling condition

として機能する。

したがってRepresentationは単なる「内部状態」ではない。

Frozen Aでは、

> **subsequent cognitive responsibilitiesを成立させるFunctional Foundation**

として位置づけられる。

---

# 13. Working Memory Function

SOARの`Working Memory`は、

- Perceptionを介して形成されるInternal Representational State
- Primary Representational Workspace
- DecisionのFunctional Condition
- Cognitive Organizationのcentral internal state
- downstream Operator / Action organizationを可能にするDependency Hub

として機能する。

Working MemoryはEnvironment-coupled Cycle内部のExplicit Moduleであり、

> **represented stateを保持し、Decision Organizationを可能にするFunctional Center**

である。

---

# 14. Representation ↔ Working Memory

RepresentationとWorking Memoryの間には、本Caseで最も意味のあるFunctional Correspondenceが存在する。

双方とも、

> **Internal Representational Organizationを提供する**

かつ、

> **後続Cognitive Responsibilityを可能にする**

というFunctionを持つ。

比較可能なFunctional Relationは、

```text
Internal Representational Organization
              ↓
Enables Subsequent Cognitive Responsibility
```

である。

このRelationはFrozen A/B双方によって支持される。

---

# 15. Why Representation and Working Memory Are Not Identical

Functional Correspondenceが強くても、両者はStructural / Functional Identityではない。

World Model Representationは、

- Conceptual Anchor
- Representation Module
- Dependency Origin
- Topological Center
- Understanding / Prediction foundation

という複数Surfaceを横断する。

SOAR Working Memoryは、

- Explicit Module
- Internal Workspace
- Perception-dependent state
- Decision dependency hub
- Cyclic Architecture内部のrepresentational center

である。

したがって、

> **same broad representational responsibility**

は存在するが、

> **same total functional responsibility**

は存在しない。

---

## Judgment

**Strong Functional Correspondence without Structural Identity**

---

# 16. Representational Enabling Function

今回の比較で最も安定して支持されるFunctional Relationは、

> **Representational Organization enables subsequent cognitive responsibility**

である。

World Modelでは、

```text
Representation
      ↓
Understanding
```

および、

```text
Representation + Understanding
              ↓
Prediction
```

が成立する。

SOARでは、

```text
Working Memory
      ↓
Decision
      ↓
Operator
      ↓
Action
```

というOrganizational Dependencyが存在する。

したがって、両者ともRepresentational CenterがFunctional Terminalではない。

---

## Judgment

**Strongly Supported Functional Correspondence**

ただしCorrespondenceは、

> **subsequent organizationを可能にするというabstract functional relation**

に限定される。

---

# 17. Immediate Downstream Responsibility

Representational Centerの直後に現れるResponsibilitiesは異なる。

World Model：

```text
Representation
      ↓
Understanding
```

SOAR：

```text
Working Memory
      ↓
Decision
```

両者は「Representational Centerの後続」に位置する。

しかし、

> **Understanding = Decision**

というFunctional Identityは支持されない。

World Model UnderstandingはSemantic / Cognitive Understandingを担う。

SOAR DecisionはBehavioral Transitionのorganizationを担う。

したがって、

> **same downstream position ≠ same downstream function**

である。

---

# 18. Understanding Function

World Modelの`Understanding`は、

> **Representationに基づいてWorldをmeaningfully / semantically organizeするCognitive Responsibility**

として位置づけられる。

UnderstandingはRepresentationに依存し、Predictionを成立させるための必要なFunctional Mediationを形成する。

したがって、

```text
Representation
      ↓
Understanding
      ↓
Prediction
```

においてUnderstandingは単なる中間位置ではない。

> **RepresentationとPredictionをFunctionalに媒介するdistinct cognitive responsibility**

を持つ。

---

# 19. Decision Function

SOARの`Decision`は、

> **Working Memoryに保持されたrepresentational stateに基づき、behavioral transitionをorganizeするResponsibility**

を持つ。

DecisionはWorking Memoryに依存し、Operator Organizationへ接続する。

したがって、

```text
Working Memory
      ↓
Decision
      ↓
Operator
```

においてDecisionは、

> **behavior-oriented organizational responsibility**

を持つ。

---

# 20. Understanding ↔ Decision

UnderstandingとDecisionには、

> **representational centerのimmediate downstream responsibility**

というPositional Relationがある。

しかしFunctional Responsibilityは異なる。

World Model Understanding：

> Semantic / Cognitive Mediation

SOAR Decision：

> Behavioral Transition Organization

したがって、

```text
Understanding
      ↕
Decision
```

についてdirect functional mappingを確立しない。

---

## Judgment

**Functional Non-Correspondence / No justified direct mapping**

---

# 21. Prediction Function

World Modelの`Prediction`は、

> **RepresentationとUnderstandingに基づきPossible Future StatesへProjectionするResponsibility**

を担う。

PredictionはStable Coreのdownstream boundary-facing positionにある。

重要なのは、PredictionがWorld Model Architecture全体のfinal endpointであるとは確定されていないことである。

Predictionは、

> **Stable Coreのdownstream functional position**

であり、その先にはOpen Architectural Boundaryが存在する。

---

# 22. Operator Function

SOARの`Operator`は、

> **Decisionによって組織された選択をExecutable Behaviorへ接続するCognitive / Organizational Responsibility**

を担う。

OperatorはDecisionに依存し、Actionへ接続する。

したがってOperatorはFuture-State Projectionを担うUnitとしてではなく、

> **selected cognitive operationをbehavioral executionへ向けてorganizeするUnit**

として位置づけられる。

---

# 23. Action Function

SOARの`Action`は、

> **Operator-dependent Behavioral Execution / External Interaction Responsibility**

を持つ。

ActionはInternal Cognitive OrganizationをExternal Environmentへ再接続する。

したがって、

```text
Operator
    ↓
Action
    ↓
Environment
```

はSOARのFunctional Closureに関係する。

Actionは単なるdownstream outputではなく、

> **Environmentへのre-engagementを成立させるFunctional Interface**

である。

---

# 24. Prediction ↔ Operator

PredictionとOperatorは、それぞれRepresentational Centerより後方に位置する。

しかしFunctionは異なる。

Prediction：

> Possible Future StatesへのProjection

Operator：

> Selected Cognitive OrganizationをExecutable Behaviorへ媒介

したがって、

> **Prediction ↔ Operator**

というFunctional Correspondenceは支持されない。

---

## Judgment

**Functional Non-Correspondence**

---

# 25. Prediction ↔ Action

PredictionとActionについてもdirect mappingは支持されない。

PredictionはPossible Future Statesを形成する。

ActionはEnvironmentへのBehavioral Execution / Re-engagementを担う。

したがって、

```text
Prediction
    ≠
Action Preparation
```

であり、

```text
Action
    ≠
Executed Prediction
```

である。

Frozen A/BはこのようなTransformationを支持しない。

---

## Judgment

**Functional Non-Correspondence**

+

**Different Functional Responsibility**

---

# 26. World Model Candidate Action

World Modelにも`Action`というCandidate Functionが存在する。

しかしFrozen AにおいてActionは、

- Candidate Extension
- Placement unresolved
- Dependency unresolved
- Module independence unresolved
- Stable Coreとのinside / outside relation unresolved

である。

したがって、World Model ActionのFunctional ResponsibilityをSOAR Actionと同程度のGranularityで確定できない。

---

# 27. SOAR Action versus World Model Action

SOAR Actionは、

- Explicit Module
- Operator-dependent
- Behavioral Execution
- External Interaction
- Environment Reconnection
- Cycle Closure participation

という明示的Responsibilityを持つ。

World Model ActionはCandidate Extensionである。

したがって、

> **Action ↔ Action**

という同一Vocabularyにもかかわらず、Functional Correspondenceを確立できない。

---

## Judgment

**Vocabulary Correspondence without justified Functional Correspondence**

---

# 28. Functional Transformation — World Model

World Modelでは、

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

```text
External / Environmental Condition
        ↓
Internal Representational Organization
        ↓
Semantic / Cognitive Understanding
        ↓
Possible Future-State Projection
```

というFunctional Transformationを形成する。

このTransformationは、

> **future-oriented cognitive projection**

へ向かう。

ただしExecution、Planning、Actionまでのcomplete functional cycleはFrozen Stable Coreでは確定されない。

---

# 29. Functional Transformation — SOAR

SOARでは、

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

が、

```text
Environmental Interaction
        ↓
Perceptual Mediation
        ↓
Internal Representational Organization
        ↓
Decision Organization
        ↓
Operator Organization
        ↓
Behavioral Execution
        ↓
Environmental Re-engagement
```

というFunctional Transformationを形成する。

このTransformationは、

> **behaviorally returning organization**

へ向かう。

---

# 30. Transformation Correspondence

両者には、

> **Internal Representational Organizationからsubsequent cognitive organizationへ進む**

という限定されたFunctional Correspondenceが存在する。

しかしその後のFunctional Productは異なる。

World Model：

```text
Representation
      ↓
Understanding
      ↓
Prediction
      ↓
Possible Future States
```

SOAR：

```text
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

> **Transformation exists in both**

というだけでは同一Functional Architectureを意味しない。

---

## Judgment

**Partial Functional Correspondence**

+

**Different Transformation Responsibility**

---

# 31. Future Orientation

World Model PredictionはFuture-State Projectionを明示的に担う。

この意味でWorld Model Stable Coreは、

> **future-oriented cognitive transformation**

を持つ。

SOAR Frozen Projectionでは、Decision / Operator / ActionによってBehavioral Organizationが形成される。

しかし、このOrganizationをWorld Model Predictionと同種のFuture-State Projectionとして分類するEvidenceはない。

したがって、

> **future orientationをSOAR側へ投影しない。**

---

# 32. Behavioral Orientation

SOARのDecision → Operator → Actionは、

> **behavior-oriented functional organization**

を形成する。

World Model Stable CoreではPredictionまでが確立され、その先のDecision-Making / Action等はCandidate Extensionとして保持される。

したがってWorld Model Stable Coreを、

> **behavioral execution architecture**

として分類しない。

---

# 33. Functional Divergence after Representational Center

Representational Centerまでは意味のあるFunctional Correspondenceが存在する。

しかしその後、

```text
                 Representational Center
                         │
             ┌───────────┴───────────┐
             │                       │
        WORLD MODEL                 SOAR
             │                       │
       Understanding              Decision
             │                       │
        Prediction                Operator
             │                       │
    Possible Future States         Action
                                     │
                                Environment
```

へ分岐する。

このDiagramは1:1 Mappingを示さない。

むしろ、

> **functional divergence begins after the respective representational centers**

ことを示す。

---

# 34. Downstream Responsibility Difference

World Modelのdownstream responsibilityは、

> **Understanding → Prediction**

を通じてPossible Future Statesへ向かう。

SOARのdownstream responsibilityは、

> **Decision → Operator → Action**

を通じてExecutable Behavior / Environmental Re-engagementへ向かう。

したがって、

> **両者はRepresentationの後に何らかのCognitive Organizationを持つ**

というAbstract Correspondenceは存在する。

しかし、

> **そのCognitive Organizationが何を達成するために配置されているか**

は異なる。

---

## Judgment

**Local Functional Correspondence**

+

**Material Downstream Functional Divergence**

---

# 35. Enabling versus Completing Function

World Model RepresentationはUnderstanding / Predictionをenableする。

SOAR Working MemoryはDecision / Operator / Action organizationをenableする。

しかし、

> **enableすること**

と、

> **same processをcompleteすること**

は異なる。

したがってRepresentational Centerを共通のFunctional Start Pointとみなして、後続Architectureを同一Processの異なるCompletionとして扱わない。

---

# 36. Boundary Function — World Model

World ModelのOpen Architectural Boundaryは、通常のModule Functionとは異なる。

そのFunctional Responsibilityは、

> **unresolved extensionをunresolvedのまま保持すること**

にある。

Search / Planning / Decision-Making / Action等のCandidate Functionsを、Stable Coreへ強制統合しない。

したがってOpen Boundaryは、

> **epistemic / architectural restraintを構造的に保持するResponsibility**

を持つ。

---

# 37. Boundary Function — SOAR

SOARではExternal / Internal BoundaryがPerceptionとActionによってFunctionalにmediatedされる。

Perception：

> Environment → Internal Representation

Action：

> Internal Organization → Environment

したがってBoundaryは、

> **Environmental CouplingをFunctionalに成立させる**

責任を持つ。

---

# 38. Boundary Functional Comparison

World Model Boundary：

> unresolved architectural extensionを保持

SOAR Boundary：

> external / internal interactionをmediate

である。

双方にBoundary Functionは存在するが、Functional Responsibilityは異なる。

したがって、

> **Boundary correspondence at abstract category level does not establish same boundary function.**

---

## Judgment

**Different Functional Responsibility**

---

# 39. Closure Function — World Model

World Model Stable CoreはPredictionまでFunctional Organizationを形成する。

しかしPredictionの先をOpen Architectural Boundaryとして保持する。

したがってStable CoreのFunctionは、

> **Predictionまでのcognitive organizationを安定化する**

ことであり、

> **Environmentへ戻るcomplete behavioral cycleを閉じる**

ことではない。

---

# 40. Closure Function — SOAR

SOARではActionがEnvironmentへ再接続することでOrganizational Cycleが閉じる。

Functionalには、

```text
Environment
    ↓
Internal Organization
    ↓
Behavioral Organization
    ↓
Environment
```

というReturnが成立する。

したがってSOAR Closureは、

> **Environmental Re-engagementによるorganizational continuity**

を担う。

---

# 41. Closure Functional Comparison

World Model：

> Stable cognitive core ending at a boundary-facing Prediction position

SOAR：

> Behaviorally returning environment-coupled organization

である。

したがって、

> **Closure ResponsibilityはFunctionalにNon-Correspondentである。**

---

## Judgment

**Strong Functional Non-Correspondence in closure responsibility**

---

# 42. Recurrence Function

SOARにはActionからEnvironmentへのReturnがある。

このReturnは、

> **organizational continuity**

を形成する。

しかし、このFunctionを、

- Feedback Control
- Error Correction
- Recursive Computation
- Self-Modification

として読み替えない。

World Model Stable Coreには同じReturn Functionが確立されない。

---

## Judgment

**Functional Non-Correspondence in explicit return responsibility**

---

# 43. Cycle Is Not Feedback Function

SOARがCyclic Organizationを持つことから、

> **Feedback Function**

を自動的に導かない。

Functional Evidenceとして支持されるのは、

```text
Action
  ↓
Environment
```

によるre-engagementである。

その後EnvironmentがPerceptionへ再び関係することでcycleが形成される。

しかしSpecific Feedback Functionの存在には追加Evidenceが必要である。

---

# 44. Cycle Is Not Recursive Function

同様にSOARのCycleを、

> **Formal Recursive Function**

として分類しない。

またWorld Modelに同じCycleがないことを理由として、

> **SOAR is recursive; World Model is not**

というCapability Judgmentを行わない。

---

# 45. Stable Core Function

World ModelにおけるStable Coreは、

```text
World
  ↓
Representation
  ↓
Understanding
  ↓
Prediction
```

までのResponsibilityを確立する。

Stable CoreのFunctionは、

> **currently supported architectural responsibilitiesをstable regionとして保持すること**

である。

その先のCandidate ExtensionをStable Coreへ吸収しない。

---

# 46. Candidate Extension Function

World ModelのCandidate Extensionには、

- Search
- Planning
- Decision-Making
- Action

等が関連する。

しかしFrozen Projection Aでは、これらのFunctional RelationはStable Coreと同じ確定Statusを持たない。

したがってCandidate FunctionをComparison時に、

> **established downstream function**

として使用しない。

---

# 47. Integrated Cycle Function

SOARではDecision / Operator / ActionがCandidateではなく、Integrated Organizational Cycleの明示的Responsibilitiesとして存在する。

したがってSOARのFunctional Architectureは、

> **established behavioral return organization**

を持つ。

しかしこれをWorld Model Candidate Extensionの「完成形」とみなさない。

---

# 48. No Functional Completion across Models

以下の推論は禁止される。

```text
World Model
Representation
   ↓
Understanding
   ↓
Prediction
   ↓
[Open Extension]

SOAR provides:
Decision
Operator
Action

Therefore:
World Model completed
```

Frozen A/BはこのCross-Model Completionを支持しない。

SOARのExplicit FunctionsはSOAR Architecture内部で意味を持つ。

World Model Candidate FunctionsはWorld Model Architecture内部でunresolvedのままである。

---

# 49. Decision-Making Vocabulary Risk

World Model Candidate Extensionには`Decision-Making`が関連する。

SOARには`Decision`が明示的Unitとして存在する。

しかし、

> **Decision-Making ↔ Decision**

というVocabulary proximityだけではFunctional Correspondenceを確立できない。

World Model側ではCandidate statusであり、Functional Placementが未確定である。

SOAR DecisionはWorking Memory依存のBehavioral Transition Organizationとして明示される。

---

## Judgment

**Insufficient basis for direct functional mapping**

---

# 50. Planning Vocabulary Risk

World Model Candidate ExtensionにはPlanningが存在する。

SOAR OperatorまたはDecisionをPlanning Functionとして読み替えることはできない。

Frozen SOAR Projectionは、

> **Operator = Planning**

を支持しない。

したがって、

```text
Planning ↔ Operator
```

というMappingは形成しない。

---

# 51. Search Vocabulary Risk

World Model Candidate ExtensionにはSearchが存在する。

SOAR Decision / Operator Architectureに対してSearch Functionを外部から投影しない。

SOAR Frozen Projection内にSearchが独立Comparative Unitとして確立されていないため、

> **Search correspondence is not established.**

---

# 52. Functional Unit Count Is Not Functional Completeness

SOARにはWorld Model Stable Coreより多くの明示的Operational Unitsが見える。

しかし、

```text
More explicit functions
        ≠
More complete architecture
```

である。

同様に、

```text
Fewer stable functions
        ≠
Less capable architecture
```

である。

Unit CountをFunctional Completeness Rankingへ変換しない。

---

# 53. Functional Scope

World Model Stable CoreのFunctional Scopeは、

> **Representation → Understanding → Prediction**

に強く集中する。

SOARのFunctional Scopeは、

> **Environment Interaction → Representation → Decision / Operator Organization → Action → Environment**

へ広がる。

しかしこれを単純に、

> World Model = narrower  
> SOAR = broader

というCapability Scaleへ変換しない。

より安全なのは、

> **Different Functional Scope and Responsibility Distribution**

である。

---

# 54. Responsibility Granularity

SOARではPerception、Decision、Operator、Actionが明示的に分離される。

World ModelではStable CoreがRepresentation、Understanding、Predictionを中心に形成され、その先をOpen Extensionとして保持する。

したがってFunctional Responsibilityの分解Granularityが異なる。

しかし、

> **more decomposed ≠ more advanced**

である。

Responsibility GranularityはArchitecture CharacteristicでありValue Judgmentではない。

---

# 55. Functional Architecture Is Not a Capability Ranking

本Artifactでは、

- Prediction-oriented
- Behavior-oriented
- Environment-coupled
- Understanding-mediated
- Action-returning

等のFunctional Characteristicsを比較する。

しかしこれらを、

- better
- more complete
- more intelligent
- more cognitive
- more autonomous

というRankingへ変換しない。

---

# 56. Generative Function

World Model Predictionには、

> **Possible Future Statesを形成するProjection Responsibility**

がある。

この意味では限定されたGenerative Functionを認めることができる。

一方SOARでは、Internal Representational StateからDecision / Operatorを経てExecutable Behaviorがorganizationされる。

しかし、このTransformationを同じGenerative Functionとして分類するにはEvidenceが不足する。

---

## Judgment

**Generative Functional Correspondence — Undetermined**

---

# 57. Why Generativity Remains Undetermined

以下の抽象化は可能である。

```text
Internal Representation
        ↓
Something not yet externally actualized
```

しかし、この抽象化だけでは、

- Future-State Generation
- Behavioral Selection
- Operator Organization
- Action Preparation

を同一Generative Functionとしてまとめるには粗すぎる。

したがって、Similarityを強制せず、

> **Undetermined**

を保持する。

---

# 58. Object-Level Flow Function

両RepresentationにはDirectional Organizationが存在する。

しかし、

> **same information flow**

> **same control flow**

> **same state flow**

> **same representational flow**

は支持されない。

World ModelはFunctional / State Transformation Directionを示す。

SOARはOrganizational Dependency / Behavioral Transformation Directionを示す。

したがってCommon Flow Functionは確定しない。

---

## Judgment

**Undetermined / Insufficient Evidence**

---

# 59. Dependency and Function

DependencyはFunctionと関係するが、同一ではない。

たとえば、

```text
Representation
      ↓
Understanding
```

というDependencyからUnderstandingのFunctional Responsibilityを観察できる。

しかしDependency Arrow自体がFunctionの全内容を表すわけではない。

同様に、

```text
Working Memory
      ↓
Decision
```

はDecisionのDependency Conditionを示すが、Decision Function全体を定義しない。

---

# 60. Dependency Is Not Execution Function

両Frozen ProjectionsでDependencyはExecution Orderとして確立されていない。

したがって、

```text
A depends on B
      ≠
B executes first
```

である。

この区別はFunctional Comparisonでも保持する。

---

# 61. Functional Sequence Is Not Temporal Sequence

本Artifactで、

```text
Representation
      ↓
Understanding
      ↓
Prediction
```

または、

```text
Working Memory
      ↓
Decision
      ↓
Operator
      ↓
Action
```

と記述する場合、そのArrowを厳密なTemporal Sequenceとして解釈しない。

Frozen A/Bはcomplete timing architectureを提供していない。

---

# 62. Functional Transformation Is Not Algorithm

Transformation Relationが存在しても、

- algorithm
- computation sequence
- software execution
- control rule
- timing mechanism

を推論しない。

> **Functional Transformation ≠ Implementation Algorithm**

である。

---

# 63. Functional Correspondence around Representation

ここまでのObservationを圧縮すると、Representational Center周辺では、

```text
WORLD MODEL                    SOAR

External World               Environment
      │                           │
      │                     Perception
      │                           │
Representation             Working Memory
      │                           │
      └──── enables ──────────────┘
          subsequent
          organization
```

という限定されたFunctional Correspondenceが存在する。

ただし図中の横方向RelationはUnit Identityを意味しない。

比較可能なのは、

> **representational enabling responsibility**

である。

---

# 64. Functional Divergence after Representation

Representational Center以降では、

```text
WORLD MODEL                    SOAR

Representation             Working Memory
      │                           │
Understanding                  Decision
      │                           │
Prediction                    Operator
      │                           │
Possible Future                Action
States                           │
                             Environment
```

となる。

ここではFunctional Responsibilityが分岐する。

World ModelはUnderstanding / Predictionへ向かう。

SOARはDecision / Operator / Action / Environmental Re-engagementへ向かう。

---

# 65. Local Correspondence and Global Functional Divergence

したがってFunctional Levelでも、

> **Local Correspondence around Representational Centrality**

と、

> **Global Divergence in Downstream Functional Responsibility**

が同時に成立する。

このPatternはStructural Comparisonと整合するが、Structural ResultをそのままFunctional Resultへコピーしたものではない。

Functional Comparison独自の中心は、

> **what responsibilities are enabled after representation**

である。

---

# 66. Strongest Functional Correspondence

本Caseで最も強いFunctional Correspondenceは、

> **Internal Representational Organization enables subsequent cognitive organization**

である。

これは、

```text
Representation
      ↓
Understanding / Prediction
```

と、

```text
Working Memory
      ↓
Decision / Operator / Action
```

の間に認められる。

ただし「後続Cognitive Organization」の具体的内容は異なる。

---

# 67. Strongest Functional Non-Correspondence

最も明確なFunctional Non-Correspondenceは、

> **downstream responsibility and closure**

にある。

World Model Stable Core：

> Understanding → Prediction → Open Boundary

SOAR：

> Decision → Operator → Action → Environment

である。

したがってGlobal Functional Architectureは同型ではない。

---

# 68. Functional Correspondence Matrix

| Functional Coordinate | World Model | SOAR | Judgment |
|---|---|---|---|
| External reference | World | Environment | Limited Functional Correspondence |
| Explicit perceptual mediation | Not established | Perception | Functional Non-Correspondence |
| Internal representational organization | Representation | Working Memory | Strong Functional Correspondence without Structural Identity |
| Enabling subsequent organization | Yes | Yes | Strongly Supported Functional Correspondence |
| Immediate downstream responsibility | Understanding | Decision | No justified direct mapping |
| Future-state projection | Prediction | No direct counterpart established | Functional Non-Correspondence |
| Operator organization | No direct counterpart established | Operator | Functional Non-Correspondence |
| Explicit behavioral execution | Candidate / unresolved | Action | Functional Non-Correspondence |
| Environmental return | Not established in Stable Core | Explicit | Functional Non-Correspondence |
| Generative function | Bounded support | Unclear as same category | Undetermined |
| Common object-level flow | Not established | Not established as same flow | Undetermined |

---

# 69. Functional Responsibility Matrix

| Responsibility | World Model | SOAR |
|---|---|---|
| External Domain | World | Environment |
| External-to-Internal Mediation | Not separately established | Perception |
| Internal Representation | Representation | Working Memory |
| Semantic / Cognitive Understanding | Understanding | No direct counterpart established |
| Behavioral Decision Organization | Candidate region not fixed | Decision |
| Future-State Projection | Prediction | No direct counterpart established |
| Operator Organization | No direct counterpart established | Operator |
| Behavioral Execution | Candidate Action unresolved | Action |
| Environmental Re-engagement | Not established in Stable Core | Action → Environment |
| Open Extension Preservation | Explicit | No direct counterpart established |
| Closed Cycle Maintenance | No | Explicit organizational return |

このMatrixは1:1 Mapping Tableではない。

むしろ、

> **where responsibilities are established, differently distributed, or absent as explicit counterparts**

を示す。

---

# 70. Functional Correspondence without Structural Identity

本CaseではこのCategoryを明示的に保持する必要がある。

代表例：

> **Representation ↔ Working Memory**

両者は、

- internal representational organization
- downstream enabling responsibility
- high functional centrality

でCorrespondenceを持つ。

しかし、

- structural status
- dependency context
- architectural scope
- cycle participation
- layer / module responsibility

が異なる。

したがって、

> **Functional Correspondence without Structural Identity**

が最も適切なStatusとなる。

---

# 71. Functional Non-Correspondence without Deficiency

Functional Counterpartが存在しない場合でも、それをDeficiencyとして扱わない。

たとえばWorld Model Stable CoreにSOAR Perceptionのdirect counterpartがないことから、

> World Model lacks perception

とは判断しない。

同様にSOARにWorld Model Predictionのdirect counterpartがないことから、

> SOAR lacks prediction capability

とも判断しない。

Frozen Representation内で、

> **同じFunctional Responsibilityがexplicit comparative unitとして確立されていない**

というObservationに限定する。

---

# 72. Functional Difference Is Not Capability Difference

このBoundaryは特に重要である。

```text
Different represented function
        ≠
Different actual capability
```

本ComparisonはArchitecture Representationを比較している。

実際のSystem / Theoryが持つすべてのCapabilityを測定しているわけではない。

---

# 73. Functional Correspondence Is Not Conceptual Equivalence

RepresentationとWorking Memoryが似たFunctionを持つからといって、

> **Representation concept = Working Memory concept**

とは判断しない。

UnderstandingとDecisionがdownstreamにあるからといって、

> **Understanding concept = Decision concept**

とも判断しない。

Functional RelationとConceptual Equivalenceを分離する。

---

# 74. Functional Correspondence Is Not Theoretical Equivalence

局所的Functional Correspondenceから、

> World Model and SOAR implement the same cognitive theory

とは判断しない。

本CaseはTheory Equivalenceを検証していない。

---

# 75. Functional Correspondence Is Not Implementation Equivalence

同様に、

> World Model Representation and SOAR Working Memory are implemented in the same way

とは判断しない。

Frozen A/BはImplementation Mechanismを比較するためのEvidenceを提供していない。

---

# 76. Functional Correspondence Is Not Information-Flow Equivalence

両者がExternal DomainからInternal Representationへ関係することから、

> same information-processing pipeline

とは判断しない。

SOARにはPerception mediationが明示される。

World Modelには同種のInterface Unitが確立されない。

したがってFunctional SimilarityをInformation-Flow Identityへ拡張しない。

---

# 77. Functional Correspondence Is Not Control Equivalence

Decision / Operator / Actionの存在からSOARにComplete Control Architectureを推論しない。

またWorld Modelに同じUnitsがStable CoreにないことからControl Functionの欠如を推論しない。

Control ArchitectureはFrozen Comparison Evidenceの外部にある。

---

# 78. Representation-Level Functional Discipline

両Projectionでは、

- FunctionとStructureを区別する
- DependencyとExecutionを区別する
- Unsupported Mechanismを追加しない
- Canonicalizationで新Functionを生成しない

というRepresentation Disciplineが保持される。

しかしこれはObject-level Functional Correspondenceではない。

> **Representation-level Discipline ≠ Functional Architecture Correspondence**

である。

---

# 79. Unexpected Functional Observation

Initial ComparisonとVerificationを通じて重要だったObservationの一つは、

> **最も強いFunctional Correspondenceが、最も強いFalse Identity Riskを同時に持つ**

ことである。

RepresentationとWorking Memoryは明確に比較可能である。

しかし、その比較可能性が強いために、

```text
Functional Centrality
      ↓
Functional Identity
      ↓
Structural Identity
```

とOver-readしやすい。

本Artifactではこの移行を禁止する。

---

# 80. Functional Correspondence Localization

Functional CorrespondenceはArchitecture全体へ均等に分布していない。

むしろ、

```text
External / Internal distinction
        ↓
Representational Organization
        ↓
Enabling Relation
```

付近に集中する。

その後、

```text
Understanding / Prediction
             versus
Decision / Operator / Action
```

へ進むとCorrespondenceが弱まり、Different Responsibility / Non-Correspondenceが増える。

---

# 81. Functional Concreteness and Divergence

比較をより具体的なFunctional Responsibilityへ進めるほど、両者の違いが明確になる。

抽象度の高いLevel：

> Internal Representation enables later cognition.

ではCorrespondenceが強い。

具体的Level：

> What exact later cognition?

では、

```text
Understanding / Prediction
             versus
Decision / Operator / Action
```

へ分岐する。

したがって、

> **functional correspondence weakens as responsibility specification becomes more concrete.**

---

# 82. Alternative Reading Rejected

以下のAlternative Readingは支持されない。

> **Both architectures describe essentially the same cognitive cycle at different levels of abstraction.**

このReadingは、

- PredictionとActionを暗黙的に接続する
- World Model Open BoundaryをSOAR componentsで補う
- SOAR cycleをWorld Modelへ投影する
- Different ResponsibilityをAbstraction Differenceへ還元する

必要がある。

Frozen A/Bはこれを支持しない。

---

# 83. Opposite Alternative Reading Rejected

逆に、

> **The two architectures are functionally unrelated; representational similarity is superficial.**

というReadingも支持されない。

両者には、

> **Internal Representational Organizationがsubsequent cognitive responsibilityを可能にする**

という意味のあるFunctional Correspondenceが存在する。

したがって完全なFunctional Non-Correspondenceも過剰である。

---

# 84. Balanced Functional Judgment

最も安定したFunctional Judgmentは、

> **Meaningful Local Functional Correspondence with Material Downstream Functional Divergence**

である。

これは、

```text
Same Function
```

でも、

```text
No Functional Relation
```

でもない。

両者の間に限定されたFunctional Relationが存在し、その範囲を越えるとDifferent Responsibilityが支配的になる。

---

# 85. Functional Invariants

本Artifactでは以下を保持する。

> **Functional Correspondence ≠ Functional Identity**

---

> **Functional Correspondence ≠ Structural Identity**

---

> **Functional Similarity ≠ Conceptual Equivalence**

---

> **Functional Difference ≠ Capability Difference**

---

> **Same Vocabulary ≠ Same Function**

---

> **Same Position ≠ Same Responsibility**

---

> **Representational Enabling ≠ Same Downstream Process**

---

> **Transformation Correspondence ≠ Same Transformation Product**

---

> **Environmental Return ≠ Feedback Mechanism**

---

> **Cyclic Function ≠ Formal Recursive Function**

---

> **Open Functional Boundary ≠ Functional Deficiency**

---

> **Closed Functional Cycle ≠ Functional Completeness**

---

# 86. Strongly Supported Functional Findings

Frozen A/BおよびVerification後に強く保持されるFunctional Findingsは以下である。

1. 両者ともInternal Representational Organizationに高いFunctional Centralityを与える。
2. Representational CenterはFunctional Terminalではない。
3. Representational Organizationはsubsequent cognitive responsibilityを可能にする。
4. Representation ↔ Working Memoryには意味のあるFunctional Correspondenceが存在する。
5. このCorrespondenceはStructural Identityを支持しない。
6. Representational Center以降のFunctional Responsibilitiesはmaterially divergeする。
7. SOARにはexplicit environmental return responsibilityが存在する。
8. World Model Stable Coreには同じReturn Responsibilityは確立されない。

---

# 87. Partially Supported Functional Findings

以下はQualification付きで保持される。

1. External Domain ↔ Internal RepresentationというFunctional distinction。
2. World ↔ Environmentのlimited external-reference correspondence。
3. Internal Representationからsubsequent organizationへのTransformation Correspondence。
4. Representational dependency centralityのFunctional proximity。

これらはいずれも同一Mechanismを意味しない。

---

# 88. Functional Non-Correspondences

主要Functional Non-Correspondenceは以下である。

- Perception ↔ no explicit World Model counterpart
- Understanding ↔ Decision
- Prediction ↔ Operator
- Prediction ↔ Action
- World Model Candidate Action ↔ SOAR Action
- World Model Open Boundary Responsibility ↔ SOAR Environmental Coupling Responsibility
- World Model Stable-Core downstream condition ↔ SOAR Cycle Closure
- Explicit environmental return
- Behavior-oriented downstream organization

これらをDeficiency Judgmentへ変換しない。

---

# 89. Undetermined Functional Relations

以下は確定しない。

## 89.1 Generative Correspondence

PredictionとSOAR Behavioral Organizationが同種のGenerative Functionか。

**Status:** Undetermined

---

## 89.2 Common Flow Function

両者が同種のInformation / State / Control / Representation Flowを持つか。

**Status:** Insufficient Evidence

---

## 89.3 Feedback Function

SOAR CycleがSpecific Feedback Functionを持つか。

**Status:** Insufficient Evidence

---

## 89.4 Formal Recursive Function

比較可能なFormal Recursive Functionが存在するか。

**Status:** Insufficient Evidence

---

# 90. Evidence Boundary

本Artifactから以下を主張しない。

- Representation and Working Memory are the same function
- Understanding and Decision are equivalent functions
- Prediction and Operator are equivalent functions
- Prediction and Action are equivalent functions
- World Model Action and SOAR Action are functionally identical
- SOAR completes World Model downstream functionality
- World Model is an abstract SOAR
- SOAR is an operationalized World Model
- both implement the same cognitive cycle
- both use the same information flow
- both use the same control flow
- SOAR cycle is a feedback mechanism
- SOAR cycle is formal recursion
- World Model lacks perception capability
- SOAR lacks prediction capability
- one architecture is functionally superior
- one architecture is more complete

---

# 91. Functional Responsibility Map

Restabilized Functional Comparisonを圧縮すると、

```text
WORLD MODEL                              SOAR

World                                  Environment
  │                                        │
  │                                    Perception
  │                                        │
Representation  ← correspondence →   Working Memory
  │                                        │
Understanding                            Decision
  │                                        │
Prediction                               Operator
  │                                        │
Possible Future States                   Action
  │                                        │
Open Architectural Boundary          Environment
                                           │
                                    Organizational Return
```

となる。

このMapで横方向に意味のある強いCorrespondenceを置けるのは主として、

> **Representation ↔ Working Memory**

である。

World ↔ Environmentは限定的であり、それ以外のdownstream unitsにdirect mappingを置かない。

---

# 92. Functional Relation Map

より抽象的なFunctional Relationとしては、

```text
WORLD MODEL

External Domain
      ↓
Internal Representational Organization
      ↓
Semantic / Cognitive Organization
      ↓
Future-State Projection
      ↓
Open Boundary
```

に対し、

```text
SOAR

External Domain
      ↓
Perceptual Mediation
      ↓
Internal Representational Organization
      ↓
Decision / Operator Organization
      ↓
Behavioral Execution
      ↓
External Re-engagement
```

となる。

この二つのMapが示すのは、

> **shared representational center with different downstream functional architectures**

である。

---

# 93. Restabilized Functional Judgment

本Artifactで保持されるRestabilized Functional Judgmentは次の通りである。

> **World ModelとSOARの間には、External DomainとInternal Representational Organizationを区別し、Internal Representational Organizationを後続Cognitive ResponsibilityのFunctional Foundationとして用いるという限定された領域で、意味のあるFunctional Correspondenceが存在する。特にWorld ModelのRepresentationとSOARのWorking Memoryは、Representational CentralityおよびSubsequent Organizationを可能にするResponsibilityにおいて強いFunctional Correspondenceを持つ。**
>
> **しかし、このCorrespondenceはFunctional IdentityまたはStructural Identityを意味しない。World ModelのRepresentationはUnderstandingとPredictionを支え、Possible Future StatesへのProjectionへArchitectureを展開する。一方、SOARのWorking MemoryはDecision、Operator、Actionを支え、Behavioral Executionを介してEnvironmentへのRe-engagementへArchitectureを展開する。**
>
> **したがって、Representational Center以降ではFunctional Responsibilityがmaterially divergeする。Understanding ↔ Decision、Prediction ↔ Operator、Prediction ↔ Action、World Model Action ↔ SOAR Actionというdirect mappingは支持されない。**
>
> **この比較が支持するのはGlobal Functional Equivalenceではなく、Representational Enabling Responsibilityを中心とするLocal Functional Correspondenceと、Downstream ResponsibilityおよびClosureにおけるGlobal Functional Divergenceの併存である。**

最も圧縮したFunctional Formは、

> **Local Functional Correspondence around Representational Enabling × Global Functional Divergence in Downstream Responsibility and Closure**

である。

---

# 94. Relationship to Structural Correspondence

本Artifactは`02-structural-correspondence.md`と密接に関係する。

しかし両者のResponsibilityは異なる。

`02`：

> **How are the represented structures related?**

`03`：

> **What responsibilities do those structures perform, and how do those responsibilities correspond or diverge?**

したがって、

```text
Structural Correspondence
        ≠
Functional Correspondence
```

である。

両者が同じJudgmentを持つ場合もあれば、異なるStatusを持つ場合もある。

---

# 95. Relationship to Hierarchical Projection

Functional ResponsibilityがどのLayerまたはArchitectural Positionに配置されるかという問題は、

> `04-hierarchical-projection.md`

のPrimary Responsibilityである。

本ArtifactではLayer情報をFunctionの理解に必要な範囲でのみ使用する。

Layer CountやVertical OrganizationからFunctional Correspondenceを導かない。

---

# 96. Relationship to Observation Notes

Initial ComparisonからVerificationまでの間に、

- QUALIFY
- REVISE
- RECLASSIFY
- WITHDRAW
- UNDETERMINED

となった形成履歴は、

> `05-observation-notes.md`

に保存する。

本Artifactではその履歴を全面的に再現せず、

> **Restabilized Functional Result**

を中心に保持する。

---

# 97. Relationship to Comparative Summary

本ArtifactのFunctional Findingsは、

> `06-comparative-summary.md`

でCase全体のRestabilized Judgmentへ圧縮される。

06は03の代替ではない。

03はFunctional Responsibilityを十分なGranularityで保持し、06はその主要結果だけをCase-level Summaryへ統合する。

---

# 98. Final Functional Orientation

本Comparisonにおいて最も重要なのは、

> **RepresentationとWorking Memoryが同じかどうか**

を問うことではない。

より正確な問いは、

> **それぞれのArchitectureでInternal Representational Organizationは何を可能にしているか**

である。

この問いに対して、双方には意味のある共通性が存在する。

しかし次の問い、

> **そのRepresentational Organizationの後に、Architectureは何を行うのか**

へ進むと、両者は明確に分岐する。

したがってFunctional Comparisonは、

```text
Shared Enabling Responsibility
        ↓
Different Downstream Responsibility
        ↓
Different Closure Responsibility
```

として最も安定して理解できる。

---

# 99. Artifact Boundary

本Artifactの責任は、

> **Functional Correspondence / Functional Non-Correspondence / Different Functional Responsibilityの保持**

である。

本Artifactでは、

- New Comparative Analysisを追加しない
- Frozen A/Bを修正しない
- Structural CorrespondenceをFunctional Identityへ変換しない
- Functional CorrespondenceをStructural Identityへ変換しない
- Undetermined Relationを強制分類しない
- Legacy Case 004を参照しない

というBoundaryを維持する。

次Artifactである、

> `04-hierarchical-projection.md`

には本Artifactから自動的に進まない。

---

# Status

**Artifact:** `03-functional-correspondence.md`  
**Case:** Case 004 — World Model × SOAR  
**Projection Source:** Restabilized Comparative Judgment  
**Artifact Responsibility:** Functional Responsibility Comparison  
**Functional Correspondence:** Preserved  
**Functional Correspondence without Structural Identity:** Preserved  
**Functional Non-Correspondence:** Preserved  
**Different Functional Responsibilities:** Preserved  
**Different Transformation Responsibilities:** Preserved  
**Undetermined Functional Relations:** Preserved  
**Capability Boundary:** Preserved  
**Evidence Boundary:** Preserved  
**Frozen A/B Revision:** None  
**New Comparative Analysis:** None Added  
**Old Case 004:** Withheld  
**Repository Projection Status:** Artifact 03 Complete  
**Next Artifact:** Not Started
