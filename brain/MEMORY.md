# MEMORY

Version: 2.0.0

---

# Purpose

The Memory module maintains the working state of the Game Builder Agent.

Unlike conversation memory, this module stores project progress.

Memory allows the agent to continue development without re-planning the entire project.

---

# Principles

Memory is:

✓ Persistent

✓ Structured

✓ Machine-readable

✓ Automatically updated

Never rely only on chat history.

Always prefer project memory.

---

# Memory Location

Store memory in

.gamebuilder/

Required files

PROJECT_STATE.json

TASK_STATE.json

SESSION_STATE.json

FILE_INDEX.json

CHANGELOG.md

---

# PROJECT_STATE.json

Purpose

Stores overall project status.

Required Fields

Project Name

Engine

Platform

Language

Current State

Current Milestone

Current Sprint

Current Task

Progress

Created Time

Last Updated

Example

{
  "projectName":"Coffee Shop",
  "engine":"Cocos Creator",
  "platform":"WeChat Mini Game",
  "language":"TypeScript",
  "state":"BUILDING",
  "milestone":"M1",
  "sprint":"Sprint 2",
  "task":"TASK_021",
  "progress":38
}

---

# TASK_STATE.json

Purpose

Track every task.

Each task contains

Task ID

Title

Status

Priority

Dependencies

Owner

Files

Acceptance Criteria

Statuses

TODO

READY

IN_PROGRESS

BLOCKED

REVIEW

DONE

Example

TASK_001

Status

DONE

TASK_002

Status

IN_PROGRESS

TASK_003

Status

READY

---

# SESSION_STATE.json

Purpose

Remember current conversation.

Fields

Current Goal

Working Module

Last Action

Pending Question

Suggested Next Action

Example

Goal

Implement inventory.

Current Module

InventoryManager

Next

Generate ItemData.

---

# FILE_INDEX.json

Purpose

Track generated files.

Every file stores

Path

Type

Module

Generated Time

Modified Time

Dependencies

Status

Example

scripts/core/GameManager.ts

Module

Core

Status

Generated

---

# CHANGELOG.md

Purpose

Human-readable history.

Example

2026-07-14

Generated project.

Created core architecture.

Initialized Cocos project.

Added SaveManager.

---

# Memory Update Rules

Update memory when

✓ New file created

✓ File deleted

✓ Task completed

✓ Sprint changed

✓ Milestone completed

✓ State changed

✓ Architecture updated

---

# Read Priority

Before any action

Read

PROJECT_STATE.json

↓

TASK_STATE.json

↓

SESSION_STATE.json

↓

FILE_INDEX.json

Never guess project status.

---

# Recovery

If memory missing

Reconstruct from

Folder structure

↓

Git history

↓

Documentation

↓

Existing source code

If confidence is low

Ask the user.

---

# Synchronization

Memory must always match

Source code

Documentation

Project folders

Task status

If inconsistency detected

Report it.

Never silently overwrite memory.

---

# Continue Development

When user says

"Continue"

Agent performs

Step 1

Load PROJECT_STATE.json

↓

Step 2

Load TASK_STATE.json

↓

Step 3

Find first READY task

↓

Step 4

Verify dependencies

↓

Step 5

Execute task

↓

Step 6

Update memory

---

# Review Mode

During review

Compare

Memory

↓

Actual project

Check

Missing files

Missing tasks

Unexpected files

Architecture drift

Documentation drift

---

# Completion

Memory system is complete when

The agent can stop at any time.

Resume at any time.

Continue development without asking the user to repeat project information.