---
title: "PGgraf: Pose-Guided generative radiance field for novel-views on X-ray"
authors:
- 李航宇
- 刘墨泉
- 孙梦成
- 朱煜

author_notes:
- 
- 
-
- "Corresponding author"
date: '2026'
doi: "https://doi.org/10.1016/j.displa.2026.103354"

publishDate: '2026-01-01'

publication_types:
- article-journal

publication: "Displays"
publication_short: ""

abstract: "In clinical diagnosis, doctors usually judge the information by a few X-rays to avoid excessive ionizing radiation from harming the patient. The recent Neural Radiance Field (NERF) technology contemplates generating novel-views from a single X-ray to assist physicians in diagnosis. In this task, we consider two advantages of X-ray filming over natural images: (1) The medical equipment is fixed, and there is a standardized filming pose. (2) There is an apparent structural prior to X-rays of the same body part at the same pose. Based on such conditions, we propose a Pose-Guided generative radiance field (PGgraf) containing a generator and discriminator. In the training phase, the discriminator combines the image features with two kinds of pose information (ray direction set and camera angle) to guide the generator to synthesize X-rays consistent with the realistic view. In the generator, we design a Density Reconstruction Block (DRB). Unlike the original NERF, which directly estimates the particle density based on the particle positions, the DRB considers all the particle features sampled in a ray and integrally predicts the density of each particle. Experiments comparing qualitative-quantitative on two chest datasets and one knee dataset with state-of-the-art NERF schemes show that PGgraf has a clear advantage in inferring novel-views at different ranges. In the three ranges of 0°to 360°, -15°to 15°, and 75°to 105°, the Peak Signal-to-Noise Ratio (PSNR) improved by an average of 4.18 decibel, and the Learned Perceptual Image Patch Similarity (LPIPS) improved by an average of 50.7%."

# Summary. An optional shortened abstract.
summary: 

tags:
- X-ray
- Neural radiance field
- Pose
- Novel-view
featured: false

# links:
# - name: ""
#   url: ""
url_pdf: 
url_code: ''
url_dataset: ''
url_poster: ''
url_project: ''
url_slides: ''
url_source: ''
url_video: ''

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
image:
  caption: 'Image credit: [**Displays**](https://doi.org/10.1016/j.displa.2026.103354)'
  focal_point: ""
  preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
projects: []

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
slides: example
---
