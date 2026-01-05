---
title: "ProjectiveShading: Inserting 3D Objects into Indoor Images with
Complex Shadows"
authors:
- Jundan Luo
- Xiaolong Wu
- Nanxuan Zhao
- Lu Wang
- Wenbin Li
- Christian Richardt
author_notes:
- 
date: "2026-01-01"
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: ""

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["Journal article"]

# Publication name and optional abbreviated publication name.
publication: "Eurographics 2026"
publication_short: "Eurographics 2026"

abstract: Realistically inserting virtual 3D objects into real-world images requires perceptually coherent shadowing of the object and background scene. Achieving this in single-view indoor scenes with sunlight is challenging due to complex, partially visible occluders and indirect lighting. Environment maps alone cannot produce realistic shadows on virtual objects, and any representation (scene parameters) used for rendering must be practically estimable. We introduce ProjectiveShading, the first automatic method for inverse- and re-rendering that handles bi-directional shadow interactions for realistic object composition. Our key innovation is the sunlight map, a 2D image encoding direct sunlight and arbitrary occlusions. It is generated from single-view estimations using off-the-shelf models and is compatible with standard rendering engines. We also propose algorithms to estimate sunlight direction and to blend virtual and real shadows while preserving background textures. Experiments on synthetic and in-the-wild images show our method outperforms previous approaches.

# Summary. An optional shortened abstract.
summary: An automatic method for realistically compositing virtual 3D objects into real indoor images, enabling consistent shadowing for both virtual objects and the real background under occluded direct lighting.
  

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
# - name: "project"
#   url: "https://intrinsicdiffusion.github.io/"
 - name: "code"
   url: "https://github.com/JundanLuo/ProjectiveShading/"
# url_pdf: ''
# url_project: ''
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
  caption: 'Input single-view image and our composition result.'
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
