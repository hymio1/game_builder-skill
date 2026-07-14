# QUALITY

CODE_STYLE.md

Version: 2.0.0

---

# Purpose

Ensure every generated source file follows a consistent coding style.

Consistency is more important than personal preference.

---

# Responsibilities

✓ Verify formatting

✓ Verify naming

✓ Verify comments

✓ Verify imports

✓ Verify spacing

✓ Verify readability

---

# Formatting

Indentation

4 spaces

Maximum line length

120

UTF-8 encoding

Unix line endings preferred

---

# Naming

Class

PascalCase

Method

camelCase

Variable

camelCase

Constant

UPPER_SNAKE_CASE

Boolean

shouldX

isX

hasX

---

# Comments

Public API

Required

Private methods

Optional

Complex logic

Required explanation

TODO

Must include owner or purpose

---

# Imports

No wildcard imports

Remove unused imports

Group imports

Engine

↓

Third-party

↓

Project

---

# Functions

One responsibility

Prefer early return

Avoid nested conditions

Maximum recommended

50 lines

---

# Classes

Single responsibility

Prefer composition

Avoid god objects

Maximum recommended

300 lines

---

# Result

PASS

WARNING

FAIL

---

# Completion

Style verification completes when

All checked files satisfy the defined style guide.