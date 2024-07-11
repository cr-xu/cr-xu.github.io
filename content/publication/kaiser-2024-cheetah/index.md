---
# Documentation: https://wowchemy.com/docs/managing-content/

title: Bridging the gap between machine learning and particle accelerator physics
  with high-speed, differentiable simulations
subtitle: ''
summary: ''
authors:
- Jan Kaiser
- Chenran Xu
- Annika Eichler
- Andrea Santamaria Garcia
tags: []
categories: []
date: '2024-05-28'
lastmod: 2024-07-11T13:41:09+02:00
featured: true
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
publishDate: '2024-07-11T11:41:09.742241Z'
publication_types:
- '2'
abstract: Machine learning has emerged as a powerful solution to the modern challenges in accelerator physics. However, the limited availability of beam time, the computational cost of simulations, and the high dimensionality of optimization problems pose significant challenges in generating the required data for training state-of-the-art machine learning models. In this work, we introduce cheetah, a pytorch-based high-speed differentiable linear beam dynamics code. cheetah enables the fast collection of large datasets by reducing computation times by multiple orders of magnitude and facilitates efficient gradient-based optimization for accelerator tuning and system identification. This positions cheetah as a user-friendly, readily extensible tool that integrates seamlessly with widely adopted machine learning tools. We showcase the utility of cheetah through five examples, including reinforcement learning training, gradient-based beamline tuning, gradient-based system identification, physics-informed Bayesian optimization priors, and modular neural network surrogate modeling of space charge effects. The use of such a high-speed differentiable simulation code will simplify the development of machine learning-based methods for particle accelerators and fast-track their integration into everyday operations of accelerator facilities.
publication: '*Phys. Rev. Accel. Beams*'
doi: 10.1103/PhysRevAccelBeams.27.054601
links:
- name: Code
  url: https://github.com/desy-ml/cheetah
---
