---
title: 'Derivative-Agnostic Inference of Nonlinear Hybrid Systems'
subtitle: ''

featured: true
draft: false

authors:
  - Hengzhi Yu
  - Bohan Ma
  - Mingshuai Chen
  - Huangying Dong
  - Jie An
  - Bin Gu
  - Naijun Zhan
  - Jianwei Yin
author_notes:
  - 'equal contribution'
  - 'equal contribution'

date: '2026-05-11T00:00:00Z'
#lastmod: 2021-10-07T18:49:05-06:00

# TODO
doi: ''

# Schedule page publish date (NOT publication's date).
publishDate: '2017-01-01T00:00:00Z'

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ['1']

# Publication name and optional abbreviated publication name.
publication: In *HSCC 2026*
publication_short: In *HSCC 2026*


abstract: 'This paper addresses the problem of inferring hybrid automata from input-output traces of hybrid systems exhibiting discrete mode switches between continuously evolving dynamics. Existing approaches primarily rely on derivative-based strategies in which (i) mode switches are detected by drastic variations in derivatives and (ii) trace segments are clustered based on signal similarity -- both requiring user-supplied thresholds. We present a derivative-agnostic approach, named <span style="font-variant:small-caps;">Dainarx</span>, for inferring nonlinear hybrid systems whose dynamics are captured by nonlinear autoregressive exogenous (NARX) models. <span style="font-variant:small-caps;">Dainarx</span> employs NARX models as a unified, threshold-free representation for both mode switching and segment clustering. We show that <span style="font-variant:small-caps;">Dainarx</span> suffices to learn models that closely approximate a general class of hybrid systems featuring high-order nonlinear dynamics with exogenous inputs, nonlinear guard conditions, linear resets, and noise. Experimental results on a collection of benchmarks demonstrate that our approach effectively and efficiently infers nontrivial hybrid automata with high-order dynamics, yielding significantly more accurate approximations than state-of-the-art techniques, while achieving robustness comparable to approaches dedicated to fitting noisy data.'

tags:
  - hybrid systems
  - hybrid automata
  - system identification
  - automata learning
  - nonlinear dynamics
  - differential dynamics
  - learnability
  - synthesis


# Summary. An optional shortened abstract.
summary: ''

url_pdf: ''
url_code: ''
url_dataset: ''
url_poster: ''
url_project: ''
url_slides: '/slides/Dainarx.pdf'
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
