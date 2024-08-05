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
  - block: collection
    id: Career
    content:
      title: Career
      filters:
        folders:
          - event
    design:
      columns: '2'
      view: compact
---
