---
title: "Enhancing Deep Learning Performance Using Displaced Rectifier Linear Unit"
summary: Editora Dialética
tags:
- b
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

Recently, deep learning has caused a significant impact on computer vision, speech recognition, and natural language understanding. In spite of the remarkable advances, deep learning recent performance gains have been modest and usually rely on increasing the depth of the models, which often requires more computational resources such as processing time and memory usage. To tackle this problem, we turned our attention to the interworking between the activation functions and the batch normalization, which is virtually mandatory currently. In this work, we propose the activation function Displaced Rectifier Linear Unit (DReLU) by conjecturing that extending the identity function of ReLU to the third quadrant enhances compatibility with batch normalization. Moreover, we used statistical tests to compare the impact of using distinct activation functions (ReLU, LReLU, PReLU, ELU, and DReLU) on the learning speed and test accuracy performance of VGG and Residual Networks state-of-the-art models. These convolutional neural networks were trained on CIFAR-10 and CIFAR-100, the most commonly used deep learning computer vision datasets. The results showed DReLU speeded up learning in all models and datasets. Besides, statistical significant performance assessments (p<0.05) showed DReLU enhanced the test accuracy obtained by ReLU in all scenarios. Furthermore, DReLU showed better test accuracy than any other tested activation function in all experiments with one exception.

https://github.com/dlmacedo/SVM-CNN
