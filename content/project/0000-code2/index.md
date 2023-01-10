---
title: "Entropic Out-of-Distribution Detection"
summary: A code project to add scalable state-of-the-art out-of-distribution detection (open set recognition) support to your deep learning model.
tags:
- c
date: "2023-01-10T00:00:00Z"

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

A project to add scalable state-of-the-art out-of-distribution detection (open set recognition) support by changing two lines of code! Perform efficient inferences (i.e., do not increase inference time) and detection without classification accuracy drop, hyperparameter tuning, or collecting additional data. We call our approach seamless because it neither presents special requirements (e.g., hyperparameter tuning, additional data) nor produces side effects (e.g., inefficient inference or detection, classification accuracy drop). Our approach consists of a loss that works as a drop-in replacement to the SoftMax loss (i.e., the combination of the output linear layer, the SoftMax activation, and the cross-entropy loss). The out-of-distribution detection is performed using a zero computational cost score. Besides all the above, the IsoMax+ loss (the most recent version) produces state-of-the-art out-of-distribution detection performance.

https://github.com/dlmacedo/entropic-out-of-distribution-detection
