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
      title: '🔬🤖 My Research'
      subtitle: ''
      text: |-
        My research is highly interdisciplinary at the intersection of particle physics, AI/ML, and quantum, aiming to understand the universe at its fundamental level and to accelerate scientific discovery through innovation. Below shows the broad areas of research I am interested in. Click to find more in-depth information on each.
    design:
      columns: 1

  - block: collection
    content:
      title: Selected Research
      text: Here are a selection of research projects that I have worked on over the years.
      filters:
        folders:
        - research
#          - research/ai
#          - research/quantum
#          - research/particle-physics          # ← Add this (or whatever your exact folder name is)
          # Optional: featured_only: true         # Only show if you mark folders as featured
        kinds:
          - page
      count: 0
    design:
      view: article-grid
      fill_image: true
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
