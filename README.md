# Wazuh-Threat-Analysis
SIEM monitoring and automated threat mitigation lab
### **Full Technical Reports**
For a deep dive into the methodology and findings of these projects, please view the full reports below:
# Cybersecurity Research & Threat Investigation Portfolio

## 🛡️ Enterprise SIEM: Wazuh Threat Analysis
This project focuses on real-time threat detection and automated response within a Wazuh SIEM environment.

* [📄 Full Threat Research Report (PDF)](threat-report.pdf?raw=true)
    * A comprehensive 30-day investigation into automated brute-force campaigns and unauthorized access attempts.
* [📊 SIEM Dashboard Visualizations (PDF)](dashboard-evidence.pdf?raw=true)
    * Visual evidence of 137,352 security events, including geographic threat mapping and Rule Level 10+ alert spikes.

**Key Findings:**
* Identified a high-volume attack origin from a Romanian IP (2.57.122.177) responsible for over 7% of total malicious traffic.
* Documented a 7.036% error code spike from UK-based infrastructure, indicating targeted web-server probing.

---

## 🏠 Infrastructure Hardening: Home Network Sovereignty
Implementation of a recursive DNS "black hole" and secure remote access using Raspberry Pi hardware.

* [📄 Home Network Security Report (PDF)](pi-project.pdf?raw=true)
    * Technical documentation on deploying Pi-hole and Unbound to achieve DNS privacy and ad-blocking at the network level.

**Project Highlights:**
* **DNS Sovereignty:** Configured a local recursive DNS resolver to eliminate reliance on third-party upstream providers.
* **Telemetry Mitigation:** Successfully blocked 34% of network-wide tracking and advertisement traffic.
* **Secure Connectivity:** Integrated Tailscale to maintain encrypted DNS protection while on public Wi-Fi or cellular networks.
