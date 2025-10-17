---
title: ""
type: widget_page

sections:
  - block: collection
    title: "Working papers"
    content:
      filters:
        # Limit to your research folder so we don't pull in other content
        folder: "research"
        # Positive include: only items explicitly tagged working-paper
        publication_type: ["working-paper"]
      count: 100
    design:
      view: citation
      columns: 1

  - block: collection
    title: "Publications"
    content:
      filters:
        folder: "research"
        # Positive include: list all *published* types you want shown
        publication_type:
          - "article-journal"
          - "report"
          - "technical-report"
          - "paper-conference"
          - "inproceedings"
      count: 200
    design:
      view: citation
      columns: 1
---
