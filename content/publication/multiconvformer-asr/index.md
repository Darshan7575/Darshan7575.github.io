---
title: 'Multi-Convformer: Extending Conformer with Multiple Convolution Kernels'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - admin3
  - Yifan Peng
  - Preethi Jyothi
  - Shinji Watanabe

# Author notes (optional)
author_notes:
  - ''
  - ''

date: '2024-10-02T00:00:00Z'
doi: '10.21437/Interspeech.2024-2384'

# Schedule page publish date (NOT publication's date).
publishDate: '2023-10-02T00:00:00Z'

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ['paper-conference']

# Publication name and optional abbreviated publication name.
publication: In *Interspeech 2024*
publication_short: In **Interspeech 2024**

abstract: Convolutions have become essential in state-of-the-art end-to-end Automatic Speech Recognition~(ASR) systems due to their efficient modelling of local context. Notably, its use in Conformers has led to superior performance compared to vanilla Transformer-based ASR systems. While components other than the convolution module in the Conformer have been reexamined, altering the convolution module itself has been far less explored. Towards this, we introduce **Multi-Convformer** that uses **multiple convolution kernels** within the convolution module of the Conformer in conjunction with gating. This helps in improved modeling of local dependencies at varying granularities. Our model rivals existing Conformer variants such as CgMLP and E-Branchformer in performance, while being more parameter efficient. We empirically compare our approach with Conformer and its variants across four different datasets and three different modelling paradigms and show up to 8% relative word error rate~(WER) improvements.

# Summary. An optional shortened abstract.
summary: 

tags: ['ASR','convolution', 'architecture']

# Display this page in the Featured widget?
featured: true

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

url_pdf: 'https://www.isca-archive.org/interspeech_2024/prabhu24_interspeech.pdf'
url_code: 'https://github.com/espnet/espnet'
url_dataset: ''
url_poster: 'poster.pdf'
url_project: ''
url_slides: ''
url_source: ''
url_video: ''

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
image:
  caption: 'Overview of our proposed architecture'
  size: cover
  filters:
    brightness: 0.9
  focal_point: ''
  preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
projects:
  - ''

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
slides:  
---
