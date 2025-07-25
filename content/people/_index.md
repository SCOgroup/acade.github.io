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
        tag: Staff
    design:
      view: card-grid
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
        tag: Postgraduate Student
    design:
      view: card-grid
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
        tag: Graduated Postgraduate
    design:
      view: card-grid
      columns: 3
      people:
        show_avatar: true
        show_name: true
        show_role: true
        show_interests: true
        show_organization: false
---
