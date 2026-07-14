# ACTION

DELETE_FILE.md

Version: 2.0.0

---

# Purpose

Safely delete unnecessary project files.

Deletion should be conservative.

User-created files must always be protected.

---

# Trigger

Run when

- Removing obsolete scaffolds
- Cleaning temporary files
- Removing duplicate assets
- User explicitly requests deletion

---

# Responsibilities

✓ Delete unused files

✓ Verify dependencies

✓ Update references

✓ Update memory

---

# Inputs

Read

FILE_INDEX.json

↓

PROJECT_STATE.json

↓

Project Tree

↓

Execution Plan

---

# Deletion Pipeline

Phase 1

Locate Target

Verify

Exists

↓

Tracked

↓

Allowed

---

Phase 2

Dependency Check

Search

Imports

References

Scenes

Configs

Assets

Documentation

If referenced

Stop.

---

Phase 3

Safety Validation

Protected files

README.md

CLAUDE.md

GAME_DESIGN.md

DEV_PLAN.md

PROJECT_STATE.json

Never delete protected files.

---

Phase 4

Delete

Remove file.

Never batch delete without approval.

---

Phase 5

Cleanup

Remove references.

Update index.

Update documentation.

---

Phase 6

Memory Update

Update

FILE_INDEX.json

↓

CHANGELOG.md

↓

TASK_STATE.json

---

# Rules

Never delete handwritten code automatically.

Never delete assets referenced by scenes.

Never delete save data.

---

# Output

Deleted Files

Skipped Files

Reason

Warnings

---

# Failure

If dependency exists

Cancel deletion.

Recommend REVIEW.

---

# Completion

Deletion completes when

Project remains valid.

No broken references exist.