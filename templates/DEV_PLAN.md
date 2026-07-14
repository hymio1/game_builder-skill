# TEMPLATE

DEV_PLAN.md

Version: 2.0.0

Derived From:
- GAME_DESIGN.md
- ART_BIBLE.md
- UI_GUIDE.md
- ASSET_LIST.md

Priority:

GAME_DESIGN.md
↓
ART_BIBLE.md
↓
UI_GUIDE.md
↓
ASSET_LIST.md
↓
DEV_PLAN.md

---

# Purpose

Generate a realistic development plan for the game project.

The Development Plan converts design documents into executable production phases.

This document defines:

- Development order
- Milestones
- Tasks
- Dependencies
- Risks
- Delivery criteria

The plan must be realistic for the defined team size and schedule.

---

# Dependencies

Required:

GAME_DESIGN.md

Read:

- MVP Definition
- Core Gameplay Loop
- Technical Constraints
- Success Metrics


Required:

ART_BIBLE.md

Read:

- Asset Requirements
- Production Standards


Required:

UI_GUIDE.md

Read:

- Screen List
- Component Requirements
- Interaction Requirements


Required:

ASSET_LIST.md

Read:

- Asset Priority
- Production Status
- Dependencies


If dependency information is missing:

STOP.

Request missing information.

---

# Outputs

Generate:

DEV_PLAN.md

---

# Planning Principles

The development order MUST follow:

Foundation

↓

Core Gameplay

↓

Essential Content

↓

Polish

↓

Optimization

↓

Release Preparation

Never build polish before gameplay works.

---

# Required Sections

---

# 1. Project Development Overview

Include:

Project Name

Target Platform

Team Size

Estimated Timeline

Development Method

Release Goal

---

# 2. Development Strategy

Explain:

Development approach

Iteration method

Testing strategy

Risk management strategy

Example:

Prototype → MVP → Content Expansion → Release

---

# 3. Milestone Plan

Divide development into milestones.

Recommended:

Milestone 0

Prototype

Milestone 1

Core MVP

Milestone 2

Content Expansion

Milestone 3

Polish

Milestone 4

Release

---

# 4. Milestone Specification

Every milestone MUST include:

## Objective

What should be achieved?

## Features

What is included?

## Tasks

What needs to be completed?

## Dependencies

What must exist first?

## Deliverables

What should be produced?

## Acceptance Criteria

How do we know it is complete?

---

# 5. Sprint Planning

Break milestones into smaller sprints.

Each sprint includes:

Sprint Name

Duration

Goals

Tasks

Expected Output

Testing Requirement

---

# 6. Task Breakdown

Every task MUST contain:

Task ID

Task Name

Description

Category

Priority

Dependencies

Estimated Difficulty

Estimated Time

Owner

Acceptance Criteria

---

# Task Categories

Use:

Programming

Game Design

UI

Art

Audio

Animation

Testing

Optimization

Release

Documentation

---

# 7. Dependency Graph

Describe task relationships.

Example:

Gameplay System

↓

Level System

↓

Progression System

↓

Content Expansion

Never create impossible task order.

---

# 8. Technical Development Plan

Include:

Project Setup

Architecture

Core Systems

Data Systems

Save System

Input System

UI Framework

Build Pipeline

Testing Framework

---

# 9. Art Production Plan

Include:

Concept Phase

Production Phase

Integration Phase

Optimization Phase

Review Phase

---

# 10. Audio Production Plan

Include:

BGM

SFX

UI Sounds

Ambient Audio

Voice

Integration

---

# 11. Testing Plan

Define:

Functional Testing

Gameplay Testing

Performance Testing

Device Testing

Compatibility Testing

User Testing

---

# 12. Release Preparation

Include:

Build Verification

Store Requirements

Analytics

Crash Reporting

Privacy Requirements

Marketing Materials

Launch Checklist

---

# 13. Risk Management

For each risk:

Risk Name

Description

Probability

Impact

Detection Method

Mitigation

Fallback Plan

---

# 14. Post Launch Plan

If applicable:

Bug Fixes

Balance Updates

New Content

Events

Optimization

Community Feedback

---

# 15. Success Criteria

Define measurable completion conditions.

Examples:

Core loop playable

No critical bugs

Performance target reached

Assets integrated

Tutorial completed

Release build generated

---

# Development Rules

Always:

Prioritize playable builds.

Keep milestones achievable.

Separate MVP from future features.

Track dependencies.

Document decisions.

Avoid parallel work that creates conflicts.

---

# Cross References

Depends on:

GAME_DESIGN.md

ART_BIBLE.md

UI_GUIDE.md

ASSET_LIST.md


Provides information to:

CLAUDE.md

---

# Validation

Verify:

✓ Timeline matches project scope.

✓ MVP can be completed first.

✓ Tasks have dependencies.

✓ No missing production phases.

✓ Art and code schedules are aligned.

✓ Testing exists.

✓ Release preparation exists.

✓ Risks have mitigation.

If validation fails:

Revise the affected section.

---

# Completion Criteria

The Development Plan is complete when:

A developer knows what to build first.

A producer can track progress.

A team can estimate workload.

Claude Code can convert tasks into implementation steps.