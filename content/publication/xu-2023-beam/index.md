---
# Documentation: https://wowchemy.com/docs/managing-content/

title: Beam trajectory control with lattice-agnostic reinforcement learning
subtitle: ''
summary: ''
authors:
- Chenran Xu
- Erik Bründermann
- Anke-Susanne Müller
- Andrea Santamaria Garcia
- Annika Eichler
- Jan Kaiser
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
publishDate: '2023-09-27T09:32:28.868713Z'
publication_types:
- '1'
abstract: In recent work, it has been shown that reinforcement learning (RL) is capable
  of outperforming existing methods on accelerator tuning tasks. However, RL algorithms
  are difficult and time-consuming to train and currently need to be retrained for
  every single task. This makes fast deployment in operation difficult and hinders
  collaborative efforts in this research area. At the same time, modern accelerators
  often reuse certain structures within or across facilities such as transport lines
  consisting of several magnets, leading to similar tuning tasks. In this contribution,
  we use different methods, such as domain randomization, to allow an agent trained
  in simulation to easily be deployed for a group of similar tasks. Preliminary results
  show that this training method is transferable and allows the RL agent to control
  the beam trajectory at similar lattice sections of two different real linear accelerators.
  We expect that future work in this direction will enable faster deployment of learning-based
  tuning routines, and lead towards the ultimate goal of autonomous operation of accelerator
  systems and transfer of RL methods to most accelerators.
publication: "*Proc. IPAC'23*"
doi: doi:10.18429/jacow-ipac2023-thpl029
url_pdf: https://accelconf.web.cern.ch/ipac2023/papers/thpl029.pdf
---
