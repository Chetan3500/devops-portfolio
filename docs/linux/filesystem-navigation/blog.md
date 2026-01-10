# Linux Filesystem Navigation via SSH — v1.1

> Previous iteration: [v1.0](https://github.com/Chetan3500/devops-portfolio/blob/Linux-v1.0-artifact/docs/linux/filesystem-navigation/README.md)

## Introduction

Navigating a remote Linux server is a routine task for DevOps engineers.
As systems grow in complexity, the challenge shifts from basic movement to **maintaining context and operating safely**.

This post documents **v1.1** of this workcard, focused on **efficient navigation** and **safe inspection** while working inside deep or unfamiliar directory structures.

---

## Problem Statement

When switching frequently between:

- logs
- configuration files
- application directories

it’s easy to lose context or open the wrong file unintentionally.

The goal of this iteration was:

> **Move across multiple directories efficiently while preserving context and minimizing risk.**

---

## Approach

This iteration builds on navigation fundamentals and introduces:

- **directory stack–based movement**
- **safe, read-only file inspection**
- **structure awareness before interaction**

The emphasis is on **control and safety**, not speed.

---

## Key Concepts Learned

### Context-Preserving Navigation

- `pushd` and `popd` enable movement across multiple directories while preserving history
- `cd -` allows instant toggling between the current and previous location
- `dirs -v` provides indexed visibility into the directory stack

These tools eliminate guesswork during backtracking.

---

### Understanding Directory Structure

- `tree` and `ls -R` help visualize deep or unfamiliar directory layouts
- This prevents blindly entering directories without understanding their structure

---

### Safe File Inspection

Before opening or editing unknown files:

- `file` identifies file type
- `less` allows safe, read-only viewing
- `head` provides a quick preview

These commands reduce the risk of accidental execution or modification.

---

## Outcomes

By the end of this iteration, I could:

- Move confidently between logs, configs, and app directories
- Preserve navigation context during troubleshooting
- Inspect unknown files safely
- Understand directory structure before acting

---

## Demo

🎥 [**YouTube v1.1 — Directory Stack (pushd, popd) — Linux Filesystem**](https://youtu.be/dfw3tnPdwnY)

---

## Reflections

> v1.0 focused on orientation.
> v1.1 introduces **control, safety, and repeatability**.

This marks a shift from _learning Linux navigation_ to _operating Linux systems deliberately_.

---

## Next Steps

Upcoming iterations will expand into:

- File and directory operations
- Permissions and ownership
- Search and filtering techniques

Each version continues to build incrementally.

---

## Canonical Reference

📘 **Workcard (living, updated):**
See [`README.md`](README.md) and [`worklog.md`](worklog.md) in this directory for the latest state and full iteration history.
