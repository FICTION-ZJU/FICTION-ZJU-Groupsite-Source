---
title: 'Fill the GAP: A Granular Alignment Paradigm for Visual Reasoning in Multimodal Large Language Models'
subtitle: ''

featured: false
draft: false

authors:
  - Yanting Miao
  - Yutao Sun
  - Dexin Wang
  - Mengyu Zhou
  - Pascal Poupart
  - Lei Lv
  - Qi Zhao
  - Li Wang
  - Hao Li
  - Xiaoxi Jiang
  - Guanjun Jiang

date: '2026-05-12T00:00:00Z'

doi: ''

# Schedule page publish date (NOT publication's date).
publishDate: '2017-01-01T00:00:00Z'

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ['3']

# Publication name and optional abbreviated publication name.
publication: '*arXiv preprint*'
publication_short: '*arXiv*'

abstract: "Visual latent reasoning lets a multimodal large language model (MLLM) create intermediate visual evidence as continuous tokens, avoiding external tools or image generators. However, existing methods usually follow an output-as-input latent paradigm and yield unstable gains. We identify evidence for a feature-space mismatch that can contribute to this instability: dominant visual-latent models build on pre-norm MLLMs and reuse decoder hidden states as predicted latent inputs, even though these states occupy a substantially different norm regime from the input embeddings the model was trained to consume (Xie et al., 2025; Li et al., 2026; Team et al., 2026). This mismatch can make direct latent feedback unreliable. Motivated by this diagnosis, we propose GAP, a Granular Alignment Paradigm for visual latent modeling. GAP aligns visual latent reasoning at three levels: feature-level alignment maps decoder outputs into input-compatible visual latents through a lightweight PCA-aligned latent head; context-level alignment grounds latent targets with inspectable auxiliary visual supervision; and capacity-guided alignment assigns latent supervision selectively to examples where the base MLLM struggles. On Qwen2.5-VL 7B, the resulting model achieves the best mean aggregate perception and reasoning performance among our supervised variants. Inference-time intervention probing further suggests that generated latents provide task-relevant visual signal beyond merely adding token slots."

tags:
  - multimodal large language models
  - visual reasoning
  - visual latent reasoning
  - alignment
  - large language models

# Summary. An optional shortened abstract.
summary: ''

url_pdf: '/papers/GAP2026.pdf'
url_code: ''
url_dataset: ''
url_poster: ''
url_project: ''
url_slides: ''
url_source: 'https://arxiv.org/abs/2605.12374'
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
