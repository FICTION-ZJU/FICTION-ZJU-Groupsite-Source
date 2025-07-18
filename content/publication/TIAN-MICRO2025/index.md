---
title: 'YOUTIAO: Hybrid Multiplexing with Dynamic Qubit Grouping for Low-cost and Scalable Quantum Wiring'
subtitle: ''

featured: false
draft: false

authors:
  - Wuwei Tian
  - Liqiang Lu
  - Siwei Tan
  - Shiyu Li
  - Hengyi Li
  - Tianyao Chu
  - Xuhong Zhang
  - Mingshuai Chen
  - Jianwei Yin
# author_notes:
#  - 'Equal contribution'
#  - 'Equal contribution'

date: '2025-07-15T00:00:00Z'
#lastmod: 2021-10-07T18:49:05-06:00

doi: ''

# Schedule page publish date (NOT publication's date).
publishDate: '2017-01-01T00:00:00Z'

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ['1']

# Publication name and optional abbreviated publication name.
publication: In *MICRO 2025*
publication_short: In *MICRO 2025*

abstract: "With continuous advances in physical technology, the number of qubits has increased from just a few to several thousand. To further extend the scale, the density of control lines has become one of the major limitations that decide the cost, heat dissipation, and fidelity. Specifically, each qubit requires dedicated control lines to manipulate its state, but these lines introduce additional thermal noise, degrading overall computational fidelity. Inspired from colinear signal transmission, a promising solution is to adopt multiplexing methods—such as frequency-division multiplexing (FDM) and time-division multiplexing (TDM)—to share control lines among qubits. However, existing methods lack a systematic architectural approach to support multiplexing-aware wiring, which leads to low parallelism and high crosstalk during deployment. In this work, we propose a multiplexing-aware design for the peripheral control lines of quantum processors, combining cryostat-level wiring optimization with on-chip routing. Our key novelty lies in a hybrid multiplexing architecture that adopts FDM for XY control and readout lines, and TDM for Z control lines. This enables high utilization of natural non-parallel operations, thereby cutting the additional circuit depth for TDM control. Finally, we develop an interaction model that co-optimizes qubit layout and multiplexed channel allocation. Our experiments are conducted on a self-developed quantum platform with 6x6 Xmon qubits. The results show that YOUTIAO achieves a 67.7% reduction in cryostat-level wiring complexity and overall superconducting quantum system costs, while reducing on-chip routing area by 23%. With these improvements, we still keep the 1q-gate fidelity at 99.98%, and only introduce 5% extra latency compared to the non-multiplexing system."

tags:
  - quantum systems
  - quantum wiring systems
  - signal multiplexing
  - uncertainty

# Summary. An optional shortened abstract.
summary: ''

# links:
#   - icon_pack: fas
#     icon: stamp
#     name: "Artifact Evaluated"
#     url: "https://github.com/LKlinke/Prodigy"
url_pdf: ''
url_code: ''
url_dataset: ''
url_poster: ''
url_project: ''
url_slides: ''
url_source: ''
url_video: ''

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
# Focal points: Smart, Center, TopLeft, Top, TopRight, Left, Right, BottomLeft, Bottom, BottomRight.
image:
  caption: ''
  focal_point: ''
  preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
projects: []

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
slides:
---

<!-- {{% callout note %}}
Click the _Cite_ button above to demo the feature to enable visitors to import publication metadata into their reference management software.
{{% /callout %}} -->
