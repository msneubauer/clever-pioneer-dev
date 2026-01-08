---
title: Particle Physics

sections:
  - block: markdown
    content:
      title: Overview
      text: |-
        Overview of research in particle physics, including neutrinos, vector boson scattering, and Higgs boson physics.
    design:
      columns: '1'

  - block: collection
    content:
      title: Neutrinos Projects
      text: Ongoing and completed projects in neutrino physics.
      filters:
        folders:
          - research/particle-physics/neutrinos  # ← Full relative path from content/
        # Optional filters: featured_only: true (only show featured projects)
        # tag: "Neutrinos" (if you use tags)
      count: 0  # 0 = show all items in the folder
      sort_by: date
      sort_ascending: false  # Newest first
    design:
      view: article-grid  # ← This renders as cards!
      columns: '3'  # Adjust: '2' for narrower, '4' for more
      flip_back: false
      show_date: true  # Show project date in card
      show_read_time: false
      show_read_more: true  # "Read more" link to full page
---