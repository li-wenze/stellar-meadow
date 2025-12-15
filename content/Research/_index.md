---
title: Research
summary: My research
type: landing

cascade:
  - target:
      path: '{/research/*/**}'
    type: docs
    params:
      show_breadcrumb: true

sections:
  - block: collection
    id: research
    content:
      title: research
      filters:
        tag: research
        kinds:
          - section
    design:
      view: article-grid
      show_read_time: false
      show_date: false
      show_read_more: false
      columns: 1
---
