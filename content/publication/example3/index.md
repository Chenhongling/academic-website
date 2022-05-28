---
title: 'An Adaptive Time-Varying Seismic Super-Resolution Inversion Based on Lp Regularization'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - admin
  - Jinghuai Gao
  - Xiudi Jiang
  - Zhaoqi Gao
  - Wei Zhang

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
publication: In *Geophysics*
publication_short: In *Geophysics*

abstract: Seismic high-resolution processing plays a critical role in reservoir target detection. As one of the most common approaches, regularization can achieve a high-resolution inversion result. However, the performance of regularization depends on the settings of the associated parameters and constraint functions. Further, it is difficult to solve an objective function with complex constraints, and it requires designing an optimization algorithm. In addition, existing algorithms have high computational complexity, which impedes the inversion of the large data volume. To address these problems, an optimization-inspired deep learning inversion solver is proposed to solve the blind high-resolution inverse (BHRI) problems of various seismic wavelets rapidly, called BHRI-Net. The method builds on ideas from classic regularization theory and recent advances in deep learning, and it makes full use of prior information encoded in the forward operator and noise model to learn an accurate mapping relationship. It unrolls the alternating iterative BHRI algorithm into a deep neural network, and it applies the convolutional neural network to learn proximal mappings, in which all parameters of the BHRI algorithm are learned from training data. Further, the proposed network can be split into two parts and incorporate the transfer learning strategy to invert field data, which increases the flexibility of the proposed network and reduces training time. Finally, the tests on synthetic and field data show that the proposed method can effectively invert the high-resolution data and seismic wavelet from observation data with improved accuracy and high computational efficiency.

# Summary. An optional shortened abstract.
summary:

tags: []

# Display this page in the Featured widget?
featured: true

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

url_pdf: 'https://library.seg.org/doi/abs/10.1190/geo2020-0034.1'
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

{{% callout note %}}
Click the _Cite_ button above to demo the feature to enable visitors to import publication metadata into their reference management software.
{{% /callout %}}

{{% callout note %}}
Create your slides in Markdown - click the _Slides_ button to check out the example.
{{% /callout %}}

Supplementary notes can be added here, including [code, math, and images](https://wowchemy.com/docs/writing-markdown-latex/).
