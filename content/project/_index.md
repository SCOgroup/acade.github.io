---
# 标题，会显示在页面顶部
title: 项目

# 不要修改这个！这告诉Hugo这个页面是一个版块的“主页”
type: landing

# --- Widget配置开始 ---
sections:
  - block: portfolio
    id: projects
    content:
      # 告诉Widget去哪个文件夹里找内容。
      # page_type: project 会让它去 content/project/ 文件夹。
      page_type: project
      # 可选：按日期（降序）、标题（升序）或文件名（升序）排序
      # 0 = 日期降序, 1 = 标题升序, 2 = 文件名升序
      sort_by: 'Date'
      sort_ascending: false
      # 过滤规则 (我们这里不过滤，全部显示)
      filter:
        # 按标签过滤 (可选)
        tag: ''
        # 按分类过滤 (可选)
        category: ''
        # 显示/隐藏草稿 (draft: true)
        exclude_drafts: true
        # 显示/隐藏未来日期的内容
        exclude_future: false
        # 显示/隐藏已过期的内容
        exclude_past: false
    design:
      # 视图样式:
      # 1 = 列表 (List)
      # 2 = 卡片 (Card)
      # 3 = 展示 (Showcase)
      # 我们必须用 2，这样才能激活我们自定义的 card.html 文件！
      view: 2
      # 卡片的列数 (1, 2, or 3)
      columns: 2
---
