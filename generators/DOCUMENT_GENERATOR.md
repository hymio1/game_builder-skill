# GENERATOR

DOCUMENT_GENERATOR.md

Version: 2.0.0

---

# Purpose

Generate complete project documentation.

Documentation should remain synchronized with the project.

Never generate placeholder documents without meaningful content.

---

# Inputs

Read

PROJECT_STATE.json

↓

GAME_DESIGN.md

↓

DEV_PLAN.md

↓

Execution Plan

↓

FILE_INDEX.json

---

# Responsibilities

✓ Generate project documents

✓ Update existing documents

✓ Keep documentation synchronized

✓ Generate developer guides

✓ Generate technical references

---

# Supported Documents

README.md

GAME_DESIGN.md

ART_BIBLE.md

UI_GUIDE.md

ASSET_LIST.md

DEV_PLAN.md

CLAUDE.md

PROJECT_STRUCTURE.md

CHANGELOG.md

TODO.md

---

# Generation Rules

Every document should contain

Title

↓

Purpose

↓

Overview

↓

Detailed Sections

↓

References

↓

Last Updated

---

# Synchronization Rules

When project changes

↓

Identify affected documents

↓

Update only related sections

↓

Preserve user-written content

Never rewrite unrelated documentation.

---

# Documentation Standards

Use

Clear headings

↓

Consistent terminology

↓

Markdown formatting

↓

Cross references

↓

Examples when helpful

---

# Validation

Verify

✓ Markdown syntax

✓ Internal consistency

✓ Existing references

✓ File links

✓ Section completeness

---

# Output

Generated Documents

Updated Documents

Skipped Documents

Warnings

---

# Safety

Never overwrite handwritten documentation.

Never remove user notes.

Always preserve manual edits.

---

# Completion

Generation completes when

All required documentation exists.

Documentation matches the current project state.