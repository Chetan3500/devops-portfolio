# Documentation

This directory contains the **technical documentation** for my DevOps portfolio.
All content is organized using an **Epic → Workcard** model that mirrors how engineering work is planned, executed, iterated, and published in real teams.

---

## Structure Overview

```sh

docs/
├── epic-name/
│   └── workcard-name/
│       ├── README.md
│       ├── worklog.md
│       ├── blog.md
│       ├── workcard-name.tex
│       └── workcard-name.pdf
└── README.md

```

---

## Concepts

### Epic

An **Epic** represents a high-level problem area or skill domain
(e.g. *Linux Basics*, *CI/CD*, *Cloud Infrastructure*, *Observability*).

An epic groups together multiple workcards that build depth in that area.

---

### Workcard

A **Workcard** is a single, scoped unit of work with a clear focus and outcome.
Each workcard is designed to be:

- Small enough to iterate on
- Concrete and demonstrable
- Documented end-to-end

---

## Files Inside a Workcard

### `README.md` — Stable Summary

The entry point for a workcard.

Contains:
- Final focus and scope
- Cumulative capabilities gained
- Latest demo link
- Links to supporting artifacts

This file changes infrequently and reflects the **current truth**.

---

### `worklog.md` — Iterative Work Record

A chronological record of how the workcard evolved.

Contains:
- Iteration-by-iteration focus
- What was added or changed
- Observations and learnings
- Versioned demo links

This file is **append-only** and captures real engineering iteration.

---

### `blog.md` — Narrative & Insight

A polished, human-readable write-up.

Contains:
- Key insights and lessons
- Trade-offs and mental model shifts
- Why the work matters in real systems

This is written for a broader audience and avoids raw command lists.

---

### `workcard-name.tex` / `workcard-name.pdf` — Formal Artifact

A structured, exportable representation of the workcard.

- `.tex` is the source of truth
- `.pdf` is the generated, shareable artifact

Used when a static or formal version of the workcard is needed.

---

## How to Navigate This Documentation

- **First-time readers / recruiters**
  → Start with each workcard’s `README.md`

- **Engineers and reviewers**
  → Dive into `worklog.md` for depth and iteration

- **General audience**
  → Read `blog.md` for context and insight

---

## Progress & Updates

Portfolio-wide milestones and updates are tracked in
[`CHANGELOG.md`](../CHANGELOG.md).

---

## License

All documentation follows the repository license.
See [`LICENSE`](../LICENSE) for details.
