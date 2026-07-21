# Research Note: External–Internal Orientation Hypothesis

**Status:** Research Hypothesis / Core Extension Candidate
**Version:** 0.1
**Date:** 2026-07-22

---

## 1. Overview

The Cognitive OS Dynamic Structure Model currently describes cognitive characteristics through a set of core, extended, and control parameters.

During exploratory consideration of differences between individuals with similar parameter tendencies, a new hypothesis emerged:

> Even when two individuals exhibit similar values on the same cognitive parameter, their cognitive processing may differ according to the direction in which information is primarily processed: externally oriented or internally oriented.

This note proposes the **External–Internal Orientation Hypothesis** as a candidate for future extension of the Core Model.

At this stage, this is **not a confirmed parameter or finalized model component**. Multiple structural interpretations remain possible and require empirical validation.

---

## 2. Origin of the Hypothesis

The hypothesis emerged from a simple observation:

> Individuals who appear to share the same exploratory tendency can nevertheless behave, think, learn, and interact with AI in substantially different ways.

For example, two people may both exhibit high exploratory tendencies, while one primarily explores through:

* direct interaction with the external environment,
* conversations with other people,
* experimentation,
* acquisition of new experiences,

while another primarily explores through:

* internal thought,
* conceptual manipulation,
* hypothesis generation,
* mental simulation,
* integration of previously acquired information.

Both may be described as "highly exploratory," but their cognitive processes may differ substantially.

This raises the possibility that the existing parameter value alone does not fully explain the observed difference.

The question therefore becomes:

> Is there an additional structural dimension that determines the direction of cognitive processing?

---

## 3. Initial Hypothesis

The initial hypothesis is that cognitive processing may possess an **External–Internal Orientation** that interacts with existing cognitive parameters.

Conceptually:

```text
Existing Cognitive Parameter
        +
External–Internal Orientation
        ↓
Individual Cognitive Processing Pattern
```

For example:

```text
Exploration: High
Orientation: External
```

may produce a different cognitive pattern from:

```text
Exploration: High
Orientation: Internal
```

The distinction is not intended to represent sociability, personality, or a simple introversion/extraversion classification.

Instead, the hypothesis concerns the **direction of information processing**.

Possible distinctions include:

* external information acquisition,
* internal information generation,
* external validation,
* internal integration,
* external experimentation,
* internal simulation.

The meaning and operational definition of this orientation remain subject to future research.

---

## 4. Relationship to Existing Parameters

One possibility is that External–Internal Orientation functions as a **cross-cutting dimension** across existing parameters.

Conceptually:

```text
                 External ↔ Internal
                        │
        ┌───────────────┼───────────────┐
        │               │               │
     Parameter A     Parameter B     Parameter C
        │               │               │
      State           State           State
```

Under this interpretation, External–Internal Orientation is not itself a new independent cognitive ability.

Instead, it describes the direction in which an existing cognitive process is primarily operating.

This could potentially explain why individuals with similar parameter values exhibit different observable behaviors.

---

## 5. Alternative Structural Hypotheses

The final Core structure should not be determined until competing interpretations are examined.

At least four structural models are currently conceivable.

### 5.1 Cross-Cutting Dimension Model

External–Internal Orientation is a dimension applied across existing parameters.

```text
Parameter
    ×
External–Internal Orientation
```

This model is relatively simple and may be suitable if the orientation consistently explains differences across multiple parameters.

---

### 5.2 Dual-State Model

External and Internal are treated as two possible operating states of the same cognitive process.

```text
External State
      ↕
Internal State
```

Under this model, the important variable may not be a fixed orientation but the individual's tendency to transition between states.

---

### 5.3 Transition-Direction Model

External–Internal Orientation may represent the direction of state transitions.

For example:

```text
External Input
      ↓
Internal Exploration
      ↓
Internal Integration
      ↓
External Validation
```

In this model, the relevant characteristic is not simply "external" or "internal," but the individual's characteristic transition pathway.

---

### 5.4 Cognitive Flow Model

External and Internal may represent nodes or regions within a larger information-processing flow.

```text
External Environment
        ↓
Attention
        ↓
Exploration
        ↓
Thought
        ↓
Meaning Generation
        ↓
Behavior / Language / Creation
        ↓
External Environment
```

Under this interpretation, External–Internal Orientation describes the structure and direction of information flow rather than an independent parameter.

---

## 6. Potential Importance for AI Systems

If the hypothesis is valid, External–Internal Orientation may have practical implications for adaptive AI systems.

Two users with similar cognitive parameter values may nevertheless benefit from different forms of AI interaction.

For example:

```text
User A
High Exploration
External-oriented

Potentially effective AI behavior:
- provide new information
- offer external examples
- introduce alternative perspectives
- encourage experimentation
```

versus:

```text
User B
High Exploration
Internal-oriented

Potentially effective AI behavior:
- organize concepts
- support hypothesis generation
- deepen internal reasoning
- facilitate conceptual integration
```

The relevant question is therefore not only:

> "What cognitive characteristics does the user have?"

but also:

> "In which direction is the user's cognitive processing currently operating?"

---

## 7. Dynamic State Hypothesis

External–Internal Orientation may not be static.

During interaction with AI, the orientation may change dynamically.

A hypothetical sequence might be:

```text
Initial State
Internal-oriented
        ↓
AI provides external information
        ↓
External-oriented
        ↓
Information becomes sufficient
        ↓
Internal integration
        ↓
New hypothesis emerges
        ↓
External exploration resumes
```

This suggests that AI systems may eventually benefit from tracking **state transitions** rather than maintaining only static user profiles.

A potentially useful model could therefore distinguish:

* baseline orientation,
* current orientation,
* transition frequency,
* transition direction,
* transition triggers,
* duration of each state.

However, these concepts remain hypotheses and require empirical validation.

---

## 8. Computational Cost Considerations

Introducing External–Internal Orientation may increase the computational cost of state estimation.

However, the cost does not necessarily need to scale linearly with the full cognitive model.

Possible optimization strategies include:

### Selective Estimation

Only estimate External–Internal Orientation for parameters relevant to the current task.

```text
Task
 ↓
Relevant Parameters
 ↓
Selective State Estimation
```

### Change-Triggered Re-estimation

Re-estimate only when a meaningful state change is detected.

```text
No significant change
→ Maintain previous estimate

Potential state change
→ Re-estimate relevant parameters
```

### Adaptive Observation Frequency

Parameters that change frequently can be monitored at higher frequency, while relatively stable parameters are updated less frequently.

This suggests a possible future architecture in which:

> The theoretical Core Model is comprehensive, while practical implementations selectively activate only the parameters and state dimensions relevant to a given application.

---

## 9. Potential Research Questions

The following questions should be investigated before integrating External–Internal Orientation into the Core Model.

### RQ1

Do individuals with similar cognitive parameter values exhibit systematic differences in information-processing direction?

### RQ2

Can External–Internal Orientation explain behavioral differences that cannot be explained by existing parameters alone?

### RQ3

Is External–Internal Orientation a stable individual characteristic, a dynamic state, or both?

### RQ4

Does the orientation apply consistently across multiple cognitive parameters?

### RQ5

Is a cross-cutting dimension sufficient, or is a transition/flow model more explanatory?

### RQ6

Can External–Internal Orientation improve AI response adaptation?

### RQ7

Can the additional predictive value justify the computational cost of state estimation?

### RQ8

Can state-transition patterns be inferred from natural interaction with AI?

---

## 10. Proposed Validation Strategy

A future validation study could compare models with and without External–Internal Orientation.

### Model A

```text
Existing Core Parameters
        ↓
State Estimation
        ↓
Predicted Cognitive State
```

### Model B

```text
Existing Core Parameters
        +
External–Internal Orientation
        ↓
State Estimation
        ↓
Predicted Cognitive State
```

The two models could be compared on:

* explanatory power,
* behavioral prediction,
* AI response adaptation,
* user satisfaction,
* task completion,
* interaction efficiency,
* model routing efficiency,
* inference cost.

The key question is not simply whether Model B is more complex.

The key question is:

> Does the additional explanatory power and practical utility of External–Internal Orientation justify the additional model complexity and computational cost?

---

## 11. Current Position in the Core Model

At present, External–Internal Orientation should **not** be treated as a finalized Core parameter.

Recommended status:

```text
Core Model
    │
    ├─ Existing Core Parameters
    │
    ├─ Existing Extended Parameters
    │
    ├─ Control Parameters
    │
    └─ Core Extension Candidates
           │
           └─ External–Internal Orientation
                Status: Hypothesis
                Validation: Required
```

The hypothesis should remain separate from the finalized Core specification until empirical evidence supports one of the proposed structural interpretations.

---

## 12. Research Note

This hypothesis originated from observing that individuals with similar apparent cognitive tendencies may nevertheless exhibit substantially different cognitive behavior.

The initial observation was:

> "If two people are both highly exploratory, why can their exploration look so different?"

The resulting hypothesis is that the difference may not require an entirely new cognitive parameter. Instead, the same cognitive process may operate in different directions, states, or transition pathways.

This suggests a broader possibility:

> Cognitive models may need to represent not only **what characteristics a person has**, but also **where cognitive processing is directed and how that direction changes over time**.

Further research is required to determine whether External–Internal Orientation should ultimately be represented as:

1. a cross-cutting dimension,
2. a dual-state structure,
3. a transition direction,
4. a cognitive flow structure,
5. or another model not yet identified.

Until validated, this concept remains a **research hypothesis and Core Extension Candidate**.
