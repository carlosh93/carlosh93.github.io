---
title: "Single-pixel camera sensing matrix design for hierarchical compressed spectral clustering"
authors:
- admin
- Jorge Bacca
- Edwin Vargas
- Sergio Castillo
- Henry Arguello
date: "2019-10-24T00:00:00Z"
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: "2019-10-24T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: In *2019 IEEE International Workshop on Machine Learning for Signal Processing*
publication_short: In *MLSP 2019*

abstract: Compressive spectral imaging (CSI) acquires random projections of a spectral scene. Typically, before applying any post-processing task, e.g. clustering, it is required a computationally expensive reconstruction of the underlying 3D scene. Therefore, several works focus on improving the reconstruction quality by adaptively designing the sensing matrix aiming at better post-processing results. Instead, this paper proposes a hierarchical adaptive approach to design a sensing matrix of the single pixel camera,  such that pixel clustering  can be performed in the compressed domain. Specifically, in each step of the hierarchical model, a sensing matrix is designed such that clustering features can be extracted directly from the compressed measurements. Finally, the complete segmentation map is obtained with the majority voting method in the partial clustering results at each hierarchy step. In general, an overall accuracy of 78.94%, and 65.35% was obtained using the ``Salinas'', and `` Pavia University'' spectral image datasets, respectively.

# Summary. An optional shortened abstract.
summary: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis posuere tellus ac convallis placerat. Proin tincidunt magna sed ex sollicitudin condimentum.

tags:
- Compressive spectral clustering
- Single pixel camera
- Hierarchical clustering
- Matrix design
featured: true

links:
#- name: Custom Link
#  url: http://example.org
url_pdf: /files/mlsp_template.pdf
# url_code: '#'
# url_dataset: '#'
url_poster: 'https://sigport.org/sites/default/files/docs/poster_portrait.pdf'
# url_project: ''
# url_slides: ''
# url_source: '#'
# url_video: '#'

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
image:
  caption: 'Proposed Method'
  focal_point: ""
  preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
projects:
# - internal-project

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
# slides: example
---

