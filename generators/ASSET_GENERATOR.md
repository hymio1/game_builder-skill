# GENERATOR

ASSET_GENERATOR.md

Version: 2.0.0

---

# Purpose

Generate a complete production asset specification.

This generator does not create art.

It creates the asset planning required for implementation.

---

# Inputs

Read

GAME_DESIGN.md

↓

ART_BIBLE.md

↓

UI_GUIDE.md

↓

DEV_PLAN.md

---

# Responsibilities

✓ Analyze gameplay

✓ Generate asset requirements

✓ Categorize assets

✓ Estimate production workload

✓ Define technical specifications

---

# Asset Categories

Characters

Environment

Props

UI

Icons

Animations

Particles

Effects

Audio

Music

Localization

Fonts

Shaders

---

# Asset Specification

Each asset should include

Asset ID

↓

Display Name

↓

Category

↓

Purpose

↓

Format

↓

Resolution

↓

Estimated Quantity

↓

Priority

↓

Production Status

---

# Technical Rules

Images

PNG

WebP

Spritesheet

Audio

WAV

OGG

MP3

Animations

Spine

Frame Animation

Particle

Engine Native

Fonts

TTF

OTF

---

# Production Priority

P0

Required for MVP

P1

Core Gameplay

P2

Important

P3

Optional

---

# Validation

Verify

✓ No duplicated assets

✓ Correct folder mapping

✓ Required specifications

✓ Naming consistency

---

# Output

Asset List

Folder Mapping

Production Order

Estimated Workload

Validation Result

---

# Safety

Never invent unsupported formats.

Never reference missing folders.

Never duplicate asset IDs.

---

# Completion

Generation completes when

Every gameplay feature has corresponding asset specifications.

All assets are categorized and prioritized.