---
# Documentation: https://wowchemy.com/docs/managing-content/

title: Bayesian Optimization for SASE Tuning at the European XFEL
subtitle: ''
summary: ''
authors:
- Chenran Xu
- Erik Bründermann
- Anke-Susanne Müller
- Andrea Santamaria Garcia
tags: []
categories: []
date: '2023-06-27'
lastmod: 2023-09-27T11:32:29+02:00
featured: false
draft: false

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
# Focal points: Smart, Center, TopLeft, Top, TopRight, Left, Right, BottomLeft, Bottom, BottomRight.
image:
  caption: ''
  focal_point: ''
  preview_only: false

# Projects (optional).
#   Associate this post with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `projects = ["internal-project"]` references `content/project/deep-learning/index.md`.
#   Otherwise, set `projects = []`.
projects: []
publishDate: '2023-09-27T09:32:29.193466Z'
publication_types:
- '1'
abstract: Parameter tuning is a regular task and takes considerable time for daily
  operations at FEL facilities. In this contribution, we demonstrate SASE pulse energy
  optimization at the European XFEL with Bayesian optimization (BO) as an alternative
  approach to the widely used simplex method. Preliminary experimental results show
  that BO could reach a comparable performance as the simplex method, even with an
  out-of-the-box implementation. Compared to previous attempts, our version of BO
  does not require setting hyperparameters via additional measurements, thus effectively
  reducing the required effort for machine operators to use it during operation. On
  the other hand, BO has the potential to be further improved by introducing prior
  physical knowledge about the task and fine-tuning the algorithm to specific tasks.
  This makes BO a promising candidate for routine tuning tasks at particle accelerators
  in the future.
publication: "*Proc. IPAC'23*"
doi: doi:10.18429/jacow-ipac2023-thpl028
url_pdf: https://accelconf.web.cern.ch/ipac2023/papers/thpl028.pdf
---
