# GENERATOR

PROJECT_BOOTSTRAP.md

Version: 2.0.0

---

# Purpose

Bootstrap a production-ready game project from generated design documents.

Unlike templates, this generator creates a real project structure that Claude Code can immediately continue developing.

The goal is not documentation.

The goal is a runnable project foundation.

---

# Trigger

Run AFTER:

✓ GAME_DESIGN.md

✓ ART_BIBLE.md

✓ UI_GUIDE.md

✓ ASSET_LIST.md

✓ DEV_PLAN.md

✓ CLAUDE.md

have all been generated.

---

# Inputs

Required

GAME_DESIGN.md

Read

- Engine
- Platform
- Programming Language
- Target Resolution
- Core Systems

Required

DEV_PLAN.md

Read

- MVP
- Milestones
- Sprint 1

Required

ASSET_LIST.md

Read

- Folder Mapping

---

# Responsibilities

Generate

✓ Project folders

✓ Empty source files

✓ Configuration files

✓ Documentation

✓ Initial TODO list

Do NOT implement gameplay.

Do NOT invent extra features.

---

# Step 1

Determine Engine

Supported

Cocos Creator

Unity

Godot

Unknown

If unknown

Ask user.

Never guess.

---

# Step 2

Generate Folder Structure

Example

project/

docs/

assets/

scripts/

resources/

scenes/

configs/

tools/

README.md

CLAUDE.md

The folder structure MUST match the selected engine.

---

# Step 3

Create Core Source Structure

Generate empty modules.

Example

GameManager

SceneManager

UIManager

AudioManager

SaveManager

ConfigManager

InputManager

Each module should contain

Purpose

TODO

Public API

No business logic.

---

# Step 4

Generate Configuration Files

Depending on engine

Examples

package.json

tsconfig.json

.editorconfig

.gitignore

README.md

Never overwrite existing files.

---

# Step 5

Generate Documentation

Create

PROJECT_STRUCTURE.md

Describe

Folder purpose

Naming rules

Module responsibilities

Dependency directions

---

# Step 6

Generate Development Queue

Create

TODO.md

Automatically extract

Sprint 1

Task list

Priority

Acceptance Criteria

Dependencies

---

# Step 7

Project Validation

Verify

✓ Folder structure complete

✓ Engine detected

✓ Source folders exist

✓ Docs exist

✓ Configuration files exist

✓ TODO generated

---

# Output

When complete

Display

Bootstrap Complete

Project Root

Detected Engine

Detected Platform

Generated Folders

Generated Files

Next Recommended Action

Example

Next:

Create Core Architecture

or

Implement Sprint 1 Task 001

---

# Safety Rules

Never

Delete files

Rename user folders

Overwrite source code

Generate fake assets

Modify project settings without approval

---

# Completion

Bootstrap is complete when

The project can be opened in the selected engine.

Claude Code can continue implementation without asking for project structure.