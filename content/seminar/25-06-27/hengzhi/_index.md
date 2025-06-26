---
title: Automated Verification of Monotonic Data Structure Traversals in C
date: 2025-06-27
publishDate: 2025-05-24
---

**Presenter**: {{% mention "Yucheng Wang" %}}

**Author**: Matthew Sotoudeh

**Abstract**: Bespoke data structure operations are common in real-world C code. We identify one common subclass, monotonic data structure traversals (MDSTs), that iterate monotonically through the structure. For example, strlen iterates from start to end of a character array until a null byte is found, and a binary search tree insert iterates from the tree root towards a leaf. We describe a new automated verification tool, Shrinker, to verify MDSTs written in C. Shrinker uses a new program analysis strategy called scapegoating size descent, which is designed to take advantage of the fact that many MDSTs produce very similar traces when executed on an input (e.g., some large list) as when executed on a 'shrunk' version of the input (e.g., the same list but with its first element deleted). We introduce a new benchmark set containing over one hundred instances proving correctness, equivalence, and memory safety properties of dozens of MDSTs found in major C codebases including Linux, NetBSD, OpenBSD, QEMU, Git, and Musl. Shrinker significantly increases the number of monotonic string and list traversals that can be verified vs. a portfolio of state-of-the-art tools.

**URL**: https://arxiv.org/abs/2505.18818