## 🎯 Objective
Deploy your own Security Information and Event Management (SIEM) stack, ingest logs from multiple systems, and create actionable security alerts and dashboards—critical skills for enterprise and SOC environments.

---

## 🧠 Quiz Topics

- What is a SIEM? Core purpose and enterprise value.
- Difference between a log and an event.
- How agents forward logs from endpoints to a central SIEM.
- Basic alert creation and dashboarding.

---

## 📖 Reading

- [Wazuh Documentation — Quickstart](https://documentation.wazuh.com/current/installation-guide/index.html)
- [Splunk Fundamentals I (free course)](https://education.splunk.com/virtual-courses/splunk-fundamentals-1.html)
- [Elastic SIEM Overview](https://www.elastic.co/guide/en/security/current/index.html) (optional, for broader context)

---

## 🛠️ Lab Environment Setup

### Virtual Machines (VMs)

- **SIEM VM:** Ubuntu Server (for Wazuh manager + Splunk)
- **Endpoint VMs:** Kali Linux, Windows 10 (log sources/agents)

### Required Tools

- Wazuh Manager & Agent
- Splunk Free Edition (local install)
- Syslog-ng or rsyslog (log forwarding)

---

## ⚔️ Practical Tasks

**Task 1: Deploy Wazuh SIEM Stack**
- Install Wazuh Manager on Ubuntu Server.
- Configure and deploy Wazuh Agents to Kali and Windows VMs.
- Verify agent-to-manager log forwarding.

**Task 2: Deploy Splunk (Local)**
- Install Splunk Free Edition on your SIEM VM.
- Forward sample logs from endpoints (Kali, Windows) to Splunk.
- Parse, index, and search for critical events.

**Task 3: Ingest & Analyze Logs**
- Collect authentication and syslog data from all endpoints.
- Configure log parsing rules for security-relevant events (failed logins, suspicious activity).
- Set up dashboards visualizing key security metrics.

**Task 4: Create Alerts & Dashboards**
- Build basic alerts for critical events (e.g., brute force attempts, unauthorized access).
- Configure at least one dashboard in both Wazuh and Splunk to monitor live security data.

---

## 📌 Weekly Deliverable (Mandatory)

- **SIEM Deployment Report** (`week6_siem_deployment.md`):
  - Installation/configuration steps for Wazuh and Splunk.
  - Agent deployment details and verification logs.
  - Screenshots of dashboards and sample alerts.
  - Lessons learned and troubleshooting notes.

---

## 🚩 Success Criteria

- Stand up a working SIEM (Wazuh + Splunk), ingesting real logs from at least two endpoints.
- Demonstrate ability to create actionable alerts and visualize log data.
- Clear, reproducible documentation of setup, configs, and results.

---

## ✅ Week 6 Completion Checklist

- [ ] Completed all readings and SIEM docs.
- [ ] SIEM VM and endpoint agents installed and functional.
- [ ] Log forwarding, ingestion, and dashboarding validated in both Wazuh and Splunk.
- [ ] Weekly deliverable (`week6_siem_deployment.md`) submitted to portfolio.

---

## 🚨 Important Notes

- Use only your own lab systems for log ingestion—**never** send real/production data to your SIEM.
- Take VM snapshots before major changes.
- If resources are tight, focus on Wazuh first (Splunk as bonus/secondary).

This is your first taste of real SOC tooling—get it working, own the process, document everything.
