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

abstract: The time-varying seismic super-resolution inversion technique becomes more and more attractive in seismic exploration. However, most existing inversion methods suffer from amplitude loss and manual adjustment parameters. In this letter, we present an adaptive time-varying seismic super-resolution inversion method based on the L p (0 <; p <; 1) regularization to address these issues. First, the L p -norm with 0 <; p <; 1 is applied to constrain the reflectivity to obtain a sparser and more robust solution than the L 1 regularization. To solve the nonconvex inversion problem adaptively, second, we provide a new algorithm called singular value decomposition (SVD)-Hadamard product parametrization (HPP). The idea of the new algorithm is to apply an HPP to express the L p (0 <; p ≤ 1) regularization into a sum of the L 2 regularizations that are easy to be programed and solved. Then, the SVD is adopted to solve each L 2 regularization. It is convenient to apply the L-curve method or its variants to determine the regularization parameters at each iteration for finishing the inversion adaptively. Finally, synthetic and field data examples are tested to validate the effectiveness of the proposed method. 

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
