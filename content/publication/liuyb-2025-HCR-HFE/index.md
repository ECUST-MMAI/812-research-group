---
title: 'Hybrid CNN-RWKV with high-frequency enhancement for real-world chinese-english scene text image super-resolution'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - 刘燕滨
  - 朱煜
  - 李航宇

# Author notes (optional)
author_notes:
  - 
  - "Corresponding author"

date: '2025'
doi: 'https://doi.org/10.1007/s10489-025-06785-8'

# Schedule page publish date (NOT publication's date).
publishDate: '2025-08-30'

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: 
- article-journal

# Publication name and optional abbreviated publication name.
publication: "Applied Intelligence"
publication_short: ""

abstract: 'Existing scene text image super-resolution (STISR) methods primarily focus on the restoration of fixed-size English text images. Compared to English characters, Chinese characters present a greater variety of categories and more intricate stroke structures. In recent years, Transformer-based methods have achieved significant progress in image super-resolution task, but face the dilemma between global modeling and efficient computation. The emerging Receptance Weighted Key Value (RWKV) model can serve as a promising alternative to Transformer, enabling long-distance modeling with linear computational complexity. In this paper, we propose a Hybrid CNN-RWKV with High-Frequency Enhancement (HCR-HFE) model for STISR task. First, we design a recurrent bidirectional WKV (Re-Bi-WKV) attention which integrates bidirectional WKV (Bi-WKV) attention with a recurrent mechanism. Bi-WKV achieves global receptive field with linear complexity, while the recurrent mechanism establishes 2D image dependencies from different scanning directions. Additionally, a computationally efficient high-frequency enhancement module (HFEM) is incorporated to enhance high-frequency details, such as character edge information. Furthermore, we design a multi-scale large kernel convolutional (MLKC) block which integrates large kernel decomposition, gated aggregation and multi-scale mechanism to capture various-range dependencies with reduced computational cost. Finally, we introduce a multi-frequency channel attention (MFCA) which extends channel attention to the frequency domain, enabling the model to focus on critical features. Extensive experiments on real-world Chinese-English (Real-CE) dataset demonstrate that HCR-HFE outperforms previous methods in both quantitative metrics and visual results. Furthermore, HCR-HFE achieves excellent performance on natural image datasets, demonstrating its broad applicability.'

# Summary. An optional shortened abstract.
summary: 

tags: 
 - Text image super-resolution
 - Recurrent bi-directional WKV attention
 - Multi-scale large kernel convolution
 - High-frequency enhancement
 - Multi-frequency channel attention

# Display this page in the Featured widget?
featured: true

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

url_pdf: ''
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
  caption: 'Image credit: [**Applied Intelligence**](https://doi.org/10.1007/s10489-025-06785-8)'
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
