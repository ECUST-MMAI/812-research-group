---
title: "Fine-grained grading network based on sparse transformer and spectral attention for multiparametric MR image segmentation"
authors:
- 刘雅童
- 朱煜
- 李航宇
author_notes:
- 
- "Corresponding author"
date: '2025'
doi: "https://doi.org/10.1016/j.neucom.2025.131094"

publishDate: '2025-11-01'

publication_types:
- article-journal

publication: "Neurocomputing"
publication_short: ""

abstract: "Multiparametric magnetic resonance imaging (mpMRI) is crucial in excluding serious diseases by providing clear scans that can quickly locate diseased tissue. Subjective assessment of lesion aggressiveness can vary among clinicians. We propose a network for mpMRI segmentation capable of effectively segmenting fine-grained lesion groups in prostate cancer (PCa), with potential applicability to other magnetic resonance imaging (MRI) segmentation tasks such as brain strokes. Specifically, a bi-oriented bi-level routing transformer (BBRT) with a flexible sparse attention mechanism is designed to enhance the network’s target perception. This design optimizes the Transformer’s long-range modeling capabilities. An adaptive multispectral channel attention (AMSA) module with an automatically selected frequency components mechanism is designed to enhance target contour recognition accuracy. It improves the network’s sensitivity to detect crucial texture information. Experiments are conducted using three MRI datasets. Our method achieved a dice similarity coefficient (DSC) of 76.09% for grading PCa on PCAMM, demonstrating improvements of 2.77%, 3.79%, 3.64%, and 0.29 % over the suboptimal method in clinically significant Gleason score (GS) groups (GS 3+4, GS 4+3, GS=8, and GS≥9), respectively. The prostate region segmentation obtained DSC of 94.03% and 84.52% for the central gland (CG) and peripheral zone (PZ), respectively, on PROSTATEx. The stroke segmentation achieved a DSC of 86.33% on ISLES2022. The experimental results demonstrate that the proposed model excels in generalization and outperforms other state-of-the-art methods."

# Summary. An optional shortened abstract.
summary: 

tags:
- Magnetic resonance imaging segmentation
- Prostate cancer
- Sparse transformer
- Spectral attention
- Brain stroke
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
  caption: 'Image credit: [**Elsevier**](https://doi.org/10.1016/j.neucom.2025.131094)'
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
