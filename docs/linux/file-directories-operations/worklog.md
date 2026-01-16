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

---

## File & Directory Operations — v1.1

### Focus

Safe and efficient bulk file and directory operations on a remote Linux server.

---

### What I practiced

- Use wildcards (`*`, `?`) to operate on multiple files
- Perform safe deletions using `rm -i`
- Remove non-empty directories using `rm -r`
- Copy entire directory trees using `cp -r`
- Verify files before moving or deleting using `ls -lh`, `stat`, and `file`
- Clean up broken or unused application folders
- Handle large sets of files without making mistakes

---

### Demo Link

[YouTube — File & Directory Operations v1.1 (Remote Linux via SSH)](https://youtu.be/YnF2tqPoVpQ)

---

### Notes

- Wildcards are extremely powerful — always preview targets with `ls` first.
- `rm -i` adds a critical safety layer when working on real systems.
- `rm -r` should only be used after verifying directory contents.
- `cp -r` is essential when dealing with project directories, backups, or staging copies.
- Checking file size (`ls -lh`) before deleting or moving prevents costly mistakes.
- Bulk operations feel fast, but they demand more discipline than single-file commands.

**Bottom line:**
This iteration upgraded me from **basic operator (v1.0)** to a **safe and efficient operator (v1.1)** who can handle real-world cleanup and maintenance tasks on a live Linux system.
