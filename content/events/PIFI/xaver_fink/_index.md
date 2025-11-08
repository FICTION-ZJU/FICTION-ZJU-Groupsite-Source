---
title: "Neural Network Robustness Verification for Control Systems at CERN"
date: 2025-11-07
publishDate: 2025-10-29
---

**Speaker**: {{% mention "Xaver Fink" %}}

**Abstract**: CERN increasingly relies on AI-driven components to operate and protect safety-critical accelerator infrastructure, from beam steering and alignment to fault detection in accelerator control systems. Many of these components are neural networks, which are powerful but brittle: small, structured perturbations to sensor inputs can trigger incorrect control decisions. First, we outline where neural networks are being considered in CERN control systems and motivate robustness to adversarial inputs. We then present a concrete case study from LHC crystal collimator alignment, where a time-series classifier is analyzed under realistic, correlated noise. We show how robustness can be assessed by inserting a differentiable reparameterization layer that captures both noise and process model, and we introduce the notion of adversarial sequences for sliding-window time-series classification. We demonstrate that gradient-based attacks are successful in inducing such sequences. Beyond this, we give a short overview of our recent research into data-driven verification methods, where machine learning is used to guide neural network verification via branch-and-bound and bound propagation.

**Bio**: Xaver Fink is a PhD student in the Software Modeling and Verification group at RWTH Aachen University and part of the CERN doctoral student programme. Prior to this, he worked on programmable logic controller (PLC) program verification via model checking as part of the CERN Fellowship program. His current research focuses on formal methods for the analysis, verification, and certification of neural networks in control systems and control-related applications.
