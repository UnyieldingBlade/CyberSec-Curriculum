## 🎯 Objective
Rapidly acquire foundational Linux command-line skills and core networking concepts necessary for operator-level cybersecurity tasks.

---

## 🧠 Quiz Topics

- Identify and explain the OSI model layers.
- Perform basic subnet calculations (CIDR, subnet masks).
- Navigate and manipulate the Linux filesystem confidently.
- Conduct basic network reconnaissance using ICMP, DNS, and TCP/UDP scanning.

---

## 📖 Reading

- [Julia Evans' Networking Zines](https://wizardzines.com/zines/networking/) (Clear visual introductions to core networking concepts)
- [Cloudflare: "What is DNS?"](https://www.cloudflare.com/learning/dns/what-is-dns/) (Concise explanation of DNS operations)
- [Linux Command Line Crash Course](https://linuxjourney.com/lesson/the-shell) (Essential shell commands and navigation basics)

---

## 🛠️ Lab Environment Setup

### Virtual Machines (VMs)

- **Primary VM:** Kali Linux (latest)
- **Secondary VM:** Ubuntu Server (minimal install)

### Required Tools

- Networking: `ip`, `ping`, `dig`, `nmap`, `tcpdump`
- Linux CLI: `ls`, `cd`, `chmod`, `mkdir`, `grep`, `cat`, `nano`/`vim`

---

## ⚔️ Practical Tasks

**Task 1: Linux CLI Familiarization**
- Navigate the filesystem, manage files/directories, and set permissions.
- Practice file operations (`cp`, `mv`, `rm`) and file permissions (`chmod`).

**Task 2: Network Enumeration**
- Identify your VM’s IP and subnet using `ip addr`.
- Enumerate all active devices on your local network (`ping`, `nmap -sn`).
- Document device IP addresses, MAC addresses, and open ports.

**Task 3: DNS Reconnaissance**
- Query common DNS records (`A`, `MX`, `TXT`) using `dig`.
- Document responses and interpret basic DNS configurations.

---

## 📌 Weekly Deliverable (Mandatory)

- **Network Enumeration Report** (`week1_network_report.md`):
  - Network diagram or table of devices.
  - List of discovered open ports, IPs, and DNS records.
  - Brief summary of methods used and findings.

---

## 🚩 Success Criteria

- Clear understanding of Linux command-line fundamentals.
- Ability to enumerate and document a basic network environment independently.
- Confident execution of basic network reconnaissance commands.

---

## ✅ Week 1 Completion Checklist

- [ ] Completed assigned readings.
- [ ] VM environments correctly configured.
- [ ] Successfully finished practical tasks (CLI, network enumeration, DNS recon).
- [ ] Submitted weekly deliverable (`week1_network_report.md`) to portfolio.

---

## 🚨 Important Notes

- Document clearly and precisely; maintain discipline and clarity.
- Adhere strictly to ethical usage of all reconnaissance techniques (only scan networks you own or have explicit permission to scan).

Begin immediately—output and action first, theory second.  
