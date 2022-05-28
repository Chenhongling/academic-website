---
title: 'HQS-HRINet: An unrolled deep learning method for seismic high-resolution inversion with an inaccurate wavelet'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - admin
  - JingHuai Gao
  - Zhaoqi Gao
  - Shian Shen
  - Zhiguo Wang
  - Xiudi Jiang
  
# Author notes (optional)
author_notes:
  - 'Equal contribution'
  - 'Equal contribution'

date: '2021-05-31T00:00:00Z'
doi: ''

# Schedule page publish date (NOT publication's date).
publishDate: '2021-01-01T00:00:00Z'

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ['1']

# Publication name and optional abbreviated publication name.
publication: In *82nd EAGE Annual Conference & Exhibition*
publication_short: In *82nd EAGE Annual Conference & Exhibition*

abstract:An unrolled deep neural network, called HQS-HRINet, is introduced to finish the seismic high-resolution inversion. It unrolls the iterative half-quadratic splitting (HQS) algorithm into a deep neural network and applies the residual convolutional neural network (CNN) blocks to learn the proximal mapping to avoid the design of regularization functions and complex algorithms. Further, the regularization parameter at each iteration can be explicitly learned from the training sets. Significantly, the errors brought by the inaccurate zero-phase wavelets, estimated by a simple amplitude spectral fitting, can be compensated by the error back-propagation. Finally, the synthetic and field data examples are conducted to demonstrate the effectiveness of the proposed method. 

# Summary. An optional shortened abstract.
summary:

tags: []

# Display this page in the Featured widget?
featured: true

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

url_pdf: 'https://www.earthdoc.org/content/papers/10.3997/2214-4609.202112656'
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
