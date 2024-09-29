---
title: Automaton Distillation for Non-Markovian Knowledge Transfer in Deep RL
summary: Existing methods in knowledge transfer for reinforcement learning as policy distillation suffer from two weaknesses. First, the learned policies exhibit poor generalization on tasks outside the training distribution; second, existing methods usually rely on the Markovian assumptions to reach good performance. To mitigate these issues, we propose automaton distillation for non-Markovian knowledge transfer. Our proposed algorithm first trains a teacher agent using standard Deep Q-Learning and then distills teacher Q-value estimates into student model learned in the target environment. We experimented on various grid-world environments and demonstrated better performance and faster convergence compared to existing baseline methods.

tags:
  - Reinforcement Learning
date: '2021-12-16T00:00:00Z'

# Optional external URL for project (replaces project detail page).
external_link: ''

image:
  caption: Illustration of decision process and automaton 
  focal_point: Smart

links:
#  - icon: twitter
#   icon_pack: fab
#  name: Follow
# url: https://twitter.com/georgecushen
url_code: ''
url_pdf: ''
#url_slides: https://docs.google.com/presentation/d/1kOETrRfDcrd5V2ryQy7lSJpzlZ3pkm8a/edit?#usp=sharing&ouid=109948757699213231480&rtpof=true&sd=true
url_slides: uploads/Final_presentation.pdf
url_video: ''

# Slides (optional).
#   Associate this project with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides = "example-slides"` references `content/slides/example-slides.md`.
#   Otherwise, set `slides = ""`.
slides: 

---


Existing methods in knowledge transfer for reinforcement learning as policy distillation suffer from two weaknesses. First, the learned policies exhibit poor generalization on tasks outside the training distribution; second, existing methods usually rely on the Markovian assumptions to reach good performance. To mitigate these issues, we propose automaton distillation for non-Markovian knowledge transfer. Our proposed algorithm first trains a teacher agent using standard Deep Q-Learning and then distills teacher Q-value estimates into student model learned in the target environment. We experimented on various grid-world environments and demonstrated better performance and faster convergence compared to existing baseline methods.
