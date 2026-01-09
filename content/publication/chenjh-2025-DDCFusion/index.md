---
title: "DDCFusion: Dynamic Depth Compensation Fusion for Camera-Radar 3D Object Detection"
authors:
- 陈加昊
- 朱梓铭
- 申正
- 朱煜

author_notes:
- 
- 
-
- "Corresponding author"
date: '2026'
doi: "https://doi.org/10.1109/jsen.2025.3647645"

publishDate: '2026-01-01'

publication_types:
- article-journal

publication: "IEEE Sensors Journal"
publication_short: ""

abstract: "The effective representation and feature extraction from sparse point clouds of 4D millimeter-wave(4D-MMW) radar pose a significant challenge in 3D object detection. This paper proposes DDCFusion, a novel radar-camera fusion network that advances measurement precision by dynamically compensating for depth errors in sparse radar data. DDCFusion achieves this by exploiting the physical properties of 4D-MMW radar to improve measurement reliability and reduce depth uncertainty, which enhances depth measurement confidence in the view transform by integrating RCS-derived reflectivity metrics. The occupancy-weighted radar branch prioritizes image regions with high-confidence radar returns, minimizing measurement noise in view transform operation. Furthermore, DDCFusion optimizes spatial measurement consistency in Bird’s-Eye-View (BEV) space by modeling cross-sensor dependencies through the Global Feature Slice Coordinate Attention (GFSCA) fusion module. Experimental validation on the VoD and TJ4DRadSet datasets demonstrates superior measurement accuracy, achieving 51.08% mAP on VoD and 34.61% mAP on TJ4DRadSet—outperforming existing methods in depth error reduction and robustness to sparsity. Ablation studies verify the measurement-centric design: RCS-guided diffusion improves small-object detection (e.g., pedestrians), while DBSCAN-based clustering refines large-object localization (e.g., vehicles). The network demonstrates significant improvements in depth accuracy and robustness to sparse inputs while maintaining competitive inference latency with 138ms."

# Summary. An optional shortened abstract.
summary: 

tags:
- 4D-MMW radar
- Camera
- Multi-modal fusion
- Dynamic Depth Compensation
- 3D object detection
- Autonomous driving
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
  caption: 'Image credit: [**IEEE Sensors Journal**](https://doi.org/10.1109/jsen.2025.3647645)'
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
