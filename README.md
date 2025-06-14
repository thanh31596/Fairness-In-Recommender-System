

## Research Problem

Modern recommender systems often serve multiple stakeholders – for example, consumers, content providers, and the platform itself – raising complex fairness challenges. Ensuring fair outcomes is difficult because *multi-stakeholder fairness* must balance competing interests (e.g. user satisfaction vs. provider exposure).  Current fairness solutions typically rely on multi-objective optimization and algorithmic adjustments that yield improved fairness metrics (e.g. Pareto-efficient trade-offs between user relevance and provider exposure). However, these approaches assume simplified, static models of stakeholder behavior (fixed utility functions, rational actors) and thus may **fail to capture real-world behavioral dynamics**. In practice, users’ preferences evolve over time, providers may adapt or “game” the system, and information asymmetries abound – all of which can lead to *fairness violations* (situations where one group is systematically disadvantaged) that are not apparent from static analyses. There is a critical gap in our understanding of **how stakeholder behaviors and interactions give rise to fairness issues** in recommender systems.

Recent advances in *generative agents* – AI-driven agents powered by large language models that simulate believable human-like behavior – offer a promising new approach to studying these phenomena. Unlike traditional simulations with fixed rules, generative agents can maintain memory, learn, and interact in nuanced ways, mirroring the inconsistencies and adaptability of real stakeholders. This opens the door to using **simulation as a tool for foundational fairness research**: we can create sandbox recommender environments where realistic agent stakeholders (users, providers, etc.) interact, and observe when and how fairness issues emerge. By focusing on *behavioral patterns and fairness outcomes* in these simulations, we can gain deeper insight into questions like: When do certain algorithms inadvertently favor one group of providers? How do users respond to perceived unfairness in recommendations? And what unintended consequences might arise from interventions meant to improve fairness? Addressing these questions is the core problem of this research – **the lack of a nuanced, behaviorally grounded understanding of fairness dynamics in multi-stakeholder recommender systems, and how generative agent simulations can be used to uncover and analyze fairness violations**.

## Research Objective

**Objective:** To develop and utilize a generative agent-based simulation framework for multi-stakeholder recommender systems in order to explore and understand fairness dynamics and violations. This entails creating realistic simulated stakeholders (consumers, content providers, and platform agents) and analyzing their interactions to yield *foundational insights into fairness* – insights about how and why unfair outcomes arise, persist, or can be mitigated. Crucially, the aim is **not** to optimize the recommender system’s accuracy or directly design a new fairness algorithm, but rather to *evaluate fairness-related behaviors and outcomes*. By observing emergent patterns (e.g. preference shifts, strategic behavior, conflict negotiation) in a controlled simulation, the research seeks to explain fairness trade-offs and identify potential points of intervention from a more human-centered perspective. Ultimately, this objective supports a deeper theoretical understanding of fairness in recommender systems – informing future system designs and policies – without being driven by immediate performance gains.

## Research Questions

To accomplish the above goal, the study will address several key research questions (RQs) about behavioral dynamics and fairness in a multi-stakeholder recommender context. Each question focuses on using **generative agents as a simulation tool** to probe different aspects of fairness:

1. **What behavioral patterns emerge among simulated stakeholders, and how do these lead to fairness issues or violations in the recommender system?**
   *Rationale:* This question focuses on observation and analysis: given a realistic multi-agent simulation, what kinds of behaviors do we see, and which of those behaviors correlate with unfair outcomes? The aim is to identify specific *fairness-related dynamics*. For instance:

   * Do **user preference changes** (such as the formation of filter bubbles or echo chambers) amplify inequality in exposure or relevance across content providers?
   * Does **strategic behavior by providers** (e.g. content creators adapting or “gaming” their content to the algorithm) result in certain groups of providers unfairly dominating recommendations?
   * How do **multi-role interactions** (e.g. a user who is also a creator balancing personal content curation vs. public visibility) produce new fairness trade-offs?
   * What is the effect of **information asymmetry** (one stakeholder having more knowledge about the system than others) on fair outcomes?
     By answering RQ2, we expect to catalog a range of emergent phenomena – such as *preference drift, social contagion of choices, competitive provider behavior,* or *provider–platform conflicts* – and explicitly link them to fairness metrics or violations. This will reveal **which fairness issues are inherently driven by stakeholder behavior**, complementing the static view provided by traditional metrics.


2. How can generative agent simulations model realistic negotiation processes between stakeholders with asymmetric information, and what do these simulations reveal about effective communication protocols or mediation mechanisms for resolving fairness conflicts?


