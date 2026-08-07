---
title: 'Formal Specification of Linux eBPF Instruction Set Architecture in Sail'
subtitle: ''

featured: true
draft: false

authors:
  - Yazhou Tang
  - Shenghao Yuan
  - Jean-Pierre Talpin
  - Mingshuai Chen
# author_notes:
#  - 'Equal contribution'
#  - 'Equal contribution'

date: '2026-09-29T00:00:00Z'
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
publication: 'In *eBPF 2026*'
publication_short: 'In *eBPF 2026*'


abstract: 'eBPF has become a widely-used mechanism for extending the Linux kernel, and recent standardization efforts have produced the first draft of eBPF ISA standard. However, eBPF still lacks a formal reference specification with rigorous semantics. This paper presents a Sail formalization of Linux eBPF ISA based on Linux 7.1. The model covers all sequential instructions in the Linux eBPF. From the same Sail source, we generate a human-readable formal specification document and Rocq definitions, while we provide a handwritten Rocq driver with a CompCert-based memory adapter to execute the generated semantics.'

tags:
  - eBPF
  - Sail
  - Mechanized Semantics
  - Formal Specification
  - Linux Kernel

# Summary. An optional shortened abstract.
summary: ''

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
