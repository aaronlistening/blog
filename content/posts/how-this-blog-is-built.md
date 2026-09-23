---
title: "这个博客是怎么搭起来的"
date: 2026-09-19T09:00:00+08:00
categories: ["Tech"]
tags: ["hugo", "blog"]
---

本站使用 [Hugo](https://gohugo.io/) 生成，主题复刻自 [blog.joway.io](https://blog.joway.io/)。

## 目录结构

```text
blog/
├── hugo.toml
├── content/
│   └── posts/
└── themes/
    └── joway/
        ├── layouts/
        └── assets/
```

## 常用命令

```bash
hugo server        # 本地预览 http://localhost:1313
hugo              # 生成静态文件到 public/
```

写一篇新文章：

```bash
hugo new content posts/my-new-post.md
```
