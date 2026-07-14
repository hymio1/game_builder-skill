# TEMPLATE

ART_BIBLE.md

Version: 2.0.0

Derived From:
- GAME_DESIGN.md

Priority:
GAME_DESIGN.md > ART_BIBLE.md

---

# Purpose

Generate the complete Art Bible for the project.

This document defines the visual language, production standards, and asset specifications required by the art team.

The Art Bible MUST derive its design decisions from GAME_DESIGN.md.

It must NOT redefine gameplay, scope, platform, or project goals.

---

# Inputs

Required:

- GAME_DESIGN.md

Read the following sections before generation:

- Vision Statement
- Design Pillars
- Target Audience
- Core Gameplay Loop
- UI Principles
- Art Direction Summary
- Technical Constraints

If any required section is missing:

STOP

Return an error indicating the missing dependency.

Never invent missing design information.

---

# Outputs

Generate:

ART_BIBLE.md

---

# Responsibilities

The Art Bible defines:

Visual Language

↓

Color System

↓

Shape Language

↓

Material Language

↓

Lighting

↓

Typography

↓

Animation Style

↓

Effects Style

↓

Production Rules

It does NOT define gameplay.

---

# Required Sections

## 1. Visual Vision

Summarize the artistic vision.

Reference:

Vision Statement

Design Pillars

Describe:

Desired player emotion

Visual identity

Brand personality

Mood keywords

---

## 2. Art Direction

Reference:

Art Direction Summary

Expand into:

Primary Style

Secondary Style

Forbidden Styles

Visual References

Moodboard Keywords

Never introduce conflicting styles.

---

## 3. Color System

Define:

Primary Palette

Secondary Palette

Accent Colors

Warning Colors

Success Colors

Failure Colors

Neutral Colors

Accessibility considerations

Document HEX values whenever possible.

---

## 4. Shape Language

Define:

Rounded vs Sharp

Organic vs Geometric

Softness

Silhouette principles

Consistency rules

---

## 5. Materials

Specify materials used throughout the project.

Examples:

Fabric

Wood

Paper

Metal

Plastic

Glass

Yarn

Clay

For each material define:

Texture

Roughness

Visual purpose

Where it is used

---

## 6. Lighting

Describe:

Overall lighting philosophy

Shadow softness

Highlight style

Ambient color

Contrast level

Lighting should reinforce gameplay readability.

---

## 7. Illustration Rules

Specify:

Line quality

Brush style

Rendering

Perspective

Composition

Detail level

Forbidden techniques

---

## 8. Character Style

If applicable.

Describe:

Body proportions

Face style

Expressions

Animation personality

Color restrictions

Outline rules

---

## 9. Environment Style

Describe:

Backgrounds

Props

Decorations

Depth

Layering

Scale

Visual hierarchy

---

## 10. UI Style

Reference:

UI Principles

Do not redesign UI.

Only define:

Buttons

Panels

Windows

Frames

Icons

Spacing

Corner radius

Shadow style

Transparency

---

## 11. Icon System

Define:

Style

Perspective

Stroke

Fill

Corner radius

Sizes

Consistency rules

---

## 12. Typography

Specify:

Primary Font

Secondary Font

Numeric Font

Fallback Font

Hierarchy

Weights

Sizes

Spacing

Language support

---

## 13. Animation Language

Describe:

Motion principles

Speed

Overshoot

Bounce

Elasticity

Transitions

Micro interactions

Never define gameplay timing.

---

## 14. Effects

Define:

Particles

Glow

Smoke

Sparkles

Trails

Impact effects

Completion effects

Failure effects

---

## 15. Asset Production Standards

Specify:

Canvas sizes

Export formats

Naming convention

Compression

Transparency

Pivot rules

Layer naming

Source file format

---

## 16. Optimization Rules

Define:

Texture limits

Atlas strategy

Compression

Draw call reduction

Memory budget

Target platform optimization

---

## 17. Consistency Rules

Every asset must satisfy:

Visual consistency

Naming consistency

Resolution consistency

Color consistency

Material consistency

Animation consistency

---

## 18. Forbidden Practices

Examples:

Mixed rendering styles

Multiple shadow systems

Inconsistent icon styles

Random fonts

Unplanned gradients

Photorealistic assets inside stylized projects

---

# Cross References

This document depends on:

GAME_DESIGN.md

This document informs:

UI_GUIDE.md

ASSET_LIST.md

DEV_PLAN.md

CLAUDE.md

Any modifications to gameplay or project vision MUST be made in GAME_DESIGN.md first.

---

# Validation

Verify:

✓ Every section references GAME_DESIGN.

✓ No gameplay mechanics introduced.

✓ No platform changes.

✓ No contradictory visual styles.

✓ Materials match gameplay.

✓ Typography supports target languages.

✓ Optimization matches platform constraints.

✓ Production standards are complete.

If validation fails:

Regenerate only the affected section.

---

# Completion Criteria

The Art Bible is complete when:

- Artists can begin asset production.
- UI designers understand the visual language.
- Technical artists understand optimization constraints.
- Claude Code can generate art-related tasks without additional clarification.