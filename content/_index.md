---
# Leave the homepage title empty to use the site title
title: ''
summary: ''
date: 2022-10-24
type: landing

design:
  # Default section spacing
  spacing: '6rem'

sections:
  - block: resume-biography-3
    content:
      # Choose a user profile to display (a folder name within `content/authors/`)
      username: me
      text: ''
      # Show a call-to-action button under your biography? (optional)
#      button:
#        text: Download CV
#        url: uploads/CV.pdf
      headings:
        about: 'About Me'
        education: ''
        interests: ''
    design:
      # Use the new Gradient Mesh which automatically adapts to the selected theme colors
      background:
        gradient_mesh:
          enable: true

      # Name heading sizing to accommodate long or short names
      name:
        size: sm # Options: xs, sm, md, lg (default), xl

      # Avatar customization
      avatar:
        size: medium # Options: small (150px), medium (200px, default), large (320px), xl (400px), xxl (500px)
        shape: circle # Options: circle (default), square, rounded  

  - block: collection
    content:
      title: Featured Publications
      filters:
        folders:
          - publications
        featured_only: true
      count: 3  # or however many you want to show
    design:
      view: article-grid
      columns: 3

# NEW: Simple button-only block (no card, no background)
  - block: cta-button-list
    content:
      buttons:
        - text: See all publications
          url: /publications/
          # Optional: add icon
          # icon: book
    design:
      # Make it compact and centered
      padding: sm     # small padding
      background:
        color: transparent
      align: center   # center the button

#  - block: collection
#    content:
#      title: Recent Publications
#      text: ''
#      filters:
#        folders:
#          - publications
#        exclude_featured: false
#    design:
#      view: citation
#  
#  - block: collection
#    id: talks
#    content:
#      title: Recent & Upcoming Talks
#      filters:
#        folders:
#          - events
#    design:
#      view: card
  
  - block: collection
    id: news
    content:
      title: Recent News
      subtitle: ''
      text: ''
      # Page type to display. E.g. post, talk, publication...
      page_type: blog
      # Choose how many pages you would like to display (0 = all pages)
      count: 10
      # Filter on criteria
      filters:
        author: ''
        category: ''
        tag: ''
        exclude_featured: false
        exclude_future: false
        exclude_past: false
        publication_type: ''
      # Choose how many pages you would like to offset by
      offset: 0
      # Page order: descending (desc) or ascending (asc) date.
      order: desc
    design:
      # Choose a layout view
      view: card
      # Reduce spacing
      spacing:
        padding: [0, 0, 0, 0]
---
