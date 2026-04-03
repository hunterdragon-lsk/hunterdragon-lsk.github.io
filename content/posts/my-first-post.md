---
title: "第一篇博客: 自动部署测试"
date: 2026-04-03T10:00:00+00:00
draft: false
tags: ["hugo", "github actions"]
---

你好！这是自动部署的第一篇博客。

通过在 GitHub 上创建一个新的 Markdown 文件，GitHub Actions 就会自动把它编译成静态页面，并发布到 GitHub Pages 上。

### 为什么选择 Hugo
1. **速度极快**：几毫秒就能完成构建。
2. **主题丰富**：这个博客使用的是极简但不简单的 `PaperMod` 主题。
3. **Markdown 优先**：只需关注内容创作本身。

之后你可以把你的内容直接放到 `content/posts/` 目录下（记得修改文件开头的 `draft: false`，或者是利用 GitHub Actions 脚本设置自动发布）。
