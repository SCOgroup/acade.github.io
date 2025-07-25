---
title: "People"
type: landing

design:
  spacing: "6rem"

sections:
  - block: collection
    content:
      title: "Staff"
      content_type: author
      filters:
        folders: []
        role: "Staff"
      group_by: "group"
    design:
      view: card
      columns: 1
      spacing:
        padding: [1rem, 1rem, 1rem, 1rem]
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
        folders: []
        role: "Postgraduate Student"
      group_by: "group"
    design:
      view: card
      columns: 3
      spacing:
        padding: [1rem, 1rem, 1rem, 1rem]
      people:
        show_avatar: true
        show_name: true
        show_role: false
        show_interests: true
        show_organization: false

  - block: collection
    content:
      title: "Graduated Postgraduates"
      content_type: author
      filters:
        folders: []
        role: "Graduated Postgraduate"
      group_by: "group"
    design:
      view: card
      columns: 3
      spacing:
        padding: [1rem, 1rem, 1rem, 1rem]
      people:
        show_avatar: true
        show_name: true
        show_role: false
        show_interests: true
        show_organization: false
---
