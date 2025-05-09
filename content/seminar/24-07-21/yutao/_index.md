---
title: "Enhancing Static Analysis for Practical Bug Detection: An LLM-Integrated Approach"
date: 2024-07-21
---

**Presenter**: {{% mention "Yutao Sun" %}}

**Authors**: Haonan Li, Yu Hao, Yizhuo Zhai and Zhiyun Qian

**Abstract**: While static analysis is instrumental in uncovering software bugs, its precision in analyzing large and intricate codebases remains challenging. The emerging prowess of Large Language Models (LLMs) offers a promising avenue to address these complexities. In this paper, we present LLift, a pioneering framework that synergizes static analysis and LLMs, with a spotlight on identifying use-before-initialization (UBI) bugs within the Linux kernel. Drawing from our insights into variable usage conventions in Linux, we enhance path analysis using post-constraint guidance. This approach, combined with our methodically crafted procedures, empowers LLift to adeptly handle the challenges of bug-specific modeling, extensive codebases, and the unpredictable nature of LLMs. Our real-world evaluations identified four previously undiscovered UBI bugs in the mainstream Linux kernel, which the Linux community has acknowledged. This study reaffirms the potential of marrying static analysis with LLMs, setting a compelling direction for future research in this area.

**URL**: https://dl.acm.org/doi/10.1145/3649828
