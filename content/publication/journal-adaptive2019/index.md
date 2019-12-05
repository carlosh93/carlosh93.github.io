---
title: "Adaptive grayscale compressive spectral imaging using optimal blue noise coding patterns"
authors:
- Nelson Diaz
- admin
- Henry Arguello
date: "2019-09-01T00:00:00Z"
doi: "https://doi.org/10.1016/j.optlastec.2019.03.038"

# Schedule page publish date (NOT publication's date).
publishDate: "2019-04-16T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["2"]

# Publication name and optional abbreviated publication name.
publication: "*ELSEVIER Optics & Laser Technology*"
publication_short: "Optics & Laser Technology"

abstract: Imaging spectroscopy collects the spectral information of a scene by sensing all the spatial information across the electromagnetic wavelengths and are useful for applications in surveillance, agriculture, and medicine, etc. In contrast, compressive spectral imaging (CSI) systems capture compressed projections of the scene, which are then used to recover the whole spectral scene. A key component in such optical systems is the coded aperture which performs the scene codification and defines the sensing scheme of the system. The proper design of the coded aperture entries leads to good quality reconstructions with few compressed measurements. Commonly, the acquired measurements are prone to saturation due to the limited dynamic range of the sensor, however, the saturation is not usually taking into account in the coded aperture design. The saturation errors in compressed measurements are unbounded leading to poor reconstructions since CSI recovery algorithms only provide solutions for bounded or noisy-bounded errors. This paper proposes an adaptive grayscale coded aperture design which combines the advantages of blue noise and block-unblock coding patterns. Blue noise coding patterns are optimal and provide high-quality image reconstructions on regions of non-saturated compressed pixels. On the other hand, the block-unblock coding patterns provide redundancy in the sampling which helps to reduce the saturation in the detector. Further, the saturation is reduced between snapshots by using an adaptive filter which updates the entries of the grayscale coded aperture based on the previously acquired measurements. The proposed coded apertures are optimized such that the number of saturated measurements is minimized. Extensive simulations and an experimental setup were made using the coded aperture snapshot spectral imager (CASSI) sensing scheme, where the results show an improvement up to 2 dB of peak signal-to-noise ratio is achieved when the proposed adaptive grayscale blue noise and block-unblock coded aperture (AGBBCA) design is compared with adaptive grayscale block-unblock coded apertures (AGBCA).

# Summary. An optional shortened abstract.
summary: This paper proposes an adaptive grayscale coded aperture design which combines the advantages of blue noise and block-unblock coding patterns. Blue noise coding patterns are optimal and provide high-quality image reconstructions on regions of non-saturated compressed pixels. On the other hand, the block-unblock coding patterns provide redundancy in the sampling which helps to reduce the saturation in the detector.

tags:
- Compressive spectral imaging
- Spectral imaging systems
- Coded aperture design
- Grayscale coded aperture
- Adaptive imaging
- Computational imaging
featured: false

# links:
# - name: ""
#   url: ""
url_pdf: /files/diaz2019adaptivegrayscale.pdf
url_code: 'https://github.com/carlosh93/Adaptive-Grayscale-CSI-Blue-Noise-Patterns'
# url_dataset: ''
# url_poster: ''
# url_project: ''
# url_slides: ''
# url_source: ''
# url_video: ''

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
image:
  caption: 'Image credit: [**Unsplash**](https://unsplash.com/photos/jdD8gXaTZsc)'
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
# slides: example
---