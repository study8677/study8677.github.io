---
layout: post
title: "如何在这个网站写文章"
date: 2026-05-15
tags: [Website, Writing, Jekyll]
summary: "这个网站已经支持用 Markdown 写文章。新增一篇文章，只需要在 _posts 目录里创建一个带日期的 .md 文件。"
---

这篇文章是一个模板。以后写文章时，复制这个文件，改文件名、标题、日期、标签和正文即可。

## 文件名规则

文章必须放在 `_posts/` 目录，文件名格式是：

```text
YYYY-MM-DD-your-title.md
```

例如：

```text
2026-05-15-agent-memory.md
```

## 文章头部

每篇文章开头都要有一段 front matter：

```yaml
---
layout: post
title: "文章标题"
date: 2026-05-15
tags: [Agent, Codex]
summary: "一句话摘要。"
---
```

## 正文

front matter 后面直接写 Markdown：

```markdown
## 小标题

正文内容。

- 要点一
- 要点二
```

推送到 GitHub 后，GitHub Pages 会自动把 Markdown 构建成文章页，并出现在首页和文章列表里。
