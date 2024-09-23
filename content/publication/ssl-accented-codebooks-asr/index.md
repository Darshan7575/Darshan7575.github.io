---
title: 'Accented Speech Recognition With Accent-specific Codebooks'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - admin3
  - Abhishek Gupta
  - Omkar Nitsure
  - Preethi Jyothi
  - Sriram Ganapathy

# Author notes (optional)
author_notes:
  - 'Equal contribution'
  - 'Equal contribution'

date: '2024-10-01T00:00:00Z'
doi: '10.21437/Interspeech.2024-2438'

# Schedule page publish date (NOT publication's date).
publishDate: '2023-12-01T00:00:00Z'

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ['paper-conference']

# Publication name and optional abbreviated publication name.
publication: In *Interspeech 2024*
publication_short: In **Interspeech 2024**

abstract: Speech accents present a serious challenge to the performance of state-of-the-art end-to-end Automatic Speech Recognition (ASR) systems. Even with self-supervised learning and pre-training of ASR models, accent invariance is seldom achieved. In this work, we propose an **accent-aware adaptation technique** for self-supervised learning that introduces a trainable set of **accent-specific codebooks** to the self-supervised architecture. These learnable codebooks enable the model to capture accent specific information during pre-training, that is further refined during ASR finetuning. On the Mozilla Common Voice dataset, our proposed approach outperforms all other accent-adaptation approaches on both seen and unseen English accents, with up to 9% relative reduction in word error rate (WER).

# Summary. An optional shortened abstract.
summary: 

tags: ['ASR','accent', 'codebooks']

# Display this page in the Featured widget?
featured: true

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

url_pdf: 'https://www.isca-archive.org/interspeech_2024/prabhu24b_interspeech.pdf'
url_code: 'https://github.com/csalt-research/accented-codebooks-asr'
url_dataset: 'https://github.com/csalt-research/accented-codebooks-asr/tree/main/data'
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
