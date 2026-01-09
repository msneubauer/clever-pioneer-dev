---
title: 'Research'
date: 2024-05-19
type: landing

design:
  spacing: '5rem'
  show_title: false

build:
  list: false   # this is needed to not show extraneous research block in collection

########### Research Areas
sections:
  - block: collection
    content:
      title: Research Areas
      text: Select an area below to explore my current and prior research
      filters:
        folders:
          - research
        kinds:
          - section
    design:
      view: article-grid
      columns: 3
      fill_image: true
      show_date: false
      show_read_time: false
      show_read_more: false
      flip_back: false

########### Team
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
