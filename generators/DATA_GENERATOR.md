# GENERATOR

DATA_GENERATOR.md

Version: 2.0.0

---

# Purpose

Generate structured game content data.

The generated data should support gameplay, balancing, localization, and future expansion.

---

# Inputs

Read

GAME_DESIGN.md

↓

DEV_PLAN.md

↓

Current Feature

---

# Responsibilities

✓ Generate game data

✓ Generate configuration

✓ Generate localization

✓ Generate balancing tables

---

# Supported Data

Items

Recipes

Levels

NPCs

Dialogue

Skills

Achievements

Economy

Localization

Settings

---

# Rules

Every record must contain

Unique ID

Display Name

Version

Default Values

Description

Never generate duplicate IDs.

---

# Validation

Verify

✓ Schema

✓ References

✓ Required Fields

✓ Version

---

# Output

Generated Files

Record Count

Validation Result

---

# Completion

Complete when

All generated data passes validation.