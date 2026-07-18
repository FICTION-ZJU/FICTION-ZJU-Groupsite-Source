---
title: 'Tolerant Barrier Certificates for Stochastic Systems'
subtitle: ''

featured: false
draft: false

authors:
  - Shenghua Feng
  - Han Su
  - Hao Wu
  - Jie An
  - Mingshuai Chen
  - Naijun Zhan
# author_notes:
#  - 'Equal contribution'
#  - 'Equal contribution'

date: '2026-10-04T00:00:00Z'
#lastmod: 2021-10-07T18:49:05-06:00

#TODO
doi: ''

# Schedule page publish date (NOT publication's date).
publishDate: '2017-01-01T00:00:00Z'

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ['2']

# Publication name and optional abbreviated publication name.
publication: '*IEEE Transactions on Computer-Aided Design of Integrated Circuits and Systems*, XX(X)'
publication_short: '*IEEE Trans. Comput. Aided Des. Integr. Circuits Syst.*'

abstract: "We study stochastic verification under tolerant specifications, where unsafe behavior is allowed as long as the total unsafe exposure remains below a prescribed budget with high probability. In discrete time, unsafe exposure is the number of visits to an unsafe set; in continuous time, it is the occupation time spent there. We introduce tolerant barrier certificates, whose key idea is to force the barrier to decrease more aggressively whenever the state is unsafe, so that the barrier compensates for the unsafe exposure accumulated along the trajectory. This construction yields supermartingale-based upper bounds on the probability that the unsafe-exposure budget is exceeded, for both tolerant safety and tolerant reach-avoid properties. We investigate both discrete-time stochastic systems and stochastic differential dynamics, and demonstrate the effectiveness of our approach on a collection of benchmarks."

tags:
  - differential dynamics
  - stochastic systems
  - barrier certificates
  - safety
  - reach-avoid
  - verification
  - supermartingales
  - semidefinite programming
  - uncertainty

# Summary. An optional shortened abstract.
summary: ''

# links:
# - name: ""
#   url: ""
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
