# ACTION

MOVE_FILE.md

Version: 2.0.0

---

# Purpose

Safely move or rename project files and directories while preserving project integrity.

This action is responsible for relocating existing resources.

It never generates new content.

---

# Trigger

Run when

- Project structure changes
- Module refactoring
- Folder reorganization
- User requests rename
- Architecture optimization

---

# Responsibilities

✓ Move files

✓ Rename files

✓ Move folders

✓ Update references

✓ Update memory

✓ Preserve history

---

# Inputs

Read

PROJECT_STATE.json

↓

FILE_INDEX.json

↓

Current Project Tree

↓

Execution Plan

---

# Execution Pipeline

Phase 1

Validate Source

Verify

✓ Source exists

✓ Target valid

✓ No conflict

---

Phase 2

Dependency Analysis

Detect

Imports

References

Configuration

Documentation

Memory

Asset References

---

Phase 3

Move

Execute

Move

or

Rename

Never duplicate files.

---

Phase 4

Reference Update

Update

Imports

Paths

Configuration

Documentation

Memory

---

Phase 5

Verification

Verify

✓ File exists

✓ References valid

✓ No broken links

✓ Compilation safe

---

Phase 6

Synchronization

Update

FILE_INDEX.json

↓

CHANGELOG.md

↓

SESSION_STATE.json

---

# Rules

Never overwrite destination.

Never move generated files outside project.

Never move engine system folders.

---

# Failure Handling

If target exists

Stop.

If dependency broken

Rollback.

If verification fails

Restore original location.

---

# Output

Moved Files

Updated References

Warnings

Verification Result

---

# Completion

Move completes when

All references remain valid.

Memory is synchronized.

Project integrity is preserved.