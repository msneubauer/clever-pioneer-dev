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
    id: areas
    content:
      title: Research Areas
      filters:
        folders:
          - research
        kinds:
          - section
      count: 0
      offset: 0
    design:
      view: article-grid
      columns: 3
      fill_image: true
      show_date: false
      show_read_time: false
      show_read_more: false
      flip_back: false


########### Artificial Intelligence
  - block: collection
    id: ai
    content:
      title: Artificial Intelligence
      filters:
        tag: "Artificial Intelligence"
        folders:
          - research
        kinds:
          - page
      order: desc
      count: 0
      offset: 0
    design:
      view: article-grid
      columns: 3
      fill_image: true
      show_date: false
      show_read_time: false
      show_read_more: false
      flip_back: false

########### Particle Physics
  - block: collection
    id: particle-physics
    content:
      title: Particle Physics
      filters:
        tag: "Particle Physics"
        folders:
          - research
        kinds:
          - page
      order: desc
      count: 0
      offset: 0
    design:
      view: article-grid
      columns: 3
      fill_image: true
      show_date: false
      show_read_time: false
      show_read_more: false
      flip_back: false

########### Quantum
  - block: collection
    id: quantum
    content:
      title: Quantum
      filters:
        tag: "Quantum"
        folders:
          - research
        kinds:
          - page
      order: desc
      count: 0
      offset: 0
    design:
      view: article-grid
      columns: 1
      fill_image: true
      show_date: false
      show_read_time: false
      show_read_more: false
      flip_back: false

########### Team
  - block: markdown
    content:
#      title: ''
#      text: "## Team {#team}"
      title: "## Meet the Team {#team}"
      text: |-
        Our group consists of postdocs, PhD students, master's students, and collaborators working on interdisciplinary projects in AI, quantum, and particle physics.

        We welcome inquiries from prospective students and collaborators!
    design:
      columns: '1'

  - block: collection
    content:
      title: Current Members
      subtitle: ''
      text: ''
      filters:
        folders:
          - team
        user_groups:
          - "Current Members"
      count: 0
      sort_by: Params.last_name
      sort_ascending: true
    design:
      view: article-grid
      columns: 4
      fill_image: true
      show_role: true
      show_social: true
      show_interests: false
      show_organizations: true
      show_read_time: false
      show_date: false
      show_read_more: false

  - block: collection
    content:
      title: Alumni
      subtitle: Former members of the group
      text: Alumni who have moved on to exciting positions in academia and industry.
      filters:
        folders:
          - team
        user_groups:
          - "Alumni"
      count: 0
      sort_by: Params.last_name
      sort_ascending: true
    design:
      view: article-grid
      columns: 4
      fill_image: true
      show_role: true
      show_social: true
      show_interests: false
      show_organizations: true
      show_read_time: false
      show_date: false
      show_read_more: false
---
