---
title: "People"
type: landing # ✅ 必须是 widget_page，用于支持 sections
layout: page

design:
  # Default section spacing
  spacing: "6rem"

sections:
  - block: collection
    content:
      title: "Staff"
      page_type: author        # ✅ 正确的写法是 page_type，而不是 filters.role
      filters:
        role: "Staff"          # ✅ role 是没问题的，但请确认 authors 里有这个值
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
