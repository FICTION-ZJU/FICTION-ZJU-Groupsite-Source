---
title: "Derivative-Agnostic Inference of Nonlinear Hybrid Systems"
date: 2025-11-07
publishDate: 2025-10-29
---

**Speaker**: {{% mention "Mingshuai Chen" %}}

**Abstract**: This talk addresses the problem of inferring a hybrid automaton from a set of input-output traces of a hybrid system exhibiting discrete mode switching between continuously evolving dynamics. Existing approaches mainly adopt a derivative-based method where (i) the occurrence of mode switching is determined by a drastic variation in derivatives and (ii) the clustering of trace segments relies on signal similarity -- both subject to user-supplied thresholds. In this talk, I present a derivative-agnostic approach, named Dainarx, to infer nonlinear hybrid systems where the dynamics are captured by nonlinear autoregressive exogenous (NARX) models. Dainarx employs NARX models as a unified, threshold-free representation through the detection of mode switching and trace-segment clustering. We show that Dainarx suffices to learn models that closely approximate a general class of hybrid systems featuring high-order nonlinear dynamics with exogenous inputs, nonlinear guard conditions, and linear resets. Experimental results on a collection of benchmarks indicate that our approach can effectively and efficiently infer nontrivial hybrid automata with high-order dynamics yielding significantly more accurate approximations than state-of-the-art techniques.
