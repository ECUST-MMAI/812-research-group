---
title: "SFJD-Net: spatial-frequency domain joint feature enhancement with differential learning for brain stroke segmentation"
authors:
- 黄鑫
- 朱煜
- 刘雅童

author_notes:
- 
- "Corresponding author"
-

date: '2026'
doi: "https://doi.org/10.1007/s10489-026-07121-4"

publishDate: '2026-03-03'

publication_types:
- article-journal

publication: "Applied Intelligence"
publication_short: ""

abstract: "Brain stroke is a major cause of disability and death, and accurate lesion segmentation is essential for early diagnosis and treatment planning. Although CT and MRI provide critical diagnostic information, the large variations in lesion appearance and the noise introduced by manual annotations make precise segmentation challenging. To address these issues, we propose SFJD-Net, a novel Stroke lesion segmentation network that leverages joint spatial-frequency domain feature enhancement and differential learning. SFJD-Net consists of three core modules: Multi-Branch Convolution Attention Encoder (MBCAE), Spatial-Frequency domain Joint feature Enhancement (SFJE), and Differential Learning Decoder (DLD). Compared with the traditional U-Net architecture, SFJD-Net introduces shallow edge information into deep semantic features to enhance texture and boundary representation. The MBCAE module adaptively captures multi-scale lesion features to enrich representations. The SFJE module enhances feature representations from both the spatial and frequency domains, which integrates positional cues and structural details to guide the network in focusing more accurately on target regions. The DLD module uses the reconstructed convolution kernel to record the differences between encoder and decoder, and integrates it into the decoding process through convolution operation, which reduces the semantic gaps and the probability of misjudgment of decoder. Extensive experiments on the published Ischemic Stroke Lesion Segmentation (ISLES) 2022 and 2018 datasets demonstrate that our method achieves state-of-the-art performance. In addition, SFJD-Net is successfully migrated to the pancreas cancer segmentation task of the MSD Cancer dataset, which fully proves that the network has a certain generalization ability."

# Summary. An optional shortened abstract.
summary: 

tags:
- Medical image segmentation
- Brain stroke
- Encoder
- Decoder

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
  caption: 'Image credit: [**Applied Intelligence**](https://doi.org/10.1007/s10489-026-07121-4)'
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
