---
title: "Entropic Out-of-Distribution Detection: Seamless Detection of Unknown Examples"
summary: IEEE Transactions on Neural Networks and Learning Systems 2021
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

In this article, we argue that the unsatisfactory out-of-distribution (OOD) detection performance of neural networks is mainly due to the SoftMax loss anisotropy and propensity to produce low entropy probability distributions in disagreement with the principle of maximum entropy. On the one hand, current OOD detection approaches usually do not directly fix the SoftMax loss drawbacks, but rather build techniques to circumvent it. Unfortunately, those methods usually produce undesired side effects (e.g., classification accuracy drop, additional hyperparameters, slower inferences, and collecting extra data). On the other hand, we propose replacing SoftMax loss with a novel loss function that does not suffer from the mentioned weaknesses. The proposed IsoMax loss is isotropic (exclusively distance-based) and provides high entropy posterior probability distributions. Replacing the SoftMax loss by IsoMax loss requires no model or training changes. Additionally, the models trained with IsoMax loss produce as fast and energy-efficient inferences as those trained using SoftMax loss. Moreover, no classification accuracy drop is observed. The proposed method does not rely on outlier/background data, hyperparameter tuning, temperature calibration, feature extraction, metric learning, adversarial training, ensemble procedures, or generative models. Our experiments showed that IsoMax loss works as a seamless SoftMax loss drop-in replacement that significantly improves neural networks’ OOD detection performance. Hence, it may be used as a baseline OOD detection approach to be combined with current or future OOD detection techniques to achieve even higher results.

https://doi.org/10.1109/TNNLS.2021.3112897
