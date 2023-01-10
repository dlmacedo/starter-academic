---
title: "Reducing Squeezenet Storage Size with Depthwise Separable Convolutions"
summary: International Joint Conference on Neural Networks 2018
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

Current research in the field of convolutional neural networks usually focuses on improving network accuracy, regardless of the network size and inference time. In this paper, we investigate the effects of storage space reduction in SqueezeNet as it relates to inference time when processing single test samples. In order to reduce the storage space, we suggest adjusting SqueezeNet's Fire Modules to include Depthwise Separable Convolutions (DSC). The resulting network, referred to as SqueezeNet-DSC, is compared to different convolutional neural networks such as MobileNet, AlexNet, VGG19, and the original SqueezeNet itself. When analyzing the models, we consider accuracy, the number of parameters, parameter storage size and processing time of a single test sample on CIFAR-10 and CIFAR-100 databases. The SqueezeNet-DSC exhibited a considerable size reduction (37% the size of SqueezeNet), while experiencing a loss in network accuracy of 1,07% in CIFAR-10 and 3,06% in top 1 CIFAR-100.

https://doi.org/10.1109/IJCNN.2018.8489442
