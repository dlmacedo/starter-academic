---
title: "Improving Universal Language Model Fine-Tuning using Attention Mechanism"
summary: International Joint Conference on Neural Networks 2019.
tags:
- nlp
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

Inductive transfer learning is widespread in computer vision applications. However, in natural language processing (NLP) applications is still an under-explored area. The most common transfer learning method in NLP is the use of pre-trained word embeddings. The Universal Language Model Fine-Tuning (ULMFiT) is a recent approach which proposes to train a language model and transfer its knowledge to a final classifier. During the classification step, ULMFiT uses a max and average pooling layer to select the useful information of an embedding sequence. We propose to replace max and average pooling layers with a soft attention mechanism. The goal is to learn the most important information of the embedding sequence rather than assuming that they are max and average values. We evaluate the proposed approach in six datasets and achieve the best performance in all of them against literature approaches.

https://doi.org/10.1109/IJCNN.2019.8852398