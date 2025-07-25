---
# Leave the homepage title empty to use the site title
title: ""
date: 2025-04-20
type: landing
design:
  # Default section spacing
  spacing: "6rem"
sections:
  - block: resume-biography-3
    content:
      # Choose a user profile to display (a folder name within `content/authors/`)
      username: admin
      text: ""
      # Show a call-to-action button under your biography? (optional)
      button:
        text: CV
        url: uploads/resume2025_col.pdf
    design:
      css_class: dark
      background:
        color: black
        image:
          # Add your image background to `assets/media/`.
          filename: stacked-peaks.svg
          filters:
            brightness: 1.0
          size: cover
          position: center
          parallax: false
  - block: collection
    id: publications
    content:
      title: Publications
      text: ""
      filters:
        folders:
          - publication
        exclude_featured: false
    design:
      view: citation
  - block: collection
    id: working_papers
    content:
      title: Work in progress
      text: ""
      filters:
        folders:
          - working_papers
        exclude_featured: false
    design:
      view: citation
  - block: markdown
    id: project
    content:
      title: 'Projects'
      text: |-
        - Strengthening the Implementation of a Bilingual Education Reform in Mozambique, with Juliette Crespin-Boucaud Magona Sande. *Funded by an IGC SPF (January 2025)*
    design:
      columns: '1'
  - block: markdown
    id: teaching
    content:
      title: 'Teaching'
      text: |-
        - 2024: Econometrics of causality (Univ. of Bordeaux - Master 1)
    design:
      columns: '1'
---
