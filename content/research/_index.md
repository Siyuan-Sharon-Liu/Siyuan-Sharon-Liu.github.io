---
title: Research
summary: My research
type: landing

# cascade:
#   - target:
#       path: '{/research/*/**}'
#     type: docs
#     params:
#       show_breadcrumb: true

design:
  # Section spacing
  spacing: '5rem'

# Page sections
sections:
  - block: collection
    content:
      title: Selected Projects
      text: I enjoy making things. Here are a selection of projects that I have worked on over the years.
      filters:
        folders:
          - research
    design:
      view: article-grid
      fill_image: false
      columns: 1
      show_date: false
      show_read_time: false
      show_read_more: false
---