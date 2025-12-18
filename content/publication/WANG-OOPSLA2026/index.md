---
title: 'A Tale of 1001 LoC: Potential Runtime Error-Guided Specification Synthesis for Verifying Large-Scale Programs'
subtitle: ''

featured: true
draft: false

authors:
  - Zhongyi Wang
  - Tengjie Lin
  - Mingshuai Chen
  - Haokun Li
  - Mingqi Yang
  - Xiao Yi
  - Shengchao Qin
  - Yixing Luo
  - Xiaofeng Li
  - Bin Gu
  - Liqiang Lu
  - Jianwei Yin
author_notes:
  - 'equal contribution'
  - 'equal contribution'

date: '2026-10-XXT00:00:00Z'
#lastmod: 2021-10-07T18:49:05-06:00

doi: 'XX.XXXX/XXXXXXX.XXXXXXX'

# Schedule page publish date (NOT publication's date).
publishDate: '2017-01-01T00:00:00Z'

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ['1']

# Publication name and optional abbreviated publication name.
publication: In *OOPSLA 2026*
publication_short: In *OOPSLA 2026*


abstract: Fully automated verification of large-scale software and hardware systems is arguably the holy grail of formal methods. Large language models (LLMs) have recently demonstrated their potential for enhancing the degree of automation in formal verification by, e.g., generating formal specifications as essential to deductive verification, yet exhibit poor scalability due to context-length limitations and, more importantly, the difficulty of inferring complex, interprocedural specifications. This paper presents <span style="font-variant:small-caps;">Preguss</span> -- a modular, fine-grained framework for automating the generation and refinement of formal specifications. <span style="font-variant:small-caps;">Preguss</span> synergizes between static analysis and deductive verification by steering two components in a divide-and-conquer fashion: (i) potential runtime error-guided construction and prioritization of verification units, and (ii) LLM-aided synthesis of interprocedural specifications at the unit level. We show that <span style="font-variant:small-caps;">Preguss</span> substantially outperforms state-of-the-art LLM-based approaches and, in particular, it enables highly automated RTE-freeness verification for real-world programs with over a thousand LoC, with a reduction of 80.6\%$\sim$88.9\% human verification effort.
tags:
  - abstract interpretation
  - large language models
  - minimal contract
  - undefined behaviors

# Summary. An optional shortened abstract.
summary: ''

url_pdf: '/papers/OOPSLA2026.pdf'
url_code: 'https://zenodo.org/records/17296158'
url_dataset: 'https://zenodo.org/records/17296158'
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
