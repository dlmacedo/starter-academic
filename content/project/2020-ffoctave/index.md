---
title: "A Fast Fully Octave Convolutional Neural Network for Document Image Segmentation"
summary: International Joint Conference on Neural Networks 2020.
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

The Know Your Customer (KYC) and Anti Money Laundering (AML) are worldwide practices to online customer identification based on personal identification documents, similarity and liveness checking, and proof of address. To answer the basic regulation question: are you whom you say you are? The customer needs to upload valid identification documents (ID). This task imposes some computational challenges since these documents are diverse, may present different and complex backgrounds, some occlusion, partial rotation, poor quality, or damage. Advanced text and document segmentation algorithms were used to process the ID images. In this context, we investigated a method based on U-Net to detect the document edges and text regions in ID images. Besides the promising results on image segmentation, the U-Net based approach is computationally expensive for a real application, since the image segmentation is a customer device task. We propose a model optimization based on Octave Convolutions to qualify the method to situations where storage, processing, and time resources are limited, such as in mobile and robotic applications. We conducted the evaluation experiments in two new datasets CDPhotoDataset and DTDDataset, which are composed of real ID images of Brazilian documents. Our results showed that the proposed models are efficient to document segmentation tasks and portable.

https://doi.org/10.1109/IJCNN48605.2020.9206711
