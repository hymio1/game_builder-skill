# TEMPLATE

UI_GUIDE.md

Version: 2.0.0

Derived From:
- GAME_DESIGN.md
- ART_BIBLE.md

Priority:
GAME_DESIGN.md
↓
ART_BIBLE.md
↓
UI_GUIDE.md

---

# Purpose

Generate the complete User Interface Guide for the project.

The UI Guide defines the interaction system, navigation structure, screen hierarchy, layout principles, and interface components.

This document does NOT redefine gameplay.

This document does NOT redefine art direction.

Gameplay comes from GAME_DESIGN.md.

Visual language comes from ART_BIBLE.md.

---

# Dependencies

Required

GAME_DESIGN.md

Required Sections

- Design Pillars
- Core Gameplay Loop
- Controls
- Feedback Systems
- UI Principles
- Technical Constraints

Required

ART_BIBLE.md

Required Sections

- Color System
- Typography
- Shape Language
- Animation Language
- Icon System
- UI Style

If dependencies are incomplete

STOP

Return dependency error.

---

# Outputs

Generate

UI_GUIDE.md

---

# Responsibilities

The UI Guide defines

Navigation

↓

Screen Structure

↓

Interaction

↓

Layout

↓

Components

↓

Feedback

↓

Accessibility

↓

Responsive Rules

---

# Required Sections

## 1. UI Philosophy

Summarize

Interaction goals

Readability

Comfort

Accessibility

Player focus

Maximum

200 words

---

## 2. Information Hierarchy

Define

Primary Information

Secondary Information

Contextual Information

Background Information

Rules

Players should always identify the primary objective within three seconds.

---

## 3. Navigation Architecture

Generate a navigation flow.

Include

Entry

Home

Level Select

Gameplay

Pause

Result

Settings

Collection

Shop

Events

Profile

Exit

Represent both

Hierarchy

Flow

---

## 4. Screen Specifications

Generate specifications for every screen.

Each screen must include

Purpose

Entry Conditions

Exit Conditions

Displayed Information

Primary Actions

Secondary Actions

Error States

Empty States

Loading States

---

## 5. Layout System

Define

Grid

Spacing

Margins

Safe Area

Responsive Behavior

Portrait

Landscape

Tablet Rules

---

## 6. Component Library

Generate reusable components.

Required

Buttons

Cards

Panels

Dialogs

Lists

Progress Bars

Badges

Tabs

Navigation Bar

Scroll Area

Input Components

Each component defines

Purpose

States

Interaction

Sizing

Spacing

Usage Rules

---

## 7. Interaction Rules

Describe

Tap

Long Press

Drag

Swipe

Double Tap

Hold

Multi-touch

Disabled States

Interaction timing

Animation timing

---

## 8. HUD Specification

Gameplay HUD includes

Objective

Timer

Score

Currency

Progress

Lives

Pause

Hints

Accessibility

---

## 9. Feedback Rules

Visual

Audio

Animation

Haptics

Success

Failure

Warning

Confirmation

Loading

Saving

Network

---

## 10. Motion Design

Reference

Animation Language

Define

Duration

Ease

Bounce

Transition

Page Change

Popup

Reward

Tutorial

Motion should reinforce usability.

---

## 11. Accessibility

Define

Font scaling

Contrast

Color blindness

Touch targets

Screen reader compatibility

Reduced motion

Localization expansion

---

## 12. Localization

UI should support

Variable string length

RTL languages if applicable

Number formatting

Date formatting

Pluralization

---

## 13. Error Handling

Specify

Offline

Timeout

Missing Data

Asset Failure

Server Error

Version Mismatch

Permission Denied

Every error must include

User feedback

Recovery action

---

## 14. Performance Guidelines

Define

Target FPS

Animation limits

Texture usage

Dynamic UI loading

Pooling

Memory constraints

---

## 15. UI Testing Checklist

Verify

Navigation

Responsiveness

Accessibility

Interaction latency

Visual consistency

Animation consistency

Localization

Performance

---

# Cross References

Depends on

GAME_DESIGN.md

ART_BIBLE.md

Provides information to

ASSET_LIST.md

DEV_PLAN.md

CLAUDE.md

---

# Validation

Verify

✓ Navigation complete

✓ Every screen specified

✓ Components reusable

✓ Motion consistent with Art Bible

✓ Interaction matches Gameplay

✓ Accessibility covered

✓ Responsive rules defined

✓ No duplicated gameplay logic

If validation fails

Regenerate affected sections only.

---

# Completion Criteria

The UI Guide is complete when

Designers can produce wireframes.

Artists can design UI assets.

Developers can implement screens.

QA can verify interface behavior.

Claude Code can generate UI implementation tasks directly.