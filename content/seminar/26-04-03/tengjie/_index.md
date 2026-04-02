---
title: Dependency-Aware Specification Weakening and Multi-Agent Parallel Verification for C Programs
date: 2026-04-03
publishDate: 2026-04-02
---

**Presenter**: {{% mention "Tengjie Lin" %}}

**Abstract**: We present three complementary techniques for scalable LLM-driven C program verification. **Minimal Support Set (MSS)** captures mandatory and disjunctive dependency structures between specifications and verification targets, enabling precise cascade prediction — when a precondition is weakened, the system determines which targets remain safe, which must fail, and which need re-checking, without exhaustive re-verification. **Eva-Guided Precondition Weakening** addresses failing call-sites caused by over-constrained callee preconditions through a pipeline combining LLM-based decision, formal entailment verification bounded by abstract interpretation, and cascading recovery across the call graph. **Verdict** is a multi-agent runtime where each function is owned by a persistent LLM agent; agents publish monotonically versioned contracts to a shared registry, and a central orchestrator drives convergence by detecting version mismatches, invalidating stale dependents, and re-activating them until a global fixpoint is reached. Optimistic draft assumptions enable full parallelism, while targeted proof demands allow directed inter-agent collaboration. Together, MSS provides dependency analysis, weakening provides specification repair, and Verdict provides the parallel execution harness.
