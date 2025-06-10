---
title: "NIID-Net: adapting surface normal knowledge for intrinsic image decomposition in indoor scenes"
authors:
- Jundan Luo*
- Zhaoyang Huang*
- Yijin Li
- Xiaowei Zhou
- Guofeng Zhang
- Hujun Bao
author_notes:
- "Equal contribution"
- "Equal contribution"
date: "2020-09-17"
doi: "10.1109/TVCG.2020.3023565"

# Schedule page publish date (NOT publication's date).
publishDate: "2020-09-17"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["article-journal"]

# Publication name and optional abbreviated publication name.
publication: "TVCG 2020"
publication_short: "TVCG 2020"

abstract: Intrinsic image decomposition, i.e. , decomposing a natural image into a reflectance image and a shading image, is used in many augmented reality applications for achieving better visual coherence between virtual contents and real scenes. The main challenge is that the decomposition is ill-posed, especially in indoor scenes where lighting conditions are complicated, while real training data is inadequate. To solve this challenge, we propose NIID-Net, a novel learning-based framework that adapts surface normal knowledge for improving the decomposition. The knowledge learned from relatively more abundant data for surface normal estimation is integrated into intrinsic image decomposition in two novel ways. First, normal feature adapters are proposed to incorporate scene geometry features when decomposing the image. Secondly, a map of integrated lighting is proposed for propagating object contour and planarity information during shading rendering. Furthermore, this map is capable of representing spatially-varying lighting conditions indoors. Experiments show that NIID-Net achieves competitive performance in reflectance estimation and outperforms all previous methods in shading estimation quantitatively and qualitatively. The source code of our implementation is released at https://github.com/zju3dv/NIID-Net .

# Summary. An optional shortened abstract.
summary: Jundan Luo*, Zhaoyang Huang*, Yijin Li, 
  Xiaowei Zhou, Guofeng Zhang, Hujun Bao


#tags:
#- Computer Vision
#- Computer Graphics
#- Inverse Rendering
#- Intrinsic Image Decomposition
#- Augmented Reality
#- Image Editing
featured: true

links:
#- name: "pdf"
#  url: 'http://www.cad.zju.edu.cn/home/gfzhang/papers/NIID-Net/NIID-Net.pdf'
- name: "supplement"
  url: "http://www.cad.zju.edu.cn/home/gfzhang/papers/NIID-Net/NIID-Net-supple.pdf"
#- name: "presentation"
#  url: "https://www.youtube.com/watch?v=BvoYwCdzoZU"
#- name: "project"
#  url: "https://zju3dv.github.io/niid/"
#- name: "code"
#  url: "https://github.com/zju3dv/NIID-Net"
url_pdf: 'http://www.cad.zju.edu.cn/home/gfzhang/papers/NIID-Net/NIID-Net.pdf'
url_project: 'https://zju3dv.github.io/niid/'
url_code: 'https://github.com/zju3dv/NIID-Net'
# url_dataset: ''
# url_poster: ''
# url_slides: ''
# url_source: ''
url_video: 'https://www.youtube.com/watch?v=BvoYwCdzoZU'

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
image:
  placement: 3
  caption: 'One example from an edited image sequence.'
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
