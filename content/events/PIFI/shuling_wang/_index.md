---
title: "Integrating Symbolic Execution with LLMs for Automated Generation of Program Specifications"
date: 2025-11-07
publishDate: 2025-10-29
---

**Speaker**: {{% mention "Shuling Wang" %}}

**Abstract**: Automatically generating formal specifications including loop invariants, preconditions, and postconditions for legacy code is critical for program understanding, reuse and verification. However, the complexity of control and data structures in programs makes this task particularly challenging. In this paper, we propose a novel framework that combines symbolic execution with large language models (LLMs) to automatically generate formally verified specifications. Our method uses symbolic execution to compute strongest postconditions for loop-free code segments. These results, along with carefully designed invariant templates, are used to guide LLMs in synthesizing and refining loop invariants. The process iterates until a complete program specification is achieved. A key contribution of our approach is its general applicability to effectively handle diverse types of programs. Notably, our approach remains effective even in the absence of explicit verification goals, required by many existing work to guarantee the accuracy of the generated specifications. We have conducted an extensive empirical evaluation, demonstrating that our approach outperforms state-of-the-art tools across both numerical and data structure benchmarks.
