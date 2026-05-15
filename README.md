# JingWen Fan

JingWen Fan 的个人网站，使用 GitHub Pages 托管。

访问地址：

```text
https://study8677.github.io/
```

## 写文章

这个网站使用 GitHub Pages + Jekyll。写文章时，在 `articles/` 目录新建 Markdown 文件：

```text
articles/title.md
```

例如：

```text
articles/agent-memory.md
```

文件开头写 front matter：

```yaml
---
title: "文章标题"
date: 2026-05-15
tags: [Agent, Codex]
summary: "一句话摘要。"
permalink: /articles/agent-memory/
---
```

下面直接写 Markdown 正文。提交并推送到 `main` 分支后，GitHub Pages 会自动构建文章页，并展示在首页和 `/articles/`。

可以从 `articles/TEMPLATE.txt` 复制模板，另存为新的 `.md` 文件。

## 更新首页

首页内容在 `index.html`，样式在 `style.css`。

内容来源主要来自 GitHub 个人主页：

```text
https://github.com/study8677
```
