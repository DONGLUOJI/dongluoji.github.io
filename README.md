# 董逻辑 Open Content Repository

这是 `dongluoji.github.io` 的源码仓库，用来建设一个长期增长的个人开源内容库。

## 本地预览

如果本机已经安装 Ruby 和 Bundler，可以运行：

```bash
bundle exec jekyll serve
```

也可以直接推送到 GitHub Pages，由 GitHub 自动构建。

## 写新文章

在 `_posts/` 下创建文件：

```text
YYYY-MM-DD-title.md
```

文章开头使用 front matter：

```markdown
---
layout: post
title: "文章标题"
date: 2026-05-31 10:00:00 +0800
categories: ["随笔"]
tags: ["AI", "项目", "工作流"]
description: "文章摘要。"
lang: zh-CN
permalink: /notes/example/
---
```
