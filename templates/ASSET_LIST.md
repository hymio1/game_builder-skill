# TEMPLATE

ASSET_LIST.md

Version: 2.0.0

Derived From:
- GAME_DESIGN.md
- ART_BIBLE.md
- UI_GUIDE.md

Priority:
GAME_DESIGN.md
↓
ART_BIBLE.md
↓
UI_GUIDE.md
↓
ASSET_LIST.md

---

# Purpose

Generate a complete production-ready Asset List.

The Asset List is the master inventory of all assets required for the project.

It is the single source of truth for production tracking.

Do NOT invent gameplay.

Do NOT redesign UI.

Do NOT redefine visual style.

Generate assets strictly from upstream documents.

---

# Dependencies

Required:

GAME_DESIGN.md

Read:

- Core Gameplay
- Secondary Systems
- Level Design
- Controls
- Feedback Systems
- Progression

Required:

ART_BIBLE.md

Read:

- Visual Vision
- Color System
- Shape Language
- Materials
- Typography
- Animation
- Effects

Required:

UI_GUIDE.md

Read:

- Screen Specifications
- Component Library
- HUD
- Navigation
- Motion Design

If any dependency is incomplete

STOP.

Report missing dependency.

---

# Outputs

Generate

ASSET_LIST.md

---

# Asset Categories

Assets must be grouped by category.

Required Categories:

Characters

Environment

Props

Gameplay Objects

Collectibles

Interactive Objects

UI

Icons

Buttons

Panels

Illustrations

Animations

Visual Effects

Particles

Shaders

Fonts

Audio

Music

Sound Effects

Voice

Localization

Configuration Assets

Third-party Assets

Marketing Assets

---

# Asset Specification

Each asset MUST include:

Asset ID

Asset Name

Category

Purpose

Description

Reference Document

Source Section

File Name

Folder

Format

Resolution

Pivot Rule

Animation

Dependencies

Priority

Owner

Status

Notes

---

# Naming Convention

Asset IDs

CATEGORY_001

Examples

UI_001

ICON_014

CHAR_003

FX_025

File Names

snake_case

Example

main_menu_background.png

red_yarn_ball.png

button_primary_normal.png

---

# Folder Mapping

Every asset must map to a folder.

Example

assets/

characters/

environment/

ui/

icons/

effects/

audio/

music/

sfx/

fonts/

localization/

marketing/

---

# Priority Levels

Critical

Required for MVP.

High

Gameplay dependent.

Medium

Improves experience.

Low

Optional polish.

Future

Post-launch.

---

# Production Status

Each asset should contain

Not Started

Concept

In Progress

Review

Approved

Integrated

Deprecated

---

# Reuse Policy

Whenever possible

Reuse assets.

Avoid duplicate production.

Reference existing assets before creating new ones.

---

# Technical Standards

Specify

Supported Formats

PNG

WEBP

JPG

SVG

MP3

OGG

WAV

TTF

JSON

Atlas Support

Compression

Maximum Texture Size

Memory Budget

---

# Animation Assets

For animated assets define

Idle

Hover

Pressed

Drag

Drop

Success

Failure

Loop

Transition

---

# UI Assets

Generate separately

Buttons

Icons

Panels

Windows

Badges

Progress Bars

Dialogs

Tabs

Navigation

HUD

Backgrounds

---

# Audio Assets

Separate

BGM

Ambient

UI

Gameplay

Rewards

Failure

Tutorial

Notifications

Voice

---

# Localization Assets

Include

Language Files

Font Files

Dynamic Strings

Images with Text

RTL Support

Plural Rules

---

# External Resources

If external assets are recommended

Specify

Source

License

Modification Required

Commercial Compatibility

Never assume unrestricted licenses.

---

# Production Order

Recommend creation sequence

1. Core Gameplay Assets

2. UI Assets

3. Environment

4. Audio

5. Effects

6. Marketing Assets

---

# Cross References

Depends on

GAME_DESIGN.md

ART_BIBLE.md

UI_GUIDE.md

Provides information to

DEV_PLAN.md

CLAUDE.md

---

# Validation

Verify

✓ Every gameplay mechanic has supporting assets.

✓ Every screen has UI assets.

✓ Every interaction has feedback assets.

✓ Folder mapping exists.

✓ Naming convention is consistent.

✓ File formats match target platform.

✓ No duplicate assets.

✓ No orphan assets.

If validation fails

Regenerate affected sections only.

---

# Completion Criteria

The Asset List is complete when

Artists know exactly what to produce.

Developers know where assets belong.

Producers can estimate workload.

QA can verify completeness.

Claude Code can generate production tasks directly.