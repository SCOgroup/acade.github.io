---
# 页面顶部显示的标题
title: 项目

# 告诉系统这是一个“落地页”
type: landing

# --- 部件配置开始 ---
sections:
  - # --- 这是关键的修正 ---
    # 在新版 Hugo Blox 中，部件的正确名称是 `collection`
    block: collection
    id: projects
    content:
      # 告诉部件去 content/project/ 文件夹里找内容
      page_type: project
      # 排序方式：'Date' (降序), 'Title' (升序), or 'Filename' (升序)
      sort_by: 'Date'
      sort_ascending: false
      # 过滤规则
      filter:
        tag: ''
        category: ''
        exclude_drafts: true
        exclude_future: false
        exclude_past: false
    design:
      # 视图样式: 1 = List, 2 = Card, 3 = Showcase
      # 我们必须用 2，才能激活我们自定义的 card.html
      view: 2
      # 卡片列数
      columns: 2
---
