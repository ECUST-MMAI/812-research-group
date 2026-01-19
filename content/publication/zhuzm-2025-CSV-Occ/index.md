---
title: 'CSV-Occ: Fusing Multi-frame Alignment for Occupancy Prediction with Temporal Cross State Space Model and Central Voting Mechanism'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - 朱梓铭
  - 朱煜
  - 陈加昊

# Author notes (optional)
author_notes:
  - 
  - "Corresponding author"

date: '2025-07-15'
doi: ''

# Schedule page publish date (NOT publication's date).
publishDate: '2025-07-15'

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ['paper-conference']

# Publication name and optional abbreviated publication name.
publication: In *Forty-second International Conference on Machine Learning (ICML 2025)*
publication_short: In *ICML 2025*

abstract: 'Recently, image-based 3D semantic occupancy prediction has become a hot topic in 3D scene understanding for autonomous driving. Compared with the bounding box form of 3D object detection, the ability to describe the fine-grained contours of any obstacles in the scene is the key insight of voxel occupancy representation, which facilitates subsequent tasks of autonomous driving. In this work, we propose CSV-Occ to address the following two challenges: (1) Existing methods fuse temporal information based on the attention mechanism, but are limited by high complexity. We extend the state space model to support multi-input sequence interaction and conduct temporal modeling in a cascaded architecture, thereby reducing the computational complexity from quadratic to linear. (2) Existing methods are limited by semantic ambiguity, resulting in the centers of foreground objects often being predicted as empty voxels. We enable the model to explicitly vote for the instance center to which the voxels belong and spontaneously learn to utilize the other voxel features of the same instance to update the semantics of the internal vacancies of the objects from coarse to fine. Experiments on the Occ3D-nuScenes dataset show that our method achieves state-of-the-art in camera-based 3D semantic occupancy prediction and also performs well on lidar point cloud semantic segmentation on the nuScenes dataset. Therefore, we believe that CSV-Occ is beneficial to the community and industry of autonomous vehicles.'

# Summary. An optional shortened abstract.
summary: 

tags: ['Autonomous Driving', '3D Occupancy Prediction']

# Display this page in the Featured widget?
featured: true

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

url_pdf: ''
url_code: 'https://github.com/ZeaZoM/CSV-Occ'
url_dataset: ''
url_poster: ''
url_project: ''
url_slides: ''
url_source: ''
url_video: ''

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
image:
  caption: 'Image credit: [**ICML**](https://icml.cc/virtual/2025/poster/46333)'
  focal_point: ''
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
