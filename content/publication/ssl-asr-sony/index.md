---
title: 'Efficient infusion of self-supervised representations in Automatic Speech Recognition'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - admin3
  - Sai Ganesh Mirishkar
  - Pankaj Wasnik

# Author notes (optional)
author_notes:
  - ''
  - ''

date: '2023-12-16T00:00:00Z'
doi: ''

# Schedule page publish date (NOT publication's date).
publishDate: '2024-04-19T00:00:00Z'

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ['paper-conference']

# Publication name and optional abbreviated publication name.
publication: In *Efficient Natural Language and Speech Processing(ENLSP) workshop at NeurIPS 2023* 
publication_short: In **ENLSP workshop, NeurIPS 2023**

abstract: Self-supervised learned (SSL) models such as Wav2vec and HuBERT yield state-of-the-art results on speech-related tasks. Given the effectiveness of such models, it is advantageous to use them in conventional ASR systems. While some approaches suggest incorporating these models as a trainable encoder or a learnable frontend, training such systems is extremely slow and requires a lot of computation cycles. In this work, we propose two simple approaches that use (1) framewise addition and (2) cross-attention mechanisms to **efficiently incorporate the representations from the SSL model(s) into the ASR** architecture, resulting in models that are comparable in size with standard encoder-decoder conformer systems while also avoiding the usage of SSL models during training. Our approach results in faster training and yields significant performance gains on the _Librispeech_ and _Tedlium_ datasets compared to baselines. We further provide detailed analysis and ablation studies that demonstrate the effectiveness of our approach..

# Summary. An optional shortened abstract.
summary: 

tags: ['ASR','SSL', 'Wav2Vec', 'Hubert']

# Display this page in the Featured widget?
featured: false

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

url_pdf: 'https://arxiv.org/pdf/2404.12628'
url_code: ''
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
