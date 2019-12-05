---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: "Coded aperture design for compressive spectral subspace clustering"
authors: 
- admin
- Jorge Bacca
- Henry Arguello
date: "2018-10-26T15:15:15-05:00"
doi: "https://doi.org/10.1109/JSTSP.2018.2878293"

# Schedule page publish date (NOT publication's date).
publishDate: "2018-12-17T15:15:15-05:00"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["2"]

# Publication name and optional abbreviated publication name.
publication: "**IEEE** *Journal of Selected Topics in Signal Processing* 2018"
publication_short: "IEEE JSTSP"

abstract: "Compressive spectral imaging (CSI) acquires compressed observations of a spectral scene by applying different coding patterns at each spatial location and then performing a spectral-wise integration. Relying on compressive sensing, spectral image reconstruction is achieved by using nonlinear and relatively expensive optimization-based algorithms. In the CSI literature, several works have focused on improving reconstructions quality by properly designing the set of coding patterns. However, signal recovery is not actually necessary in many signal processing applications. For instance, assuming that compressed measurements with similar characteristics lie on the same subspace, unsupervised methods such as subspace clustering can be used to separate them into the same cluster. Since the structure of compressed measurements is defined by the applied codification, it is possible to improve clustering performance. This paper proposes to design a set of coding patterns such that inter-class and intra-class data structure is preserved after the CSI acquisition in order to improve clustering results directly on the compressed domain. To validate the coding pattern design, an algorithm based on sparse subspace clustering (SSC) is proposed to perform clustering on the compressed measurements. The proposed algorithm adds a three-dimensional (3-D) spatial regularizer to the SSC problem exploiting the spatial correlation of spectral images. In general, an overall accuracy up to 83.81% is obtained, when noisy measurements are assumed. In addition, a difference of at most 4% in terms of overall accuracy was observed when comparing the clustering results obtained by the full 3-D data with those achieved using CSI measurements acquired with the proposed coding pattern design."

# Summary. An optional shortened abstract.
summary: "This paper proposes to design a set of coding patterns such that inter-class and intra-class data structure is preserved after the CSI acquisition in order to improve clustering results directly on the compressed domain. To validate the coding pattern design, an algorithm based on sparse subspace clustering (SSC) is proposed to perform clustering on the compressed measurements."

tags:
- Compressive Spectral imaging
- Coded Aperture Design
- Unsupervised Classification
- Subspace Clustering
featured: false

# Custom links (optional).
#   Uncomment and edit lines below to show custom links.
# links:
# - name: Follow
#   url: https://twitter.com
#   icon_pack: fab
#   icon: twitter

url_pdf: /files/hinojosa2018csiclustering.pdf
url_code: 'https://github.com/carlosh93/compressive_spectral_subspace_clustering'
#url_dataset:
url_poster: /files/poster_coded_design_clustering.pdf
#url_project:
#url_slides:
#url_source:
#url_video:

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
# Focal points: Smart, Center, TopLeft, Top, TopRight, Left, Right, BottomLeft, Bottom, BottomRight.
image:
  caption: "CSI subspace clustering workflow"
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
#slides: ""
---
