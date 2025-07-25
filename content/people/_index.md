---
title: "People"
date: 2024-05-19
type: landing

design:
  spacing: "5rem"

sections:
  - block: collection
    content:
      title: "Staff"
      filters:
        folders:
          - people
        role: Staff
    design:
      view: article-grid
      columns: 3
      people:
        show_avatar: true
        show_name: true
        show_role: true
        show_interests: true
        show_organization: false

  - block: collection
    content:
      title: "Postgraduate Students"
      filters:
        folders:
          - people
        role: Postgraduate Student
    design:
      view: article-grid
      columns: 3
      people:
        show_avatar: true
        show_name: true
        show_role: true
        show_interests: true
        show_organization: false

  - block: collection
    content:
      title: "Graduated Postgraduates"
      filters:
        folders:
          - people
        role: Graduated Postgraduate
    design:
      view: article-grid
      columns: 3
      people:
        show_avatar: true
        show_name: true
        show_role: true
        show_interests: true
        show_organization: false
---
