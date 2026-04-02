# Threat-Analysis-and-Infrastructure-Hardening
### **Full Technical Reports**
For a deep dive into the methodology and findings of these projects, please view the full reports below:
# Cybersecurity Research & Threat Investigation Portfolio

## 🛡️ Enterprise SIEM: Wazuh Threat Analysis
This project documents my work as a Threat Research Intern, focusing on real-time monitoring, pattern recognition, and automated mitigation within a Wazuh SIEM environment.

### **Technical Reports & Evidence**
* [📄 View: Security Threat Research Report (PDF)](threat-report.pdf)
* [📊 View: SIEM Dashboard Visualizations (PDF)](visualizations.pdf)

**Project Impact:**
* **Data Volume:** Monitored and analyzed **137,352 high-severity alerts** over a 30-day period.
* **Threat Identification:** Isolated a high-volume brute-force campaign originating from a **Romanian IP (2.57.122.177)**, which accounted for over 7% of total malicious hits.
* **Pattern Recognition:** Documented a 7.036% error spike from UK-based infrastructure (195.178.110.28) targeting web-server vulnerabilities.

---

## 🏠 Infrastructure Hardening: Home Network Sovereignty
Implementation of a recursive DNS "black hole" and secure remote access using Raspberry Pi hardware to achieve network-wide privacy.

### **Technical Reports & Evidence**
* [📄 View: Home Network Hardening Report (PDF)](pi-project.pdf)
* [📸 View: Pi-hole & Networking Visual Evidence (PDF)](pi-evidence.pdf)

**Technical Implementation:**
* **Ad-Tech Mitigation:** Achieved a **34.2% block rate** of total network traffic, successfully neutralizing tracking telemetry and malicious domains.
* **DNS Sovereignty:** Deployed **Unbound** as a recursive DNS resolver (localhost#5335) to eliminate reliance on third-party upstream providers.
* **Encrypted Tunneling:** Integrated **Tailscale** to maintain secure, private DNS resolution for mobile devices while on public or cellular networks.
