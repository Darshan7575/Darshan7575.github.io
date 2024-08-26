---
# Leave the homepage title empty to use the site title
title: ""
date: 2024-07-28
type: landing

design:
  # Default section spacing
  spacing: "2rem"

sections:
  - block: my-biography
    content:
      # Choose a user profile to display (a folder name within `content/authors/`)
      username: admin
      text: ""
      # Show a call-to-action button under your biography? (optional)
      button:
        text: Download Résumé
        url: uploads/resume.pdf
    design:
      css_class: light
      background:
        image:
          # Add your image background to `assets/media/`.
          filename: wave.svg
          filters:
            brightness: 0.9
          size: cover
          position: top
          parallax: true
    skills:
      block: my-skills
      content:
        username: admin
  - block: collection
    id: papers
    content:
      title: Recent Publications
      text: ""
      filters:
        folders:
          - publication
        exclude_featured: false
    design:
      view: citation
      columns: '1'
  - block: my-collection
    id: updates
    content:
      title: Life Updates
      subtitle: ''
      text: ''
      # Use https://gist.github.com/rxaviers/7360908 for copy-paste emojis
      news_list:
        - block: news
          title: 3 first-authored papers accepted in **Interspeech 2024**
          icon: 🎉
          date: Aug, 2024
          content: |
            Details coming soon
        - block: news
          title: Joined **Ph.D program** at IITB under Prof. Preethi Jyothi
          icon: 📢
          date: Aug, 2024
          content: |
            Will be supervised by Prof. Preethi Jyothi where I will be working towards pushing the boundaries of ASR and other speech tasks 🎯. Exciting times ahead ✨.
        - block: news
          title:
          small_title: Attended S4P workshop at DA-IICT
          icon: 
          date: July, 2024
          content: 
        - block: news
          title: 1 first-authored paper accepted in ENLSP workshop at **NeurIPS 2023**
          icon: 🎉
          date: Nov, 2023
          content: |-
            Our paper titled <a href='https://arxiv.org/abs/2404.12628'>Efficient infusion of self-supervised representations in Automatic Speech Recognition</a> has been accepted at the Efficient Natural Language and Speech Processing (ENLSP) workshop of NeurIPS 2023 to be held in New Orleans, USA 😄.
        - block: news
          title: 1 first-authored paper accepted in **EMNLP 2023**
          date: Sept, 2023
          icon: 🎉
          content: |
            Our paper titled <a href="https://aclanthology.org/2023.emnlp-main.444/">Accented Speech Recognition With Accent-specific Codebooks</a> has been accepted at the main conference of EMNLP 2023 to be held in Singapore 😃.
            
            [ ==Microsoft Reserach Travel Grant== awarded to attend the conference ]
        - block: news
          title: Joined **Sony Research** as an ASR Research intern
          icon: 💼
          date: July, 2023
          content: |
            Joined the Audio Content Analysis team at Sony Research India as a resarch intern. I am working on integrating speech foundation models into downstream ASR systems. 
        - block: news
          title: Graduated M.Tech with **Dr. George B Fernandes Award** 
          icon: 🎓
          date: June, 2023
          content: |
            Finished my master's from IIT Bombay with Dr. George B Fernandes Award for Excellence in Research 🎉. This award was from my thesis titled `Improving Accented Automatic Speech Recognition using Cross-attention`.
    design:
      background:
        # Choose a color such as from https://html-color-codes.info
        color: '#F2F2F2'
        # Text color (true=light, false=dark, or remove for the dynamic theme color).
        text_color_light: false
        filters:
            brightness: 0.95
  - block: collection
    id: blogs
    content:
      title: Featured Blogs
      filters:
        folders:
          - publication
        featured_only: true
    design:
      view: article-grid
      columns: 2
---
