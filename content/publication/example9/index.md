---
title: 'Nonstationary sparse deconvolution with the SPGL1 algorithm'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - admin
  - Siyuan Cao
  - Sanyi Yuan
  - Zhiqiang Wang
  - Yongxin Li
  - Qing Dong
  - Shian Shen
  
# Author notes (optional)
author_notes:
  - 'Equal contribution'
  - 'Equal contribution'

date: '2017-05-31T00:00:00Z'
doi: ''

# Schedule page publish date (NOT publication's date).
publishDate: '2017-01-01T00:00:00Z'

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ['1']

# Publication name and optional abbreviated publication name.
publication: In *International Geophysical Conference, Qingdao, China*
publication_short: In *International Geophysical Conference, Qingdao, China*

abstract: Conventional deconvolution is based on the stationary convolution model and theoretically requires a stationary input. However, the field data is nonstationary due to effects of anelastic attenuation and dispersion which make it necessary to compensate for the attenuation through inverse Q-filtering methods. Nevertheless, the attenuation compensation algorithm for inverse Q-filtering is inherently unstable. To solve this issue, a nonstationary sparse deconvolution (NSD) can be handled as a basis pursuit (BP) or a basis pursuit de-noising (BPDN) problem, which can also be solved by a spectral projected gradient for L1 minimization (SPGL1) in a short time. Both the synthetic data and field data prove the efficiency of the proposed method and its superiority over the results by stationary deconvolution.

# Summary. An optional shortened abstract.
summary:

tags: []

# Display this page in the Featured widget?
featured: true

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

url_pdf: 'https://library.seg.org/doi/abs/10.1190/IGC2017-051'
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