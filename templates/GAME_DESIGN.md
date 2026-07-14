# TEMPLATE

GAME_DESIGN.md

Version: 1.0.0

---

# Purpose

This template defines the complete Game Design Document (GDD).

The generated GDD serves as the single source of truth for gameplay design.

All subsequent documents (Art Bible, UI Guide, Asset List, Development Plan) MUST align with this document.

If conflicts arise, this document takes precedence.

---

# Required Sections

The generated Game Design Document MUST include the following sections in order.

---

# 1. Executive Summary

Purpose

Summarize the project in under 300 words.

Include:

- Game Name
- Genre
- Platform
- Target Audience
- Core Value Proposition
- Elevator Pitch

---

# 2. Vision Statement

Answer:

Why should this game exist?

Why would players continue playing?

What emotional experience should players have?

---

# 3. Design Pillars

Exactly 3–5 pillars.

Example:

- Relaxing
- Easy to Learn
- Short Sessions
- Satisfying Feedback

Every gameplay decision must support at least one pillar.

---

# 4. Target Audience

Describe:

Primary audience

Secondary audience

Age range

Gaming habits

Preferred session length

Motivations

Avoid vague descriptions.

---

# 5. Core Gameplay Loop

Describe the complete gameplay loop.

Example:

Enter Level

↓

Observe

↓

Interact

↓

Receive Feedback

↓

Complete Objective

↓

Earn Rewards

↓

Unlock Progress

↓

Repeat

Include both text and flow representation.

---

# 6. Secondary Systems

Document optional systems.

Examples:

Daily Rewards

Achievements

Collection

Customization

Progression

Events

Label each system as:

MVP

Post-MVP

Future Version

---

# 7. Progression System

Describe:

Player progression

Content unlocks

Difficulty progression

Reward pacing

Session pacing

---

# 8. Economy

If applicable:

Currencies

Resources

Energy

Crafting

Unlock requirements

Upgrade systems

If the project has no economy, explicitly state so.

---

# 9. Level Design

Specify:

Level structure

Objectives

Failure conditions

Difficulty curve

Replayability

Content generation strategy

---

# 10. Controls

Describe:

Input methods

Touch gestures

Keyboard

Controller

Accessibility considerations

---

# 11. Feedback Systems

Define:

Visual feedback

Audio feedback

Haptics

Animation

Success states

Failure states

Feedback timing

---

# 12. UI Principles

Summarize UI philosophy.

Do not design screens here.

Reference UI_GUIDE.md for detailed layouts.

---

# 13. Art Direction Summary

Summarize:

Visual style

Color palette

Mood

References

Link to ART_BIBLE.md for details.

---

# 14. Audio Direction

Describe:

Music

Ambient audio

UI sounds

Gameplay sounds

Voice requirements

---

# 15. Technical Constraints

Document:

Target FPS

Memory limits

Build size

Platform limitations

Online/offline requirements

---

# 16. Monetization

Specify:

Ads

In-App Purchases

Premium

Subscription

None

Explain how monetization supports the player experience.

---

# 17. Live Operations

If applicable:

Daily missions

Events

Seasonal content

Balance updates

Content pipeline

Otherwise state:

"Live Operations not planned."

---

# 18. Risks

List:

Gameplay risks

Technical risks

Production risks

Commercial risks

Mitigation strategy

---

# 19. MVP Definition

Categorize features into:

Must Have

Should Have

Could Have

Won't Have

Provide rationale for each category.

---

# 20. Success Metrics

Define measurable goals.

Examples:

Retention

Session Length

Completion Rate

Tutorial Completion

Crash Rate

FPS

---

# Writing Rules

Use concise language.

Avoid repetition.

Prefer diagrams or lists over long paragraphs.

Keep each section focused.

Do not introduce implementation details.

---

# Cross References

The generated document must remain consistent with:

README.md

ART_BIBLE.md

UI_GUIDE.md

ASSET_LIST.md

DEV_PLAN.md

CLAUDE.md

Any changes here should propagate to dependent documents.

---

# Validation

Before completion verify:

✓ Vision is clear

✓ Core loop is defined

✓ MVP exists

✓ Risks documented

✓ Success metrics defined

✓ No contradictory mechanics

✓ No placeholder text

✓ Every section is complete

If validation fails,

regenerate only the failed section.

---

# Completion Criteria

The Game Design Document is considered complete when:

- Designers can begin balancing gameplay.
- Artists understand the required visual direction.
- Programmers understand the gameplay systems.
- Producers can estimate development scope.
- Claude Code can generate implementation tasks without additional clarification.