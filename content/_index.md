---
# Leave the homepage title empty to use the site title
title: Wunna Kyaw
date: 2022-10-24
type: landing

sections:
  - block: about.biography
    id: about
    content:
      title: Biography
      # Choose a user profile to display (a folder name within `content/authors/`)
      username: admin
  - block: collection
    content:
      title: Publications
      text: |-

      filters:
        folders:
          - publication
        exclude_featured: true
    design:
      columns: '2'
      view: citation
  - block: experience
    content:
      title: Experience
      date_format: Jan 2006
      items:
        - title: Summer Research Associate
          company: Flatiron Institute, Center for Computational Biology
          company_url: ''
          company_logo: flatiron
          location: New York City, United States
          date_start: '2024-05-28'
          date_end: '2024-08-30'
          description: |2-
              * Deep learning for gene expression prediction in Troyanskaya Lab at the Flatiron Institute and Princeton University
        - title: PhD Candidate
          company: UNSW Sydney, Garvan Institute of Medical Research
          company_url: ''
          company_logo: unsw
          location: Sydney, Australia
          date_start: '2021-01-31'
          date_end: '2024-08-30'
          description: |2-
              * ML for 'omics data (Bioinformatics, 2023)
              * Agent-based simulations (Cell, 2023)
              * 3D Live Imaging and Image Analysis (Cell, 2023; Nat. Protocols, 2023)
    design:
      columns: '2'
---
