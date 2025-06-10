---
title: "IntrinsicDiffusion: Joint Intrinsic Layers from Latent Diffusion Models"
authors:
    - Jundan Luo
    - Duygu Ceylan
    - Jae Shin Yoon
    - Nanxuan Zhao
    - Julien Philip
    - Anna Frühstück
    - Wenbin Li
    - Christian Richardt
    - Tuanfeng Y. Wang
author_notes:
- 
date: "2024-01-01"
doi: "10.1145/3641519.3657472"

# Schedule page publish date (NOT publication's date).
publishDate: ""

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ['paper-conference']

# Publication name and optional abbreviated publication name.
publication: "SIGGRAPH 2024"
publication_short: "SIGGRAPH 2024"

abstract: Reasoning about the intrinsic properties of an image, such as albedo, illumination, and surface geometry, is a long-standing problem with many applications in image editing and compositing. Existing solutions to this ill-posed problem either heavily rely on manually designed priors or learn priors from limited datasets that lack diversity. Hence, they fall short in generalizing to in-the-wild test scenarios. In this paper, we show that a large-scale text-to-image generation model trained on a massive amount of visual data can implicitly learn intrinsic image priors. In particular, we introduce a novel conditioning mechanism built on top of a pre-trained foundational image generation model to jointly predict multiple intrinsic modalities from an input image. We demonstrate that predicting different modalities in a collaborative manner improves the overall quality. This design also enables mixing datasets with annotations of only a subset of the modalities during training, contributing to the generalizability of our approach. Our method achieves state-of-the-art performance in intrinsic image decomposition, both qualitatively and quantitatively. We also demonstrate downstream image editing applications, such as relighting and retexturing.

# Summary. An optional shortened abstract.
summary: Jundan Luo, Duygu Ceylan, Jae Shin Yoon, 
  Nanxuan Zhao, Julien Philip, Anna Frühstück, 
  Wenbin Li, Christian Richardt, Tuanfeng Y. Wang

#tags:
#- Computer Vision
#- Computer Graphics
#- Inverse Rendering
#- Intrinsic Image Decomposition
featured: true

links:
# - name: "pdf"
#   url: 'https://purehost.bath.ac.uk/ws/portalfiles/portal/304058985/Jundan_s_TVCG_submission.pdf'
# - name: "supp doc"
#   url: "https://drive.google.com/file/d/13yi0vXYD1Ph5-noZr_Ndx0_SHHtoQrwq/view?usp=sharing"
# - name: "supp materials"
#   url: "https://drive.google.com/file/d/1B2oe3c2tYZwYyOwvRHGoyCbNBWGH6lJb/view?usp=drive_link"
# - name: "presentation"
#   url: "https://www.youtube.com/watch?v=BvoYwCdzoZU"
# - name: "code"
#   url: "https://github.com/JundanLuo/CRefNet"
# url_pdf: ''
url_project: 'https://intrinsicdiffusion.github.io/'
# url_code: ''
# url_dataset: ''
# url_poster: ''
# url_slides: ''
# url_source: ''
# url_video: ''

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
image:
  placement: 3
  caption: 'Intrinsic image decomposition and its applications.'
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
