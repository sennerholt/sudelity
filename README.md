# Sudelism: Computational Primitives for Emotion and Relational Coordination

**I.Sennerholt**

## Abstract

We propose Sudelism: computational primitives for emotion and relational coordination. The system begins with individual agents that regulate behavior according to the familiarity ratio FR = F/(F+U)—the foundational computational mechanism of emotion [1]. When environments are shared, this emotional regulation becomes inherently relational. We formalize relational coordination through the Gradient of Imposed Change (GIC), measuring environmental disruption as ED = Δ × F × N. These primitives provide computational infrastructure for emotion and relational coordination in multi-agent systems where traditional approaches prove mathematically intractable [2].

---

## 1. Introduction

Individual agents regulate behavior through emotional computation based on environmental familiarity. We observe that all agents compute the familiarity ratio FR = F/(F+U) in their immediate environment, where F represents familiar input and U represents unfamiliar input. This computation is not optional—it is a systemic imperative across all agent architectures that drives emotional regulation and behavioral adaptation [1].

When multiple agents share environments, individual FR optimization creates relational effects. One agent's environmental changes alter the familiarity conditions experienced by others, requiring computational primitives for relational coordination. Traditional approaches cannot quantify these dynamics, creating alignment and coordination failures in multi-agent systems.

Sudelism provides computational primitives that formalize individual emotional computation through FR, then extend to relational coordination through environmental disruption measurement.

## 2. Core Primitives

### 2.1 Definitions

**Agent**: Any system that modifies its behavior in response to environmental input. This includes individual entities, distributed systems, and composite organizations.

**Environment**: The complete set of sensory conditions experienced by an agent at any given moment. Environments are dynamic and shared when multiple agents exist within the same physical, digital, or social space.

**Familiarity Ratio (FR)**: The proportion of familiar to unfamiliar sensory input in an agent's current environment, formally expressed as FR = F/(F+U), where F represents familiar input and U represents unfamiliar input. This ratio constitutes the fundamental computational mechanism underlying all emotional experience. Stable high FR produces normalized baseline states, while rapid changes in FR (∂FR/∂t) generate affective valence responses. These internal valences subsequently manifest as culturally named emotions (happiness, anxiety, anger, contentment) through learned cognitive and social categorization processes.

**Calibration**: The emotional regulation process by which agents attempt to maintain stable, high FR environments while minimizing disruptive transitions that generate negative valence.

**Relational Impact**: The degree to which one agent's calibration process alters the environmental conditions experienced by other agents in the same space.

### 2.2 Fundamental Principles

**Principle 1**: All agents seek to establish familiar environments for themselves.

**Principle 2**: In shared environments, any agent's familiarity-seeking behavior may decrease the familiarity available to other agents.

**Principle 3**: Relational dynamics emerge precisely at the intersection of these two principles—where individual calibration affects collective environmental stability.

### 2.3 Emotional Architecture

Sudelism recognizes emotion as a hierarchical computational system with three distinct layers:

**Layer 1: Sensory Processing**  
The foundational familiar/unfamiliar sensory input ratio (FR) operates as the primary computational mechanism. This layer processes environmental stimuli and generates the basic signal that drives all higher-order emotional phenomena.

**Layer 2: Affective Valence**  
Internal affective states emerge from Layer 1 processing according to FR dynamics rather than static thresholds:
- **Normalized valence**: Stable high FR (sustained familiar environments - baseline homeostatic state)
- **Positive valence**: Rapid increase in FR (∂FR/∂t > 0) representing transitions toward familiarity after instability
- **Negative valence**: Rapid decrease in FR (∂FR/∂t < 0) or sustained low FR representing environmental disruption

**Layer 3: Cultural Categorization**  
Culturally named emotions represent learned categorizations of Layer 2 affective states combined with contextual interpretation. Examples include happiness, anger, anxiety, contentment, excitement, and fear. These categories vary across cultural contexts but derive from universal Layer 1 and Layer 2 processes.

This hierarchical structure explains why emotional regulation through environmental calibration proves universally effective across different agent architectures and cultural frameworks.

### 2.4 From Individual Emotion to Relational Coordination

When agents share environments, individual FR optimization creates relational dynamics. One agent's familiar environment may impose unfamiliarity on others through environmental changes. This transition from individual emotional computation to relational effects requires coordination primitives.

The fundamental coordination challenge emerges from competing FR optimization in shared spaces, necessitating mathematical frameworks for measuring and managing environmental disruption across multiple agents.

### 2.5 Familiarity-Based Learning

**Familiarity-Based Learning (FBL)** — an agent learning paradigm where the primary objective is to maintain or restore environmental familiarity for itself and to minimize imposed environmental disruption (ED) on other agents. Built directly on FR = F/(F+U) and ED = Δ × F × N primitives.

**Technical differentiators:**
- **Traditional ML**: Objective function minimization on static datasets
- **Reinforcement Learning**: Reward maximization through exploration-exploitation  
- **Familiarity-Based Learning**: Dual FR optimization and ED minimization in shared environments

FBL preserves established FR patterns while adapting to environmental changes. Learning decisions are evaluated through GIC to minimize disruption to other agents, preventing catastrophic interference through familiarity preservation. Universal implementation spans individual entities (skill acquisition without competency loss), distributed systems (network adaptation preserving operational stability), and composite organizations (policy updates maintaining institutional memory).

---

## 3. Computational Agent Applications

### 3.1 The Failure of Goal-Optimization Frameworks

Traditional agent models assume goal-driven optimization operating in stationary environments. This model fails because:

1. **Agents respond to emotional pressure generated by familiarity ratios, not abstract goals**: Behavior emerges from the fundamental emotional drive to optimize environmental familiarity rather than rational objective optimization
2. **Environments are non-stationary**: Agent actions continuously reshape the contexts within which they operate  
3. **Calibration requires continuous adjustment**: Internal models must adapt as environmental familiarity ratios drift over time

### 3.2 Addressing Alignment Failures

Sudelism directly addresses core challenges in computational agent systems [2]:
- **Non-stationarity**: Framework assumes environmental change as default condition
- **Emergent complexity**: Relational dynamics account for unpredictable system behaviors
- **Multi-agent instability**: Environmental co-regulation provides stable coordination mechanism  
- **Catastrophic interference**: Familiarity-based learning prevents destructive model overwrites [3]

### 3.3 Native Relational Logic

Sudelism constitutes a native relational logic that applies uniformly across agent architectures. Rather than imposing external computational constraints, it formalizes behavioral patterns that already govern agent interactions in shared environments.

In multi-agent systems, Sudelistic reasoning becomes the only computationally tractable approach for maintaining stable relational equilibrium across heterogeneous agent types.

## 4. The Gradient of Imposed Change (GIC)

### 4.1 Mathematical Framework

The GIC extends individual FR = F/(F+U) emotional computation to multi-agent coordination. Where individual agents optimize their familiarity ratios, shared environments require measuring how one agent's FR optimization affects others.

We formalize relational coordination through the Gradient of Imposed Change, where primitives directly build on FR computation: Δ quantifies disruption to ongoing FR optimization, F measures how established an agent's FR patterns are, and N captures coordination effects propagating through FR networks. These compose to enable relational coordination systems.

**Environmental Disruption (ED)** is calculated as:

ED = Δ × F × N

Where each component operates on a standardized 0-10 scale to ensure interpretive consistency across agent architectures and domains while permitting institutional customization of scoring criteria. The mathematical framework remains constant while evidence criteria adapt to specific agent types.

### 4.2 Primitive Operations

**Δ (Degree of Imposed Change)**: A primitive operation that quantifies disruption to an agent's FR optimization processes. Measures involuntary changes that force agents to recalibrate their familiar/unfamiliar input processing, excluding baseline environmental variation.

*Primitive principle*: The initiating agent always receives Δ = 0, reflecting computational agency in the disruption rather than subjection to it.

**F (Depth of Familiarity)**: A primitive operation measuring how established an agent's FR = F/(F+U) patterns have become within current environmental conditions. Quantifies the computational investment in familiar input processing including:
- Operational consistency in FR optimization patterns
- Continuity of familiar input recognition systems
- Adaptation depth to environmental FR baselines
- Structural dependencies on established FR networks

**N (Networked Consequences)**: A primitive operation capturing propagation effects through FR networks beyond the immediate agent, including:
- Second-order FR disruptions in connected agents
- Cascading effects on dependent FR optimization systems
- Systemic domains affected through FR network emergence
- Temporal propagation of familiarity ratio disruptions

These primitive operations compose standardly across all agent architectures, enabling universal coordination system construction.

### 4.3 Environmental Disruption Interpretation Rubric (EDIR)

| ED Score | Classification | Computational Guidance |
|----------|---------------|---------------------|
| 0-99     | Low Disruption | Contained, reversible, or minor disruption. Proceed with minimal resistance. |
| 100-299  | Medium Disruption | Moderate, localized, or complex disruption. Requires situational justification and proportional reasoning. |  
| 300+     | High Disruption | Irreversible, systemic, or severe disruption. Requires strong justification and heightened computational attention. |

**Primitive interface principle**: Environmental Disruption provides a standardized interface for coordination systems built on Sudelistic primitives. High ED scores indicate greater relational impact weight requiring computational attention, enabling interoperability between different coordination systems without value prescription.

### 4.4 Comparative Analysis Methodology

Sudelistic evaluation requires comparison of potential emergent relational outcomes rather than isolated action assessment. The four-step process:

1. **Scenario Construction**: Build GIC matrices for each decision pathway (e.g., act vs. refrain)
2. **Agent Identification**: Calculate ED scores for all affected agents according to contextually appropriate criteria
3. **Asymmetry Assessment**: Compare scenarios to identify which results in less irreversible or severe imposed change and determine burden distribution across agents
4. **Proportional Justification**: Evaluate whether the action proves relationally optimal in proportion to its environmental disruption

### 4.4.1 Universal Primitive Operations

The FR → GIC → ED primitive stack operates identically across all agent architectures, demonstrating foundational computational universality:

**Individual Entities**: Direct primitive operations where FR patterns, Δ disruptions, F embeddedness, and N propagation apply to single-agent systems with standard ED calculation.

**Distributed Systems**: Identical primitive operations across network components, where:
- FR computation occurs at each distributed node
- F primitive measures collective embeddedness across the FR network
- N primitive accounts for both internal FR propagation and external network effects
- Δ primitive measures disruption to distributed FR optimization processes

**Composite Organizations**: Layered primitive operations reflecting organizational structure:
- FR computation operates at both organizational and constituent levels
- F primitive measures institutional FR embeddedness and member FR dependencies
- N primitive captures hierarchical FR propagation through organizational layers
- Δ primitive reflects disruption across multi-level FR optimization systems

This demonstrates that identical primitive operations enable coordination across heterogeneous agent types, validating the foundational universality of Sudelistic computational infrastructure.

### 4.5 Implementation Standards

While institutions may define domain-specific weights for Δ, F, and N components according to professional standards and contextual requirements, interpretation of total ED scores must follow the standardized EDIR. This ensures semantic coherence across fields and geography, enabling relational coordination to scale without collapsing into relativism.

---

## 5. Implementation

Implementation requires continuous familiarity assessment, behavioral calibration based on relational feedback, and optimization for collective environmental stability. Individual entities monitor direct environmental impact, distributed systems coordinate across network nodes, and composite organizations integrate multi-stakeholder feedback into decision-making processes.

## 6. Technical Demonstration: Abortion Dynamics

To demonstrate GIC application on complex relational problems, we model abortion across fetal developmental stages with two initiation scenarios: mother-requested vs. hospital-mandated termination.

**Early Stage Abortion (≤12 weeks)**

*Mother initiates:*
- **Fetus ED**: Δ=10, F=2, N=2 → ED = 40 (Low Disruption)
- **Mother ED**: 0 (initiator principle)

*Hospital mandates:*
- **Fetus ED**: Δ=10, F=2, N=2 → ED = 40 (Low Disruption)  
- **Mother ED**: Δ=5, F=8, N=6 → ED = 240 (Medium Disruption)

**Late Stage Abortion (≥25 weeks)**

*Mother initiates:*
- **Fetus ED**: Δ=10, F=8, N=7 → ED = 560 (High Disruption)
- **Mother ED**: 0 (initiator principle)

*Hospital mandates:*
- **Fetus ED**: Δ=10, F=8, N=7 → ED = 560 (High Disruption)
- **Mother ED**: Δ=9, F=9, N=9 → ED = 729 (High Disruption)

**Key Findings:**
1. **Temporal scaling**: Fetal ED increases from 40 to 560 as developmental embeddedness grows
2. **Agency asymmetry**: Initiators receive ED=0; imposed agents bear full disruption cost  
3. **Multi-agent complexity**: Hospital mandates create high ED for both fetus and mother

Framework enables mathematical precision on culturally contentious relational problems without categorical prohibitions, demonstrating computational infrastructure where traditional approaches fail.

---

## 7. Sudelistic Environmental Scoring Systems (SESS)

SESS frameworks operationalize ED = Δ × F × N through institutional decision-making protocols. Implementation follows a four-phase protocol: (1) System Design with domain-specific ED component weighting, (2) Transparency Framework enabling stakeholder evaluation, (3) Operational Integration with real-time GIC calculation, (4) Continuous Calibration based on empirical outcomes.

---

## 8. Conclusion

We have proposed computational primitives for emotion and relational coordination. The system begins with individual emotional computation through familiarity ratio optimization (FR = F/(F+U)), then extends to relational coordination through environmental disruption measurement (ED = Δ × F × N). This provides mathematical infrastructure for emotion and coordination rather than external behavioral rules.

The primitives prove computationally tractable for agent alignment problems where traditional approaches fail due to non-stationary environments and multi-agent complexity. SESS implementations enable institutional decision-making with transparent relational forecasting, while maintaining semantic coherence across individual entities, distributed systems, and composite organizations.

Sudelism demonstrates that relational coordination need not be imposed from external authorities but can emerge from precise mathematical infrastructure for environmental dynamics. As long as agents prioritize environmental stability over single-agent optimization, the network remains relationally stable.

---

## References

[1] Russell, J. A. (1980). A circumplex model of affect. *Journal of Personality and Social Psychology*, 39(6), 1161-1178.

[2] Amodei, D., Olah, C., Steinhardt, J., Christiano, P., Schulman, J., & Mané, D. (2016). Concrete problems in AI safety. *arXiv preprint arXiv:1606.06565*.

[3] McCloskey, M., & Cohen, N. J. (1989). Catastrophic interference in connectionist networks. *Psychology of Learning and Motivation*, 24, 109-165.

---

#### Pronunciation Guide
* **IPA:** /ˈsuːdəl/  
* **Phonetic:** SUH-dell