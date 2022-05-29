---
title: 'A Sequential Iterative Deep Learning Seismic Blind High-Resolution Inversion'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - admin
  - Jinghuai Gao
  - Zhaoqi Gao
  - Daoyu Chen
  - Tao Yang

# Author notes (optional)
author_notes:
  - 'Equal contribution'
  - 'Equal contribution'

date: '2021-07-01T00:00:00Z'
doi: ''

# Schedule page publish date (NOT publication's date).
publishDate: '2021-01-01T00:00:00Z'

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ['2']

# Publication name and optional abbreviated publication name.
publication: In *IEEE Journal of Selected Topics in Applied Earth Observations and Remote Sensing*
publication_short: In *IEEE Journal of Selected Topics in Applied Earth Observations and Remote Sensing*

abstract: Seismic blind high-resolution inversion (BHRI) aims at retrieving the high-resolution data to characterize the stratigraphic structures in the case of an unknown seismic wavelet. However, the unknown wavelet and ill-posedness pose a great challenge to the high-resolution inversion. Regularization-based BHRI is an effective approach. However, it is sensitive to the sets of initial values, regularization terms, and regularization parameters and suffers from computational burden problems. To address these issues, we propose a sequential iterative deep learning method (SIDLM) to implement a BHRI in a fast computational speed, which incorporates three learned components to sequentially invert initial high-resolution data, seismic wavelet, and final high-resolution data in an end-to-end fashion. Specifically, to mitigate the influence of initial values, a data-driven network U-Net is adopted to learn an initial high-resolution data. Furthermore, the architecture makes use of prior information encoded in the forward operator to build a new general alternating direction method of multipliers (ADMM)-like iterative deep neural network, instead of the traditional alternating iterative inversion. The proposed ADMM-like network utilizes the convolutional neural networks to learn the proximal operators to solve each subproblems in alternating iterative inversion. Therefore, all parameters of BHRI, such as the regularization parameters and transform operator, can be implicitly learned from the training datasets in an end-to-end fashion, not limited to the form of the penalty function. Finally, the synthetic and field data examples are conducted to demonstrate the effectiveness of the proposed SIDLM.

# Summary. An optional shortened abstract.
summary:

tags: []

# Display this page in the Featured widget?
featured: true

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

url_pdf: 'https://ieeexplore.ieee.org/abstract/document/9497758'
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
  caption: 'Image credit: [**Unsplash**](https://unsplash.com/photos/pLCdAaMFLTE)'
  focal_point: ''
  preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
projects:
  - example

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
slides: example
---

