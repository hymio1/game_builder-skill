# Claude Code Game Builder

> An AI Agent Skill for transforming game ideas into production-ready game development projects.

![Claude Code](https://img.shields.io/badge/Claude-Code-blue)
![Skill Version](https://img.shields.io/badge/Skill-V2-green)
![License](https://img.shields.io/badge/license-MIT-orange)

---

# Overview

Claude Code Game Builder is a modular AI Agent Skill designed to help developers transform game ideas into structured, production-ready game projects.

Instead of only generating code, this Skill provides a complete game development workflow.

It helps Claude Code work like a professional game development team by providing:

- Game concept analysis
- Gameplay system planning
- Technical architecture design
- Project structure generation
- Asset planning
- Development workflow management
- Quality verification

The goal is to transform simple game ideas into complete and executable development plans.

---

# Features

## Idea → Game Project

Convert natural language game ideas into structured game development documents.

Example:

Input:

```
Create a cozy puzzle game about knitting.
```

Output:

```
Game Design Document

Core Gameplay Mechanics

System Architecture

Asset Requirements

Development Roadmap

Implementation Plan
```

---

# Modular AI Agent Architecture

This Skill uses a layered architecture instead of a single large prompt.

```
                 SKILL.md

                    ↓

            Workflow Controller

                    ↓

        ┌───────────┼───────────┐
        ↓           ↓           ↓

      Brain    Executors    Quality

                    ↓

                 Actions

                    ↓

               Generators
```

Each module has independent responsibilities.

---

# Architecture

## Brain

Responsible for:

- Understanding user requirements
- Analyzing game concepts
- Breaking down complex tasks
- Making development decisions
- Selecting appropriate workflows


---

## Executors

Responsible for:

- Running development workflows
- Managing task execution order
- Coordinating multiple actions
- Controlling the production process


---

## Actions

Responsible for:

- Executing specific operations
- Creating project files
- Updating structures
- Applying development rules


---

## Generators

Responsible for:

- Creating documents
- Generating templates
- Producing structured outputs
- Standardizing development materials


---

## Quality

Responsible for:

- Checking output consistency
- Reviewing generated content
- Detecting missing requirements
- Improving development quality


---

# Project Structure

```
claude-code-game-builder/

├── SKILL.md

├── WORKFLOW.md
├── DECISION_TREE.md
├── OUTPUT_SPEC.md
├── QUALITY_CHECK.md
├── SYSTEM_RULES.md

├── brain/
│
├── executors/
│
├── actions/
│
├── generators/
│
├── quality/

├── templates/

└── examples/
```

---

# Installation

## Clone Repository

```bash
git clone https://github.com/your-name/claude-code-game-builder.git
```

---

## Install Skill

Copy the Skill into your Claude Code skills directory.

Example:

```
.claude/

└── skills/

    └── game-builder/

        └── SKILL.md
```

Restart Claude Code after installation.

---

# Usage

Example:

```
Create a mobile puzzle game about cooking.
```

Claude Code will analyze:

```
Game Idea

↓

Requirement Analysis

↓

Core Gameplay Loop

↓

Game Systems

↓

Technical Architecture

↓

Development Tasks

↓

Quality Review
```

---

# Development Workflow

The Skill follows a complete game development pipeline.

```
Game Idea

↓

Game Analysis

↓

Design Documents

↓

System Planning

↓

Project Structure

↓

Implementation Guidance

↓

Quality Verification

↓

Production Ready Output
```

---

# Design Philosophy

## Structure Before Code

A good game starts with a clear system design.

This Skill prioritizes:

- Gameplay clarity
- Technical feasibility
- Scalable architecture
- Maintainable structure


---

## Modular Intelligence

Instead of depending on one huge prompt, the Skill separates intelligence into independent modules.

Benefits:

- Easier maintenance
- Better scalability
- More reliable outputs
- Flexible expansion


---

## Production-Oriented Output

The goal is not only generating ideas.

The goal is helping developers actually build games.

---

# Examples

Supported scenarios:

- Puzzle Games
- Simulation Games
- Casual Mobile Games
- WeChat Mini Games
- Indie Game Prototypes


---

# Roadmap

## Version 2

Completed:

- Modular Skill architecture
- Workflow system
- Decision system
- Executor system
- Generator system
- Quality verification system
- Output specifications


---

## Future Development

Planned:

- More game templates
- Engine-specific workflows
- Automated project generation
- Asset pipeline integration
- Advanced AI game production assistant


---

# Contributing

Contributions are welcome.

You can contribute:

- New workflows
- New generators
- New templates
- Quality rules
- Example projects


---

# License

MIT License


---

# About

Claude Code Game Builder is an experimental AI game development workflow system.

Built for Claude Code.

Mission:

Turn game ideas into structured, production-ready projects with AI assistance.
