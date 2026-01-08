---
title: Particle Physics
date: 2023-10-26
type: landing

sections:
  - block: markdown
    content:
      title: Particle Physics
      text: |-
        Overview of high-energy physics research, including neutrinos, vector boson scattering, etc.
    design:
      columns: '1'

  - block: collection
    content:
      title: Neutrinos Research
      text: Projects, publications, and notes on neutrino physics.
      filters:
        folders:
          - research/particle-physics/neutrinos   # ← full relative path from content/
        # Optional: only show featured or tagged items
        # featured_only: true
        # tag: "neutrinos"
      count: 0  # 0 = show all
    design:
      view: article-grid   # cards with photo/title/summary
      columns: '3'
      show_date: false
      show_read_time: false
      show_read_more: true   # links to full page

---


Why are the subfolders not showing?
