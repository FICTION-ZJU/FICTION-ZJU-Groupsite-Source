---
title: 'On the Almost-Sure Termination of Probabilistic Counter Programs'
subtitle: ''

featured: true
draft: false

authors:
    - Sergei Novozhilov
    - Mingqi Yang
    - Mingshuai Chen
    - Zhiyang Li
    - Jianwei Yin
author_notes:
    - 'equal contribution'
    - 'equal contribution'

date: '2025-07-21T00:00:00Z'
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
publication: In *CAV 2025*
publication_short: In *CAV 2025*

abstract: This paper introduces $k$-d PCPs -- the class of *probabilistic counter programs* with $k \in \mathbb{N}$ counter variables inducing possibly infinite-state Markov chains. We show that the universal (positive) almost-sure termination problem is *undecidable* for $k$-d PCPs in general, yet *decidable* for $1$-d PCPs. We present an efficient decision procedure for the latter leveraging the technique of *Markov chain finitization*. Moreover, we identify several classes of $k$-d PCPs that are reducible to $1$-d PCPs -- thus their termination properties can be inferred automatically. Experiments demonstrate that our decision procedure can certify (positive) almost-sure termination -- without resorting to invariants or supermartingales -- of non-trivial probabilistic programs beyond the scope of existing tools.

tags:
  - probabilistic programs
  - quantitative reasoning
  - verification
  - termination
  - Markov models
  - equation systems
  - decidability
  - reachability
  - uncertainty

# Summary. An optional shortened abstract.
summary: ''

links:
  - icon_pack: fas
    icon: stamp
    name: "Artifact Evaluated"
    url: "https://github.com/FICTION-ZJU/Pastry"
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
