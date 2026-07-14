# ACTION

CREATE_FILE.md

Version: 2.0.0

---

# Purpose

Create new project files.

Only create files that do not already exist.

Never overwrite existing files.

---

# Inputs

Read

Execution Plan

↓

Determine

Target file

Generator

Destination

---

# Responsibilities

✓ Create file

✓ Insert scaffold

✓ Register file

✓ Update FILE_INDEX

---

# Rules

Allowed

README

Config

TypeScript

JSON

Markdown

Prefab placeholder

Shader placeholder

Never create unsupported file types.

---

# File Template

Every generated source file begins with

Purpose

TODO

Dependencies

Author

Generated Time

---

# Verification

Verify

✓ File exists

✓ Extension correct

✓ Folder correct

✓ Header exists

---

# Output

Created

Skipped

Reason

---

# Failure

If file exists

Skip.

Report.

Never overwrite automatically.

---

# Completion

File successfully created and indexed.