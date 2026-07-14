# Example

Cooking Simulation Game

Version: 1.0.0

---

# User Input

I want to create a cooking simulation game.

Game Name:

Cozy Kitchen Story

Platform:

Mobile

Genre:

Cooking Simulation

Art Style:

Warm cartoon style

Core Idea:

Players run a small restaurant, prepare dishes, serve customers, and expand the kitchen.

Target Audience:

Casual players who enjoy relaxing management games.

Session:

5-10 minutes.

---

# Generated Project Summary

## Project Name

Cozy Kitchen Story

---

## Genre

Cooking Simulation / Casual Management

---

## Platform

Mobile

Orientation:

Portrait

Input:

Touch

---

## Core Gameplay

Players manage a small kitchen.

They select recipes, prepare ingredients, complete cooking steps, serve customers, earn coins, and upgrade the restaurant.

---

# Design Pillars

## 1. Relaxing Experience

The game should feel comfortable rather than stressful.

---

## 2. Creative Cooking

Players gradually unlock new recipes and kitchen equipment.

---

## 3. Meaningful Progress

Every cooking session improves the restaurant.

---

# MVP Definition

## Must Have

### Basic Cooking Flow

Players can:

- Select recipe
- Prepare ingredients
- Cook
- Serve customer
- Receive reward

---

### Recipe System

Include:

- Recipe data
- Ingredients
- Cooking time
- Reward value

---

### Restaurant Upgrade

Players can upgrade:

- Tables
- Kitchen equipment
- Decoration

---

## Should Have

- Customer personalities
- Special orders
- Daily missions

---

## Could Have

- Staff management
- Restaurant events
- Online ranking

---

## Won't Have

- Real-time multiplayer cooking
- Complex economic simulation
- User-generated recipes

---

# Core Gameplay Loop

```
Receive Order

↓

Choose Recipe

↓

Prepare Ingredients

↓

Complete Cooking Actions

↓

Serve Customer

↓

Earn Coins

↓

Upgrade Kitchen

↓

Unlock Recipes
```

---

# Game Systems

## Customer System

Responsibilities:

- Generate orders
- Control waiting time
- Calculate satisfaction

---

## Recipe System

Responsibilities:

- Store recipe data
- Define cooking process
- Calculate rewards

---

## Cooking Interaction System

Responsibilities:

- Handle player actions
- Detect completion
- Provide feedback

---

## Economy System

Responsibilities:

- Coins
- Costs
- Upgrades
- Rewards

---

# Data Structure Example

## Recipe Data

```
Recipe

id

name

ingredients

steps

time

reward

unlockLevel
```

---

## Ingredient Data

```
Ingredient

id

name

cost

category

storageLimit
```

---

# Technical Architecture

Engine:

Unity

Language:

C#

Structure:

```
Assets/

Scripts/

Scenes/

Prefabs/

Data/

UI/

Audio/

```

---

# UI Structure

## Main Restaurant

Contains:

- Restaurant view
- Upgrade button
- Currency display

---

## Cooking Screen

Contains:

- Recipe selection
- Cooking area
- Ingredient panel
- Progress

---

## Customer Screen

Contains:

- Customer orders
- Satisfaction

---

## Upgrade Screen

Contains:

- Equipment
- Decorations
- Costs

---

# Art Direction

Style:

Cozy cartoon

Keywords:

- Warm
- Handmade
- Friendly
- Colorful

Materials:

- Wood
- Ceramic
- Fabric
- Food textures

---

# Asset List Example

## Characters

| Asset | Purpose |
|-|-|
| customer_basic | Customer model |
| chef_character | Player character |

---

## Environment

| Asset | Purpose |
|-|-|
| kitchen_room | Main scene |
| cooking_table | Interaction object |

---

## Food

| Asset | Purpose |
|-|-|
| pizza_dish | Recipe output |
| vegetable_set | Ingredient |

---

# Development Plan

## Phase 1

Prototype Cooking Loop

Deliver:

- Recipe selection
- Cooking interaction
- Basic reward

---

## Phase 2

Restaurant Management

Deliver:

- Upgrades
- Economy
- Customer system

---

## Phase 3

Content Expansion

Deliver:

- More recipes
- More decorations
- More customers

---

# Claude Code Tasks

## Task 001

Create recipe data system.

Files:

data/

scripts/

Acceptance:

Recipes can be loaded from data files.

---

## Task 002

Implement cooking interaction.

Files:

CookingController

CookingUI

Acceptance:

Player can complete a recipe.

---

## Task 003

Implement upgrade system.

Files:

EconomySystem

UpgradeSystem

Acceptance:

Player can spend coins and improve restaurant.

---

# Quality Check

Passed:

✓ Clear management loop

✓ Data-driven design

✓ Expandable content system

✓ Realistic MVP

✓ Claude tasks are executable