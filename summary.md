# Linux Fundamentals Summary

## 1. Objective
The objective of this exercise was to gain practical proficiency with essential Linux terminal operations, including directory navigation, file manipulation, text editing, permission management, ownership control, and basic system monitoring.

## 2. Completed Topics
During the hands-on session, the following topics and commands were practiced:

- Directory navigation: `pwd`, `ls`, `cd`
- File and directory creation/removal: `touch`, `mkdir`, `rm`, `rmdir`
- Viewing and editing files: `cat`, `less`, `nano`, `vim`
- Permissions management: `ls -l`, `chmod`
- System resource monitoring: `top`, `htop`, `df -h`, `free -m`

## 3. Key Concepts Learned

### 3.1 Filesystem Hierarchy
- The Linux filesystem starts at the root directory `/`.
- User directories are typically located under `/home/<username>`.
- Commands such as `pwd` and `ls` assist in identifying location and contents.

### 3.2 File and Directory Operations
- `touch` creates empty files.
- `mkdir` creates directories, and `mkdir -p` creates nested directories recursively.
- `rm` removes files and `rmdir` removes empty directories.
- Redirection (`>`) can write output into files.
- `cat` displays contents; `less` provides scrollable viewing for long files.

### 3.3 Editing Text Files
- `nano` provides a simple terminal-based editor for beginners.
- `vim` offers advanced editing capabilities with command and insert modes.

### 3.4 Permissions & Ownership
- `ls -l` displays permissions in `rwx` format for user, group, and others.
- `chmod` modifies permission bits, for example `755` grants execute rights.
- `chown` alters file owner and group, typically requiring elevated privileges.

### 3.5 System Monitoring
- `top` and `htop` show active processes, CPU usage, memory usage, and load.
- `df -h` reports available disk capacity in human-readable units.
- `free -m` displays available and utilized memory in megabytes.

## 4. Challenges Encountered
- Editing in `vim` can be initially confusing due to mode switching.
- Running `chown` requires `sudo`, which may prompt for a password.
- Terminal viewing tools like `top` and `htop` do not print persistent output, requiring screenshots instead.

## 5. Outcomes
At the conclusion of the tasks, a higher degree of confidence was achieved in the following areas:
- Navigating the Linux filesystem efficiently
- Managing files and directories safely
- Understanding permission and ownership models
- Observing real-time system performance metrics

## 6. Conclusion
This practical exercise strengthened foundational Linux command-line skills and provided exposure to core administration concepts. These fundamentals are essential for further learning in Devops.

