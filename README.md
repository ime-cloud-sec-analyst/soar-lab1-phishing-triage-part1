# soar-lab1-phishing-triage-part1
Part 1 of the SOAR Lab Project – Building and Accessing a Splunk Enterprise Environment for Phishing Triage (SIEM/SOAR Use Case)

# 🧪 Lab 1 (Part 1): Build & Access a SOAR Platform for Phishing Triage

**Project:** Core SIEM/SOAR Case Study Lab Portfolio  
**Platform:** AWS + Splunk Enterprise  
**User:** Ime Ben  
**Date:** July 2025  
**GitHub:** https://github.com/ime-cloud-sec-analyst/soar-lab1-phishing-triage-part1  

---

## 🎯 Objective  
To provision and configure a Splunk SIEM/SOAR environment on AWS EC2 for monitoring phishing emails as part of a scalable Security Operations Center (SOC) workflow.

---

## 🎯 Aim  
- Launch an EC2 instance using Ubuntu AMI  
- Install and configure Splunk Enterprise  
- Verify access to the Splunk GUI  
- Take inventory screenshots (17 steps total)

---

## 🧰 Tools & Technologies  
- **AWS EC2 (Ubuntu Linux 20.04)**  
- **Splunk Enterprise (Free version)**  
- **PowerShell (Windows 10)**  
- **Web browser** (Chrome/Edge)  
- **GitHub** (Documentation)  
- **LinkedIn** (Knowledge sharing)

---

## 🧠 Skills Developed  
- Infrastructure deployment (EC2)  
- Linux command line (update, install)  
- Web app access and port configuration  
- Security best practices: key pair handling, firewall rules  
- Cloud logging & SIEM fundamentals

---

## 🛠️ Implementation Strategy  
1. Launch EC2 instance  
2. Configure inbound rules (TCP port 8000)  
3. SSH into the instance  
4. Install `wget`, `tar`, and dependencies  
5. Download and install Splunk  
6. Start the Splunk service  
7. Access GUI via browser  
8. Capture screenshots for documentation

---

## 🚫 Limitations  
- No `.pem` key was available (used PowerShell workarounds)  
- Manual steps due to no automation yet (to be improved in Part 2)  
- Limited to free tier instance  
- Splunk license limited to free version (500 MB/day indexing)

---

## 🧩 Significance  
This lab provides foundational knowledge for deploying real-world SIEM platforms and preparing automated playbooks in Part 2. It bridges the gap between cloud infrastructure and security operations.

---

## 🧪 Screenshots Documentation  
All 17 screenshots are stored in `/screenshots` folder.

---

## 🛡️ Recommendations (as advice/remediation)  
- 🔐 Always store `.pem` keys securely (use AWS Secrets Manager or download once and archive)  
- ✅ Consider automating this setup with Terraform or AWS CLI in Part 2  
- 📊 Use Splunk App for Monitoring AWS and Threat Intel integration next  
- 🔄 Test Splunk logging with fake phishing data using Splunk Add-on  
- 🧪 Enable SSL and secure access to Splunk in production environments

---

## 🔗 Next Steps (Part 2 Preview)  
In the next phase, we'll:  
- Ingest phishing email samples  
- Create detection rules in Splunk  
- Automate response using Python scripts and pre-built playbooks

---

## 📬 Contact  
**Ime Ben**  
`AWS Cloud Sec Analyst | SIEM Engineer | DevSecOps Enthusiast`  
📧 imegcu55@gmail.com
