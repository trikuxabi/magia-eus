---
# Leave the homepage title empty to use the site title
title: ''
summary: ''
date: 2026-02-19
type: landing

design:
  # Default section spacing
  spacing: '6rem'

sections:
  - block: markdown
    id: hero
    content:
      title: Magia gidaliburua
      subtitle: Ikasi magia, euskaraz.
      text: Adin guztietako magoentzat kartomagia hastapena.
    design:
      background:
        gradient_mesh:
          enable: true

  - block: collection
    id: papers
    content:
      title: Gidaliburuak
      filters:
        folders:
          - gidaliburuak
        featured_only: false
    design:
      view: card
      columns: 2

  - block: collection
    id: news
    content:
      title: Berriak
      subtitle: ''
      text: ''
      # Page type to display. E.g. post, talk, publication...
      page_type: blog
      # Choose how many pages you would like to display (0 = all pages)
      count: 1
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
