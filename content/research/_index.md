---
title: Research Works
summary: My courses
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
      title: reseach
      filters:
        tag: research_work
        kinds:
          - section
    design:
      view: compact
      show_read_time: false
      show_date: false
      show_read_more: false
      columns: 1
---