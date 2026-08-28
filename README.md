# Hajimin's Notes

使用 Jekyll 和 GitHub Pages 发布的个人博客。

## 写一篇新文章

在 `_posts/` 目录新建文件，命名为 `YYYY-MM-DD-title.md`，例如：

```text
_posts/2026-08-28-my-first-post.md
```

文件开头需要写文章信息，之后直接使用 Markdown 写正文：

```md
---
layout: post
title: 我的第一篇博客
date: 2026-08-28
categories: [随笔]
description: 一句话摘要，会显示在首页。
---

这是正文。

## 小标题

- 支持列表
- 支持链接和代码块
```

推送到 `main` 后，GitHub Actions 会自动构建和发布站点。
