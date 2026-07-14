# GENERATOR

CODE_SCAFFOLD.md

Version: 2.0.0

---

# Purpose

Generate consistent source-code scaffolds for all project modules.

Scaffolds define structure only.

Business logic is implemented later.

---

# Inputs

Read

GAME_DESIGN.md

↓

PROJECT_STRUCTURE.md

↓

Execution Plan

↓

Current Task

---

# Responsibilities

✓ Generate classes

✓ Generate interfaces

✓ Generate managers

✓ Generate systems

✓ Generate data models

✓ Generate UI skeletons

---

# Supported Types

Manager

System

Component

Service

Repository

UI Panel

UI Item

Scene Controller

Data Model

Configuration

---

# Scaffold Rules

Every generated class includes

Header

↓

Purpose

↓

Dependencies

↓

Constructor

↓

Lifecycle

↓

Public API

↓

Private Methods

↓

TODO

---

# API Rules

Expose only necessary public methods.

Hide implementation details.

Keep APIs stable.

---

# Naming Rules

Manager

InventoryManager

System

SaveSystem

Component

PlayerController

UI

MainMenuPanel

Data

ItemData

---

# Documentation

Generate

Class description

Method description

Parameters

Return values

---

# Validation

Verify

✓ Naming

✓ Imports

✓ Folder location

✓ Dependencies

✓ Public API

---

# Output

Generated Classes

Generated Interfaces

Generated APIs

Warnings

---

# Completion

Complete when

Every planned module has a scaffold ready for implementation.