---
title: Blog
#view: article-grid
cms_exclude: true
date: 2023-10-24
type: landing

sections:
  - block: collection
    content:
      title: Recent News
      subtitle: ''
      text: ''
      page_type: blog
      # Choose how many pages you would like to display (0 = all pages)
      count: 10
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
      view: article-grid
      columns: 4
      spacing:
        padding: ['40px', '0', '0', '0']

---
