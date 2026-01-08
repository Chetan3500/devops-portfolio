# Worklog — Linux Filesystem Navigation via SSH

← Back to [Workcard Overview](README.md)
↑ Back to [Linux Basics Epic](../README.md)

---

## Iteration v1.0 — Filesystem & Navigation

### Focus

Survival navigation on a remote Linux server.
Using: `ssh`, `pwd`, `cd`

### What I learned

- Connect to a remote Linux server using `ssh`
- Check current location in the filesystem using `pwd`
- Navigate into `/etc`, `/var/log`, and `/home` directories
- Move between directories using absolute (start with `/`) and relative paths (start with `./` or `../`)
- Locate log and configuration files on a running system
- Recover when lost inside deep directory structures using `cd`

### Demo Link

[YouTube v1.0 — Navigating /etc, /var, /home — Linux Filesystem (Remote SSH)](https://youtu.be/6ulATWG-vR0)

### Notes

- **SSH (`ssh user@host`)** is used to securely connect to a remote Linux server and work on it as if you were local.
- **`pwd`** always tells you where you are in the filesystem — use it whenever you feel unsure.
- Linux follows a **standard directory structure**:
  - `/etc` → system and application configuration files
  - `/var/log` → log files used for troubleshooting
  - `/home` → user home directories
- **Absolute paths** (start with `/`) work from anywhere and are predictable.
- **Relative paths** (`./`, `../`) are shorter and depend on your current location.
- Logs and configs are usually found in **`/var/log` and `/etc`**, which are key places to inspect on a running system.
- If you get lost:
  - `cd ..` → go up one directory
  - `cd /` → go to the root
  - `cd ~` → return to your home directory
  - `pwd` → re-orient yourself

**Bottom line:**
Mastering `ssh`, `pwd`, and `cd` lets you confidently navigate any Linux system, find logs and configs quickly, and recover easily when you lose your place in deep directory structures.
