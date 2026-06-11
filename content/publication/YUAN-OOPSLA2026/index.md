---
title: 'Formalizing the Linux eBPF Core ISA: A Mechanized Operational Semantics and Its Real-World Applications'
subtitle: ''

featured: true
draft: false

authors:
  - Shenghao Yuan
  - Yazhou Tang
  - Tianci Cao
  - Frederic Besson
  - Jean-Pierre Talpin
  - Mingshuai Chen
author_notes:
  - 'equal contribution'
  - 'equal contribution'

date: '2026-10-03T00:00:00Z'
#lastmod: 2021-10-07T18:49:05-06:00

doi: ''

# Schedule page publish date (NOT publication's date).
publishDate: '2017-01-01T00:00:00Z'

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ['2']

# Publication name and optional abbreviated publication name.
publication: '*Proc. ACM Program. Lang., X(OOPSLA2)*'
publication_short: '*Proc. ACM Program. Lang. (OOPSLA)*'


abstract: 'This paper presents a mechanized formal semantics for the Linux eBPF instruction set architecture (ISA). We develop a small-step semantics in Rocq that faithfully formalizes all 160 sequential in-kernel instructions of the eBPF ISA. The semantics is fully executable and has been validated against the official Linux eBPF test suite. This extensive testing revealed inconsistencies in our original formalization. Using this semantics, we have designed, implemented, and verified the soundness of the bit-level abstract domain employed by the Linux eBPF verifier. Our semantics also complements the existing Linux eBPF documentation by providing a rigorous formal specification. During the formalization process, we have discovered previously unknown bugs in the Linux eBPF implementation, and developed new verifier optimizations; all of these changes have been upstreamed to the latest version of the Linux kernel.'

tags:
  - eBPF
  - verification
  - mechanized semantics
  - abstract interpretation

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
