# Git & GitHub for DevOps — Epic

## 📌 Epic Intent

Develop **job-ready Git and GitHub skills** required for DevOps workflows using **Lean learning (only what matters)** and **Agile execution (small, iterative work cards)**.

This epic focuses on **real operational usage**, not academic Git theory.

---

## 🎯 Why This Epic Exists

In DevOps, Git is used to:

- version infrastructure (Terraform, YAML, Helm)
- collaborate across teams
- trigger CI/CD pipelines
- recover from bad changes
- audit and trace deployments

This epic builds **exactly those capabilities**.

---

## 🧠 Learning Model Used

### Lean Principles

- Learn only what DevOps actually uses
- Remove low-value Git internals
- Focus on outcomes, not commands

### Agile Principles

- Break learning into small work cards
- Practice → demo → document
- Iterate and improve incrementally

---

## 🗂 Epic Structure

This epic is divided into **independent work cards**.
Each work card delivers a **clear operational capability**.

## Work Cards

| Work Card                                                   | Current Level | Description                                                        |
| ----------------------------------------------------------- | ------------- | ------------------------------------------------------------------ |
| [**Local Git Foundations**](./WC-01-Local-Git-Foundations/) | Active        | Tracking files, committing changes, and inspecting history locally |
| **Branching & Merging**                                     | Planned       | Working safely using feature branches and merges                   |
| **GitHub Remote Workflow**                                  | Planned       | Syncing local repositories with GitHub remotes                     |
| **Pull Request–Based Team Workflow**                        | Planned       | Collaborating using forks, PRs, and reviews                        |
| **Undoing & Recovery**                                      | Planned       | Safely reverting, resetting, and recovering from mistakes          |

Each work card is **versioned using Git itself**:

- improvements are tracked via commits
- stable milestones are marked using **Git tags**
- learning progression is visible through `git log` and `git tag`

---

## 📦 Work Cards Overview

### WC-01 — Local Git Foundations

**Capability:**
Version-control files locally with confidence.

**Focus:**

- initialize repository
- track files
- commit changes
- inspect history
- ignore unnecessary files

---

### WC-02 — Branching & Merging

**Capability:**
Work safely without breaking the main branch.

**Focus:**

- create feature branches
- switch branches
- merge changes
- resolve basic conflicts

---

### WC-03 — GitHub Remote Flow

**Capability:**
Sync local work with remote repositories.

**Focus:**

- clone repositories
- push local commits
- pull remote changes
- manage remotes

---

### WC-04 — Team Workflow (DevOps Style)

**Capability:**
Collaborate using pull-request based workflows.

**Focus:**

- fork repositories
- create feature branches
- open pull requests
- review and merge changes

---

### WC-05 — Undoing & Recovery

**Capability:**
Recover safely from mistakes.

**Focus:**

- reset and revert commits
- restore deleted files
- stash unfinished work

---

## 🔁 Execution Flow (Same for Every Work Card)

Each work card follows this loop:

```
PLAN → PRACTICE → DEMO → DOCUMENT → SHARE → IMPROVE
```

| Stage    | Description                         |
| -------- | ----------------------------------- |
| Plan     | Understand the concept              |
| Practice | Execute commands hands-on           |
| Demo     | Record short demo (video / CLI log) |
| Document | Blog or markdown artifact           |
| Share    | LinkedIn / GitHub update            |
| Improve  | Next iteration refinement           |

---

## 📁 Repository Layout

```sh
git-and-github/
├── README.md
├── CHANGELOGS.md
├── WORKCARD/
│   ├── README.md
│   ├── worklog.md
│   └── blog.md
└── Workcard_Snapshot.pdf

```

---

## 🧪 Definition of Done (Epic)

This epic is considered **complete** when:

- All work cards are implemented
- Each work card has:
  - hands-on demo
  - documentation artifact

- GitHub profile shows:
  - commits
  - branches
  - pull requests
  - meaningful history

---

## 🚀 Outcome

After completing this epic, I can:

- work confidently with Git in DevOps projects
- collaborate using GitHub workflows
- support CI/CD pipelines
- recover from failed changes
- demonstrate skills via public artifacts
