---
title: 'Pathway-based Bayesian factor models for gene expression data'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - Lorenzo Mauri
  - admin
  - Amy H. Herring
  - Cameron Miller
  - David B. Dunson

date: '2026-01-21T00:00:00Z'
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

#abstract: Interpreting gene expression data requires methods that can uncover coordinated patterns corresponding to biological pathways. Traditional approaches such as principal component analysis and factor models reduce dimensionality, but latent components may have unclear biological meaning. Current approaches to incorporate pathway annotations impose restrictive assumptions, require extensive hyperparameter tuning, and do not provide principled uncertainty quantification, hindering the robustness and reproducibility of results. Here, we develop Bayesian Analysis with gene-Sets Informed Latent space (BASIL), a scalable Bayesian factor modeling framework that incorporates gene pathway annotations into latent variable analysis for RNA-sequencing data. BASIL places structured priors on factor loadings, shrinking them toward combinations of annotated gene sets, enhancing biological interpretability and stability, while simultaneously learning new unstructured components. BASIL provides accurate covariance estimates and uncertainty quantification, without resorting to computationally expensive Markov chain Monte Carlo sampling. An automatic empirical Bayes procedure eliminates the need for manual hyperparameter tuning, promoting reproducibility and usability in practice. In simulations and large-scale human transcriptomic datasets, BASIL consistently outperforms state-of-the-art approaches, accurately reconstructing gene-gene covariance, selecting the correct latent dimension, and identifying biologically coherent modules.

# Summary. An optional shortened abstract.
#summary:

tags:
- Source Themes
featured: false

links:
- name: "Code"
  url: https://github.com/federicastolf/BASIL
- name: "arXiv"
  url: https://arxiv.org/abs/2601.13419
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

