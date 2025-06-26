---
title: Distributed SMT Solving Based on Dynamic Variable-Level Partitioning
date: 2025-06-27
publishDate: 2025-06-25
---

**Presenter**: {{% mention "Zhiyang Li" %}}

**Author**: Mengyu Zhao, Shaowei Cai, and Yuhang Qian

**Abstract**: Satisfiability Modulo Theories on arithmetic theories have significant applications in many important domains. Previous efforts have been mainly devoted to improving the techniques and heuristics in sequential SMT solvers. With the development of computing resources, a promising direction to boost performance is parallel and even distributed SMT solving. We explore this potential in a divide-and-conquer view and propose a novel dynamic parallel framework with variable-level partitioning. To the best of our knowledge, this is the first attempt to perform variable-level partitioning for arithmetic theories. Moreover, we enhance the interval constraint propagation algorithm, coordinate it with Boolean propagation, and integrate it into our variable-level partitioning strategy. Our partitioning algorithm effectively capitalizes on propagation information, enabling efficient formula simplification and search space pruning. We apply our method to three state-of-the-art SMT solvers, namely CVC5, OpenSMT2, and Z3, resulting in efficient parallel SMT solvers. Experiments are carried out on benchmarks of linear and nonlinear arithmetic over both real and integer variables, and our variable-level partitioning method shows substantial improvements over previous partitioning strategies and is particularly good at non-linear theories.

**URL**: https://link.springer.com/chapter/10.1007/978-3-031-65627-9_4