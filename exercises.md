# Bash Learning Exercises

A collection of practical bash scripting exercises to build real-world skills.

## Level 1: Basics

### 1. Git Branch Cleanup
Write a script that lists all local git branches and deletes any that have been merged to main.

**Status**: [ ] Not started

---

### 2. Log Analyzer
Parse a log file and count occurrences of ERROR, WARN, INFO.

**Status**: [ ] Not started

---

### 3. Batch Renamer
Rename all `.jpeg` files to `.jpg` in a directory.

**Status**: [ ] Not started

---

### 4. File Organizer
Move files into subdirectories based on extension (images/, docs/, etc.).

**Status**: [ ] Not started

---

## Level 2: Text Processing

### 5. CSV Parser
Read a CSV file and extract specific columns without using `awk` (just bash string manipulation).

**Status**: [ ] Not started

---

### 6. Duplicate Finder
Find duplicate files in a directory tree by comparing checksums.

**Status**: [ ] Not started

---

### 7. Environment Diff
Compare two `.env` files and show which keys are missing/different.

**Status**: [ ] Not started

---

### 8. URL Extractor
Parse an HTML file and extract all URLs (regex practice).

**Status**: [ ] Not started

---

## Level 3: Automation

### 9. Dev Environment Checker
Script that verifies required tools are installed (node, python, docker, etc.) and shows versions.

**Status**: [ ] Not started

---

### 10. Backup Script
Create timestamped backups of a directory, keep only last 5, compress old ones.

**Status**: [ ] Not started

---

### 11. Port Checker
Check if specific ports are in use and show which process is using them.

**Status**: [ ] Not started

---

### 12. Git Stats
Show commit counts per author for the last month.

**Status**: [ ] Not started

---

## Level 4: Advanced

### 13. Simple Build Script
Run tests, lint, build - stop if any step fails, show elapsed time for each.

**Status**: [ ] Not started

---

### 14. Process Monitor
Watch a process and restart it if it dies.

**Status**: [ ] Not started

---

### 15. Interactive Menu
Build a menu-driven script with `select` for common dev tasks.

**Status**: [ ] Not started

---

## Bonus Challenges

Once you're comfortable with the basics, enhance your scripts with:

- **Command-line arguments**: Make scripts accept flags (`-h`, `--help`, `-v`, etc.)
- **Error handling**: Check if files exist, handle empty input, validate arguments
- **Colored output**: Add colored output for success/failure messages using ANSI codes
- **Logging**: Write script output to log files with timestamps
- **Functions**: Break scripts into reusable functions
- **Testing**: Write test cases for your scripts

---

## Tips

- Start with exercises 1-4 and work your way up
- Don't worry about making scripts perfect - focus on getting them working first
- Use `shellcheck` to catch common bash mistakes
- Read `man bash` when you get stuck
- Practice using `set -e` and `set -u` for better error handling

## Resources

- [Bash Guide](https://mywiki.wooledge.org/BashGuide)
- [ShellCheck](https://www.shellcheck.net/) - Online bash linter
- `man bash` - The bash manual (local)
