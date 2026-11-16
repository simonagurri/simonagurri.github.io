---
title: Publications
type: landing
cms_exclude: true

sections:
  - block: collection
    id: journal
    content:
      title: Journal Articles
      filters:
        folders:
          - publications
        publication_type: 'article-journal'
    design:
      view: citation

  - block: collection
    id: underreview
    content:
      title: Under Review
      filters:
        folders:
          - publications
        publication_type: 'manuscript'
    design:
      view: citation

  - block: collection
    id: conference
    content:
      title: Conference Contributions
      filters:
        folders:
          - publications
        publication_type: 'paper-conference'
    design:
      view: citation
---
