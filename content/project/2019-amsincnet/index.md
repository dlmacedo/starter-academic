---
title: "Additive Margin SincNet for Speaker Recognition"
summary: International Joint Conference on Neural Networks 2019.
tags:
- as
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

Speaker Recognition is a challenging task with essential applications such as authentication, automation, and security. The SincNet is a new deep learning based model which has produced promising results to tackle the mentioned task. To train deep learning systems, the loss function is essential to the network performance. The Softmax loss function is a widely used function in deep learning methods, but it is not the best choice for all kind of problems. For distance-based problems, one new Softmax based loss function called Additive Margin Softmax (AM-Softmax) is proving to be a better choice than the traditional Softmax. The AM-Softmax introduces a margin of separation between the classes that forces the samples from the same class to be closer to each other and also maximizes the distance between classes. In this paper, we propose a new approach for speaker recognition systems called AM-SincNet, which is based on the SincNet but uses an improved AM-Softmax layer. The proposed method is evaluated in the TIMIT dataset and obtained an improvement of approximately 40% in the Frame Error Rate when compared to SincNet.

https://doi.org/10.1109/IJCNN.2019.8852112
