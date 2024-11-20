---
title: 'Bayesian Adaptive Tucker Decompositions for Tensor Factorization'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - admin
  - Antonio Canale

date: '2024-11-15T00:00:00Z'
doi: ''

# Schedule page publish date (NOT publication's date).
publishDate: '2017-01-01T00:00:00Z'

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ['3']

# Publication name and optional abbreviated publication name.
publication: ""
publication_short: ""

abstract: Tucker tensor decomposition offers a more effective representation for multiway data compared to the widely used PARAFAC model. However, its flexibility brings the challenge of selecting the appropriate latent multi-rank. To overcome the issue of pre-selecting the latent multi-rank, we introduce a Bayesian adaptive Tucker decomposition model that infers the multi-rank automatically via an infinite increasing shrinkage prior. The model introduces local sparsity in the core tensor, inducing rich and at the same time parsimonious dependency structures. Posterior inference proceeds via an efficient adaptive Gibbs sampler, supporting both continuous and binary data and allowing for straightforward missing data imputation when dealing with incomplete multiway data. We discuss fundamental properties of the proposed modeling framework, providing theoretical justification. Simulation studies and applications to chemometrics and complex ecological data offer compelling evidence of its advantages over existing tensor factorization methods.


# Summary. An optional shortened abstract.
#summary:

tags:
- Source Themes
featured: false

links:
- name: "arXiv"
  url: https://arxiv.org/abs/2411.10218
- name: "Code"
  url: https://github.com/federicastolf/AdaTuck
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

