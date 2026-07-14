# ACTION

INITIALIZE_PROJECT.md

Version: 2.0.0

---

# Purpose

Initialize a new game project.

This action prepares the project for development.

Initialization should create the minimum required environment for future actions.

Initialization never implements gameplay.

---

# Trigger

Run when

Project State

BOOTSTRAPPING

or

User Request

"Initialize project"

"Setup project"

"Create project"

---

# Responsibilities

✓ Detect project type

✓ Detect engine

✓ Detect platform

✓ Detect language

✓ Initialize folder structure

✓ Initialize configuration

✓ Initialize documentation

✓ Initialize source structure

✓ Register project

---

# Inputs

Read

GAME_DESIGN.md

↓

PROJECT_STRUCTURE.md

↓

DEV_PLAN.md

↓

PROJECT_STATE.json

---

# Initialization Pipeline

Phase 1

Project Detection

Determine

Project Name

↓

Engine

↓

Platform

↓

Programming Language

↓

Rendering Pipeline

↓

Package Manager

---

Phase 2

Environment Validation

Verify

Required software

Engine support

Language support

Folder permissions

Existing project files

---

Phase 3

Initialize Structure

Call

CREATE_DIRECTORY

↓

Verify directories

↓

Update FILE_INDEX

---

Phase 4

Initialize Configuration

Call

GENERATE_CONFIG

Generate

README

↓

.gitignore

↓

.editorconfig

↓

package.json

↓

tsconfig.json

↓

engine configuration

---

Phase 5

Initialize Source

Create

scripts/

↓

core/

↓

managers/

↓

systems/

↓

data/

↓

ui/

↓

utils/

Create placeholder files only.

Never generate gameplay logic.

---

Phase 6

Initialize Documentation

Verify

README.md

↓

GAME_DESIGN.md

↓

ART_BIBLE.md

↓

UI_GUIDE.md

↓

ASSET_LIST.md

↓

DEV_PLAN.md

↓

CLAUDE.md

Generate missing documents if allowed.

Never overwrite existing documentation.

---

Phase 7

Register Project

Update

PROJECT_STATE.json

↓

FILE_INDEX.json

↓

CHANGELOG.md

↓

SESSION_STATE.json

---

Phase 8

Verification

Verify

✓ Folder structure

✓ Configuration

✓ Documentation

✓ Source folders

✓ Memory files

↓

Return

Initialization Complete

---

# Safety Rules

Never

Delete existing projects.

Overwrite user files.

Modify engine settings without approval.

Replace handwritten code.

---

# Output

Display

Project Name

Detected Engine

Detected Platform

Language

Created Directories

Created Files

Configuration Generated

Memory Updated

Next Recommended Action

---

# Failure Handling

If initialization fails

Stop immediately.

Report

Failed step

Reason

Recovery suggestion

Never continue after a critical failure.

---

# Completion

Initialization completes when

The project structure is ready.

Configuration exists.

Memory is initialized.

The Build Executor can begin implementation.