---
title: 博客换新装：从 Hexo 默认主题到 Butterfly
date: 2026-06-16 11:30:00
tags:
  - Hexo
  - Butterfly
  - 博客
categories:
  - 技术
---

经过一番折腾，这个博客终于从 Hexo 自带的 Landscape 主题，换成了更现代的 **Butterfly** 主题。

## 为什么换主题

Landscape 是 Hexo 的默认主题，胜在简洁，但样式偏老旧，自定义空间也有限。Butterfly 是社区里非常受欢迎的一款主题，特点包括：

- 卡片式布局，阅读体验更好
- 内置本地搜索、代码高亮、暗色模式
- 中文文档完善，配置灵活

## 部署方式

本站托管在 GitHub Pages，使用 GitHub Actions 自动构建部署。每次推送 `main` 分支后，会自动执行 `hexo generate` 并发布，无需手动 `hexo deploy`。

## 接下来

后续会在这里记录开发笔记、项目心得和生活碎片。欢迎常来看看。

---

*本文由 gitfdy 发布于 2026 年 6 月 16 日。*
