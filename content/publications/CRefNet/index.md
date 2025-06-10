---
title: "CRefNet: Learning Consistent Reflectance Estimation with a Decoder-sharing Transformer"
authors:
- Jundan Luo
- Nanxuan Zhao
- Wenbin Li
- Christian Richardt
author_notes:
- 
date: "2023-12-01"
doi: "10.1109/TVCG.2023.3337870"

# Schedule page publish date (NOT publication's date).
publishDate: ""

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["article-journal"]

# Publication name and optional abbreviated publication name.
publication: "TVCG 2023"
publication_short: "TVCG 2023"

abstract: We present CRefNet, a hybrid transformer-convolutional deep neural network for consistent reflectance estimation in intrinsic image decomposition. Estimating consistent reflectance is particularly challenging when the same material appears differently due to changes in illumination. Our method achieves enhanced global reflectance consistency via a novel transformer module that converts image features to reflectance features. At the same time, this module also exploits long-range data interactions. We introduce reflectance reconstruction as a novel auxiliary task that shares a common decoder with the reflectance estimation task, and which substantially improves the quality of reconstructed reflectance maps. Finally, we improve local reflectance consistency via a new rectified gradient filter that effectively suppresses small variations in predictions without any overhead at inference time. Our experiments show that our contributions enable CRefNet to predict highly consistent reflectance maps and to outperform the state of the art by 10% WHDR.
# Summary. An optional shortened abstract.
summary: Jundan Luo, Nanxuan Zhao, Wenbin Li, Christian Richardt

#tags:
#- Computer Vision
#- Computer Graphics
#- Inverse Rendering
#- Intrinsic Image Decomposition
featured: true

links:
# - name: "pdf"
#   url: 'https://purehost.bath.ac.uk/ws/portalfiles/portal/304058985/Jundan_s_TVCG_submission.pdf'
 - name: "supp doc"
   url: "https://drive.google.com/file/d/13yi0vXYD1Ph5-noZr_Ndx0_SHHtoQrwq/view?usp=sharing"
 - name: "supp materials"
   url: "https://drive.google.com/file/d/1B2oe3c2tYZwYyOwvRHGoyCbNBWGH6lJb/view?usp=drive_link"
# - name: "presentation"
#   url: "https://www.youtube.com/watch?v=BvoYwCdzoZU"
# - name: "project"
#   url: "https://zju3dv.github.io/niid/"
# - name: "code"
#   url: "https://github.com/JundanLuo/CRefNet"
url_pdf: 'https://purehost.bath.ac.uk/ws/portalfiles/portal/304058985/Jundan_s_TVCG_submission.pdf'
# url_project: ''
url_code: 'https://github.com/JundanLuo/CRefNet'
# url_dataset: ''
# url_poster: ''
# url_slides: ''
# url_source: ''
# url_video: ''

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
image:
  placement: 3
  caption: 'Reflectance estimation.'
  focal_point: small
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
# slides: example
---

<!-- {{% callout note %}}
Click the *Cite* button above to demo the feature to enable visitors to import publication metadata into their reference management software.
{{% /callout %}}

{{% callout note %}}
Create your slides in Markdown - click the *Slides* button to check out the example.
{{% /callout %}}

Supplementary notes can be added here, including [code, math, and images](https://wowchemy.com/docs/writing-markdown-latex/). -->
