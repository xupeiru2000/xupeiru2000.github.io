---
title: Neural Directed Evolution for Protein Sequence Optimization
summary: We propose a Monte Carlo Tree Search-based Directed Evolution framework for sequence optimization which utilizes upper-confidence bound (UCB) algorithm that effectively search for closely related protein mutants with high fitness values and relatively low mutation counts. We formalized a bandit model for Directed Evolution as an initial population evolves via uniform mutation and directed recombination of parent sequences. In replacement of real-world wet-lab experiments and measurements, we simulate the ground-truth protein fitness landscape with a pre-trained black-box model and use TAPE embedding inputs to simulate and train the black-box oracle model. We evaluate the proposed MCTS-based DE on benchmark protein sequence datasets including GB1, AAV, and WW domain, and our proposed algorithm achieves substantial improvement over baseline algorithms including AdaLead, DyNA PPO, and PEX.

tags:
  - Reinforcement Learning
date: '2022-11-20T00:00:00Z'

# Optional external URL for project (replaces project detail page).
external_link: ''

image:
  caption: Maximum fitness for different algorithms
  focal_point: Smart

links:
#  - icon: twitter
#   icon_pack: fab
#  name: Follow
# url: https://twitter.com/georgecushen
url_code: ''
url_pdf: ''
url_slides: ''
url_video: ''

# Slides (optional).
#   Associate this project with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides = "example-slides"` references `content/slides/example-slides.md`.
#   Otherwise, set `slides = ""`.
#slides: example
---

We propose a Monte Carlo Tree Search-based Directed Evolution framework for sequence optimization which utilizes upper-confidence bound (UCB) algorithm that effectively search for closely related protein mutants with high fitness values and relatively low mutation counts. We formalized a bandit model for Directed Evolution as an initial population evolves via uniform mutation and directed recombination of parent sequences. In replacement of real-world wet-lab experiments and measurements, we simulate the ground-truth protein fitness landscape with a pre-trained black-box model and use TAPE embedding inputs to simulate and train the black-box oracle model. We evaluate the proposed MCTS-based DE on benchmark protein sequence datasets including GB1, AAV, and WW domain, and our proposed algorithm achieves substantial improvement over baseline algorithms including AdaLead, DyNA PPO and PEX.
