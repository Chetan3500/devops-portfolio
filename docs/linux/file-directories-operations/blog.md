# File & Directory Operations via SSH — v1.0

> First iteration of this workcard.

## Introduction

In DevOps work, files and directories are constantly created, copied, moved, and removed:

- build artifacts
- configuration files
- deployment packages
- logs and backups

This iteration documents **v1.0 of File & Directory Operations**, focused on learning how to **manipulate files safely and deliberately** on a remote Linux system via SSH.

---

## Problem Statement

On a real Linux server, accidental file operations can:

- overwrite important data
- break applications
- remove critical configuration files

The goal of this iteration was:

> **Learn how to create, move, copy, inspect, and delete files with control and awareness.**

---

## Approach

This iteration focused on:

- understanding how files and directories are structured
- performing controlled file operations
- verifying file details before acting

The emphasis was on **correctness and safety**, not speed.

---

## Key Concepts Learned

### Creating & Organizing Files

- `touch` creates files
- `mkdir` creates directories
- Files are organized into folders to represent application structure

---

### Copying & Moving

- `cp` duplicates files into other locations
- `mv` renames or moves files between folders
- These commands are used in deployments and CI pipelines

---

### Inspecting Files Before Using Them

Before opening or editing unknown files:

- `file` identifies file type
- `stat` shows metadata like size and timestamps
- `ls -l` shows permissions and ownership

This avoids working on the wrong file.

---

### Removing Files Safely

- `rm` removes files
- Deleting files is permanent, so inspection before removal is critical

---

## Outcomes

By the end of this iteration, I could:

- Create directories for applications
- Add files inside them
- Move and rename files confidently
- Copy files between locations
- Inspect files before acting
- Clean up unused files without damaging the system

---

## Demo

🎥 [**YouTube — File & Directory Operations v1.0 (Remote Linux via SSH)**](https://youtu.be/lCOGb0MUwfg)

---

## Reflections

> Filesystem navigation tells you where things are.
> File operations give you the power to change them.

This iteration marked my transition from **observer** to **operator** on Linux systems.

---

## Canonical Reference

📘 See `README.md` and `worklog.md` in this folder for the latest state and full iteration history.
