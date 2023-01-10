---
title: "PictoBERT: Transformers for Next Pictogram Prediction"
summary: Expert Systems with Applications 2022.
tags:
- oa
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

Augmentative and Alternative Communication (AAC) boards are essential tools for people with Complex Communication Needs (e.g., a person with down’s syndrome, autism, or cerebral palsy). These boards allow the construction of messages by arranging pictograms in sequence. In this context, a pictogram is a picture with a label that denotes an action, object, person, animal, or place. Predicting the next pictogram to be set in a sentence in construction is an essential feature for AAC boards to facilitate communication. Previous work in this task used n-gram statistical language models and knowledge bases. However, neural network literature suggests they can cope better with the task, and transformers-based models like BERT (Bidirectional Encoder Representations from Transformers) are revolutionizing this field. In this paper, we present PictoBERT, an adaptation of BERT for the next pictogram prediction task. We changed the BERT’s input embeddings to allow word-sense usage instead of words, considering that a word-sense represents a pictogram better than a simple word. The proposed model outperforms the n-gram models and knowledge bases. Besides, PictoBERT can be fine-tuned to adapt to different users’ needs, making transfer learning its main characteristic.

https://doi.org/10.1016/j.eswa.2022.117231
