---
title: Robust Identification of Hybrid Automata from Noisy Data
date: 2025-06-27
publishDate: 2025-05-21
---

**Presenter**: {{% mention "Hengzhi Yu" %}}

**Author**: Niklas Kochdumper, Mohammed Aristide Foughali, Peter Habermehl, and Eugene Asarin

**Abstract**: In recent years, many different methods for identifying hybrid automata from data have been proposed. However, most of these methods consider clean simulator data, and consequently do not perform well for noisy data measured from real systems. We address this shortcoming with a new approach for the identification of hybrid automata that is specifically designed to be robust to noise. In particular, we propose a new high-level strategy consisting of the following three steps: clustering based on the dynamics identified from a local dataset, state space partitioning using decision trees, and conversion of the decision tree to a hybrid automaton. In addition, we introduce several new concepts for the realization of the single steps. For example, we propose an automated regularization of the dynamic models used for clustering via rank adaption, as well as a new variant of the Gini impurity index for decision tree learning, tailored toward hybrid systems where different dynamics can be active within the same state space region. As our experiments on 19 challenging benchmarks with different characteristics demonstrate, in addition to being robust to both process and measurement noise, our approach avoids the need for extensive hyper-parameter tuning and also performs well for clean data without noise.

**URL**: https://doi.org/10.1145/3716863.3718030