---
title: "People"
layout: page

sections:
  - block: collection
    content:
      title: "Staff"
      page_type: author
      filters:
        role: "Staff"
      group_by: "group"  # 年级（如2023），需写在每个 author 文件中
    design:
      view: card
      columns: 3
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
      page_type: author
      filters:
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
      page_type: author
      filters:
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
