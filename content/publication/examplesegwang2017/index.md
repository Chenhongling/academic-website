---
title: 'Sparse-spike deconvolution via curvelet transform and sparse-matrix factorization'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - Zhiqiang Wang
  - Siyuan Cao
  - Xiao Pan
  - Yongxin LI
  - admin

# Author notes (optional)
author_notes:
  - 'Equal contribution'
  - 'Equal contribution'

date: '2017-07-01T00:00:00Z'
doi: ''

# Schedule page publish date (NOT publication's date).
publishDate: '2017-01-01T00:00:00Z'

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ['1']

# Publication name and optional abbreviated publication name.
publication: In *2017 SEG International Exposition and Annual Meeting*
publication_short: In *2017 SEG International Exposition and Annual Meeting*

abstract: We proposed a multitrace semiblind nonstationary deconvolution method. The proposed method estimates reflectivity and source wavelet simultaneously for pursuing high-resolution seismic processing. The mathematical framework is derived based on convolution exchange law and Fourier transform property. In this framework, seismic records are treated as the convolution of a time-varying wavelet and nonattenuated reflectivity or the convolution of a constant wavelet and attenuated reflectivity. Using these two equivalence relations, we devise an objective function containing two variables, the reflectivity and wavelet. In addition, we add the 2-D total variation constraint to the cost function, which preserves lateral and vertical continuity of the estimated reflectivity. The cost function is solved by alternating iteration and proximal splitting methods, under the assumptions of a known attenuation model and sparse reflectivity. In addition, the mathematical framework is extended to implement semiblind deconvolution in an approximate layered earth model. To demonstrate the effectiveness of the proposed method, we apply the proposed method to synthetic data and field data and confirm that the proposed method can achieve better reflectivity and source wavelet.

# Summary. An optional shortened abstract.
summary: 

tags: []

# Display this page in the Featured widget?
featured: false

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

url_pdf: 'https://onepetro.org/SEGAM/proceedings-abstract/SEG17/All-SEG17/SEG-2017-17584882/103051'
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
  - other

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
slides: example
---

