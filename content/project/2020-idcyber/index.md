---
title: "Intrusion Detection for Cyber–Physical Systems Using Generative Adversarial Networks in Fog Environment"
summary: IEEE Internet of Things Journal 2020
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

Cyber-attacks cyber-physical systems (CPSs) can lead to sensing and actuation misbehavior, severe damages to physical objects, and safety risks. Machine learning algorithms have been proposed for hindering cyber-attacks on CPSs, but the absence of labeled data from novel attacks makes their detection quite challenging. In this context, generative adversarial networks (GANs) are a promising unsupervised approach to detect cyber-attacks by implicitly modeling the system. However, the detection of cyber-attacks on CPSs has strict latency requirements, since the attacks need to be stopped before the system is compromised. In this article, we propose FID-GAN, a novel fog-based, unsupervised intrusion detection system (IDS) for CPSs using GANs. The IDS is proposed for a fog architecture, which brings computation resources closer to the end nodes and thus contributes to meeting low-latency requirements. In order to achieve higher detection rates, the proposed architecture computes a reconstruction loss based on the reconstruction of data samples mapped to the latent space. Other works that follow a similar approach struggle with the time required to compute the reconstruction loss, which renders them impractical for latency constrained applications. We address this problem by training an encoder that accelerates the reconstruction loss computation. Experiments show that the proposed solution achieves higher detection rates and is at least 5.5 times faster than a baseline approach in the three studied data sets.

https://doi.org/10.1109/JIOT.2020.3024800
