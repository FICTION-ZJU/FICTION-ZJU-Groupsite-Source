---
title: "Runtime Error Assertion Guided Verification"
date: 2025-02-26
publishDate: 2025-02-24
---


**Presenter**: {{% mention "Zhongyi Wang" %}}

**Abstract**: Formal verification offers a rigorous approach to ensuring the correctness and reliability of software systems. However, constructing full specifications for verification requires domain expertise and considerable effort. A key challenge is that target programs are typically assumed to be free of run-time errors (RTEs) caused by undefined C behaviors, otherwise it's impossible to specify these behaviors correctly. Abstract interpretation-based static analyzers aim to guarantee the absence of RTEs, but their inherent over-approximation leads to precision loss, thus producing numerous false positives. Although eliminating these false alarms is challenging, they can guide LLM agents or traditional verifiers in generating appropriate specifications, aiding provers either confirm that a program is free of undefined behaviors or locate the real RTEs.

