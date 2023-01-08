---
title: "SegNetRes-CRF: A Deep Convolutional Encoder-Decoder Architecture for Semantic Image Segmentation"
summary: International Joint Conference on Neural Networks (IJCNN) 2018
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
slides: example
---

Semantic segmentation is an essential task in computer vision that aims to label each image pixel. Several of the actual best approaches in this context are based on deep neural networks. For example, SegNet is a deep encoder-decoder architecture approach whose results were disruptive because it is fast and performs well. However, this architecture fails to fine-delineating the edges between the objects of interest in the image. We propose some modifications in the SegNet-Basic architecture by using a post-processing segmentation layer (using Conditional Random Fields) and by transferring high resolution features combined to the decoder network. The proposed method was evaluated in the dataset CamVid. Moreover, it was compared with important variants of SegNet and showed to be able to improve the overall accuracy of SegNet-Basic by up to 17.5%.

https://doi.org/10.1109/IJCNN.2018.8489376
