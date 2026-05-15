---
layout: post
article: true
title: "Vibe Coding Guide：把 AI Coding 变成工程化工作流"
date: 2026-05-15
tags: [Vibe Coding, Agent, Engineering Workflow]
summary: "我参与共创的 Vibe Coding 实战教程，面向正在使用 Codex、Claude Code、Cursor、Aider 等 AI Coding 工具的开发者。"
permalink: /articles/vibe-coding-guide/
---

[Vibe Coding Guide](https://github.com/Lling0000/Vibe_coding_guide) 是我参与共创的一份 AI Agent 协作开发实战教程。

它不是在讲“让 AI 帮你写代码”，而是在讲如何把 AI Coding 变成一个可观察、可审查、可回滚、可复用的工程工作流。

## 这份指南解决什么问题

AI coding 工具可以很快生成代码，但真正困难的是让这些输出：

- 符合现有项目结构和工程约定
- 能被 review，而不是只能“看起来能跑”
- 能进入测试、CI 和长期维护流程
- 能在多 session、多 agent、多 worktree 的情况下保持可控

所以这份指南强调的是：开发者不是把控制权交给 AI，而是成为更好的 Agent operator。

## 核心内容

教程覆盖了从个人使用到团队协作的完整路径：

- 如何写 spec，并把验收标准变成 Agent 的工作边界
- 如何维护 `AGENTS.md` / `CLAUDE.md`，让项目知识长期沉淀
- 如何管理上下文窗口、压缩、交接和重启
- 如何使用 subagent、workflow 和多 Agent 协作模式
- 如何用 git worktree 支撑并行开发
- 如何把重复任务固化成 Skill
- 如何区分 system prompt 与 user prompt
- 如何用 CI/CD 和测试约束 Agent 产出的代码质量
- 如何测试 Agent 行为本身，而不只是测试普通代码

## 入口

- [GitHub 仓库](https://github.com/Lling0000/Vibe_coding_guide)
- [中文教程](https://github.com/Lling0000/Vibe_coding_guide/blob/main/vibe-coding-guide-zh.md)
- [英文教程](https://github.com/Lling0000/Vibe_coding_guide/blob/main/vibe-coding-guide-en.md)
- [中文 PDF](https://github.com/Lling0000/Vibe_coding_guide/blob/main/vibe-coding-guide-zh.pdf)
- [English PDF](https://github.com/Lling0000/Vibe_coding_guide/blob/main/vibe-coding-guide-en.pdf)

如果你正在用 Codex、Claude Code、Cursor、Aider 或类似工具写真实项目，这份指南更适合当作 field manual 反复查，而不是当成一篇普通博客读完。
