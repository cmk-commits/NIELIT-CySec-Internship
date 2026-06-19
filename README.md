# 🛡️ NIELIT Cyber Security Internship

---

## 📖 Overview
Welcome to my personal treasury of cyber security knowledge acquired during my internship at the **National Institute of Electronics & Information Technology (NIELIT)**. This repository serves as a live engineering journal documenting my hands-on technical deep dives, live command executions, expected vs. actual outputs, and the raw, unfiltered trial-and-error process that shaped my learning.

> **Explore the vastness of the Cyber Security Attack Surface through documented, practical telemetry.**

---

## 🗂️ Core Knowledge Pillars

### 💡 Theory & Concepts
* Deep dives into network security protocols and architecture.
* Understanding vulnerability assessment and penetration testing (VAPT) workflows.
* Real-world operational methodology in threat hunting.

### 💻 Live Commands & Execution
* Fully documented scripts, tool commands, and flags (Nmap, Wireshark, Metasploit, etc.).
* Verbose syntax breakdowns explaining *why* specific arguments were chosen.

### 📊 Raw Outputs & Logs
* Captured terminal logs and payloads showing successful exploits or system states.
* Side-by-side comparisons of secure vs. vulnerable configurations.

### ⚠️ Trials, Errors, & Root Cause Analysis
* A historical log of scripts that failed, misconfigured network rules, and broken tools.
* Comprehensive "Post-Mortems" explaining the exact reason for failure and the logic behind the final fix.

---

### 🔍 Error & Resolution Log Blueprint
* **The Error:** `Failed to bind to port 443 (Permission Denied)`
* **The Reason:** The tool script was executed by a non-root user trying to access privileged ports (0-1023).
* **The Fix:** Prepend execution with `sudo` or configure correct Linux capabilities (`setcap`).

---

## 🤝 Acknowledgements
Special thanks to the mentors and coordinators at **NIELIT** for providing the rigorous environments, guidelines, and frameworks necessary to explore modern cyber defensive and offensive surfaces safely.

---
<p align="center">
  <i>"In cybersecurity, failure is just data that hasn't been turned into a defense strategy yet."</i>
</p>
