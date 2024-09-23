---
title: 'SALSA: Speedy ASR-LLM Synchronous Aggregation'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - Ashish Mittal
  - admin3
  - Sunita Sarawagi
  - Preethi Jyothi

# Author notes (optional)
author_notes:
  - 'Equal contribution'
  - 'Equal contribution'

date: '2024-10-02T00:00:00Z'
doi: '10.21437/Interspeech.2024-2499'

# Schedule page publish date (NOT publication's date).
publishDate: '2023-12-01T00:00:00Z'

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ['paper-conference']

# Publication name and optional abbreviated publication name.
publication: In *Interspeech 2024* (nominted)
publication_short: In **Interspeech 2024** [ ==nominted for Best Student Paper Award== ]

abstract: Harnessing pre-trained LLMs to improve ASR systems, particularly for low-resource languages, is now an emerging area of research. Existing methods range from using LLMs for ASR error correction to tightly coupled systems that replace the ASR decoder with the LLM. These approaches either increase decoding time or require expensive training of the cross-attention layers. We propose SALSA, which couples the **decoder layers of the ASR** to the **LLM decoder**, while **synchronously advancing both decoders**. Such coupling is performed with a simple projection of the last decoder state, and is thus significantly more training efficient than earlier approaches. A challenge of our proposed coupling is handling the mismatch between the tokenizers of the LLM and ASR systems. We handle this mismatch using cascading tokenization with respect to the LLM and ASR vocabularies. We evaluate SALSA on 8 low-resource languages in the FLEURS benchmark, yielding substantial WER reductions of up to 38%.

# Summary. An optional shortened abstract.
summary: 

tags: ['ASR','LLM']

# Display this page in the Featured widget?
featured: true

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

url_pdf: 'https://www.isca-archive.org/interspeech_2024/mittal24_interspeech.pdf'
url_code: 'https://github.com/csalt-research/salsa'
url_dataset: ''
url_poster: ''
url_project: ''
url_slides: 'slides.pdf'
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
