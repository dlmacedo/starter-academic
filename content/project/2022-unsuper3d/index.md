---
title: "Unsupervised Multi-view Multi-person 3D Pose Estimation Using Reprojection Error"
summary: International Conference on Artificial Neural Networks 2022.
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

This work addresses multi-view multi-person 3D pose estimation in synchronized and calibrated camera views. Recent approaches estimate neural network weights in a supervised way; they rely on ground truth annotated datasets to compute the loss function and optimize the weights in the network. However, manually labeling ground truth datasets is labor-intensive, expensive, and prone to errors. Consequently, it is preferable not to rely heavily on labeled datasets. This work proposes an unsupervised approach to estimating 3D human poses requiring only an off-the-shelf 2D pose estimation method and the intrinsic and extrinsic camera parameters. Our approach uses reprojection error as a loss function instead of comparing the predicted 3D pose with the ground truth. First, we estimate the 3D pose of each person using the plane sweep stereo approach, in which the depth of each 2D joint related to each person is estimated in a selected target view. The estimated 3D pose is then projected onto each of the other views using camera parameters. Finally, the 2D reprojection error in the image plane is computed by comparing it with the estimated 2D pose corresponding to the same person. The 2D poses that correspond to the same person are identified using virtual depth planes, where each 3D pose is projected onto the reference view and compared to find the nearest 2D pose. Our proposed method learns to estimate 3D pose in an end-to-end unsupervised manner and does not require any manual parameter tuning, yet we achieved results close to state-of-the-art supervised methods on a public dataset. Our method achieves only 5.8% points below the fully supervised state-of-the-art method and only 5.1% points below the best geometric approach in the Campus dataset.

https://doi.org/10.1007/978-3-031-15934-3_40
