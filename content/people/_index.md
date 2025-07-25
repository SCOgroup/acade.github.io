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
      content_type: author
      filters:
        folders:
          - author
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
      content_type: author
      filters:
        folders:
          - author
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
      content_type: author
      filters:
        folders:
          - author
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
