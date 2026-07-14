# Claude Code Game Builder

> An AI Agent Skill for Claude Code that transforms game ideas into structured, production-ready game development projects.

> 一个面向 Claude Code 的 AI 游戏开发 Skill，将简单的游戏想法转化为结构化、可执行的游戏开发方案。

---

# 🎮 Overview / 项目介绍

## English

Claude Code Game Builder is a modular AI Agent Skill designed for game development.

Unlike traditional AI prompts that only generate code or answer questions, this Skill provides a complete game development workflow.

It allows Claude Code to work like a small professional game development team, helping developers move from:

```
Game Idea

↓

Game Design

↓

System Architecture

↓

Project Structure

↓

Development Plan

↓

Implementation
```

The Skill focuses on making AI-assisted game development more organized, scalable, and production-oriented.

---

## 中文

Claude Code Game Builder 是一个面向 Claude Code 的模块化 AI 游戏开发 Skill。

它不同于普通 Prompt（提示词），不会只生成代码片段或者回答问题，而是提供完整的游戏开发工作流。

它让 Claude Code 更像一个小型游戏开发团队，帮助开发者完成：

```
游戏创意

↓

游戏设计

↓

系统架构

↓

项目结构

↓

开发计划

↓

实际制作
```

目标是让 AI 辅助游戏开发更加规范、高效，并接近真实游戏制作流程。

---

# ✨ Features / 核心功能


## 1. Game Idea Analysis
## 游戏创意分析

### English

Transform natural language ideas into structured game concepts.

Example:

Input:

```
Create a cozy puzzle game about knitting.
```

The Skill analyzes:

- Game genre
- Core gameplay loop
- Player experience
- Required systems
- Technical requirements
- Asset requirements


### 中文

将一句简单的游戏想法，扩展成为完整的游戏设计方案。

例如：

输入：

```
制作一个关于咖啡店经营的治愈小游戏
```

Skill 会分析：

- 游戏类型
- 核心玩法循环
- 玩家体验
- 游戏系统
- 技术需求
- 美术资源需求


---

# 2. Complete Development Workflow
# 完整开发流程


## English

The Skill provides a structured workflow:

```
Idea

↓

Requirement Analysis

↓

Game Design Document

↓

Core Mechanics

↓

System Planning

↓

Technical Architecture

↓

Development Tasks

↓

Quality Review
```


## 中文

Skill 提供标准化游戏开发流程：

```
游戏想法

↓

需求分析

↓

游戏设计文档

↓

核心机制设计

↓

系统规划

↓

技术架构

↓

开发任务拆解

↓

质量检查
```


---

# 3. Modular AI Architecture
# 模块化 AI 架构


The Skill is built with multiple independent modules.

该 Skill 采用多个模块协作，而不是依靠一个巨大 Prompt。


```
                    SKILL.md

                       ↓

               Workflow Controller

                       ↓


        ┌──────────────┼──────────────┐

        ↓              ↓              ↓

      Brain       Executors       Quality


                       ↓

                    Actions


                       ↓

                 Generators

```


---

# 🧠 Architecture Details
# 架构说明


## Brain / 思考模块

Responsible for:

- Understanding user requirements
- Analyzing game concepts
- Making design decisions
- Choosing proper workflows


负责：

- 理解用户需求
- 分析游戏类型
- 做出开发决策
- 选择合适流程


---

## Executors / 执行模块

Responsible for:

- Managing workflow execution
- Controlling task order
- Coordinating different modules


负责：

- 执行开发流程
- 控制任务顺序
- 协调不同模块


---

## Actions / 动作模块

Responsible for:

- Performing specific operations
- Creating files
- Updating project structures


负责：

- 执行具体操作
- 创建文件
- 修改项目结构


---

## Generators / 生成模块

Responsible for:

- Generating documents
- Creating templates
- Producing structured outputs


负责：

- 生成开发文档
- 创建模板
- 输出标准化内容


---

## Quality / 质量模块

Responsible for:

- Checking completeness
- Reviewing outputs
- Improving consistency


负责：

- 检查完整性
- 审核输出
- 保证开发质量


---

# 📦 Installation / 安装方式


## Requirements / 环境要求

You need:

需要：

- Claude Code
- Git
- Claude account with Claude Code access


---

# Method 1: Clone Repository
# 方法1：克隆仓库（推荐）


Clone:

```bash
git clone https://github.com/hymio1/claude-code-game-builder.git
```


Copy the Skill into:

复制 Skill 到：


```
.claude/

└── skills/

    └── game-builder/

        ├── SKILL.md
        ├── brain/
        ├── executors/
        ├── actions/
        ├── generators/
        └── quality/
```


Restart Claude Code.

重启 Claude Code。


---

# Method 2: Manual Installation
# 方法2：手动安装


1. Download this repository

下载仓库


2. Create folder:

创建：

```
.claude/skills/game-builder/
```


3. Copy all files into this folder.

复制所有文件。


4. Make sure:

确认存在：

```
SKILL.md
```


5. Restart Claude Code.

重启 Claude Code。


---

# 🚀 Usage / 使用方法


After installation:

安装完成后：


Example:

示例：


```
Create a mobile puzzle game about cooking.
```


Claude Code will generate:

Claude Code 会生成：


- Game concept
- Gameplay systems
- Technical structure
- Development roadmap
- Required assets


包括：

- 游戏概念
- 游戏系统
- 技术结构
- 开发路线
- 所需资源


---

# 📁 Project Structure / 项目结构


```
claude-code-game-builder/

├── SKILL.md

├── WORKFLOW.md
├── DECISION_TREE.md
├── OUTPUT_SPEC.md
├── QUALITY_CHECK.md
├── SYSTEM_RULES.md

├── brain/

├── executors/

├── actions/

├── generators/

├── quality/

├── templates/

└── examples/
```


---

# 🎯 Design Philosophy / 设计理念


## Structure Before Code

## 先设计，再写代码


Good games require clear systems before implementation.

优秀游戏需要先明确系统，再进入制作。


This Skill focuses on:

这个 Skill 注重：

- Gameplay clarity
- Scalable architecture
- Maintainable development
- Professional workflow


---

# Production-Oriented AI Development

# 面向生产的 AI 开发


This is not a simple prompt collection.

这不是简单的提示词集合。


The goal:

目标：


```
Idea

↓

Design

↓

Plan

↓

Build

↓

Improve
```


让 AI 真正参与游戏制作流程。


---

# 🛣 Roadmap / 开发路线


## V2 Completed

完成：

✅ Modular architecture

✅ Workflow system

✅ Brain system

✅ Executor system

✅ Generator system

✅ Quality system


---

## Future Plans

未来：

- More game templates
- Unity workflow support
- Unreal workflow support
- Automated project generation
- AI asset pipeline integration


---

# 🤝 Contributing / 贡献


Contributions are welcome.

欢迎贡献：

- New workflows
- New templates
- New game examples
- Better quality rules


---

# 📄 License

MIT License


---

# About / 关于


Claude Code Game Builder

一个帮助开发者利用 Claude Code 完成游戏设计与开发流程的 AI Agent Skill。


Mission:

**Transform game ideas into playable experiences with AI assistance.**

使命：

**利用 AI，将游戏创意转化为可实现的游戏作品。**
