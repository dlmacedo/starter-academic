---
title: "Squeezed Deep 6DoF Object Detection Using Knowledge Distillation"
summary: International Joint Conference on Neural Networks 2020
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

The detection of objects considering a 6DoF pose is a common requirement to build virtual and augmented reality applications. It is usually a complex task which requires real-time processing and high precision results for adequate user experience. Recently, different deep learning techniques have been proposed to detect objects in 6DoF in RGB images. However, they rely on high complexity networks, requiring a computational power that prevents them from working on mobile devices. In this paper, we propose an approach to reduce the complexity of 6DoF detection networks while maintaining accuracy. We used Knowledge Distillation to teach portables Convolutional Neural Networks (CNN) to learn from a real-time 6DoF detection CNN. The proposed method allows real-time applications using only RGB images while decreasing the hardware requirements. We used the LINEMOD dataset to evaluate the proposed method, and the experimental results show that the proposed method reduces the memory requirement by almost 99% in comparison to the original architecture with the cost of reducing half the accuracy in one of the metrics.

https://doi.org/10.1109/IJCNN48605.2020.9207459
