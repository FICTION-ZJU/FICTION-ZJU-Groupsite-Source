---
title: 'Verdict: Multi-Agent Parallel Modular Verification'
subtitle: ''

featured: true
draft: false

authors:
  - Tengjie Lin
  - Zhongyi Wang
  - Haokun Li
  - Jianwei Yin
  - Mingshuai Chen
# author_notes:
#  - 'Equal contribution'
#  - 'Equal contribution'

date: '2027-04-25T00:00:00Z'
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
publication: In *ICSE 2027*
publication_short: In *ICSE 2027*

abstract: 'Deductive verification scales to large software systems through *modular reasoning*, where formal contracts summarize the behavior of individual functions and enable their independent verification. Its central bottleneck is *specification synthesis*: constructing the contracts required for modular verification. Recent advances in large language models (LLMs) have enabled automated specification synthesis at unprecedented scale. However, existing approaches remain fundamentally *bottom-up*, requiring callees to be verified before their callers. This dependency limits parallelism and provides no principled mechanism for resolving interprocedural inconsistencies that propagate across call chains. We present <span style="font-variant:small-caps;">Verdict</span>, a multi-agent framework for parallelizing modular deductive verification of large-scale programs. <span style="font-variant:small-caps;">Verdict</span> is built on two key principles. First, *assumption-based parallel specification synthesis* assigns an agent to each function and allows it to proceed immediately using assumed contracts for its callees, enabling verification to proceed in parallel across the program. Second, *bidirectional interprocedural conflict reconciliation* resolves the inconsistencies introduced by these assumptions: when a synthesized contract contradicts an assumption, agents propagate the necessary revisions both up and down the call graph until the contracts converge. Experimental results on real-world C programs show that <span style="font-variant:small-caps;">Verdict</span> synthesizes higher-quality specifications than existing approaches while substantially reducing verification time. In particular, <span style="font-variant:small-caps;">Verdict</span> is the first approach that scales to the complete 20,000-line X.509 parser, ruling out nearly all the potential runtime errors within hours, whereas prior tools like <span style="font-variant:small-caps;">Preguss</span> fall far short even after days of execution.'

tags:
  - program verification
  - specification synthesis
  - deductive verification
  - large language models
  - multi-agent systems

# Summary. An optional shortened abstract.
summary: ''

links:
  - name: arXiv
    url: https://arxiv.org/abs/2610.29147
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
