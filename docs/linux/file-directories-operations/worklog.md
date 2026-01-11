# Worklog — File & Directory Operations via SSH

← Back to [Workcard Overview](README.md)
↑ Back to [Linux Basics Epic](../README.md)

---

## File & Directory Operations — v1.0

### Focus

Basic file and directory manipulation on a remote Linux server.

---

### What I learned

- Create files using `touch`
- Create directories using `mkdir`
- Copy files using `cp`
- Move and rename files using `mv`
- Delete files using `rm`
- Inspect file type using `file`
- Inspect file metadata using `stat`
- View file details using `ls -l`
- Organize project folders for applications

---

### Demo Link

[YouTube — File & Directory Operations v1.0 (Remote Linux via SSH)](https://youtu.be/lCOGb0MUwfg)

---

### Notes

- Files on Linux do not depend on extensions; their type is identified by content.
- `file` is useful before opening unknown files.
- `stat` shows size, timestamps, and ownership information.
- `ls -l` is critical to verify what a file is before deleting or moving it.
- `rm` permanently deletes files — there is no recycle bin.

**Bottom line:**
This iteration gave me the ability to **modify a real Linux filesystem safely**, which is the foundation of all DevOps automation.
