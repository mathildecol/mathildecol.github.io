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
        url: uploads/academic_cv_052526.pdf
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
      title: Working papers
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
      title: 'Research projects'
      text: |-
        - Strengthening the Implementation of a Bilingual Education Reform in Mozambique, with [Juliette Crespin-Boucaud](https://juliettecrespinboucaud.com/) (U. Namur) and Magona Sande (U. Maputo). _[Funded by an IGC SPF (January 2025)](https://www.theigc.org/collections/strengthening-implementation-bilingual-education-reform-mozambique)_ *Ongoing data collection*
        - Air pollution air students’ achievements in Côte d’Ivoire, with [Thomas Thivillion](https://www.thomasthivillon.com/). *Early stage*
        - Language of instructions & nation building in the catholic missions in DRC, with Juliette Crespin Boucaud (U. Namur), [Yannick Dupraz](https://sites.google.com/site/yannickdupraz/) (Paris Dauphine), [Catherine Guirkinger](https://catherine.guirkinger.com/) (U. Namur), [Paola Villar](https://sites.google.com/view/paolavillar/home) (Panthéon-Sorbonne, CES). *Ongoing data collection*
    design:
      columns: '1'
  - block: markdown
    id: teaching
    content:
      title: 'Teaching'
      text: |-
        - 2026: Stata training (J-PAL Morocco - Research Assistants)
        - 2024: Econometrics of causality (Univ. of Bordeaux - Master 1)
        - 2021: Introduction to R (Ministry of Nutrition in Madagascar - MEL team)
    design:
      columns: '1'
---
