# Capstone Project: Full-Stack Enterprise Defense Simulation

**Instructor:** Abu Mu’ādh (Cybersecurity Operator-in-Chief)  
**Student:** Donnovan Stewart
**Date Assigned:** June 11, 2025

---

## 🎯 Project Goal

Simulate a realistic enterprise environment, apply security best practices for defense, perform a simulated attack, and then detect, respond to, and document the incident. This project demonstrates a holistic understanding of both offensive and defensive cybersecurity operations at the operator level.

---

## 📝 General Instructions & Expectations

- **Documentation is Paramount:**  
  Every part has mandatory deliverables. Treat these as if you are presenting to a real client or senior management. Clarity, conciseness, and accuracy are key. Use clear headings, bullet points, and visuals (screenshots, diagrams) where appropriate.

- **Version Control:**  
  Utilize Git and GitHub (or a similar platform) to manage all your project files (.md reports, scripts, configuration files). This will be part of your final "Portfolio Packaging."

- **Ethical Hacking:**  
  This project involves simulated attacks. Crucially, all offensive actions MUST ONLY be performed within your isolated lab environment. Never target systems you do not own or have explicit permission to test.

- **Snapshots:**  
  Take VM snapshots frequently, especially before making significant changes or attempting attacks. This will save you immense time if something breaks.

- **Time Management:**  
  Break down each part into smaller tasks. This project is substantial, so consistent effort is required.

- **Seek Help:**  
  If you get stuck, utilize provided resources, online documentation, and reach out for guidance (but show you've attempted to solve it first!).

---

## 📦 Project Structure & Deliverables Breakdown

---

### **Part 1: Architecture & Planning**

**Objective:**  
Define the scope, assets, and threat landscape for your simulated enterprise. Design a secure network architecture.

**Key Questions to Answer:**
- What kind of "business" is this (e.g., small tech startup, financial firm, e-commerce)? What are its primary functions and data types?
- What critical assets (servers, databases, applications, user data) are in scope?
- Who are the users, and what access do they need?
- What are the plausible threat actors and their motivations?
- What are the key security requirements/concerns based on the business context?

**Deliverable:**  
- `capstone_architecture.md`  
    - **Business Context & Requirements:** Brief overview of your simulated enterprise, critical assets, users, and identified threats.
    - **Network Diagram:** Clear, labelled diagram showing topology, segmentation, and platforms (OS types for each VM). Use draw.io, diagrams.net, or Lucidchart.
    - **Platform Selection Rationale:** Justify your choice of operating systems for each VM.
    - **High-Level Security Controls:** Outline your planned security controls (e.g., firewalls, AV, SIEM).

**Success Criteria:**
- Clear, logical design reflecting a realistic enterprise.
- Accurate, easy-to-understand diagram.
- Well-reasoned requirements and design decisions.

---

### **Part 2: System Build & Hardening**

**Objective:**  
Deploy all necessary VMs and apply foundational security hardening (CIS Benchmarks).

**Required VMs:**
- Windows Domain Controller (DC) — AD, DNS, DHCP
- Linux Server(s) — Web/app/service host
- Windows Workstation(s) — User machines
- Attacker VM — Kali Linux

**Instructions:**  
- Install/configure each VM as designed.
- Apply CIS Benchmarks:  
    - Disable unnecessary services  
    - Strong passwords/account policies  
    - Least privilege  
    - Firewall config  
    - Disable weak protocols  
    - Time sync  
- Take snapshots post-hardening.

**Deliverable:**  
- `capstone_build_guide.md`  
    - **VM Deployment Summary:** VMs, OS, IPs, roles.
    - **Hardening Steps & Evidence:** Commands/config changes, screenshots, or outputs.
    - **Pre-Hardening State (optional):** Noted defaults/vulnerabilities.

**Success Criteria:**  
- All VMs deployed/configured.
- Hardening on each system is clear and evidenced.
- Guide is replicable.

---

### **Part 3: Security Stack Deployment**

**Objective:**  
Deploy SIEM and integrate detection tools.

**Instructions:**  
- Install/configure SIEM (Wazuh/ELK).
- Deploy agents to all targets, forward logs.
- Add detection tools (Suricata, YARA/Sigma rules).
- Validate logs/alerts in SIEM.

**Deliverable:**  
- `week6_siem_deployment.md`  
    - SIEM/agent install/config  
    - Dashboard/alert screenshots  
    - Detection tool setup/rules  
    - Proof of log ingestion and alerting

**Success Criteria:**  
- SIEM operational, collecting logs from all targets.
- Detection tooling integrated.
- Evidence of log ingestion and alerts.

---

### **Part 4: Offensive Simulation**

**Objective:**  
Act as attacker: perform penetration testing techniques and document TTPs.

**Instructions:**  
- Recon (Kali): Passive/active scanning.
- Initial access: Exploit misconfig, vuln, or weak creds.
- Privilege escalation, lateral movement.
- Simulate data exfiltration.
- Document all tools, commands, outputs, and map to MITRE ATT&CK.

**Deliverable:**  
- `capstone_attack_report.md`  
    - Executive summary  
    - Chronological attack playbook  
    - TTP mapping  
    - Observed impact

**Success Criteria:**  
- Repeatable log of offensive actions.
- Understanding of all attack phases.
- Tools/commands/TTPs clearly documented.

---

### **Part 5: Detection, Response & Forensics**

**Objective:**  
Detect, analyze, and respond to the simulated attack; collect forensics.

**Instructions:**  
- Use SIEM to find IOCs/alerts.
- Analyze logs, determine root cause.
- Contain/eradicate threats (simulated).
- Document evidence collected, lessons learned, and detection gaps.

**Deliverable:**  
- `capstone_defense_report.md`  
    - Executive summary  
    - Incident logs  
    - Detection/response/evidence per attack  
    - Detection gaps and proposed improvements

**Success Criteria:**  
- Effective SIEM use for detection.
- Clear incident/root cause analysis.
- Forensic methodology evidenced.

---

### **Part 6: IR Playbook & After-Action Review**

**Objective:**  
Develop incident response playbook and conduct after-action review.

**Instructions:**  
- Write a high-level IR playbook (covering detection, triage, containment, eradication, recovery, post-incident).
- Reflect on project: what worked, what didn’t, what you learned, what’s next.

**Deliverable:**  
- `capstone_ir_playbook.md`  
    - IR playbook  
    - After-action review

**Success Criteria:**  
- Practical IR playbook.
- Honest, critical self-assessment.

---

### **Part 7: Portfolio Packaging & Demo (Highly Recommended)**

**Objective:**  
Organize and present all deliverables for maximum impact.

**Instructions:**  
- Organize all files in a clean GitHub repo.
- Write a polished `README.md` summarizing the project and linking to all parts.
- (Optional) Record and link a video demo/walkthrough.

**Deliverable:**  
- Portfolio-ready GitHub repo  
- Root `README.md`  
- Demo video (optional)

**Success Criteria:**  
- Portfolio is navigable and polished.
- All deliverables present and understandable.
- README summarizes and showcases your work.

---

## 🛡️ Execute each part in order.  
**No shortcuts. Every deliverable is non-negotiable. This is your operator’s proof of mastery.**  
— *Abu Mu’ādh*  
