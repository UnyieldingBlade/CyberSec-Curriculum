## 🎯 Objective
Master Linux permission management, robust system logging, and auditing processes crucial for cybersecurity operations.

---

## 🧠 Quiz Topics

- Explain Linux file permission attributes (`rwx`).
- Describe the lifecycle of a systemd service (`systemctl` commands).
- Filter and interpret logs with `journalctl`.
- Basic audit logging configuration (`auditd`).

---

## 📖 Reading

- ["The Linux Command Line" by William Shotts (Chapter 9: Permissions)](https://linuxcommand.org/tlcl.php)
- ["Introduction to systemd"](https://www.freedesktop.org/wiki/Software/systemd/)
- ["Understanding Linux Audit with auditd"](https://linux-audit.com/linux-audit-quick-start/)

---

## 🛠️ Lab Environment Setup

### Virtual Machines (VMs)

- **Primary VM:** Kali Linux (from Week 1)
- **Secondary VM:** Ubuntu Server (fresh minimal install)

### Required Tools

- Linux permissions: `chmod`, `chown`, `ls -l`
- System and log management: `systemctl`, `journalctl`, `logrotate`
- Auditing: `auditd`, `ausearch`, `auditctl`

---

## ⚔️ Practical Tasks

**Task 1: Permissions & Ownership**
- Create a new user (`useradd`) and assign permissions and ownership on directories/files (`chmod`, `chown`).
- Verify permissions (`ls -l`) and document outcomes.

**Task 2: systemd Service Management**
- Manage a basic system service (e.g., SSH): start, stop, restart, enable, disable.
- Examine service status logs using `systemctl` and `journalctl`.

**Task 3: Audit Logging Configuration**
- Set up basic auditing rules (monitor file changes and login attempts).
- Test audit rules by creating/modifying monitored files, verifying logs with `ausearch`.

**Task 4: Log Rotation & Management**
- Configure `logrotate` for a custom log file or system logs.
- Verify proper rotation and archiving functionality.

---

## 📌 Weekly Deliverable (Mandatory)

- **Log Auditing Bash Script** (`audit_watch.sh`):
  - Script to automate audit log monitoring.
  - Output alerts or summaries of critical events (login failures, file modifications).
- **Documentation (`week2_audit_log_summary.md`)**:
  - Clearly documented permissions set on key files/directories.
  - Overview of configured auditing rules and sample results.

---

## 🚩 Success Criteria

- Thorough understanding and practical ability to manage file permissions.
- Confident systemd service management and log inspection.
- Proven ability to configure and utilize auditing effectively for basic intrusion detection.

---

## ✅ Week 2 Completion Checklist

- [ ] Completed assigned readings.
- [ ] VM setups maintained and updated.
- [ ] Successfully executed practical tasks (permissions, systemd, audit logging).
- [ ] Submitted weekly deliverables (`audit_watch.sh`, `week2_audit_log_summary.md`) to portfolio.

---

## 🚨 Important Notes

- Maintain concise documentation and clear, reproducible audit logging rules.
- Consistently review system logs for unusual behavior or misconfigurations.

Move with urgency and discipline—master these skills decisively.
