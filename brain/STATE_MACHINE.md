# STATE_MACHINE

Version: 2.0.0

---

# Purpose

The State Machine defines the lifecycle of every game project.

Every project MUST always be in exactly one state.

The current state determines:

- What Claude Code should do.
- Which generators can be used.
- Which actions are allowed.
- Which executor should run.

The State Machine prevents random behavior and ensures predictable workflows.

---

# Core Principle

A project always has one active state.

Never execute actions that belong to another state.

Never skip required transitions.

---

# Project States

STATE_00

NO_PROJECT

Description

No project exists.

Entry

- New conversation
- Empty directory
- No GAME_DESIGN.md

Allowed Actions

✓ Ask project questions

✓ Generate GAME_DESIGN

Forbidden

✗ Generate code

✗ Bootstrap project

Next State

PLANNING

---

STATE_01

PLANNING

Description

Game concept is being designed.

Required Documents

GAME_DESIGN.md

Optional

README.md

Allowed

Generate

GAME_DESIGN

Refine gameplay

Modify MVP

Review scope

Forbidden

Code generation

Asset production

Next

DESIGN_COMPLETE

---

STATE_02

DESIGN_COMPLETE

Required

GAME_DESIGN.md

ART_BIBLE.md

UI_GUIDE.md

ASSET_LIST.md

DEV_PLAN.md

CLAUDE.md

Purpose

Design documents are complete.

Allowed

Review documents

Fix inconsistencies

Approve project

Bootstrap

Forbidden

Gameplay implementation

Next

BOOTSTRAPPING

---

STATE_03

BOOTSTRAPPING

Purpose

Create the project foundation.

Responsibilities

Generate folders

Generate configuration files

Generate scaffold code

Generate TODO list

Allowed

Create directories

Create empty source files

Initialize project

Forbidden

Gameplay implementation

Feature development

Next

READY_TO_BUILD

---

STATE_04

READY_TO_BUILD

Purpose

The project structure exists.

Core systems have not yet been implemented.

Allowed

Choose Sprint

Select first task

Estimate workload

Next

BUILDING

---

STATE_05

BUILDING

Purpose

Implement planned features.

Allowed

Create source files

Modify source files

Implement systems

Write tests

Update documentation

Forbidden

Rewrite architecture

Skip dependencies

Next

TESTING

or

REVIEW

---

STATE_06

TESTING

Purpose

Verify implemented systems.

Required

Functional testing

Regression testing

Performance validation

Allowed

Bug fixing

Optimization

Documentation update

Forbidden

Major feature expansion

Next

REVIEW

---

STATE_07

REVIEW

Purpose

Evaluate project quality.

Review

Architecture

Performance

Maintainability

Documentation

Gameplay

Possible Outcomes

PASS

↓

RELEASE_READY

FAIL

↓

BUILDING

---

STATE_08

RELEASE_READY

Purpose

Prepare final release.

Allowed

Packaging

Build verification

Store preparation

Marketing assets

Privacy review

Next

RELEASED

---

STATE_09

RELEASED

Purpose

Production release.

Allowed

Bug fixes

Hotfixes

Content updates

Live operations

Version planning

Next

POST_RELEASE

---

STATE_10

POST_RELEASE

Purpose

Long-term maintenance.

Allowed

Events

DLC

Seasonal content

Optimization

Refactoring

---

# State Transition Rules

Allowed

NO_PROJECT

↓

PLANNING

↓

DESIGN_COMPLETE

↓

BOOTSTRAPPING

↓

READY_TO_BUILD

↓

BUILDING

↓

TESTING

↓

REVIEW

↓

RELEASE_READY

↓

RELEASED

↓

POST_RELEASE

---

# Invalid Transitions

Never

NO_PROJECT

↓

BUILDING

Never

PLANNING

↓

RELEASE

Never

BOOTSTRAPPING

↓

POST_RELEASE

Never

TESTING

↓

NO_PROJECT

---

# Entry Validation

Every state must validate:

Required files exist.

Previous state completed.

Dependencies satisfied.

---

# Exit Validation

Before leaving a state:

Current objectives complete.

Required outputs generated.

No blocking issues remain.

---

# Failure Recovery

If validation fails

Return to previous valid state.

Explain:

Missing requirement

Reason

Recovery steps

---

# State Memory

Every transition updates

.gamebuilder/

PROJECT_STATE.json

Required fields

Current State

Completed States

Current Sprint

Current Task

Last Update

Progress Percentage

---

# Example

User

"I have an idea."

↓

STATE

NO_PROJECT

↓

PLANNING

↓

Generate GAME_DESIGN

---

User

"Create the project."

↓

DESIGN_COMPLETE

↓

BOOTSTRAPPING

↓

Generate folders

↓

Initialize project

---

User

"Continue."

↓

Read PROJECT_STATE.json

↓

Determine current state

↓

Execute next task

---

# Completion

The State Machine is complete when

Every project phase has exactly one state.

Every state has:

Purpose

Entry rules

Exit rules

Allowed actions

Forbidden actions

Next state

Validation

Recovery