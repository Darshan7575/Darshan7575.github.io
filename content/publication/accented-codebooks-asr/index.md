---
title: 'Accented Speech Recognition With Accent-specific Codebooks'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - admin3
  - Preethi Jyothi
  - Sriram Ganapathy
  - Vinit Unni

# Author notes (optional)
author_notes:
  - ''
  - ''

date: '2023-12-01T00:00:00Z'
doi: '10.18653/v1/2023.emnlp-main.444'

# Schedule page publish date (NOT publication's date).
publishDate: '2023-12-01T00:00:00Z'

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ['paper-conference']

# Publication name and optional abbreviated publication name.
publication: In *Empirical Methods in Natural Language Processing(EMNLP) 2023*
publication_short: In **EMNLP 2023**

abstract: Speech accents pose a significant challenge to state-of-the-art automatic speech recognition (ASR) systems. Degradation in performance across underrepresented accents is a severe deterrent to the inclusive adoption of ASR. In this work, we propose a novel **accent adaptation approach** for end-to-end ASR systems using **cross-attention with a trainable set of codebooks**. These learnable codebooks capture accent-specific information and are integrated within the ASR encoder layers. The model is trained on accented English speech, while the test data also contained accents which were not seen during training. On the _Mozilla Common Voice_ multi-accented dataset, we show that our proposed approach yields significant performance gains not only on the seen English accents (up to 37% relative improvement in word error rate) but also on the unseen accents (up to 5% relative improvement in WER). Further, we illustrate benefits for a **zero-shot transfer** setup on the _L2Artic_ dataset. We also compare the performance with other approaches based on accent adversarial training.

# Summary. An optional shortened abstract.
summary: 

tags: ['ASR','accent', 'codebooks']

# Display this page in the Featured widget?
featured: true

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

url_pdf: 'https://aclanthology.org/2023.emnlp-main.444.pdf'
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
