---
title: "Publications"
cms_exclude: true
type: widget_page  # 使用分块布局
---
---
title: "Publications"
weight: 30
type: widget
widget: collection

content:
  title: "Journal Articles"
  filters:
    folders: ["publication"]
    publication_type: "2"  # 通常 journal 是类型 2
  sort: date
  order: desc
design:
  view: citation
---

---

title: ""
type: widget
widget: collection

content:
  title: "Conference Papers"
  filters:
    folders: ["publication"]
    publication_type: "1"  # conference 类型
  sort: date
  order: desc
design:
  view: citation
---

---

title: ""
type: widget
widget: collection

content:
  title: "Patents"
  filters:
    folders: ["publication"]
    publication_type: "7"  # 假设 7 是 patent 类型
  sort: date
  order: desc
design:
  view: citation
---
