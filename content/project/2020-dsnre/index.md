---
title: "Distantly-Supervised Neural Relation Extraction with Side Information using BERT"
summary: International Joint Conference on Neural Networks (IJCNN) 2020
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

Relation extraction (RE) consists in categorizing the relationship between entities in a sentence. A recent paradigm to develop relation extractors is Distant Supervision (DS), which allows the automatic creation of new datasets by taking an alignment between a text corpus and a Knowledge Base (KB). KBs can sometimes also provide additional information to the RE task. One of the methods that adopt this strategy is the RESIDE model, which proposes a distantly-supervised neural relation extraction using side information from KBs. Considering that this method outperformed state-of-the-art baselines, in this paper, we propose a related approach to RESIDE also using additional side information, but simplifying the sentence encoding with BERT embeddings. Through experiments, we show the effectiveness of the proposed method in Google Distant Supervision and Riedel datasets concerning the BGWA and RESIDE baseline methods. Although Area Under the Curve is decreased because of unbalanced datasets, P@N results have shown that the use of BERT as sentence encoding allows superior performance to baseline methods.

https://doi.org/10.1109/IJCNN48605.2020.9206648
