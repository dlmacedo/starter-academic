---
title: "Convolution Optimization in Fire Classification"
summary: IEEE Access 2022
tags:
- cv
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

Early alert fire and smoke detection systems are crucial for daily and security management decision-making. Recent literature approaches are based on Deep Learning (DL) models. Efficient models are required for hardware-constrained systems, such as mobile devices, embedded systems, and robotics achieving high performance at low power consumption. For this research, we designed a novel specific-purpose model for fire and smoke recognition using still images and the study of state-of-the-art convolution techniques to improve the trade-off between accuracy and complexity. In this regard, the literature suggests that the inverted residual block, the depthwise and octave convolution techniques, reduces the model’s size and computation requirements working well by themselves. In this work, we propose the KutralNext architecture, an efficient model for single- and multi-label fire and smoke recognition tasks. Additionally, a more efficient architecture KutralNext+, demonstrates that those convolution techniques achieve a better trade-off combined, reaching an 84.36% average test accuracy in FireNet, FiSmo, and FiSmoA fire datasets. The KutralSmoke and FiSmo fire and smoke datasets attained an 81.53% average test accuracy. Furthermore, a previous fire and smoke recognition model considered, FireDetection, KutralNext uses 59% fewer parameters, and KutralNext+ requires 97% fewer flops and is 4x faster.

https://doi.org/10.1109/ACCESS.2022.3151660
