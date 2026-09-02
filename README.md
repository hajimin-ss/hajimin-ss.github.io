# Hajimin's Notes

使用 Jekyll 和 GitHub Pages 发布的个人博客。

## 写一篇新文章

复制根目录的 [`POST_TEMPLATE.md`](POST_TEMPLATE.md)，放到 `_posts/` 目录，并按 `YYYY-MM-DD-title.md` 命名，例如：

```text
_posts/2026-09-02-my-first-post.md
```

然后修改模板开头的文章信息，再直接使用 Markdown 写正文：

```md
---
layout: post
title: 我的第一篇博客
date: 2026-09-02
categories: [随笔]
description: 一句话摘要，会显示在首页。
---

开头先说明这篇文章想讨论什么。

## 背景

补充背景和具体场景。

## 我的做法

写下过程、观察和判断。

## 结论

总结结论，或者记录仍未解决的问题。
```

标题、日期、分类和摘要的作用：

- `title`：文章标题。
- `date`：发布日期，文件名中的日期也要保持一致。
- `categories`：文章分类，例如 `工程`、`思考`、`随笔`。
- `description`：首页文章列表显示的一句话摘要。

推送到 `main` 后，GitHub Actions 会自动构建和发布站点。
