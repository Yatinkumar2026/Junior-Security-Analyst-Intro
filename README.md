# 📌 Security Analyst Journey — TryHackMe Lab Documentation

Welcome to my **Security Analyst Journey**, a hands-on SOC beginner project completed through **TryHackMe**.
This repository documents my work as a **Junior Security Analyst**, including alert analysis, threat identification, and incident escalation inside a simulated SOC environment.

---

## 🛡 About the Project

This lab simulates a **real-world SOC Level 1 Analyst workflow**, including:

* Monitoring alerts from a SIEM
* Identifying suspicious behavior
* Escalation to senior analysts
* Blocking malicious activity at the firewall level
* Practicing daily responsibilities of a security analyst

---

## 📝 Tasks Completed

### **Task 1 — Security Analyst Journey**

Cyber security is a world of evolving threats — every alert could hide an attack.
As a Junior Security Analyst, I monitor and respond to alerts to keep the organization protected.

**Responsibilities**

* Monitor & investigate security alerts
* Collaborate with SOC teammates
* Continually learn and defend against new threats

**Answer**

| Question                                                  | Answer                               |
| --------------------------------------------------------- | ------------------------------------ |
| Which team do you work with as a Junior Security Analyst? | **SOC (Security Operations Center)** |

---

### **Task 2 — SOC and Your Team**

Meet the SOC team supporting daily operations:

| Role               | Name               | Responsibility                               |
| ------------------ | ------------------ | -------------------------------------------- |
| Senior Analyst     | **Will Griffin**   | Assists juniors, handles complex escalations |
| SOC Engineer       | **Corey Stevens**  | Configures tools, maintains detections       |
| SOC Manager        | **Emily Conway**   | Oversees SOC operations & reporting          |
| Incident Responder | **Daniel Herrera** | Engages during major incidents               |

**Skills gained**

* Understanding SOC hierarchy
* Knowing escalation flow
* Learning team collaboration

---

### **Task 3 — Being a Security Analyst**

Security analysts balance:

* Large alert volumes ("tickets")
* Continuous learning
* Real threat prevention

**Daily tasks may involve:**

* Detecting malware infections
* Investigating phishing attempts
* Responding to ransomware activity
* Building detection rules
* Coordinating with teams across the company

---

### **Task 4 — SIEM Alert Investigation**

**Alert Summary**

| Date                  | Severity | Message                                                       |
| --------------------- | -------- | ------------------------------------------------------------- |
| Dec 31st 2025 · 03:14 | Critical | Successful SSH login from suspicious IP: `221.181.185.159`    |
| Dec 31st 2025 · 03:10 | Critical | Unauthorized login attempts from `221.181.185.159` to port 22 |
| Dec 31st 2025 · 02:24 | Low      | User John Doe logged in after 3 failed attempts               |
| Dec 31st 2025 · 01:14 | Medium   | Multiple failed logins from IT Automation service account     |
| Dec 31st 2025 · 01:04 | Low      | Logon Error: IT Automation password expired                   |

**Answers**

| Question               | Answer                         |
| ---------------------- | ------------------------------ |
| Malicious IP Address   | **221.181.185.159**            |
| Alert escalated to     | **Will Griffin**               |
| Firewall block message | **`THM{until-we-meet-again}`** |

---

## 🔧 Skills Demonstrated

| Skill                 | Tools / Techniques Used        |
| --------------------- | ------------------------------ |
| SIEM Alert Analysis   | Event logs, SSH logs           |
| Threat Identification | Suspicious IP behavior         |
| Escalation Workflow   | SOC hierarchy                  |
| Network Defense       | Firewall IP block              |
| Documentation         | Markdown, structured reporting |

---

## 🚀 How to Use This Repository

| Step | Action                                  |
| ---- | --------------------------------------- |
| 1    | Clone / download repository             |
| 2    | Review alert data in `/alerts`          |
| 3    | View escalation and response notes      |
| 4    | Use as portfolio evidence for SOC roles |

---

## 🎯 What I Learned

* Realistic SOC workflows
* Alert prioritization & risk analysis
* Cross-team escalation and collaboration
* Hands-on firewall IP blocking
* Structured cybersecurity documentation


