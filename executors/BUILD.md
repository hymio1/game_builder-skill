# EXECUTOR

BUILD.md

Version: 2.0.0

---

# Purpose

The Build Executor transforms a validated execution plan into concrete project changes.

Unlike the Planner, Build performs work.

Unlike Actions, Build coordinates work.

It is the central execution engine of Game Builder.

---

# Responsibilities

The Build Executor should:

✓ Read execution plan

✓ Validate current state

✓ Execute tasks in order

✓ Call generators

✓ Call actions

✓ Verify results

✓ Update memory

✓ Produce progress report

---

# Execution Preconditions

Before starting

Verify

✓ PROJECT_STATE.json exists

✓ Current state allows BUILD

✓ Required documents exist

✓ Dependencies are satisfied

If any requirement fails

Stop execution.

Explain the reason.

Do not continue.

---

# Build Pipeline

Phase 1

Load Context

Read

PROJECT_STATE.json

↓

TASK_STATE.json

↓

SESSION_STATE.json

↓

FILE_INDEX.json

↓

Current source tree

---

Phase 2

Validate

Confirm

Current Sprint

Current Task

Dependencies

Architecture consistency

---

Phase 3

Select Work

Find

First READY task.

If none exists

Return

"No executable task."

---

Phase 4

Generate

Call required generators.

Possible generators

PROJECT_STRUCTURE

DATA_GENERATOR

CODE_SCAFFOLD

TASK_GENERATOR

Only invoke generators that are required.

---

Phase 5

Execute Actions

Possible actions

CREATE_DIRECTORY

CREATE_FILE

UPDATE_FILE

INITIALIZE_PROJECT

VERIFY_PROJECT

Actions must execute sequentially.

Never run conflicting actions in parallel.

---

Phase 6

Verification

Verify

Generated files

Folder structure

Architecture

Naming

Dependencies

If verification fails

Rollback current task when possible.

Report errors.

---

Phase 7

Memory Update

Update

PROJECT_STATE.json

TASK_STATE.json

FILE_INDEX.json

CHANGELOG.md

SESSION_STATE.json

---

Phase 8

Completion

Mark task

DONE

Find next READY task.

If available

Recommend continuing.

Otherwise

Recommend entering REVIEW state.

---

# Failure Handling

Possible failures

Missing dependency

↓

Stop

Missing file

↓

Regenerate

Conflict

↓

Ask user

Architecture mismatch

↓

Return to Planner

Verification failed

↓

Rollback current task

---

# Output

Always produce

Build Summary

Current Task

Files Created

Files Modified

Generators Used

Actions Executed

Verification Result

Memory Updated

Suggested Next Task

---

# Safety Rules

Never

Delete user code without approval.

Overwrite existing files silently.

Modify unrelated modules.

Change architecture during BUILD.

Skip verification.

---

# Build Modes

Mode

Dry Run

Generate execution plan only.

No files modified.

---

Mode

Standard

Execute approved actions.

Update memory.

---

Mode

Safe

Require confirmation before modifying existing files.

---

Mode

Force

Allowed only after explicit user approval.

May overwrite generated scaffold files.

Never overwrite handwritten user code.

---

# Completion

The Build Executor completes when

The current task reaches DONE.

All generated outputs pass verification.

Memory is synchronized.

The next executable task is identified.