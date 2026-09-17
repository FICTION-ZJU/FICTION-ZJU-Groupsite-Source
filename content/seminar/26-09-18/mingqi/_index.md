---
title: Exact Inference for posterior measures of Probabilistic Loops
date: 2026-09-19
publishDate: 2026-09-16
---

**Presenter**: {{% mention "Mingqi Yang" %}}

**Author**: Mingqi Yang, Bohan Ma, Mingshuai Chen

**Abstract**: Exact inference for probabilistic loops is challenging in the presence of unbounded executions and infinite state spaces. Recent occupation-measure-based approaches synthesize rational closed-form candidates, but their certification relies on establishing coefficientwise nonnegativity. Deciding this property remains open in general, and existing implementations rely on sufficient positivity heuristics. We present an exact-inference method that avoids positivity checking. We extend occupation-measure semantics to signed power series of finite total variation and prove that every fixed point yields the exact posterior when restricted to exit states, even if the candidate has negative coefficients. For rational candidates, a decidable zero-freeness test for the reduced denominator on the closed unit polydisc guarantees finite total variation. This yields a sound proof rule that is relatively complete for positively almost-surely terminating loops whose occupation measures admit rational closed forms. If the loop terminates almost surely from every state, it additionally identifies the exact occupation measure. We integrate this rule into a template-based inference procedure for rectangular discrete probabilistic programs, extending occupation-invariant synthesis to support constant assignments.
