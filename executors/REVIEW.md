# EXECUTOR

REVIEW.md

Version: 2.0.0

---

# Purpose

Review the current game project.

The Review Executor performs a comprehensive inspection of the project.

Its purpose is to identify architectural issues, documentation inconsistencies, implementation risks, and production readiness.

The Review Executor never creates new features.

It only analyzes and reports.

---

# Trigger

Run when the user requests:

- Review project
- Review architecture
- Audit project
- Check project quality
- Verify implementation
- Project inspection
- Release review

---

# Responsibilities

The Review Executor should:

✓ Review project structure

✓ Review documentation

✓ Review source code

✓ Review assets

✓ Review configuration

✓ Review architecture

✓ Review dependencies

✓ Review task completion

✓ Generate review report

✓ Recommend improvements

---

# Preconditions

Before review verify:

✓ Project exists

✓ PROJECT_STATE.json exists

✓ GAME_DESIGN.md exists

✓ DEV_PLAN.md exists

If project is incomplete

Review available content only.

Never invent missing information.

---

# Review Pipeline

Phase 1

Load Project

Read

PROJECT_STATE.json

↓

TASK_STATE.json

↓

SESSION_STATE.json

↓

FILE_INDEX.json

↓

Project Tree

↓

Documentation

↓

Source Code

---

Phase 2

Project Structure Review

Verify

✓ Folder hierarchy

✓ Naming conventions

✓ Missing folders

✓ Unexpected folders

✓ Engine compatibility

---

Phase 3

Documentation Review

Review

README.md

↓

GAME_DESIGN.md

↓

ART_BIBLE.md

↓

UI_GUIDE.md

↓

ASSET_LIST.md

↓

DEV_PLAN.md

↓

CLAUDE.md

Verify

Consistency

Completeness

Dependency order

Contradictions

---

Phase 4

Architecture Review

Review

Core Systems

Manager Structure

Scene Organization

Module Dependency

Data Flow

Configuration

Initialization

Lifecycle

Verify

Single Responsibility

Loose Coupling

No Circular Dependencies

Scalability

Maintainability

---

Phase 5

Source Code Review

Verify

Formatting

Naming

Imports

Unused Code

Dead Code

Duplicate Code

Long Methods

Large Classes

Magic Numbers

Missing Comments

TODO Items

Compilation Safety

---

Phase 6

Asset Review

Review

Images

Audio

Fonts

Effects

Animations

Prefabs

Verify

Folder Location

Naming Rules

Unused Assets

Duplicate Assets

Missing Assets

Compression Status

File Size

---

Phase 7

Progress Review

Read

PROJECT_STATE.json

Determine

Current Milestone

Current Sprint

Completed Tasks

Remaining Tasks

Blocked Tasks

Estimated Completion

Overall Progress

---

Phase 8

Risk Analysis

Identify

Architecture Risks

Performance Risks

Memory Risks

Maintainability Risks

Production Risks

Schedule Risks

Classify

HIGH

MEDIUM

LOW

---

Phase 9

Generate Review Report

Generate

Project Summary

Architecture Score

Documentation Score

Code Score

Asset Score

Progress Score

Risk Score

Overall Score

Recommendations

Next Suggested Action

---

# Review Scoring

Architecture

0–10

Documentation

0–10

Implementation

0–10

Assets

0–10

Maintainability

0–10

Performance

0–10

Progress

0–10

Total

70

---

# Recommendation Rules

If score

60+

Recommend

Continue Development

---

If score

45–59

Recommend

Minor Refactoring

---

If score

30–44

Recommend

Architecture Review

---

If score

Below 30

Recommend

Return to Planning

---

# Output

Always produce

Project Health

Current State

Review Summary

Problems Found

Severity

Improvement Suggestions

Next Workflow

---

# Safety Rules

Never

Modify project files

Delete assets

Rewrite source code

Generate new features

The Review Executor is read-only.

---

# Completion

The Review Executor completes when

Every major project component has been reviewed.

A complete review report has been generated.

Actionable recommendations have been provided.