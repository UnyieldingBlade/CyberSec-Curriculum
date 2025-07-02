## 🎯 Objective
Develop core automation skills by mastering Bash scripting for system administration, security monitoring, and report generation.

---

## 🧠 Quiz Topics

- Construct and explain Bash control structures (loops, if-else, functions).
- Redirect input/output, use pipes, and chain commands efficiently.
- Utilize `cron` for task scheduling.
- Apply text-processing tools (`grep`, `awk`, `sed`) for log analysis.

---

## 📖 Reading

- [LinuxCommand.org — Learning the Shell](https://linuxcommand.org/lc3_learning_the_shell.php)
- [Bash Scripting Tutorial (Ryan Chadwick)](https://ryanstutorials.net/bash-scripting-tutorial/)
- [Understanding Cron Jobs](https://opensource.com/article/17/11/how-use-cron-linux)

---

## 🛠️ Lab Environment Setup

### Virtual Machines (VMs)

- **Primary VM:** Kali Linux (continue from previous weeks)
- **Support VM:** Ubuntu Server

### Required Tools

- Bash shell
- `cron`, `crontab`
- `grep`, `awk`, `sed`, `cut`
- `rsync`, `find`

---

## ⚔️ Practical Tasks

**Task 1: Bash Scripting Fundamentals**
- Write scripts to automate file operations (backups, file organization).
- Use variables, conditionals, and loops in all scripts.
- Ensure all scripts are commented and executable.

**Task 2: Log Processing & Report Generation**
- Create scripts that parse `/var/log/auth.log` (or equivalent) for failed/successful logins.
- Output summaries in clean, readable format.

**Task 3: Cron Job Automation**
- Schedule automated log parsing or backup scripts using `cron`.
- Document the process for adding and verifying scheduled jobs.

**Task 4: Text Processing Mastery**
- Use `grep`, `awk`, and `sed` to extract specific security-relevant events from system logs.
- Chain multiple commands for advanced filtering and reporting.

---

## 📌 Weekly Deliverable (Mandatory)

- **Security Report Generator Script** (`security_report.sh`):
  - Automates log parsing and outputs summary of relevant security events.
  - Accepts date range or event type as argument (bonus: email the results).

- **Documentation (`week4_bash_automation.md`)**:
  - Explanation of script logic and functionality.
  - Evidence of cron job setup and output samples.

---

## 🚩 Success Criteria

- Efficiently build, debug, and execute Bash scripts.
- Confidently automate security and admin tasks.
- Clean documentation and robust script output.

---

## ✅ Week 4 Completion Checklist

- [ ] Completed assigned readings.
- [ ] VMs and all required tools set up.
- [ ] All practical tasks executed (scripts, cron, text-processing).
- [ ] Weekly deliverables (`security_report.sh`, `week4_bash_automation.md`) completed and added to portfolio.

---

## 🚨 Important Notes

- Scripts must be clean, well-commented, and secure (no unnecessary sudo use).
- Test all automation in a controlled VM before applying to production systems.

No theory without output. Build, automate, and document—move fast, move clean.
