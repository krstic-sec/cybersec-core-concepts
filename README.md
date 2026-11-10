# 🛡️ Introduction to Cybersecurity — Academic Seminar & Slide Deck

> ⚠️ **Disclaimer & Language Notice:** This technical summary and conceptual documentation are written in English for international accessibility. However, the original research paper, slide deck, and presentation notes were **conducted and documented in Serbian (B/C/S) to meet university coursework requirements**[cite: 1].

---

## 📌 Context & Purpose

This repository hosts the academic research, lecture slides, and notes for my seminar project titled **"Introduction to Cybersecurity"** (*Uvod u sajber bezbjednost*)[cite: 1].

The materials were created for an **oral university lecture presentation**[cite: 1]. Both the original slide deck and comprehensive reference materials are provided here to serve as an accessible reference on fundamental computing and information security principles[cite: 1].

* **Author:** Luka Krstić (Student ID: 210022)[cite: 1]
* **Field of Study:** Computer Science / Informatics[cite: 1]
* **Format:** University Seminar Paper & Oral Presentation Deck (`.pptx` / `.pdf`)[cite: 1]

---

## 📂 Available Materials

The complete visual and document assets are located in the repository directory[cite: 1]:
* 📄 **[Download Presentation Deck (.pptx)](presentation/Seminarski%20rad%20-%20Luka%20Krstic%20(Informatika,%20SB).pptx):** The original slide deck used during the oral university presentation[cite: 1].
* 📑 **[View Document (.pdf)](presentation/Seminarski%20rad%20-%20Luka%20Krstic.pdf):** Standalone format for browser preview and reading[cite: 1].

---

## 🧭 Presentation Breakdown (Slide by Slide)

### Slide 1: Title Slide
* **Title:** Introduction to Cybersecurity (*Uvod u sajber bezbjednost*)[cite: 1]
* **Author:** Luka Krstić[cite: 1]
* **Major:** Informatics / Computer Science[cite: 1]

### Slide 2: Table of Contents
* **Structural Modules:**[cite: 1]
  1. Concept and Definition of Cybersecurity[cite: 1]
  2. The Three Pillars (CIA Triad)[cite: 1]
  3. Threats and Attacks[cite: 1]
  4. Defense Mechanisms[cite: 1]
  5. Ethics and the Future[cite: 1]

### Slide 3: Module 01 — Introduction & Concepts
* **Section Title:** 01. Concept and Definition of Cybersecurity[cite: 1]
* **Scope:** Defining the parameters of modern defense in the digital era[cite: 1].

### Slide 4: Definition & Scope of Cybersecurity
* **Cybersecurity:** Collective technologies, operational procedures, and policy controls protecting systems and networks[cite: 1].
* **Resource Preservation:** Shielding hardware assets, software applications, and stored data from unauthorized digital compromise[cite: 1].
* **Broader Domain:** Spans network security, application hardening, and data privacy safeguards[cite: 1].
* **The Information Age:** The ongoing transition from physical boundary defense to virtual perimeter security[cite: 1].
* **Strategic Value:** Digital information recognized as the primary capital asset of the 21st century[cite: 1].

### Slide 5: Historical Evolution & Early Precedents (01.1)
* **Origins:** Cryptographic development from classical mechanical cipher disks to digital computation[cite: 1].
* **Alan Turing:** Wartime cryptanalysis and the decryption of the Enigma cipher machine[cite: 1].
* **ARPANET:** Deployment of early distributed networks and emergence of systemic architectural vulnerabilities[cite: 1].
* **The First Worm:** *Creeper* (1971), historically acknowledged as the initial self-replicating network experiment[cite: 1].
* **The First Antivirus Software:** *Reaper*, engineered specifically to seek out and delete Creeper across hosts[cite: 1].

### Slide 6: Historical Perspective Visual
* **Theme:** Archival-themed depiction connecting Turing's mechanical cryptanalysis to modern security terminals[cite: 1].

### Slide 7: The Security Triad (CIA Model) (02)
* **Confidentiality:** Enforcing access controls so records are readable solely by authorized entities[cite: 1].
* **Integrity:** Preserving data authenticity by preventing unapproved modifications or record erasure[cite: 1].
* **Availability:** Guaranteeing system services and network pipelines remain reachable on demand[cite: 1].

### Slide 8: Practical Application of the CIA Triad (02.1)
* **Confidentiality:** Strong symmetric/asymmetric encryption and credential complexity enforcement[cite: 1].
* **Integrity:** Cryptographic hash verification (checksums) and non-repudiation via digital signatures[cite: 1].
* **Availability:** High-availability server clusters, hardware redundancy, and load/traffic management[cite: 1].
* **The Usability Trade-off:** Harmonizing security postures with everyday user access and operational throughput[cite: 1].

### Slide 9: Practical CIA Principles Visual
* **Theme:** Visual representation of host-level multi-factor authentication (2FA) and perimeter encryption[cite: 1].

### Slide 10: Module 03 — Threats and Attacks
* **Section Title:** 03. Threats and Attacks — Network Intrusions and Vulnerabilities[cite: 1]
* **Core Groupings:** Malicious Code (Malware) and Human Exploitation (Social Engineering)[cite: 1].

### Slide 11: Malware Vectors & Classifications (03.1)
* **Viruses:** Executable strings binding to legitimate binaries and spreading upon host execution[cite: 1].
* **Worms:** Autonomous, self-propagating threats exploiting network daemon vulnerabilities[cite: 1].
* **Trojans:** Misleading payloads masked as trusted applications to bypass endpoint inspection[cite: 1].
* **Ransomware:** Extortion malware executing host-level encryption and demanding currency for decryption keys[cite: 1].
* **Spyware:** Covert surveillance programs capturing keystrokes, user habits, and authentication secrets[cite: 1].

### Slide 12: Malware Threats Visual
* **Theme:** SOC monitoring interface tracking malicious payload activity and host infections[cite: 1].

### Slide 13: Social Engineering & Behavioral Exploits (03.2)
* **The Human Element:** The individual identified as the most fragile link in defensive security architectures[cite: 1].
* **Phishing:** Mass deceptive email campaigns mimicking legitimate service providers and banking portals[cite: 1].
* **Spear Phishing:** Intelligence-driven, customized social engineering aimed at selected organizational personnel[cite: 1].
* **Smishing & Vishing:** Exploitative scams conducted via SMS channels and voice phone calls[cite: 1].
* **Mitigation:** Comprehensive security awareness training, domain validation, and URL header examination[cite: 1].

### Slide 14: Social Engineering Vectors Visual
* **Theme:** Malicious banking prompt on a mobile interface illustrating credential capture[cite: 1].

### Slide 15: Network Infiltration & Protocol Vulnerabilities (03.3)
* **DoS / DDoS Attacks:** Service denial by congesting bandwidth and exhausting computing buffers via botnets[cite: 1].
* **Man-in-the-Middle (MitM):** Active packet eavesdropping and unauthorized session tampering[cite: 1].
* **SQL Injection (SQLi):** Inserting structured database syntax into untrusted inputs to access back-end tables[cite: 1].
* **Insecure Wi-Fi:** Wireless vulnerabilities and eavesdropping over open, unencrypted radio channels[cite: 1].

### Slide 16: Module 04 — Defensive Systems
* **Section Title:** 04. Technical Protection Mechanisms[cite: 1]
* **Focus:** Perimeter controls, data encryption, and system administration baselines[cite: 1].

### Slide 17: Technical Protection Mechanisms (04.1)
* **Firewalls:** Boundary appliances monitoring, filtering, and enforcing rules on network traffic[cite: 1].
* **Antivirus & EDR:** Signature and heuristic scanning, quarantine handling, and payload neutralization[cite: 1].
* **Patch Management:** Timely deployment of OS updates to close documented vulnerabilities (CVEs)[cite: 1].
* **Backup Strategies:** Redundant data copies distributed off-site or within encrypted cloud storage[cite: 1].

### Slide 18: Cryptographic Protocols & Standards (04.2)
* **Cryptography:** The mathematical discipline of transforming cleartext into structured ciphertext[cite: 1].
* **Symmetric Encryption:** Single shared-key infrastructure utilized for rapid encryption and decryption pipelines[cite: 1].
* **Asymmetric Encryption:** Public/private key pairs enabling secure key exchanges and verifiable digital signatures[cite: 1].
* **HTTPS / TLS:** Transport-layer encryption securing web requests and sensitive session data in transit[cite: 1].
* **Digital Certificates:** Cryptographic tokens proving domain authenticity within Public Key Infrastructure (PKI)[cite: 1].

### Slide 19: Identity Verification & Authentication Practices (04.3)
* **Weak Password Risks:** Susceptibility of low-entropy credentials to automated dictionary attacks[cite: 1].
* **High-Entropy Passwords:** Mixed alphanumeric strings with custom symbols resisting brute-force cracking[cite: 1].
* **Password Vaults:** Client-side encrypted software solutions for generating and securing unique secrets[cite: 1].
* **Multi-Factor Authentication (2FA / MFA):** Requiring distinct authentication factors (e.g., OTP or hardware token)[cite: 1].

### Slide 20: Ethics, Legal Frameworks, and Emerging Frontiers (05)
* **Cybercrime:** Unauthorized access, credential theft, and financially motivated sabotage[cite: 1].
* **White Hat vs. Black Hat:** Legally authorized vulnerability assessments versus malicious intrusions[cite: 1].
* **Statutory Compliance:** Regulatory standards for data protection and privacy enforcement (e.g., GDPR)[cite: 1].
* **Artificial Intelligence (AI):** AI-powered real-time anomaly detection contrasted with automated phishing and deepfakes[cite: 1].
* **Quantum Computing:** Physical semiconductor limits and the emerging algorithmic risk to RSA/ECC, necessitating Post-Quantum Cryptography (PQC)[cite: 1].
* **Conclusion:** Cybersecurity is an ongoing lifecycle demanding sustained coordination across technology, regulation, and individual vigilance[cite: 1].
