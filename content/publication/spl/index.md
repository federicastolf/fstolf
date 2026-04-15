---
title: 'Identifiable sparse Bayesian factorizations via meta regression'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - Antonio Canale
  - Lorenzo Schiavon
  - admin


date: '2026-01-18T00:00:00Z'
doi: ''

# Schedule page publish date (NOT publication's date).
publishDate: '2017-01-01T00:00:00Z'

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ['2']

# Publication name and optional abbreviated publication name.
publication: "Statistics & Probability Letters"
publication_short: "Statistics & Probability Letters"

abstract: Sparse Bayesian factor models provide an effective framework to learn low-rank dependence structures in high-dimensional data. Their practical usefulness, however, is often limited by non-identifiability and the inability to incorporate auxiliary information in a principled way. We propose an identifiable infinite Bayesian factor model that combines a generalized lower triangular identification scheme with a structured shrinkage prior informed by variable-specific meta-covariates. The proposed prior induces sparsity in the factor loadings while ensuring identifiability up to signed permutations, enabling fully Bayesian posterior inference via Markov chain Monte Carlo methods. Unlike existing approaches, the prior we propose matches structural constraints with informed sparsity mitigating order dependence and easing interpretability. Posterior computation is carried out using an adaptive Gibbs sampler that jointly learns the number of factors, the sparsity structure, and the influence of meta-covariates. Simulation studies and an application to exchange-traded fund returns demonstrate accurate recovery of covariance structures, robustness to variable reordering, and insightful market dynamics.


# Summary. An optional shortened abstract.
#summary:

tags:
- Source Themes
featured: false

links:
- name: "Journal"
  url: https://www.sciencedirect.com/science/article/pii/S0167715226001367
- name: "Code"
  url: https://github.com/federicastolf/SIS-with-UGLT
  
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

