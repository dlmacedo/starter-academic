---
title: "The Robust Deep Learning Library"
summary: Deep Learning Code. A project to train your model from scratch or fine-tune a pretrained model using the losses provided in this library to improve out-of-distribution detection and uncertainty estimation performances.
tags:
- c
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

Calibrate your model to produce enhanced uncertainty estimations. Detect out-of-distribution data using the defined score type and threshold. Train your model from scratch or fine-tune a pretrained model using the losses provided in this library to improve out-of-distribution detection and uncertainty estimation performances. Calibrate your model to produce enhanced uncertainty estimations. Detect out-of-distribution data using the defined score type and threshold.

Model Independent:
Use models from timm library or whatever you want.

Data Independent:
Most cases work for any type of media (e.g., image, text, audio, and others).

Large-Scale Models and Data:
Train using large-scale models and data (e.g., ImageNet).

Efficient Inferences:
The trained models are as efficient as the ones trained using the cross-entropy loss.

Hyperparameter-Free:
There is no hyperparameter to tune. "You only train once" (YOTO).

Standard Interface:
Use the same API to train models with improved robustness using different losses.

No Need for Additional Data:
The losses used in this library do not require collecting or using additional data.

Temperature Calibration:
Calculate the Uncertainty Estimation and update the temperature of the output last layer.

Scalability: More data, Bigger Models, Better Results!
Entropic losses perform better and better as the size of the data and model increase.

Threshold Computation:
Compute the threshold for deciding regarding out-of-distribution examples.

Scores Computation:
Compute the scores opting from a set of many different types available.

Detect Out-of-Distribution:
Detect out-of-distribution examples using the computed scores.

State-of-the-art:
SOTA results for out-of-distribution detection and uncertainty estimation.

https://github.com/dlmacedo/robust-deep-learning
