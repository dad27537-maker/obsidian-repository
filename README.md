---
title: README
created: 2026-07-10
updated: 2026-07-10T04:37:31.376Z
type: note
status: draft
tags: []
aliases: []
source:
related: []
outline_mode: true
mindmap_ready: false
---
# Gongkao-AI 考公智能备考工作流

一个基于 Obsidian 的 AI 辅助公务员考试备考知识库。

## 项目简介

本项目整合了行测、申论、面试、时政热点、岗位选择等考公核心模块，并配合 **AI Skill 提示词**，将 Obsidian 打造成一个可持续迭代的 AI 备考系统。

核心逻辑：**不是堆资料，而是建工作流**。

- 用 AI Skill 替代搜索引擎式的碎片化学习
- 用 Obsidian 模板沉淀每日错题、复习计划、素材积累
- 用提示词（prompts）将 AI 变成你的私教：批改申论、模拟面试、解析行测

## 快速开始

1. 用 Obsidian 打开本仓库作为 Vault
2. 从 `Gongkao-AI-Skill-Hub-Obsidian/00-首页.md` 开始
3. 安装 [Dataview 插件](https://github.com/blacksmithgu/obsidian-dataview) 获得完整体验（非必需）

## 目录结构

```
Gongkao-AI/
├── Gongkao-AI-Skill-Hub-Obsidian/   # Obsidian Vault 主目录
│   ├── 00-首页.md                    # 入口文件
│   ├── skills/                       # AI Skill 说明（行测/申论/面试等）
│   ├── prompts/                      # 可直接复制给 AI 的提示词
│   ├── templates/                    # Obsidian 每日记录模板
│   ├── 知识库/                        # 各科目知识框架
│   ├── 错题本/                        # 错题沉淀区
│   ├── 复习计划/                      # 每日/每周/阶段计划
│   └── 素材库/                        # 申论&面试素材
├── .gitignore
└── README.md
```

## 内置 AI Skills

| Skill | 说明 |
|-------|------|
| 行测解析 (xingce-solver) | 自动解析行测题目，生成解析与知识点 |
| 申论批改 (shenlun-reviewer) | 模拟阅卷评分，逐段点评 |
| 错题复盘 (mistake-tracker) | 分析错题根因，推送复习卡片 |
| 复习计划 (study-planner) | 根据进度生成每日/阶段计划 |
| 面试模拟 (interview-coach) | 结构化面试全真模拟 |
| 时政热点 (hot-topic-analyzer) | 热点事件多维度解读 |
| 岗位选择 (position-selector) | 结合竞争比/专业/地域推荐 |

## 技术栈

- **知识库**: Obsidian (Markdown + Dataview)
- **AI 能力**: 通过 prompts/ 目录下的提示词调用任意大语言模型
- **版本控制**: Git + Gitee

## License

MIT

# 闪卡
