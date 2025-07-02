## 🎯 Objective
Gain foundational knowledge of Windows system security, Group Policy management, and event logging necessary for cybersecurity operations within enterprise environments.

---

## 🧠 Quiz Topics

- Describe Group Policy Objects (GPO) and their application.
- Identify key categories within Windows Event Logs.
- Explain basic Windows system hardening techniques.
- Usage of essential Sysinternals tools (Autoruns, Process Monitor).

---

## 📖 Reading

- [Microsoft Docs: Windows Security Basics](https://learn.microsoft.com/en-us/windows/security/)
- [Sysinternals Suite Documentation](https://learn.microsoft.com/en-us/sysinternals/)
- [Introduction to Windows Event Logs](https://learn.microsoft.com/en-us/windows-server/administration/windows-commands/wevtutil)

---

## 🛠️ Lab Environment Setup

### Virtual Machines (VMs)

- **Primary VM:** Windows 10 Enterprise (Evaluation ISO)
- **Support VM:** Kali Linux VM (from Weeks 1–2)

### Required Tools

- Built-in: Event Viewer, `gpedit.msc`
- Sysinternals Suite: Process Monitor, Autoruns, TCPView, Process Explorer

---

## ⚔️ Practical Tasks

**Task 1: Group Policy Hardening**
- Configure a basic Group Policy baseline (password complexity, account lockouts, user permissions).
- Document your configured GPO settings clearly.

**Task 2: Event Log Exploration & Monitoring**
- Access and navigate the Event Viewer.
- Identify critical security events (failed logins, system events).
- Save and export event logs for review.

**Task 3: System Hardening via Sysinternals**
- Utilize Autoruns to disable unnecessary startup items and services.
- Analyze system processes with Process Explorer for suspicious activity.
- Document all modifications clearly and concisely.

---

## 📌 Weekly Deliverable (Mandatory)

- **Windows Hardening & Monitoring Report** (`week3_windows_hardening.md`):
  - Documented GPO settings (screenshots and text summaries).
  - Summary of critical security events captured.
  - Changes made via Sysinternals (Autoruns, Process Explorer findings).

---

## 🚩 Success Criteria

- Confident use of GPOs to enforce security baselines.
- Familiarity with navigating and interpreting Windows Event Logs.
- Practical understanding and use of Sysinternals Suite tools for system auditing and hardening.

---

## ✅ Week 3 Completion Checklist

- [ ] Completed assigned readings.
- [ ] Windows VM properly configured and ready.
- [ ] Successfully executed all practical tasks (GPO, event log, Sysinternals).
- [ ] Submitted weekly deliverable (`week3_windows_hardening.md`) to portfolio.

---

## 🚨 Important Notes

- Maintain a methodical approach to system modifications; document every step for accountability.
- Always ensure your VM snapshots/backups are taken before making extensive configuration changes.

Operate decisively—focus on precision, clarity, and action-oriented outcomes.
