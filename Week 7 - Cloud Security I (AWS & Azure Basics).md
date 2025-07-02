## 🎯 Objective
Establish foundational competency in cloud security by deploying and hardening resources in AWS and/or Azure. Understand cloud identity, monitoring, and basic cloud attack surfaces.

---

## 🧠 Quiz Topics

- Difference between IAM users, roles, and policies.
- What is GuardDuty and why is it valuable?
- Identify common cloud misconfigurations.
- Steps to harden a default EC2 instance.

---

## 📖 Reading

- [AWS Well-Architected Framework: Security Pillar (PDF)](https://docs.aws.amazon.com/wellarchitected/latest/security-pillar/welcome.html)
- [AWS IAM — Best Practices](https://docs.aws.amazon.com/IAM/latest/UserGuide/best-practices.html)
- [Azure Security Documentation](https://learn.microsoft.com/en-us/azure/security/)

---

## 🛠️ Lab Environment Setup

### Accounts & Resources

- **AWS Free Tier account** *(preferred, minimal cost; use disposable card if needed)*
- **(Optional)** Azure Free Student/Trial account

### Required Tools

- AWS CLI (install locally on Kali/Ubuntu)
- IAM Policy Simulator (web tool)
- GuardDuty (AWS console)
- Azure CLI

---

## ⚔️ Practical Tasks

**Task 1: IAM Policy & Identity Management**
- Create users, groups, and roles in AWS IAM.
- Write custom IAM policies restricting privileges using least-privilege model.
- Test policies with the IAM Policy Simulator.

**Task 2: Deploy and Harden EC2**
- Launch an EC2 instance (Ubuntu, t2.micro/free tier).
- Harden instance: disable root login, enforce SSH key auth, apply firewall rules.
- Enable CloudWatch and GuardDuty monitoring on the instance.

**Task 3: Log Collection & Alerting**
- Forward system logs from EC2 to CloudWatch.
- Set up at least one security alert (e.g., SSH brute force detection) via GuardDuty or CloudWatch.

**Task 4: (Optional) Azure Basics**
- Create a test VM and configure basic logging/monitoring in Azure Security Center.

---

## 📌 Weekly Deliverable (Mandatory)

- **Cloud Security Lab Report** (`week7_cloud_security.md`):
  - Steps taken to create/harden IAM users, roles, and policies.
  - Evidence of EC2 hardening (screenshots/configs).
  - GuardDuty/CloudWatch alert configuration and sample results.
  - Summary: Most common cloud misconfigurations and how you prevented them.

---

## 🚩 Success Criteria

- Deploy and harden a real cloud VM securely.
- Demonstrate understanding and application of least-privilege IAM.
- Enable monitoring and alerting using built-in cloud security tools.
- Provide clear, actionable documentation.

---

## ✅ Week 7 Completion Checklist

- [ ] Completed all assigned readings.
- [ ] AWS/Azure accounts established and CLI installed.
- [ ] Practical tasks executed (IAM, EC2, logging/alerts).
- [ ] Weekly deliverable (`week7_cloud_security.md`) completed and added to portfolio.

---

## 🚨 Important Notes

- Immediately delete all cloud resources after lab completion to avoid charges.
- Never use real/production credentials or sensitive data in your cloud labs.
- Prioritize AWS for hands-on (most relevant to Middle East job market).

Cloud is not optional—master the basics, document your work, and move forward.
