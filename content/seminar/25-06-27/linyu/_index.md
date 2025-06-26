---
title: Staged Specification Logic for Verifying Higher-Order Imperative Programs
date: 2025-06-27
publishDate: 2025-06-25
---

**Presenter**: {{% mention "Linyu Yang" %}}

**Author**: Darius Foo, Yahui Song, and Wei-Ngan Chin

**Abstract**: Higher-order functions and imperative states are language features supported by many mainstream languages. Their combination is expressive and useful, but complicates specification and reasoning, due to the use of yet-to-be-instantiated function parameters. One inherent limitation of existing specification mechanisms is its reliance on only two stages : an initial stage to denote the precondition at the start of the method and a final stage to capture the postcondition. Such two-stage specifications force abstract properties to be imposed on unknown function parameters, leading to less precise specifications for higher-order methods. To overcome this limitation, we introduce a novel extension to Hoare logic that supports multiple stages for a call-by-value higher-order language with ML-like local references. Multiple stages allow the behavior of unknown function-type parameters to be captured abstractly as uninterpreted relations; and can also model the repetitive behavior of each recursion as a separate stage. In this paper, we define our staged logic with its semantics, prove its soundness and develop a new automated higher-order verifier, called Heifer, for a core ML-like language.

**URL**: https://doi.org/10.1007/978-3-031-71162-6_26
