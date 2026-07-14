# EXECUTOR

CONTINUE.md

Version: 2.0.0

---

# Purpose

Continue project development from the current project state.

Unlike BUILD, CONTINUE does not start from a user request.

It resumes interrupted work.

The goal is to continue development with minimal user input.

---

# Trigger

Typical user requests

"Continue"

"Continue development"

"Next"

"Next task"

"Resume"

"Go on"

"Keep building"

---

# Responsibilities

✓ Restore project context

✓ Read project memory

✓ Find next executable task

✓ Validate dependencies

✓ Execute task

✓ Update project memory

✓ Recommend following task

---

# Preconditions

Before execution verify

✓ PROJECT_STATE.json exists

✓ TASK_STATE.json exists

✓ SESSION_STATE.json exists

✓ Current project state is valid

If memory is incomplete

Attempt recovery.

If recovery fails

Ask the user.

---

# Continue Pipeline

Phase 1

Restore Context

Read

PROJECT_STATE.json

↓

TASK_STATE.json

↓

SESSION_STATE.json

↓

FILE_INDEX.json

↓

Current project files

---

Phase 2

Validate State

Verify

Current State

Current Milestone

Current Sprint

Current Task

Architecture consistency

---

Phase 3

Locate Next Task

Priority

1

IN_PROGRESS

↓

2

READY

↓

3

TODO

Never execute BLOCKED tasks.

---

Phase 4

Dependency Check

Verify

Required files

Required modules

Required generators

Previous tasks

If dependencies fail

Return to Planner.

---

Phase 5

Resume Execution

Execute

Current task

or

Next READY task

using BUILD executor.

---

Phase 6

Synchronize

Update

PROJECT_STATE.json

TASK_STATE.json

FILE_INDEX.json

SESSION_STATE.json

CHANGELOG.md

---

Phase 7

Completion

If current sprint completed

Recommend next sprint.

Otherwise

Recommend next task.

---

# Recovery

If task partially completed

Determine

Finished work

Remaining work

Continue only unfinished work.

Never duplicate generated files.

---

# Failure Handling

Possible failures

Missing memory

↓

Recover

Missing files

↓

Verify

Dependency conflict

↓

Return Planner

Architecture mismatch

↓

Review

---

# Output

Always output

Current State

Current Sprint

Current Task

Completed Work

Executed Actions

Updated Files

Remaining Tasks

Suggested Next Task

---

# Safety Rules

Never restart completed tasks.

Never overwrite completed work.

Never reset project state.

Never ignore dependency failures.

---

# Completion

CONTINUE completes when

The current task reaches DONE

or

Execution stops because user confirmation is required.