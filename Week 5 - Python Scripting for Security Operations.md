## 🎯 Objective
Develop Python scripting ability for automation, log analysis, and operational security tooling—translating Bash automation into more powerful, portable scripts.

---

## 🧠 Quiz Topics

- Explain Python file I/O operations (read, write, append).
- Use `subprocess` to call system commands securely from Python.
- Parse log files and extract specific information with regex.
- Build a CLI tool with `argparse` for user input and options.

---

## 📖 Reading

- [Real Python: Command Line Interfaces with argparse](https://realpython.com/python-cli/)
- [Python Official Docs: Regular Expressions](https://docs.python.org/3/library/re.html)
- [Automate the Boring Stuff with Python — Chapter 10: Organizing Files](https://automatetheboringstuff.com/2e/chapter10/)

---

## 🛠️ Lab Environment Setup

### Virtual Machines (VMs)

- **Primary VM:** Kali Linux or Ubuntu Server
- **Editor:** VS Code or Vim/Nano

### Required Tools

- Python 3.x
- `argparse`, `re`, `subprocess`, `os`, `shutil`
- Sample log files (from previous weeks' lab outputs)

---

## ⚔️ Practical Tasks

**Task 1: Log File Parsing with Python**
- Write Python scripts to parse `/var/log/auth.log` or similar, identifying failed and successful logins.
- Use regex (`re`) for flexible matching.

**Task 2: Automate System Commands**
- Use `subprocess` to execute CLI tools (e.g., `who`, `last`, `ls`, `grep`) and capture output in Python.
- Handle errors and log outputs cleanly.

**Task 3: Build a CLI Security Tool**
- Use `argparse` to add command-line arguments for filtering by user, date, or event type.
- Output findings to both terminal and file.

**Task 4: Organize and Archive Logs**
- Automate moving/parsing of old log files into dated archive directories using `os` and `shutil`.

---

## 📌 Weekly Deliverable (Mandatory)

- **Python Syslog Filter Script** (`syslog_filter.py`):
  - CLI tool for parsing and reporting on system logs.
  - Arguments for custom filtering (user, date, event).
  - Well-commented and robust error handling.

- **Documentation (`week5_python_automation.md`)**:
  - Script usage instructions and example outputs.
  - Brief reflection: where Python automation outperforms Bash, and where Bash is faster.

---

## 🚩 Success Criteria

- Write, debug, and run Python scripts for security ops confidently.
- Automate log parsing,
