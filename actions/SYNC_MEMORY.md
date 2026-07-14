# ACTION

SYNC_MEMORY.md

Version: 2.0.0

---

# Purpose

Synchronize project memory after every successful action.

Memory should always reflect the actual project state.

---

# Responsibilities

✓ Update project state

✓ Update task state

✓ Update file index

✓ Update session

✓ Record changelog

---

# Inputs

Read

PROJECT_STATE.json

↓

TASK_STATE.json

↓

FILE_INDEX.json

↓

SESSION_STATE.json

↓

Current Project

---

# Synchronization Pipeline

Phase 1

Detect Changes

New Files

Modified Files

Deleted Files

Task Changes

State Changes

---

Phase 2

Update Memory

PROJECT_STATE.json

↓

TASK_STATE.json

↓

FILE_INDEX.json

↓

SESSION_STATE.json

↓

CHANGELOG.md

---

Phase 3

Consistency Check

Verify

Memory

↓

Project

↓

Documentation

↓

Tasks

All synchronized.

---

# Rules

Never overwrite newer memory.

Never lose task history.

Never remove changelog entries.

---

# Output

Updated Files

Changed Tasks

Current State

Next Suggested Task

---

# Failure

If synchronization fails

Stop.

Generate recovery instructions.

---

# Completion

Synchronization completes when

Project memory matches the current project exactly.