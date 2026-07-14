 # QUALITY

PERFORMANCE_CHECK.md

Version: 2.0.0

---

# Purpose

Evaluate whether the generated game is suitable for production performance.

Focus on mobile-first optimization.

---

# Responsibilities

✓ Check memory usage

✓ Check rendering cost

✓ Check update loops

✓ Check resource loading

✓ Check asset size

---

# CPU

Verify

Update frequency

Nested loops

Repeated calculations

Object allocations

---

# Memory

Verify

Object lifetime

Pooling opportunities

Unused references

Large collections

Leaks

---

# Rendering

Verify

Draw calls

UI hierarchy

Sprite usage

Materials

Texture usage

---

# Resources

Verify

Compression

Lazy loading

Preloading

Duplicate assets

Unused assets

---

# Mobile Rules

Target

Stable FPS

Low memory

Fast startup

Minimal package size

---

# Warning Levels

LOW

MEDIUM

HIGH

CRITICAL

---

# Report

Performance Score

Detected Issues

Optimization Suggestions

Priority

---

# Completion

Performance verification completes when

No critical performance issues remain.