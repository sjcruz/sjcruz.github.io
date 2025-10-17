---
title: Research
cms_exclude: true

# View.
view: citation

# Optional header image (relative to `static/media/` folder).
banner:
  caption: ''
  image: ''
---

 - block: collection
    id: papers
    content:
      title: Working papers
      filters:
        folders:
          - research
        featured_only: true
    design:
      view: article-grid
      columns: 2
  - block: collection
    content:
      title: Recent Publications
      filters:
        folders:
          - research
        exclude_featured: TRUE
      view: article-grid
      columns: 2
