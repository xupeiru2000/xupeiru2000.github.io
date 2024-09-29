---
title: A Generic Approach for Statistical Stability in Model Distillation
summary: Model distillation has been a popular method for producing interpretable machine learning, where an interpretable student model is produced to mimic the predictions made by the black box teacher model. However, the interpretation of a student model is sensitive to the variability of the datasets, and existing strategy for statistical stability focuses on specific models. Therefore, we developed a generic approach for stable model distillation based on central limit theorem. We construct a multiple testing framework to select a corpus size such that the consistent student model would be selected under different pseudo sample. We demonstrate the application of our proposed approach on decision trees, falling rule lists and symbolic regression, and we provide theoretical analysis with Markov process.

tags:
  - Interpretable Machine Learning
date: '2024-07-22T00:00:00Z'

# Optional external URL for project (replaces project detail page).
external_link: ''

image:
  caption: Heatmap of the proportions of different structures
  focal_point: Smart

links:
- icon: 
  icon_pack: ai
  name: Publication
  url: https://link.springer.com/article/10.1007/s10994-024-06597-w
url_code: ''
url_pdf: https://arxiv.org/pdf/2211.12631 #uploads/arxiv_paper.pdf
url_slides: ''
url_video: ''

# Slides (optional).
#   Associate this project with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides = "example-slides"` references `content/slides/example-slides.md`.
#   Otherwise, set `slides = ""`.
#slides: example
---


Model distillation has been a popular method for producing interpretable machine learning, where an interpretable student model is produced to mimic the predictions made by the black box teacher model. However, the interpretation of a student model is sensitive to the variability of the datasets, and existing strategy for statistical stability focuses on specific models. Therefore, we developed a generic approach for stable model distillation based on central limit theorem. We construct a multiple testing framework to select a corpus size such that the consistent student model would be selected under different pseudo sample. We demonstrate the application of our proposed approach on decision trees, falling rule lists and symbolic regression, and we provide theoretical analysis with Markov process.