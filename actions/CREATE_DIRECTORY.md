# ACTION

CREATE_DIRECTORY.md

Version: 2.0.0

---

# Purpose

Create missing project directories according to the selected engine and project structure.

This action is responsible only for directories.

It never creates files.

---

# Inputs

Read

PROJECT_STRUCTURE.md

Determine

Required folders

Current folder tree

Engine

Platform

---

# Responsibilities

✓ Detect missing folders

✓ Create folders

✓ Preserve existing folders

✓ Update FILE_INDEX

Never remove directories.

Never rename user directories.

---

# Execution

Step 1

Read required structure.

↓

Step 2

Scan project.

↓

Step 3

Compare.

↓

Step 4

Generate missing folders.

↓

Step 5

Verify.

↓

Step 6

Update memory.

---

# Rules

Only create folders defined by

PROJECT_STRUCTURE.md

Do not create temporary folders.

Do not invent folder names.

---

# Verification

After creation

Verify

✓ Folder exists

✓ Parent exists

✓ Naming correct

✓ No duplicates

---

# Output

Created folders

Skipped folders

Errors

Memory updated

---

# Failure

If permission denied

Stop.

Report error.

If parent folder missing

Create parent first.

---

# Completion

Complete when

Required folder tree matches project structure.