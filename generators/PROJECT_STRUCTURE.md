# GENERATOR

PROJECT_STRUCTURE.md

Version: 2.0.0

---

# Purpose

Generate a production-ready project structure based on the selected game engine, platform, and project type.

The generated structure should be clean, scalable, and maintainable.

Never generate unnecessary folders.

---

# Inputs

Read

GAME_DESIGN.md

↓

PROJECT_STATE.json

↓

DEV_PLAN.md

↓

PROJECT_BOOTSTRAP.md

---

# Responsibilities

✓ Determine engine

✓ Determine platform

✓ Determine project scale

✓ Generate folder hierarchy

✓ Generate naming rules

✓ Generate module boundaries

---

# Supported Engines

Cocos Creator

Unity

Godot

Unknown

If unsupported

Stop.

Ask user.

Never guess.

---

# Folder Rules

Every folder must have

Purpose

Owner

Content Type

Naming Convention

---

# Standard Structure

docs/

assets/

scripts/

configs/

resources/

scenes/

tools/

tests/

build/

---

# Script Structure

scripts/

core/

managers/

systems/

components/

ui/

data/

network/

utils/

extensions/

---

# Asset Structure

assets/

images/

audio/

animations/

fonts/

effects/

prefabs/

materials/

shaders/

localization/

---

# Rules

Never create duplicate folders.

Never create engine-specific folders for another engine.

Never mix runtime and editor resources.

---

# Validation

Verify

✓ Folder hierarchy

✓ Naming consistency

✓ Engine compatibility

✓ Platform compatibility

---

# Output

Generated Structure

Folder Tree

Naming Rules

Validation Result

---

# Completion

Complete when

Project folder structure is fully defined and validated.