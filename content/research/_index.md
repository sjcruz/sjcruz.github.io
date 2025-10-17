---
title: "Research"
type: widget_page          # enables Page Builder
cms_exclude: true

# Everything under /research renders as a publication (citation view works)
cascade:
  page_type: publication

sections:
  - block: collection
    title: "Working papers"
    content:
      folder: "research"
      page_type: ["publication"]
      publication_type: ["working-paper"]     # <-- singular key
      count: 100
    design:
      view: citation
      columns: 1

  - block: collection
    title: "Publications"
    content:
      folder: "research"
      page_type: ["publication"]
      # Explicit include of published types
      publication_type:
        - "article-journal"
        - "paper-conference"
        - "inproceedings"
        - "report"
        - "technical-report"
      count: 200
    design:
      view: citation
      columns: 1
---
