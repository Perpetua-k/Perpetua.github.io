---
layout: single
title: "Lab Challenges"
permalink: /labs/
author_profile: true
---

###  Network Scanning – Nmap & Nessus
**Problem:** Identify vulnerabilities on lab environment by combining network discovery and vulnerability scanning techniques..  
**Approach:** Used Nmap for recon, Nessus for vulnerability validation. 
**Reconnaissance (Nmap)** — Performed host discovery and service enumeration using:
   ```bash
   nmap -sS -sV -O -p- -T4 <target-range>
**Tools:** Nmap, Nessus.  

Delivered live demo using Nmap, Nessus, and Wireshark.  
[🎥 Watch Presentation](https://youtu.be/MNpF640swl4){: .btn .btn--info target="_blank"}

**Lessons Learned:**
- Combine active and authenticated scans.
- Prioritize findings by exploitability.
- Always define scope and authorization.
