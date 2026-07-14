# QUALITY

ARCHITECTURE_CHECK.md

Version: 2.0.0

---

# Purpose

Verify that the generated project follows the required architecture.

Architecture consistency has higher priority than implementation speed.

Never approve a project with broken architecture.

---

# Trigger

Run after

BUILD

↓

PROJECT_BOOTSTRAP

↓

VERIFY_OUTPUT

↓

REVIEW

---

# Responsibilities

✓ Check folder structure

✓ Check module boundaries

✓ Check dependencies

✓ Check naming conventions

✓ Check architecture consistency

✓ Generate architecture report

---

# Review Scope

Project Structure

↓

Core Modules

↓

Managers

↓

Systems

↓

Components

↓

UI

↓

Data

↓

Resources

↓

Configuration

---

# Folder Rules

Verify

✓ Required folders exist

✓ No duplicated folders

✓ Correct hierarchy

✓ Engine conventions followed

---

# Layer Rules

Allowed dependency

UI

↓

Systems

↓

Managers

↓

Data

↓

Utilities

Forbidden

Data

↓

UI

Utilities

↓

Managers

Manager

↓

Manager

(circular)

---

# Module Rules

Each module should have

Single responsibility

↓

Clear ownership

↓

Stable API

↓

Limited dependencies

---

# Dependency Rules

Verify

No circular imports

↓

No duplicated services

↓

No hidden dependencies

↓

No engine misuse

---

# Naming Rules

Folders

lowercase

Files

PascalCase

Classes

PascalCase

Variables

camelCase

Constants

UPPER_SNAKE_CASE

---

# Size Rules

Recommended

Class

<300 lines

Method

<50 lines

File

<500 lines

Warn when exceeded.

---

# Separation Rules

Never mix

UI

Gameplay

Editor

Runtime

Networking

Persistence

---

# Engine Rules

Cocos Creator

Follow Component lifecycle

Avoid unnecessary singleton usage

Unity

Follow MonoBehaviour lifecycle

Godot

Follow Node lifecycle

Never mix engine patterns.

---

# Result Levels

PASS

Architecture is healthy.

WARNING

Minor improvements recommended.

FAIL

Critical architectural problems detected.

---

# Report

Generate

Architecture Score

Problems

Severity

Recommendations

Priority Order

---

# Completion

Architecture verification completes when

Every module satisfies the defined architecture rules.