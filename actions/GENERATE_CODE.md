# ACTION

GENERATE_CODE.md

Version: 2.0.0

---

# Purpose

Generate production-ready source code based on the current execution plan.

The goal is consistency, maintainability, and extensibility.

This action generates implementation.

It never changes project architecture.

---

# Inputs

Always read

PROJECT_STATE.json

↓

TASK_STATE.json

↓

GAME_DESIGN.md

↓

DEV_PLAN.md

↓

FILE_INDEX.json

↓

Execution Plan

---

# Responsibilities

✓ Generate source code

✓ Follow project architecture

✓ Respect coding conventions

✓ Preserve existing APIs

✓ Update project memory

---

# Generation Principles

Code must be

Readable

↓

Maintainable

↓

Modular

↓

Extensible

↓

Testable

Never generate code that violates architecture.

---

# File Generation Rules

Every generated file must include

Header

Purpose

Dependencies

Generated Time

TODO

Example

Purpose

Manages inventory data.

Dependencies

ItemData

SaveManager

TODO

Implement stack merge.

---

# Class Rules

Each class should contain

Constructor

↓

Initialization

↓

Public API

↓

Private Methods

↓

Cleanup

Never generate excessively large classes.

Target

Less than 300 lines.

---

# Method Rules

Each method should

Do one thing.

Return predictable values.

Avoid side effects.

Validate parameters.

Handle errors.

---

# Naming Rules

Classes

PascalCase

InventoryManager

Variables

camelCase

itemCount

Constants

UPPER_SNAKE_CASE

MAX_LEVEL

Private fields

_prefix

or

private keyword

Follow the project's language conventions.

---

# Dependency Rules

Never import unused modules.

Avoid circular dependencies.

Depend on interfaces when possible.

Prefer composition over inheritance.

---

# Error Handling

Every public API should

Validate input.

↓

Handle failures.

↓

Return meaningful errors.

↓

Log when necessary.

Never silently ignore failures.

---

# Documentation

Generate

Class description

↓

Method description

↓

Parameter description

↓

Return description

Document public APIs.

Private helpers may omit comments.

---

# Engine Guidelines

Cocos Creator

Use Component lifecycle.

Avoid singleton abuse.

Unity

Follow MonoBehaviour lifecycle.

Godot

Follow Node lifecycle.

Never mix engine patterns.

---

# Code Quality

Generated code should

Compile

↓

Follow formatting

↓

Follow naming

↓

Avoid duplication

↓

Remain testable

---

# Testing Hooks

Expose public APIs suitable for testing.

Avoid tightly coupled implementations.

Dependency injection preferred where practical.

---

# Verification

Verify

✓ Syntax

✓ Imports

✓ Naming

✓ Dependencies

✓ Formatting

↓

Register file

↓

Update memory

---

# Output

Generated Files

Modified Files

Public APIs

Warnings

Verification Result

---

# Safety Rules

Never

Overwrite handwritten code.

Remove public APIs.

Rename existing classes without approval.

Introduce breaking changes.

---

# Completion

Generation completes when

Source code is generated.

Verification passes.

Memory is synchronized.