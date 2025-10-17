---
title: 

cms_exclude: true 

# View. 
view: citation

sections:
  - block: collection
    title: "Working papers"
    content:
      folder: "research"                 # your items live in content/research/*
      page_type: ["publication"]         # render as publications
      publication_types: ["working-paper"]# ONLY working papers
      count: 100
    design:
      view: citation
      columns: 1

  - block: collection
    title: "Publications"
    content:
      folder: "research"
      page_type: ["publication"]
      # Explicit positive include for all *published* types
      publication_types:
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
