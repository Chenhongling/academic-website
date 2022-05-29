---
title: 'Seismic Acoustic Impedance Inversion via Optimization-Inspired Semisupervised Deep Learning'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - admin
  - Jinghuai Gao
  - Wei Zhang
  - Ping Yang

# Author notes (optional)
author_notes:
  - 'Equal contribution'
  - 'Equal contribution'

date: '2022-07-01T00:00:00Z'
doi: ''

# Schedule page publish date (NOT publication's date).
publishDate: '2022-01-01T00:00:00Z'

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ['2']

# Publication name and optional abbreviated publication name.
publication: In *IEEE TRANSACTIONS ON GEOSCIENCE AND REMOTE SENSING*
publication_short: In *IEEE TRANSACTIONS ON GEOSCIENCE AND REMOTE SENSING*

abstract: Seismic acoustic impedance inversion (SAII) aims at recovering the subsurface impedance to achieve lithology interpretation. However, its ill-posedness and nonlinearity pose a great challenge to find an optimal solution. Regularization is an effective method to solve SAII by imposing prior information, but it suffers from high computational complexity and limited inversion performance. To mitigate the above limitations, we propose an optimization-inspired semisupervised deep learning SAII approach that incorporates the advantages between the model-driven optimization algorithm and the data-driven deep learning method. Specifically, it is implemented by parameterizing the alternating iterative method (AIM) by splitting it into two parts where the convolutional neural networks are adopted to learn the regularization terms and a nonlinear mapping and thus called the proposed network as AIM-SAIINet. The proposed method can not only simultaneously invert the seismic wavelet and impedance but also obtain high-resolution data as an intermediate product to facilitate the training of AIM-SAIINet and enhance the inversion accuracy. In addition, we introduce a joint semisupervised training scheme in which the network is first jointly pretrained in a supervised manner using the synthetic training data to provide good initial values, and then, a semisupervised training scheme is adopted to fine-tune it using few labeled data pairs to achieve high inversion accuracy. The synthetic and field data examples are conducted to validate the effectiveness of AIM-SAIINet, which achieves higher inversion accuracy at a fast computational speed compared with the traditional methods.

# Summary. An optional shortened abstract.
summary: 

tags: []

# Display this page in the Featured widget?
featured: true

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

url_pdf: 'https://ieeexplore.ieee.org/abstract/document/9528894'
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


