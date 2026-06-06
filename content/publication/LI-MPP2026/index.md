---
title: 'On Termination of Polynomial Programs with Equality Conditions'
subtitle: ''

featured: true
draft: false

authors:
  - Yangjia Li  
  - Mingshuai Chen  
  - Liangran Zhao  
  - Naijun Zhan  
  - Hui Lu  
  - Guohua Wu  
  - Joost-Pieter Katoen
# author_notes:
#  - 'Equal contribution'
#  - 'Equal contribution'

#to be updated
date: '2026-05-04T00:00:00Z'
#date: '2015-09-01T00:00:00Z'
#lastmod: 2021-10-07T18:49:05-06:00

#to be updated
doi: '10.1016/j.ic.2026.105487'

# Schedule page publish date (NOT publication's date).
publishDate: '2017-01-01T00:00:00Z'

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ['2']

# Publication name and optional abbreviated publication name.
publication: '*Information and Computation*, XX'
publication_short: '*Inf. Comput.*'

abstract: We investigate the termination problem of a family of multi-path polynomial programs (MPPs) over a general field $\mathbb{K}$, in which all assignments to program variables are polynomials, and test conditions of loops and conditional statements are polynomial equalities. We show that the set of non-terminating inputs (NTI) of such a program is algorithmically computable, which in turn yields the decidability of its termination on a given input -- and that on a semi-algebraic set of inputs when $\mathbb{K}$ is $\mathbb{R}$. To the best of our knowledge, the considered family of MPPs is hitherto the largest fragment of nonlinear programs for which termination is decidable. We present an explicit recursive function, essentially of Ackermannian growth, to compute the maximal length of ascending chains of polynomial ideals under a control function, thereby providing a complete answer to the questions raised by Seidenberg in 1971. This maximal length facilitates a precise complexity analysis of our algorithms for computing the NTI and deciding termination of MPPs. We further extend our approach to programs with polynomial guarded commands and show how an incomplete procedure for MPPs with inequality guards can be obtained. Finally, we show that our decidability result gives rise to a complete method for computing all polynomial equality invariants (of a fixed degree) of polynomial programs.

tags:
  - termination
  - decidability
  - polynomial programs
  - uncertainty
  - Hilbert ascending chains

# Summary. An optional shortened abstract.
summary: ''

# links:
# - name: ""
#   url: ""
url_pdf: ''
url_code: 'https://github.com/Chenms404/MPPs'
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
