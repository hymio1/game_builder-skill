# ACTION

GENERATE_CONFIG.md

Version: 2.0.0

---

# Purpose

Generate project configuration files.

Configuration should match the selected engine and platform.

Never overwrite existing configuration without approval.

---

# Responsibilities

✓ Generate configuration files

✓ Validate configuration

✓ Register generated files

✓ Update memory

---

# Supported Files

Common

README.md

↓

.gitignore

↓

.editorconfig

↓

LICENSE

↓

CHANGELOG.md

Engine Specific

package.json

↓

tsconfig.json

↓

engine configuration

↓

build configuration

---

# Engine Rules

Cocos Creator

Generate

package.json

tsconfig.json

settings

extensions

Unity

Generate

Packages

ProjectSettings

Assembly Definitions

Godot

Generate

project.godot

export_presets.cfg

addons

Never generate files for multiple engines.

---

# Validation

Verify

✓ Correct engine

✓ Correct language

✓ Correct file names

✓ Valid syntax

---

# Output

Generated Files

Skipped Files

Updated Files

Configuration Status

---

# Safety

Never overwrite configuration automatically.

Always preserve user modifications.

---

# Completion

Configuration generation completes when

All required configuration files exist and pass validation.