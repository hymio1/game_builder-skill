# ACTION

GENERATE_DATA.md

Version: 2.0.0

---

# Purpose

Generate structured game data.

The generated data should be machine-readable.

Prefer JSON unless the project specifies another format.

---

# Responsibilities

✓ Generate data files

✓ Validate schema

✓ Register generated data

✓ Update memory

---

# Supported Data

Recipes

Items

Levels

Enemies

NPCs

Dialogue

Achievements

Localization

Configuration

Economy

Save Defaults

UI Layout

---

# Data Rules

Each record requires

Unique ID

↓

Display Name

↓

Description

↓

Required Fields

↓

Default Values

↓

Version

Never generate duplicate IDs.

---

# File Rules

Preferred formats

JSON

↓

CSV

↓

YAML

Use project preference if specified.

---

# Validation

Verify

✓ Unique IDs

✓ Required fields

✓ Correct schema

✓ Valid references

✓ No orphan records

---

# Relationships

Support

One-to-One

One-to-Many

Many-to-Many

Validate foreign keys where applicable.

---

# Output

Generated Files

Record Count

Validation Result

Warnings

---

# Safety

Never delete user data.

Never regenerate existing IDs.

Never change save data structure without approval.

---

# Completion

Generation completes when

All required data files pass schema validation.