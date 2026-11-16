# 🛡️ TryHackMe Lab: Cyber Defence Frameworks

> A comprehensive portfolio of hands-on investigations exploring core threat intelligence models, defensive frameworks, kill chains, and incident eradication strategies.

---

## 📋 Introduction
Understanding how adversaries operate and how defenders categorize threats is essential for modern security operations. This module explores industry-standard defense frameworks—ranging from indicator valuation models and multi-stage attack lifecycles to advanced mapping matrices and incident eviction strategies—providing a structured approach to threat hunting and detection engineering.

---

## 🏛️ Completed TryHackMe Rooms & Exercises

| Room / Module Name | Core Focus & Concepts Covered | Direct Link |
| :--- | :--- | :--- |
| **1. Pyramid Of Pain** | Analyzing the hierarchy of indicators of compromise (IOCs) from hash values to attacker tactics, techniques, and procedures (TTPs), and understanding the impact of blocking each level. | [Open Room](https://tryhackme.com/room/pyramidofpainax) |
| **2. Cyber Kill Chain** | Examining Lockheed Martin's framework for tracking adversary behavior through sequential phases: Reconnaissance, Weaponization, Delivery, Exploitation, Installation, Command & Control, and Actions on Objectives. | [Open Room](https://tryhackme.com/room/cyberkillchainzmt) |
| **3. Unified Kill Chain** | Exploring the extended 18-phase kill chain model that bridges traditional network attack cycles with modern, complex intrusion vectors across enterprise networks. | [Open Room](https://tryhackme.com/room/unifiedkillchain) |
| **4. Mitre** | Practical mapping of observed adversary tactics and techniques to the MITRE ATT&CK enterprise matrix for threat intelligence and detection rule writing. | [Open Room](https://tryhackme.com/room/mitre) |
| **5. Submit** | Practical exercise focusing on intelligence sharing, artifact submission workflows, and telemetry validation within security frameworks. | [Open Room](https://tryhackme.com/room/summit) |
| **6. Eviction** | Understanding the strategic and technical processes required to remove an established adversary from an enterprise network during incident response. | [Open Room](https://tryhackme.com/room/eviction) |
| **7. Phishing Pond** | Scenario-based analysis linking social engineering attack vectors back to foundational threat intelligence and kill chain phases. | [Open Room](https://tryhackme.com/room/phishingpond) |

---

## 💡 Key Takeaways & Defense Mapping
* **Indicator Value:** Learned why focusing defenses higher up the *Pyramid of Pains* (specifically targeting adversary TTPs rather than just simple hashes or IPs) drastically increases an attacker's operational cost.
* **Lifecycle Tracking:** Leveraged both the classic *Cyber Kill Chain* and *Unified Kill Chain* to identify exact points where intrusion detection systems (IDS) and SIEM rules can disrupt active campaigns.
* **Standardized Taxonomy:** Utilized *MITRE ATT&CK* frameworks to contextualize alerts, transforming raw indicators into actionable threat intelligence for security operations.