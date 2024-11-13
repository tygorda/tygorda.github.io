---
# Leave the homepage title empty to use the site title
title: ""
date: 2024-11-11
type: landing

design:
  # Default section spacing
  spacing: "5em"

sections:
  - block: collection
    id: talks
    content:
      count: 0
      title: Talks (partial list)
      filters:
        folders:
          - talks
        featured_only: false
    design:
      view: citation
      columns: 1
---