# Example

Match3 Puzzle Game

Version: 1.0.0

---

# User Input

I want to create a mobile puzzle game.

Game Name:

Crystal Garden

Platform:

Mobile

Genre:

Match-3 Puzzle

Art Style:

Colorful fantasy garden

Core Idea:

Players match crystals to grow a magical garden.

Target Audience:

Casual players.

Session:

3-5 minutes.

---

# Generated Project Summary

## Project Name

Crystal Garden

---

## Genre

Casual Match-3 Puzzle

---

## Platform

Mobile

Orientation:

Portrait

Input:

Touch

---

## Core Gameplay

Players swap adjacent crystals to create matches.

Successful matches remove crystals and generate resources.

Resources are used to restore and expand the magical garden.

---

# Design Pillars

## 1. Easy to Learn

The player understands the basic interaction within seconds.

## 2. Satisfying Feedback

Every match provides:

- Visual effects
- Sound effects
- Animation feedback

## 3. Continuous Progress

Every session contributes to garden growth.

---

# MVP Definition

## Must Have

### Match System

Players can swap crystals.

Matching 3 or more creates a clear.

---

### Basic Levels

Include:

- Level objectives
- Limited moves
- Win condition

---

### Garden Progress

Players unlock simple decorations.

---

## Should Have

- Special crystals
- Combo effects
- Daily rewards

---

## Could Have

- Events
- Social sharing
- Leaderboards

---

## Won't Have

- Real-time multiplayer
- Complex guild system
- PvP

---

# Core Gameplay Loop

```
Enter Level

↓

Swap Crystals

↓

Create Matches

↓

Complete Objective

↓

Earn Rewards

↓

Restore Garden

↓

Unlock New Content
```

---

# Technical Architecture

Engine:

Cocos Creator

Language:

TypeScript

Structure:

```
assets/

scripts/

scenes/

ui/

data/

effects/

audio/

```

---

# Main Systems

## Match System

Responsibilities:

- Detect matches
- Remove objects
- Calculate score
- Trigger effects

---

## Level System

Responsibilities:

- Load level data
- Track objectives
- Determine completion

---

## Reward System

Responsibilities:

- Calculate rewards
- Unlock decorations

---

# Art Direction

Style:

Fantasy garden

Keywords:

- Colorful
- Magical
- Friendly
- Soft

Materials:

- Crystal
- Plants
- Wood
- Stone

---

# UI Structure

Screens:

## Home

Contains:

- Garden preview
- Start button
- Currency

---

## Level Select

Contains:

- Level map
- Progress

---

## Gameplay

Contains:

- Board
- Moves counter
- Objective
- Pause

---

## Result

Contains:

- Score
- Rewards
- Continue

---

# Asset List Example

## Gameplay

| Asset | Purpose |
|-|-|
| crystal_red | Match object |
| crystal_blue | Match object |
| explosion_fx | Match feedback |

---

## UI

| Asset | Purpose |
|-|-|
| button_start | Start game |
| panel_result | Result window |

---

# Development Plan

## Phase 1

Prototype

Deliver:

- Board
- Match detection
- Basic interaction

---

## Phase 2

MVP

Deliver:

- Levels
- Rewards
- Garden system

---

## Phase 3

Polish

Deliver:

- Effects
- Audio
- Optimization

---

# Claude Code Tasks

## Task 001

Create project structure.

Acceptance:

Project runs successfully.

---

## Task 002

Implement grid system.

Acceptance:

Player can interact with tiles.

---

## Task 003

Implement match detection.

Acceptance:

Matching logic works correctly.

---

# Quality Check

Passed:

✓ Clear gameplay loop

✓ Realistic MVP

✓ Complete architecture

✓ Asset planning exists

✓ Tasks executable