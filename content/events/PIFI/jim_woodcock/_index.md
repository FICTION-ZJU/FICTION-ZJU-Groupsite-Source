---
title: "A bi-CKA True-Concurrency Semantics for Orc"
date: 2025-11-07
publishDate: 2025-10-29
---

**Speaker**: {{% mention "Jim Woodcock" %}}

**Abstract**: Orc is a lightweight orchestration language for composing distributed services, increasingly relevant to intelligent connected vehicles (ICVs), where coordination, latency, and failure handling demand rigorous reasoning about true concurrency. This talk proposes a semantics for Orc based on bi-Concurrent Kleene Algebra (bi-CKA) interpreted over pomsets (partial-order models of events). The algebra provides parallel (‖), sequencing (·), algebraic choice (+), (sequential) Kleene star (∗), and the exchange law, enabling compositional proofs that respect causal independence rather than interleavings. We provide denotations for the structural core (parallel, run-after/then, and atomic site calls), while publication-dependent combinators (bind, otherwise, and pruning) are specified operationally. We also demonstrate how modest algebraic enrichment (tests and preemption) yields a fully denotational treatment. On ICV scenarios (e.g., safe single-lane bridge crossing), the exchange law justifies refactoring parallel-then-sequentialpatterns into parallel pipelines, aiding optimisation and safety and liveness arguments. The framework cleanly isolates advisory LLM sidecar components, ensuring that adding human-facing explanations cannot compromise the verified plan’s behaviour, thereby supporting an auditable safety case. We outline links to Institutions and UTP, as well as a path to mechanisation in Lean. Overall, bi-CKA over pomsets supplies a mathematically transparent, true-concurrency backbone for Orc that scales to realistic orchestration tasks in safety-critical autonomy.
