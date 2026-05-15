---
layout: post
article: true
title: "如何在这个网站写文章"
date: 2026-05-15
tags: [Website, Writing, Jekyll]
summary: "这个网站已经支持用 Markdown 写文章。新增一篇文章，只需要在 articles 目录里创建一个 .md 文件。"
permalink: /articles/how-to-write-here/
---

这个网站已经按你说的方式整理好了：当前项目里有一个 `articles/` 文件夹，你把文章 Markdown 放进去，提交并推送到 GitHub 后，网站会自动同步。

## 最简单的写法

在 `articles/` 目录新建一个 Markdown 文件：

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

下面直接写正文：

```markdown
## 小标题

正文内容。

- 要点一
- 要点二
```

## 发布

写完后执行：

```bash
git add .
git commit -m "Add article"
git push
```

GitHub Pages 会自动构建。文章会出现在首页的文章区和 `/articles/` 文章列表里。

## 模板

可以复制这个模板开始写：

```text
articles/TEMPLATE.txt
```
