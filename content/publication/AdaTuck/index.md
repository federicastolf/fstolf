---
title: 'Bayesian adaptive Tucker decompositions for tensor factorization'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - admin
  - Antonio Canale

date: '2025-05-16T00:00:00Z'
doi: ''

# Schedule page publish date (NOT publication's date).
publishDate: '2017-01-01T00:00:00Z'

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ['2']

# Publication name and optional abbreviated publication name.
publication: "Journal of Computational and Graphical Statistics"
publication_short: "Journal of Computational and Graphical Statistics"

abstract: Tucker tensor decomposition offers a more effective representation for multiway data compared to the widely used PARAFAC model. However, its flexibility brings the challenge of selecting the appropriate latent multi-rank. To overcome the issue of pre-selecting the latent multi-rank, we introduce a Bayesian adaptive Tucker decomposition model that infers the multi-rank automatically via an infinite increasing shrinkage prior. The model introduces local sparsity in the core tensor, inducing rich and at the same time parsimonious dependency structures. Posterior inference proceeds via an efficient adaptive Gibbs sampler, supporting both continuous and binary data and allowing for straightforward missing data imputation when dealing with incomplete multiway data. We discuss fundamental properties of the proposed modeling framework, providing theoretical justification. Simulation studies and applications to chemometrics and complex ecological data offer compelling evidence of its advantages over existing tensor factorization methods.


# Summary. An optional shortened abstract.
#summary:

tags:
- Source Themes
featured: false

links:
- name: "Journal"
  url: https://www.tandfonline.com/doi/full/10.1080/10618600.2025.2509585?src=
- name: "Code"
  url: https://github.com/federicastolf/AdaTuck
- name: "arXiv"
  url: https://arxiv.org/abs/2411.10218
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
slides: ""
---

