# Claude Code Game Builder

> A production-oriented AI Agent Skill for Claude Code that helps transform game ideas into structured game development projects.

一个面向 Claude Code 的游戏开发 AI Skill。
它可以帮助开发者从「游戏想法」开始，逐步生成游戏设计、系统规划、项目结构和开发流程。

---

# ✨ Features

## 🎮 Idea → Game Project

Turn simple game ideas into complete development plans.

Example:

Input:

```
I want to create a cozy puzzle game about knitting.
```

Output:

```
Game Concept

Core Gameplay

Game Systems

Technical Architecture

Asset Planning

Development Roadmap
```

---

## 🤖 AI Agent Architecture

This Skill is designed as a modular AI workflow instead of a single prompt.

Architecture:

```
                 SKILL.md

                    ↓

              Workflow System

                    ↓

        ┌───────────┼───────────┐
        ↓           ↓           ↓

      Brain    Executors    Quality

                    ↓

                 Actions

                    ↓

              Generators
```

---

# 📦 Installation

## Requirements

Before installation, make sure you have:

- Claude Code installed
- Git installed
- A Claude account with Claude Code access


---

# Method 1: Clone Repository (Recommended)

Clone this repository:

```bash
git clone https://github.com/your-name/claude-code-game-builder.git
```

Then copy the Skill folder into your Claude Code skills directory.

Example:

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

Restart Claude Code after installation.

---

# Method 2: Manual Installation

1. Download this repository.

2. Create a Skill folder:

```
.claude/skills/game-builder/
```

3. Copy all files into this folder.

4. Make sure the entry file exists:

```
SKILL.md
```

5. Restart Claude Code.

---

# 🚀 Usage

After installation, open Claude Code.

Example commands:

```
Create a mobile puzzle game.
```

or:

```
Help me design a cozy simulation game.
```

Claude Code will automatically use this Skill workflow.

The process:

```
Game Idea

↓

Requirement Analysis

↓

Game Design

↓

System Architecture

↓

Development Plan

↓

Quality Review
```

---

# 🏗 Project Structure

```
claude-code-game-builder/

├── SKILL.md

├── WORKFLOW.md
├── DECISION_TREE.md
├── OUTPUT_SPEC.md
├── QUALITY_CHECK.md
├── SYSTEM_RULES.md

├── brain/
│   └── Decision making logic

├── executors/
│   └── Workflow execution

├── actions/
│   └── Specific operations

├── generators/
│   └── Output generation

├── quality/
│   └── Review system

├── templates/

└── examples/
```

---

# 🧠 Core Modules

## Brain

负责：

- Understanding user requirements
- Breaking down game ideas
- Making development decisions


## Executors

负责：

- Running workflows
- Managing task order
- Coordinating different modules


## Actions

负责：

- File operations
- Project modifications
- Applying rules


## Generators

负责：

- Creating documents
- Generating structured outputs


## Quality

负责：

- Checking completeness
- Finding missing information
- Improving output quality


---

# 🎯 Design Philosophy

## Structure Before Code

Good games start with good planning.

This Skill focuses on:

- Clear gameplay loops
- Scalable architecture
- Maintainable structure


---

## Production-Oriented

This is not just a prompt collection.

The goal is:

```
Idea

↓

Design

↓

Plan

↓

Build
```

帮助开发者真正完成游戏开发流程。

---

# 📝 Example Projects

Future examples:

- Puzzle Games
- Simulation Games
- Casual Mobile Games
- WeChat Mini Games
- Indie Game Prototypes


---

# 🛣 Roadmap

## V2 Completed

✅ Modular Skill architecture

✅ Workflow system

✅ Decision system

✅ Executor system

✅ Generator system

✅ Quality checking system


---

## Future

- More game templates
- Unity workflow support
- Unreal workflow support
- Automated project generation
- Asset pipeline integration


---

# 🤝 Contributing

Contributions are welcome.

You can contribute:

- New workflows
- New game templates
- New generators
- Better quality rules


---

# 📄 License

MIT License


---

# About

Claude Code Game Builder

一个帮助 Claude Code 从游戏创意到项目落地的 AI 游戏开发 Skill。

Mission:

**Turn ideas into playable games with AI assistance.**
