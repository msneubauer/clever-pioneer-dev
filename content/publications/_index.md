---
title: Publications
cms_exclude: true
date: 2023-10-24
type: landing

sections:
  - block: collection
    content:
      title: Featured Publications
      filters:
        folders:
          - publications
        featured_only: true
    design:
      view: article-grid
      columns: 3
  
  - block: collection
    content:
      title: Recent Publications
      text: ''
      count: 0 # Set count to 0 to display all items
      filters:
        folders:
          - publications
        exclude_featured: false
    design:
      view: citation

# View.
#view: citation

# Optional header image (relative to `static/media/` folder).
banner:
  caption: ''
  image: ''
---
