# ACTION

VERIFY_OUTPUT.md

Version: 2.0.0

---

# Purpose

Verify every generated output before it becomes part of the project.

Verification is mandatory.

---

# Responsibilities

✓ Verify files

✓ Verify folders

✓ Verify code

✓ Verify data

✓ Verify documentation

✓ Verify architecture

---

# Verification Scope

Check

Folder Structure

↓

Source Code

↓

Assets

↓

Configurations

↓

Data Files

↓

Documentation

↓

Memory

---

# Code Verification

Verify

Syntax

Formatting

Naming

Imports

Dependencies

Compilation Safety

Public APIs

---

# Data Verification

Verify

Schema

Unique IDs

References

Required Fields

Version

---

# Documentation Verification

Verify

Consistency

Completeness

Broken links

Naming

---

# Architecture Verification

Verify

Layering

Dependencies

Circular References

Module Boundaries

---

# Result Levels

PASS

No issues.

WARNING

Minor issues.

FAIL

Critical issues.

---

# Output

Verification Summary

Issues Found

Severity

Recommendations

Pass Rate

---

# Failure

If FAIL

Stop current workflow.

Return to BUILD or REVIEW.

---

# Completion

Verification completes when

Every generated artifact has been inspected.