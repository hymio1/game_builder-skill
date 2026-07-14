# Example

Farm Simulation Game

Version: 1.0.0

---

# User Input

I want to create a relaxing farming simulation game.

Game Name:

Sunny Valley Farm

Platform:

Mobile

Genre:

Farming Simulation / Cozy Management

Art Style:

Hand-painted countryside style

Core Idea:

Players build a small farm, grow crops, raise animals, and develop a peaceful village.

Target Audience:

Players who enjoy relaxing progression and customization.

Session:

5-15 minutes.

---

# Generated Project Summary

## Project Name

Sunny Valley Farm

---

## Genre

Farming Simulation / Cozy Management

---

## Platform

Mobile

Orientation:

Portrait

Input:

Touch

---

## Core Gameplay

Players manage a small farm.

They plant crops, harvest resources, complete orders, upgrade facilities, decorate the farm, and unlock new areas.

---

# Design Pillars

## 1. Relaxing Progression

Players should always feel gradual improvement.

---

## 2. Creative Ownership

Players can customize their farm.

---

## 3. Long-Term Growth

The farm should provide goals over weeks and months.

---

# MVP Definition

## Must Have

### Crop System

Players can:

- Plant crops
- Wait for growth
- Harvest crops

---

### Resource System

Include:

- Crops
- Materials
- Coins

---

### Basic Farm Expansion

Players can unlock:

- New plots
- Simple buildings

---

## Should Have

- Animal raising
- Decoration system
- Customer orders

---

## Could Have

- Seasonal events
- Social visiting
- Trading system

---

## Won't Have

- Real-time multiplayer farming

- Complex market economy

- Player-created maps

---

# Core Gameplay Loop

```
Collect Resources

↓

Plant Crops

↓

Wait / Complete Tasks

↓

Harvest

↓

Complete Orders

↓

Earn Rewards

↓

Upgrade Farm

↓

Unlock New Content
```

---

# Main Systems

## Farm Grid System

Responsibilities:

- Manage land cells
- Place objects
- Store farm state

---

## Crop System

Responsibilities:

- Crop data
- Growth stages
- Harvest rewards

---

## Building System

Responsibilities:

- Construction
- Upgrades
- Unlock requirements

---

## Inventory System

Responsibilities:

- Store items
- Stack resources
- Manage capacity

---

## Quest System

Responsibilities:

- Generate objectives
- Track completion
- Give rewards

---

# Data Structure Example

## Crop Data

```
Crop

id

name

growthTime

stages

harvestReward

unlockLevel
```

---

## Building Data

```
Building

id

name

cost

level

upgradeEffect

unlockCondition
```

---

# Technical Architecture

Engine:

Godot

Language:

GDScript

Structure:

```
project/

scenes/

scripts/

resources/

assets/

ui/

data/

audio/

```

---

# UI Structure

## Farm View

Contains:

- Farm grid
- Resource display
- Building controls

---

## Inventory

Contains:

- Items
- Quantities
- Storage capacity

---

## Shop

Contains:

- Seeds
- Buildings
- Decorations

---

## Quest Panel

Contains:

- Objectives
- Rewards
- Progress

---

# Art Direction

Style:

Cozy countryside illustration

Keywords:

- Warm
- Natural
- Peaceful
- Handmade

Materials:

- Wood
- Soil
- Plants
- Stone
- Fabric

---

# Asset List Example

## Environment

| Asset | Purpose |
|-|-|
| farm_land_tile | Farm grid |
| wooden_house | Main building |
| tree_set | Decoration |

---

## Crops

| Asset | Purpose |
|-|-|
| carrot_growth_stage | Crop stages |
| wheat_field | Harvestable crop |

---

## UI

| Asset | Purpose |
|-|-|
| inventory_panel | Item management |
| quest_card | Task display |

---

# Development Plan

## Phase 1

Farm Prototype

Deliver:

- Grid placement
- Crop planting
- Harvesting

---

## Phase 2

Progression System

Deliver:

- Inventory
- Currency
- Upgrades

---

## Phase 3

Content Expansion

Deliver:

- Animals
- Buildings
- Decoration

---

## Phase 4

Live Content

Deliver:

- Events
- Seasonal updates
- New areas

---

# Claude Code Tasks

## Task 001

Create farm grid system.

Files:

FarmGrid

TileData

Acceptance:

Player can place objects on grid.

---

## Task 002

Implement crop lifecycle.

Files:

CropSystem

CropData

Acceptance:

Crops progress through growth stages.

---

## Task 003

Implement inventory.

Files:

InventoryManager

ItemData

Acceptance:

Items can be stored and consumed.

---

# Quality Check

Passed:

✓ Long-term progression defined

✓ Resource loop exists

✓ Expandable architecture

✓ Data-driven systems

✓ Future content supported