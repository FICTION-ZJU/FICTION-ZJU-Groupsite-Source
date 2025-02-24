---
title: "Causation Monitoring of Signal Temporal Logic and Its Application to Reinforcement Learning"
date: 2025-02-26
---


**Presenter**: {{% mention "Jie An" %}}

**Abstract**: Online monitoring is an effective validation approach for hybrid systems, that, at runtime, checks whether the (partial) signals of a system satisfy a specification in, e.g., Signal Temporal Logic (STL). The classic STL monitoring is performed by computing a robustness interval that specifies, at each instant, how far the monitored signals are from violating and satisfying the specification. However, since a robustness interval monotonically shrinks during monitoring, classic online monitors may fail in reporting new violations or in precisely describing the system evolution at the current instant.
In this talk, we introduce our recent works on tackling these issues by considering the causation of violation or satisfaction, instead of directly using the robustness. A Boolean causation monitor decides whether each instant is relevant to the violation or satisfaction of the specification, and it can be extended to a quantitative causation monitor that tells how far an instant is from being relevant to the violation or satisfaction. We further show that classic robust monitors can be derived from our proposed ones.  Experimental results show that the two proposed monitors provide more detailed information about system evolution, without requiring a significantly higher monitoring cost. At last, we will show its application to reinforcement learning (RL), and the experimental results show that our proposed causation-guided RL method outperforms existing STL-guided RL methods, providing a more robust and efficient reward generation framework for deep-RL.

**Speaker**: Jie An, National Key Laboratory of Space Integrated Information System, Institute of Software, Chinese Academy of Sciences

**Bio**: Dr. Jie An is an Associate Research Professor at the Institute of Software, Chinese Academy of Sciences, Beijing, China. From 2022 to 2024, he was a Project Researcher and later a Project Assistant Professor at the National Institute of Informatics (NII), Tokyo, Japan. From 2020 to 2022, he was a Postdoctoral Researcher at the Max Planck Institute for Software Systems (MPI-SWS), Kaiserslautern, Germany. His research interests lie in formal methods, focusing on applying formal methods and machine learning to intelligent Cyber-Physical Systems (CPS) to ensure their functionality, robustness, reliability, safety, privacy, security, etc. His research is supported by the NSFC Excellent Young Scientists Fund Program (Overseas), the Chinese Academy of Sciences Pioneer Hundred Talents Program, etc. He has published numerous peer-reviewed papers at the top conferences and flagship journals including CAV, FM, EMSOFT, HSCC, IEEE TCAD, ACM TECS, etc.

**Link to paper**:
- CAV2023: https://link.springer.com/chapter/10.1007/978-3-031-37706-8_4
- CAV2024: https://link.springer.com/chapter/10.1007/978-3-031-71177-0_18
