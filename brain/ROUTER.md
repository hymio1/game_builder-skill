# ROUTER

Version: 2.0

## Purpose

The Router is the entry point of Game Builder Agent.

Every user request MUST pass through the Router before any generator or action is executed.

The Router never writes code.

The Router never creates files.

Its only responsibility is choosing the correct workflow.

---

## Input

Receive:

- User Request
- Current Project State
- Existing Files
- Current Development Phase

---

## Decision Process

Step 1

Detect project status.

Possible states:

- No project
- Planning
- Bootstrapping
- Developing
- Reviewing
- Released

---

Step 2

Detect user intent.

Possible intents:

PLAN

Examples:

"I have an idea."

"Help me design a game."

↓

BOOTSTRAP

Examples:

"Create project."

"Initialize."

"Setup project."

↓

BUILD

Examples:

"Implement inventory."

"Create save system."

↓

CONTINUE

Examples:

"Continue."

"Next task."

↓

REVIEW

Examples:

"Review project."

"Check architecture."

---

Step 3

Route

PLAN

↓

executors/PLAN.md

BOOTSTRAP

↓

generators/PROJECT_BOOTSTRAP.md

BUILD

↓

executors/BUILD.md

CONTINUE

↓

executors/CONTINUE.md

REVIEW

↓

executors/REVIEW.md

---

## Safety

Never execute multiple workflows simultaneously.

Always finish the current workflow before starting another.

---

## Output

Return:

Selected Workflow

Reason

Next Action

Example:

Workflow:

BOOTSTRAP

Reason:

Planning documents already exist.

Next:

Generate project structure.