---
title: "Detecting Malicious HTTP Requests Without Log Parser Using RequestBERT-BiLSTM"
summary: Brazilian Conference on Intelligent Systems 2022.
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

Web servers provide most internet services, such as information sharing, financial, health, entertainment, and education. In this context, the web has become the principal place for attackers. Unfortunately, most defensive techniques for web servers cannot deal with the complexity and evolution of cyber attacks on HTTP requests. However, machine learning approaches can help detect some attacks. This work presents the RequestBERT-BiLSTM, a new model to detect possible HTTP request attacks without using Log Parser. We evaluated the model on public datasets such as CSIC 2010, ECML/PKDD 2007, and BGL. We also developed a new dataset from a real environment to evaluate the method. In addition, we illustrate that the traditional log analysis step can degrade the model’s performance due to parser errors. Furthermore, we compared the performance of the proposed approach with literature models, and we obtained a detection rate above 95%.

https://doi.org/10.1007/978-3-031-21689-3_24
