# 👋 Hi, I’m Dedan!

**Security Analyst (SOC / Incident Response)** on the **SOC Analyst → Incident Response → Security Operations Manager** path.  
Focused on **detection, investigation, response, and automation** across SOC and cloud environments.

I build and document hands-on labs across AWS, Azure, and hybrid on-prem environments, integrating security monitoring, detection logic, and automated response workflows.  
My work is **defensive and operational**, focused on making security teams faster, more accurate, and more reliable.

---

## 🎯 Career Path

**SOC Analyst → Incident Response → Security Operations Manager**

All labs, incident reports, and automation projects are designed to reflect real SOC responsibilities across this progression:
- Alert triage and escalation  
- Threat hunting and investigation  
- Incident response workflows  
- Detection engineering and automation  
- SecOps-level documentation and process improvement  

---

## 🧠 Representative SOC Case Study (How I Work)

**Scenario:** IDS + SIEM alert indicating possible SSH brute force  

**Process:**
1. Alert ingestion from Suricata → Wazuh → Splunk  
2. Event normalization and enrichment (IP reputation, frequency, asset context)  
3. Investigation using correlated DNS, auth, and network logs  
4. MITRE ATT&CK mapping and severity classification  
5. Response decision (block, monitor, or escalate)  
6. Incident write-up with timeline, evidence, and lessons learned  

**Evidence:**
- Detection rules: `/threat-hunting/rules/`
- Correlated events: `/incident-reports/`
- Automation logic: `/soc-alert-automation/`
- SIEM queries & enrichment logic: `/soc-alert-automation/`

This same workflow underpins my labs, automation pipelines, and incident reports.

---

## ⭐ SOC Core Workflow (Start Here)

If you want to see how I actually work as an analyst:

1. **Alert ingestion & normalization** → [SOC Alert Automation](https://github.com/johnylabs/soc-alert-automation)  
2. **Investigation & escalation** → [Incident Reports](https://github.com/johnylabs/incident-reports)  
3. **Detection improvement & hunting** → [Threat Hunting Lab](https://github.com/johnylabs/threat-hunting)

---

## 📂 Featured SOC Projects

- [**SOC Alert Automation**](https://github.com/johnylabs/soc-alert-automation)  
  Python pipeline that ingests Wazuh/Suricata alerts, normalizes events, enriches with context, and sends structured notifications to chat platforms for fast analyst triage.

- [**Incident Reports**](https://github.com/johnylabs/incident-reports)  
  Structured SOC incident write-ups with timelines, MITRE ATT&CK mapping, evidence, impact analysis, and remediation.

- [**Threat Hunting Lab**](https://github.com/johnylabs/threat-hunting)  
  Hypothesis-driven hunts across Wazuh, Suricata, and cloud logs, including Sigma/Wazuh rules and Jupyter notebooks for DNS tunneling, SSH brute force, and cloud anomalies.

- [**Security Event Explorer**](https://github.com/johnylabs/security-event-explorer)  
  Full-stack React + Python web application for browsing, filtering, and annotating security alerts from my SOC lab.  
  Includes a FastAPI backend, Postgres database, JWT auth, and a React UI designed for analyst workflows.

- [**AI Runbook QA**](https://github.com/johnylabs/ai-runbook-qa)  
  LLM-based assistant that reads SOC runbooks and incident documentation, then answers analyst questions and suggests response steps. Designed for lab and offline use.

---

## 🧪 Supporting Projects (Analytics & Language)

These projects support my analytical, automation, and language capabilities alongside SOC work.

- [**Market Deviation Tracker**](https://github.com/johnylabs/Market-Deviation-Tracker)  
  Quantitative anomaly detection tool that tracks pricing data, identifies deviations from normal ranges, and reinforces signal vs noise analysis.

- [**ES AI Tutor**](https://github.com/johnylabs/es-ai-tutor)  
  Spanish learning lab using local and hosted LLMs to support structured conversation practice, correction, and vocabulary drills — built for operational Spanish immersion.

---

## 🧩 ThreadBlue Collaborative Projects

- [**soc-lab-projects**](https://github.com/thread-blue/soc-lab-projects)  
  Full SOC lab integrating Splunk, Wazuh (SIEM), Suricata IDS, and DNS filtering. Built for alerting, correlation, and end-to-end security automation.

- [**cybersecurity-scripts**](https://github.com/thread-blue/cybersecurity-scripts)  
  Python utilities for log parsing, enrichment, threat detection, and SOC automation — developed and tested against the ThreadBlue SOC Lab.

---

## 🧰 Tech Stack

### 🛡️ Security / SOC
![Splunk](https://img.shields.io/badge/Splunk-000000?logo=splunk&logoColor=white)
![Wazuh](https://img.shields.io/badge/Wazuh-02569B?logo=wazuh&logoColor=white)
![Suricata](https://img.shields.io/badge/Suricata-FF4500?logo=suricata&logoColor=white)
![Pi-hole](https://img.shields.io/badge/Pi--hole-96060C?logo=pihole&logoColor=white)

### ☁️ Cloud & Virtualization
![AWS](https://img.shields.io/badge/AWS-232F3E?logo=amazonaws&logoColor=white)
![Azure](https://img.shields.io/badge/Microsoft%20Azure-0078D4?logo=microsoftazure&logoColor=white)
![Proxmox](https://img.shields.io/badge/Proxmox-E57000?logo=proxmox&logoColor=white)

### 🧠 Programming & Automation
![Python](https://img.shields.io/badge/Python-3776AB?logo=python&logoColor=white)
![Bash](https://img.shields.io/badge/Bash-4EAA25?logo=gnubash&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?logo=git&logoColor=white)

### 💻 Systems & Networking
![Linux](https://img.shields.io/badge/Linux-FCC624?logo=linux&logoColor=black)
![Networking](https://img.shields.io/badge/Networking-0078D7?logo=cisco&logoColor=white)

---

## 🧠 Certifications

- 🟥 CompTIA Security+
- 🟧 CompTIA Network+
- 🟩 Splunk Core Certified Power User
- 🟦 AWS Cloud Practitioner
- 🟦 Microsoft Certified: Azure Fundamentals AZ-900
- 🟪 **Microsoft Certified: Microsoft Certified: Security Operations Analyst Associate SC-200 (In Progress)**

---

## 🎓 Education & Roadmap

- **Bachelor of Science in Cybersecurity** *(in progress)*  

**Next 12 Months:**  
- SC-200 completion  
- Continued SOC automation and detection engineering projects  
- MBA – program start  

---

## 🚀 Current Focus

- Expanding my **SOC home lab** to simulate real-world detection and response scenarios.  
- Developing **Python automation pipelines** for alert enrichment, anomaly detection, and workflow orchestration.  
- Building **cloud-integrated SOC tooling** that ties SIEM, identity, and logging together.  
- Using AI tooling to improve **runbooks, investigations, and analyst efficiency**.  
- Pushing toward **operational Spanish fluency** for security roles in Spanish-speaking environments.

---

## 🌍 Work Authorization

🇲🇽 Based in Mexico with valid work authorization  
🇦🇺 Australian citizen
