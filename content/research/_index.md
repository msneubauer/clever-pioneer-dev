---
title: 'Research'
date: 2024-05-19
type: landing

design:
  # Section spacing
  spacing: '5rem'

# Page sections
sections:
  - block: markdown
    content:
      title: '📚 My Research'
      subtitle: ''
      text: |-
        Use this area to speak to your mission. I'm a research scientist in the Moonshot team at DeepMind. I blog about machine learning, deep learning, and moonshots.

        I apply a range of qualitative and quantitative methods to comprehensively investigate the role of science and technology in the economy. $\sum_{i = 0}^N 2i = y$

        Please reach out to collaborate 😃 
        An equation: $$\int_{-\infty}^{\infty} e^{-x^2} dx$$.
    design:
      columns: 1

  - block: collection
    content:
      title: Selected Research
      text: Here are a selection of research projects that I have worked on over the years.
      filters:
        folders:
          - research
    design:
      view: article-grid
      fill_image: false
      columns: 3
      show_date: false
      show_read_time: false
      show_read_more: false
      flip_back: false

  - block: markdown
    content:
      title: ''
      text: "## Team {#team}"
    design:
      columns: '1'

  - block: collection
    content:
      title: Team & Collaborators
      text: Current members, postdocs, students, and collaborators. Click cards for full profiles.
      filters:
        folders:
          - team           # ← Your team folder
        # Optional: featured_only: true  (if you mark some as featured)
      count: 0               # 0 = show all
      sort_by: title         # or date, lastmod
      sort_ascending: true
    design:
      view: article-grid     # ← This gives nice cards!
      columns: '3'           # '2' or '4' depending on page width
      flip_back: false
      show_date: false
      show_read_more: false  # No "Read more" needed
      show_read_time: false
---
