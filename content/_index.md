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
  - block: experience
    content:
      title: Experience
      date_format: Jan 2006
      items:
        - title: Postdoc
          company: Victor Chang Cardiac Research Institute
          company_url: ''
          company_logo: vccri
          location: Sydney, Australia
          date_start: '2025-08-04'
          date_end: '2025-08-01'
          description: |2-
              * DNA language models for computational genomics
        - title: Research Associate & Guest Researcher
          company: Flatiron Institute, Center for Computational Biology
          company_url: ''
          company_logo: flatiron
          location: New York City, United States
          date_start: '2024-05-28'
          date_end: '2025-08-01'
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
  - block: collection
    content:
      title: Main Research
      text: |-

      filters:
        folders:
          - publication
        exclude_featured: true
    design:
      columns: '2'
      view: citation
  - block: collection
    content:
      title: Other Research
      text: |-

      filters:
        folders:
          - publication2
        exclude_featured: true
    design:
      columns: '2'
      view: citation
---
