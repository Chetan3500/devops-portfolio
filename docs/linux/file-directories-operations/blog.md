# File & Directory Operations via SSH — v1.1

> Second iteration of this workcard.

## Introduction

After learning how to create, move, copy, and delete files in v1.0, the next challenge was **operating safely at scale**.

In real DevOps environments, file operations are rarely one-by-one — they often involve:

- cleaning up many build artifacts
- reorganizing application directories
- removing failed deployments
- managing large sets of log files

This iteration documents **v1.1 of File & Directory Operations**, focused on learning how to perform **bulk file operations safely and efficiently** on a remote Linux system via SSH.

---

## Problem Statement

On real Linux servers, bulk file operations can be dangerous:

- a single wrong wildcard (`*`) can delete critical files
- removing the wrong directory can break an application
- copying large directory trees can overwrite important data

The goal of this iteration was:

> **Learn how to perform large-scale file operations with control, verification, and safety.**

---

## Approach

This iteration focused on:

- using wildcards responsibly
- verifying targets before acting
- adding confirmation steps before destructive actions
- working with entire directory trees instead of individual files

The emphasis shifted from **basic ability (v1.0)** to **safe efficiency (v1.1).**

---

## Key Concepts Learned

### Working with Multiple Files (Wildcards)

- `*` allows operating on many files at once
- Wildcards are powerful but risky — they must be used deliberately
- Always inspect targets (`ls`) before executing destructive commands

This is crucial in CI/CD and server cleanup scenarios.

---

### Safe Deletion Practices

Instead of blindly deleting files:

- `rm -i` prompts before each deletion
- This prevents accidental removal of important files
- Confirmation adds a safety layer on real systems

This is a habit that protects production environments.

---

### Removing Non-Empty Directories

Unlike v1.0, where only empty directories were removed:

- `rm -r` allows deleting directories with contents
- This must be used carefully and intentionally
- Verifying directory contents first is a best practice

This is common when cleaning up failed builds or deployments.

---

### Copying Entire Directory Trees

Instead of copying files one by one:

- `cp -r` duplicates full directory structures
- This is useful for backups, staging environments, and testing
- Verification after copying prevents silent errors

This mirrors real DevOps workflows.

---

### Verifying Before Acting

Before moving or deleting files, I consistently used:

- `ls -lh` to check file sizes
- `stat` to inspect metadata
- `file` to confirm file type

This reduced mistakes and improved confidence.

---

## Outcomes

By the end of this iteration, I could:

- Use wildcards safely for bulk operations
- Delete files and directories with confirmation
- Remove non-empty directories without hesitation
- Copy full directory trees reliably
- Clean up broken or unused application folders
- Operate more confidently on real remote Linux systems

This marked my transition from **basic operator (v1.0)** to **safe and efficient operator (v1.1).**

---

## Demo

🎥 [**YouTube — File & Directory Operations v1.1 (Remote Linux via SSH)**](<(https://youtu.be/YnF2tqPoVpQ)>)

---

## Reflections

> In v1.0, I learned _how_ to change files.
> In v1.1, I learned _how to change them safely at scale._

This iteration made Linux feel less like a tool and more like a **production system I am responsible for.**

---

## Canonical Reference

📘 See `README.md` and `worklog.md` in this folder for the latest state and full iteration history.
