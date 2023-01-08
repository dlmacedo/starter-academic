---
title: "Enhancing Batch Normalized Convolutional Networks using Displaced Rectifier Linear Units: A Systematic Comparative Study"
summary: Expert Systems with Applications 2019
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

A substantial number of expert and intelligent systems rely on deep learning methods to solve problems in areas such as economics, physics, and medicine. Improving the accuracy of the activation functions used by such methods can directly and positively impact the overall performance and quality of the mentioned systems at no cost whatsoever. In this sense, enhancing the design of such theoretical fundamental blocks is of great significance as it immediately impacts a broad range of current and future real-world deep learning based applications. Therefore, in this paper, we turn our attention to the interworking between the activation functions and the batch normalization, which is practically a mandatory technique to train deep networks currently. We propose the activation function Displaced Rectifier Linear Unit (DReLU) by conjecturing that extending the identity function of ReLU to the third quadrant enhances compatibility with batch normalization. Moreover, we used statistical tests to compare the impact of using distinct activation functions (ReLU, LReLU, PReLU, ELU, and DReLU) on the learning speed and test accuracy performance of standardized VGG and Residual Networks state-of-the-art models. These Convolutional Neural Networks were trained on CIFAR-100 and CIFAR-10, the most commonly used deep learning computer vision datasets. The results showed DReLU speeded up learning in all models and datasets. Besides, statistical significant performance assessments (p < 0.05) showed DReLU enhanced the test accuracy presented by ReLU in all scenarios. Furthermore, DReLU showed better test accuracy than any other tested activation function in all experiments with one exception, in which case it presented the second best performance. Therefore, this work demonstrates that it is possible to increase performance replacing ReLU by an enhanced activation function.

https://doi.org/10.1016/j.eswa.2019.01.066
