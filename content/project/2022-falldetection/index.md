---
title: "Multi-human Fall Detection and Localization in Videos"
summary: Computer Vision and Image Understanding 2022.
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
slides: ""
---

Context:
There has been a delay in the exploration of the benefits of deep learning for human action and activity recognition applications. Within these fields, the detection of falls attracts attention due to its excellent public utility. Fall detection can be implemented in facilities such as nursing homes, areas with public cameras, and the homes of older people who live alone, as the vast majority of fatalities related to falls occur in these locations.

Goal:
The YOLO object detection algorithm is combined with temporal classification models and the Kalman filter tracking algorithm, which are used to detect falls individually on video streams.

Method:
The following steps are taken when the proposed approach is used: (i) the region of the image in which the fall occurred is located; (ii) the features that comprise the fall in a temporal sequence of images are tracked and extracted, and a series of actions associated with a given person are formed; and (iii) a model is built to classify the consecutive sequence of images and aggregate the temporal information. Based on these steps, two versions of the proposed approach, YOLOK+3DCNN and YOLOK+2DCNN+LSTM, are created.

Result:
The proposed model is compared with other methods in the literature using well-known metrics. Experimental simulations using a custom dataset and state-of-the-art models show that the best results in most evaluated metrics are achieved using the proposed approach.

https://doi.org/10.1016/j.cviu.2022.103442
