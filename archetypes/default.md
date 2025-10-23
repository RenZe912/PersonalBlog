---
title: "{{ replace .Name "-" " " | title }}"
date: "{{ .Date }}"
draft: false

# 元信息
description: ""
tags: []
categories: []

# PaperMod 常用页面级参数
showToc: false         # 目录
comments: true         # 若主题/站点开启了评论，这里可单独开关
ShowReadingTime: true  # 显示阅读时长
ShowPostNavLinks: true # 上/下一篇

# 封面（按需启用）
cover:
  image: ""            # 例如: "/images/cover.jpg"
  alt: ""
  caption: ""
  relative: true       # 放在 content 同目录时设为 true
  hidden: false        # 隐藏文章页封面（仍用于列表/社交卡片）
---