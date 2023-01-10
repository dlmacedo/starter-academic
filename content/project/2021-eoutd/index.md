---
title: "Entropic Out-of-Distribution Detection"
summary: International Joint Conference on Neural Networks 2021
tags:
- f
date: "2023-01-08T00:00:00Z"

# Optional external URL for project (replaces project detail page).
external_link: ""

image:
  caption: Photo by Authors
  focal_point: Smart

links:
- icon: twitter
  icon_pack: fab
  name: Follow
  url: https://twitter.com/david_macedo
url_code: ""
url_pdf: ""
url_slides: ""
url_video: ""

# Slides (optional).
#   Associate this project with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides = "example-slides"` references `content/slides/example-slides.md`.
#   Otherwise, set `slides = ""`.
slides: ""
---

Out-of-distribution (OOD) detection approaches usually present special requirements (e.g., hyperparameter validation, collection of outlier data) and produce side effects (e.g., classification accuracy drop, slower energy-inefficient inferences). We argue that these issues are a consequence of the SoftMax loss anisotropy and disagreement with the maximum entropy principle. Thus, we propose the IsoMax loss and the entropic score. The seamless drop-in replacement of the SoftMax loss by IsoMax loss requires neither additional data collection nor hyperparameter validation. The trained models do not exhibit classification accuracy drop and produce fast energy-efficient inferences. Moreover, our experiments show that training neural networks with IsoMax loss significantly improves their OOD detection performance. The IsoMax loss exhibits state-of-the-art performance under the mentioned conditions (fast energy-efficient inference, no classification accuracy drop, no collection of outlier data, and no hyperparameter validation), which we call the seamless OOD detection task. In future work, current OOD detection methods may replace the SoftMax loss with the IsoMax loss to improve their performance on the commonly studied non-seamless OOD detection problem.

https://doi.org/10.1109/IJCNN52387.2021.9533899
