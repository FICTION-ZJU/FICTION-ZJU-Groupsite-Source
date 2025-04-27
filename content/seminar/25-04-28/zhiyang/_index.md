---
title: "Quantitative Supermartingale Certificates"
date: 2025-04-28
publishDate: 2025-04-27
---

**Presenter**: {{% mention "Zhiyang Li" %}}

**Authors**: Alessandro Abate, Mirco Giacobbe, Diptarko Roy

**Abstract**: We introduce a general methodology for quantitative model checking and control synthesis with supermartingale certificates. We show that every specification that is invariant to time shifts admits a stochastic invariant that bounds its probability from below; for systems with general state space, the stochastic invariant bounds this probability as closely as desired; for systems with finite state space, it quantifies it exactly. Our result enables the extension of every certificate for the almost-sure satisfaction of shift-invariant specifications to its quantitative counterpart, ensuring completeness up to an approximation in the general case and exactness in the finite-state case. This generalises and unifies existing supermartingale certificates for quantitative verification and control under reachability, safety, reach-avoidance, and stability specifications, as well as asymptotic bounds on accrued costs and rewards. Furthermore, our result provides the first supermartingale certificate for computing upper and lower bounds on the probability of satisfying ω-regular and linear temporal logic specifications. We present an algorithm for quantitative ω-regular verification and control synthesis based on our method and demonstrate its practical efficacy on several infinite-state examples.

**URL**: http://arxiv.org/abs/2504.05065
