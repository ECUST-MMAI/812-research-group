---
title: 'Dual attention transformer with adaptive frequency enhancement for real-world Chinese–English scene text image super-resolution'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - 刘燕滨
  - 施秦
  - 朱梓铭
  - 朱煜

# Author notes (optional)
author_notes:
  - 
  - 
  - 
  - "Corresponding author"

date: '2025'
doi: 'https://doi.org/10.1007/s00530-025-01910-6'

# Schedule page publish date (NOT publication's date).
publishDate: '2025-08-21'

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: 
- article-journal

# Publication name and optional abbreviated publication name.
publication: "Multimedia Systems"
publication_short: ""

abstract: 'Scene text image super-resolution (STISR) has achieved remarkable performance on the pure English dataset, TextZoom. Nevertheless, existing STISR models are primarily designed for fixed-size English text images, limiting their ability to reconstruct structurally complex characters like Chinese characters. Due to the squared computational complexity of standard self-attention, existing methods usually restrict the self-attention calculation within local windows, leading to a limited receptive field. In this paper, we propose a dual attention transformer with adaptive frequency enhancement (DA2FE) model which alternates between two complementary window attention mechanisms. Specifically, dense window attention (DWA) facilitates interactions between neighboring tokens, which is beneficial for learning local features. Sparse window attention (SWA) establishes associations between spaced tokens, enabling effective global information extraction. Additionally, we incorporate a parallel depth-wise convolution (DWConv) branch to establish cross-window relations. Subsequently, a spatial-channel interaction module is employed to facilitate the bi-directional interaction between the window attention branch and the DWConv branch. Furthermore, we design a feed-forward network with adaptive frequency enhancement (FFN-AFE), which introduces a learnable quantitative matrix in the frequency domain to adaptively select and enhance significant frequency information. Finally, the output features from multiple layers are aggregated and refined to provide more comprehensive information for SR reconstruction. Comparative experiments with advanced methods on the Real-CE dataset demonstrate our superior performance in terms of objective indicators and subjective visual results for both 2× and 4× STISR tasks. Furthermore, DA2FE exhibits excellent results on natural image super-resolution datasets, further demonstrating its broad applicability.'

# Summary. An optional shortened abstract.
summary: 

tags: 
 - Real-world text image super-resolution
 - Dual-branch network
 - Dense and sparse window attention
 - Spatial-channel interaction
 - Adaptive frequency enhancement

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
  caption: 'Image credit: [**Multimedia Systems**](https://doi.org/10.1007/s00530-025-01910-6)'
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
