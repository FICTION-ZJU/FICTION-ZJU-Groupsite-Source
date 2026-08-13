---
title: Image Generators are Generalist Vision Learners
date: 2026-08-14
publishDate: 2026-04-22
---

**Presenter**: {{% mention "Yutao Sun" %}}

**Author**: Valentin Gabeur, Shangbang Long, Songyou Peng, Paul Voigtlaender, Shuyang Sun, Yanan Bao, Karen Truong, Zhicheng Wang, Wenlei Zhou, Jonathan T. Barron, Kyle Genova, Nithish Kannen, Sherry Ben, Yandong Li, Mandy Guo, Suhas Yogin, Yiming Gu, Huizhong Chen, Oliver Wang, Saining Xie, Howard Zhou, Kaiming He, Thomas Funkhouser, Jean-Baptiste Alayrac, Radu Soricut

**Abstract**: We investigate whether large-scale image generators can also serve as general-purpose visual learners. The paper introduces Vision Banana, a generalist vision model obtained by lightweight instruction-tuning of Nano Banana Pro using its original generation data together with a small amount of vision-task data. By representing outputs for perception tasks directly as RGB images, tasks such as segmentation, depth estimation, and other 2D and 3D understanding problems can be reformulated as image generation. Vision Banana achieves state-of-the-art or competitive results across a broad range of visual understanding benchmarks, rivaling specialized models such as the Segment Anything and Depth Anything families, while largely preserving the original model's image-generation and editing capabilities. These results suggest that generative image pretraining can learn powerful, general visual representations, and that image generation may provide a unified interface for both visual generation and understanding.

**URL**: https://arxiv.org/pdf/2604.20329
