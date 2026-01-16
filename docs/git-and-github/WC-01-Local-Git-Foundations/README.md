# WC-01 — Local Git Foundations

This work card builds the **base capability** required before touching GitHub, PRs, or CI/CD.

---

## 📌 WC-01 Intent

> Build confidence in **local Git usage** so version control becomes _muscle memory_, not a risk.

This work card answers:

- What is Git **locally**?
- How do I safely track changes?
- How do I inspect history?
- How do I avoid committing junk?

---

## 🎯 Capability Outcome

After completing WC-01, I can:

- initialize a Git repository
- track and commit changes correctly
- inspect repository state and history
- compare changes before committing
- ignore unnecessary files safely

---

## 🧠 Lean Scope (WC-01)

### Included (Must-Know)

```
git init
git status
git add
git commit
git log
git diff
.gitignore
```

### Explicitly Excluded

```
branches
remotes
GitHub
rebase
reset
stash
```

👉 This keeps WC-01 **focused and low-risk**.

---

## 🗂 WC-01 Folder Structure

```
WORKCARD/
├── README.md        # WC overview (this file)
├── worklog.md       # iteration-by-iteration execution log
├── blog.md          # public explanation (blog / LinkedIn source)
```

---

# 🔁 WC-01 Iterations

WC-01 is completed through **incremental iterations**, not one big jump.

---

## 🧩 WC-01 — Iteration v1.0

### _Initialize & First Commit_

### Objective

Understand Git as a **local version control system**.

### Tasks

- initialize repository
- check repo status
- add files
- create first commit

### Commands Practiced

```
git init
git status
git add
git commit
```

### Outcome

- Repository is initialized
- Files are tracked
- First commit exists

---

## 🧩 WC-01 — Iteration v1.1

### _Inspecting Changes & History_

### Objective

Safely inspect changes **before** committing.

### Tasks

- view commit history
- compare working tree changes
- understand staged vs unstaged

### Commands Practiced

```
git log
git diff
git diff --staged
```

### Outcome

- I can see what changed
- I know what will be committed
- I avoid blind commits

---

## 🧩 WC-01 — Iteration v1.2

### _Ignoring Noise_

### Objective

Prevent unnecessary files from entering version control.

### Tasks

- create `.gitignore`
- ignore logs, temp files, build artifacts
- verify ignored files are not tracked

### Concepts Practiced

```
.gitignore patterns
tracked vs untracked
```

### Outcome

- Clean repository
- No accidental commits
- Production-ready hygiene

---

## 🧪 Definition of Done — WC-01

WC-01 is considered **complete** when:

- All iterations (v1.0 → v1.2) are done
- `worklog.md` records commands + observations
- `blog.md` explains Git basics in simple terms
- Repository history shows:
  - multiple commits
  - meaningful messages
  - clean status

---

## 🔄 Relationship to Next Work Card

WC-01 enables:

```
WC-02 → Branching & Merging
```

Without WC-01:

- branching becomes dangerous
- mistakes are unrecoverable
- confidence is low
