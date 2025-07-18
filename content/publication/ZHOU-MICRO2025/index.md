---
title: 'Vegapunk: Accurate and Fast Decoding for Quantum LDPC Codes with Online Hierarchical Algorithm and Sparse Accelerator'
subtitle: ''

featured: false
draft: false

authors:
  - Kaiwen Zhou
  - Liqiang Lu
  - Debin Xiang
  - Chenning Tao
  - Anbang Wu
  - Jingwen Leng
  - Fangxin Liu
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

abstract: "Quantum Low-Density Parity-Check (qLDPC) codes are a promising class of quantum error-correcting codes that exhibit constant-rate encoding and high error thresholds, thereby facilitating scalable fault-tolerant quantum computation. However, real-time decoding of qLDPC codes remains a significant challenge due to the high connectivity of their check matrices, which typically requires solving large-scale linear systems with sparse structures. In particular, off-the-shelf qLDPC decoders are often subject to a tradeoff between accuracy and latency, thus yielding no accurate and real-time decoding. This paper presents Vegapunk, a software-hardware co-design framework that enables real-time qLDPC decoding with high accuracy. To improve decoding accuracy, we design an offline decoupling strategy leveraging Satisfiability Modulo Theories (SMT) optimizations to mitigate quantum degeneracy; To enable fast decoding, we introduce an online hierarchical decoding algorithm employing a greedy strategy. Furthermore, we show that our SMT-optimized strategy suffices to produce decoupled matrices with maximized sparsity, thus admitting a dedicated accelerator to fully exploit the sparsity and parallelism to achieve real-time qLDPC decoding. Experimental results demonstrate that Vegapunk enables real-time decoding (< 1μs) for the Bivariate Bicycle (BB) code up to [[784,24,24]] while exhibiting logical error rates on par with the state-of-the-art decoder, e.g., BP+OSD."

tags:
  - quantum systems
  - quantum calibration
  - quantum error correction
  - qLDPC codes
  - real-time decoding
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
