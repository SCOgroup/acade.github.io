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
          - authors
        role: Staff
    design:
      view: card
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
          - authors
        role: Postgraduate Student
    design:
      view: card
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
          - authors
        role: Graduated Postgraduate
    design:
      view: card
      columns: 3
      people:
        show_avatar: true
        show_name: true
        show_role: true
        show_interests: true
        show_organization: false
---
