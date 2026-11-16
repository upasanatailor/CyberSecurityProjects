# 🎣 SOC Level 1: Phishing Analysis & Email Investigation Labs

> A comprehensive collection of hands-on phishing analysis investigations, examining malicious email architecture, header forensics, URL defanging, and real-world social engineering scenarios.

---
## 📧 SMTP & IMF Packet Analysis

> **Introduction:** Deep-dive into email protocol traffic capturing, examining plaintext SMTP authentication, mail transaction commands (EHLO, MAIL FROM, RCPT TO, DATA), and IMF message structures using Wireshark.

| Lab / Packet Study Name | Core Focus & Concepts Covered | Direct Link / Notes |
| :--- | :--- | :--- |
| **SMTP Packet Analysis** | Analyzing mail server communication, tracking TCP handshakes on ports 25/587, and identifying plaintext authentication tokens. | [Wireshark Capture Study](./artifacts/smtp-pcap.png) |
| **IMF Message Structure Study** | Inspecting the raw MIME headers and body payloads encapsulated within network data streams. | [Wireshark Capture Study](./artifacts/IMF-pcap.png) |
---

## 📋 Module Overview
Phishing remains one of the most common vectors for initial compromise in enterprise environments. This section documents my practical investigations into email telemetry, header anomalies, attachment inspections, and threat intelligence extraction across multiple interactive labs.

---

## 🏛️ Completed TryHackMe Rooms & Exercises

| Room / Module Name | Core Focus & Concepts Covered | Direct Link |
| :--- | :--- | :--- |
| **1. Phishing Analysis Fundamentals** | Core concepts of email spoofing, identifying malicious sender addresses, and foundational triage workflows. | [Open Room](https://tryhackme.com/room/phishingemails1tryoe) |
| **2. Phishing Emails in Action** | Analyzing real-world phishing emails, inspecting MIME parts, and tracking routing hops. | [Open Room](https://tryhackme.com/room/phishingemails2rytmuv) |
| **3. Phishing Analysis Tools** | Utilizing specialized utilities (such as CyberChef and header analyzers) to decode suspicious strings and URLs. | [Open Room](https://tryhackme.com/room/phishingemails3tryoe) |
| **4. Phishing Prevention** | Exploring defensive mechanisms, email authentication protocols (SPF, DKIM, DMARC), and user awareness strategies. | [Open Room](https://tryhackme.com/room/phishingemails4gkxh) |
| **5. The Greenholt Phish** | A scenario-based investigation analyzing a targeted phishing attack and extracting actionable IOCs. | [Open Room](https://tryhackme.com/room/phishingemails5fgjlzxc) |
| **6. Snapped Phish-ing Line** | Practical incident triage exercise tracking malicious links, domain reputation checks, and payload delivery. | [Open Room](https://tryhackme.com/room/snappedphishingline) |

---

## 💡 Key Investigation Takeaways
* **Header Forensics:** Learned to read `Received` headers from bottom to top to identify true origin IPs and spot spoofed sender domains.
* **Safe Handling & Defanging:** Practiced neutralizing malicious URLs and hashes using CyberChef before running intelligence checks on VirusTotal or OSINT feeds.
* **Triage Methodology:** Developed a repeatable workflow for assessing email attachments, links, and text patterns to protect enterprise users.