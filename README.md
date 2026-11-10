# 🛡️ Introduction to Cybersecurity — Academic Seminar & Slide Deck

> ⚠️ **Disclaimer & Notice:** This technical summary and conceptual documentation are written in English. The original academic presentation was delivered and documented in Serbian (B/C/S) to meet university coursework requirements.  
> 📌 *Direct links to the original `.pptx` slides and `.pdf` files are being updated and will be linked below shortly.*

---

## 📌 Context & Purpose

This repository hosts the academic research, lecture slides, and notes for my seminar project titled **"Introduction to Cybersecurity"** (*Uvod u sajber bezbjednost*).

The materials were created for an **oral university lecture presentation**. Both the original slide deck and comprehensive reference materials are provided here to serve as an accessible reference on fundamental computing and information security principles.

* **Author:** Luka Krstić (Student ID: 210022)
* **Field of Study:** Computer Science / Informatics
* **Format:** University Seminar Paper & Oral Presentation Deck (`.pptx` / `.pdf`)

---

## 📂 Available Materials

The complete visual and document assets are located in the repository directory:
* 📄 **[Download Presentation Deck (.pptx)](presentation/Seminarski%20rad%20-%20Luka%20Krstic%20(Informatika,%20SB).pptx):** The original slide deck used during the oral university presentation.
* 📑 **[View Document (.pdf)](presentation/Seminarski%20rad%20-%20Luka%20Krstic.pdf):** Standalone format for browser preview and reading.

---

## 🧭 Presentation Breakdown (Slide by Slide)

### Slide 1: Title Slide
* **Title:** Introduction to Cybersecurity (*Uvod u sajber bezbjednost*)
* **Author:** Luka Krstić
* **Major:** Informatics / Computer Science

### Slide 2: Table of Contents
* **Structural Modules:**
  1. Concept and Definition of Cybersecurity
  2. The Three Pillars (CIA Triad)
  3. Threats and Attacks
  4. Defense Mechanisms
  5. Ethics and the Future

### Slide 3: Module 01 — Introduction & Concepts
* **Section Title:** 01. Concept and Definition of Cybersecurity
* **Scope:** Defining the parameters of modern defense in the digital era.

### Slide 4: Definition & Scope of Cybersecurity
* **Cybersecurity:** Collective technologies, operational procedures, and policy controls protecting systems and networks.
* **Resource Preservation:** Shielding hardware assets, software applications, and stored data from unauthorized digital compromise.
* **Broader Domain:** Spans network security, application hardening, and data privacy safeguards.
* **The Information Age:** The ongoing transition from physical boundary defense to virtual perimeter security.
* **Strategic Value:** Digital information recognized as the primary capital asset of the 21st century.

### Slide 5: Historical Evolution & Early Precedents (01.1)
* **Origins:** Cryptographic development from classical mechanical cipher disks to digital computation.
* **Alan Turing:** Wartime cryptanalysis and the decryption of the Enigma cipher machine.
* **ARPANET:** Deployment of early distributed networks and emergence of systemic architectural vulnerabilities.
* **The First Worm:** *Creeper* (1971), historically acknowledged as the initial self-replicating network experiment.
* **The First Antivirus Software:** *Reaper*, engineered specifically to seek out and delete Creeper across hosts.

### Slide 6: Historical Perspective Visual
* **Theme:** Archival-themed depiction connecting Turing's mechanical cryptanalysis to modern security terminals.

### Slide 7: The Security Triad (CIA Model) (02)
* **Confidentiality:** Enforcing access controls so records are readable solely by authorized entities.
* **Integrity:** Preserving data authenticity by preventing unapproved modifications or record erasure.
* **Availability:** Guaranteeing system services and network pipelines remain reachable on demand.

### Slide 8: Practical Application of the CIA Triad (02.1)
* **Confidentiality:** Strong symmetric/asymmetric encryption and credential complexity enforcement.
* **Integrity:** Cryptographic hash verification (checksums) and non-repudiation via digital signatures.
* **Availability:** High-availability server clusters, hardware redundancy, and load/traffic management.
* **The Usability Trade-off:** Harmonizing security postures with everyday user access and operational throughput.

### Slide 9: Practical CIA Principles Visual
* **Theme:** Visual representation of host-level multi-factor authentication (2FA) and perimeter encryption.

### Slide 10: Module 03 — Threats and Attacks
* **Section Title:** 03. Threats and Attacks — Network Intrusions and Vulnerabilities
* **Core Groupings:** Malicious Code (Malware) and Human Exploitation (Social Engineering).

### Slide 11: Malware Vectors & Classifications (03.1)
* **Viruses:** Executable strings binding to legitimate binaries and spreading upon host execution.
* **Worms:** Autonomous, self-propagating threats exploiting network daemon vulnerabilities.
* **Trojans:** Misleading payloads masked as trusted applications to bypass endpoint inspection.
* **Ransomware:** Extortion malware executing host-level encryption and demanding currency for decryption keys.
* **Spyware:** Covert surveillance programs capturing keystrokes, user habits, and authentication secrets.

### Slide 12: Malware Threats Visual
* **Theme:** SOC monitoring interface tracking malicious payload activity and host infections.

### Slide 13: Social Engineering & Behavioral Exploits (03.2)
* **The Human Element:** The individual identified as the most fragile link in defensive security architectures.
* **Phishing:** Mass deceptive email campaigns mimicking legitimate service providers and banking portals.
* **Spear Phishing:** Intelligence-driven, customized social engineering aimed at selected organizational personnel.
* **Smishing & Vishing:** Exploitative scams conducted via SMS channels and voice phone calls.
* **Mitigation:** Comprehensive security awareness training, domain validation, and URL header examination.

### Slide 14: Social Engineering Vectors Visual
* **Theme:** Malicious banking prompt on a mobile interface illustrating credential capture.

### Slide 15: Network Infiltration & Protocol Vulnerabilities (03.3)
* **DoS / DDoS Attacks:** Service denial by congesting bandwidth and exhausting computing buffers via botnets.
* **Man-in-the-Middle (MitM):** Active packet eavesdropping and unauthorized session tampering.
* **SQL Injection (SQLi):** Inserting structured database syntax into untrusted inputs to access back-end tables.
* **Insecure Wi-Fi:** Wireless vulnerabilities and eavesdropping over open, unencrypted radio channels.

### Slide 16: Module 04 — Defensive Systems
* **Section Title:** 04. Technical Protection Mechanisms
* **Focus:** Perimeter controls, data encryption, and system administration baselines.

### Slide 17: Technical Protection Mechanisms (04.1)
* **Firewalls:** Boundary appliances monitoring, filtering, and enforcing rules on network traffic.
* **Antivirus & EDR:** Signature and heuristic scanning, quarantine handling, and payload neutralization.
* **Patch Management:** Timely deployment of OS updates to close documented vulnerabilities (CVEs).
* **Backup Strategies:** Redundant data copies distributed off-site or within encrypted cloud storage.

### Slide 18: Cryptographic Protocols & Standards (04.2)
* **Cryptography:** The mathematical discipline of transforming cleartext into structured ciphertext.
* **Symmetric Encryption:** Single shared-key infrastructure utilized for rapid encryption and decryption pipelines.
* **Asymmetric Encryption:** Public/private key pairs enabling secure key exchanges and verifiable digital signatures.
* **HTTPS / TLS:** Transport-layer encryption securing web requests and sensitive session data in transit.
* **Digital Certificates:** Cryptographic tokens proving domain authenticity within Public Key Infrastructure (PKI).

### Slide 19: Identity Verification & Authentication Practices (04.3)
* **Weak Password Risks:** Susceptibility of low-entropy credentials to automated dictionary attacks.
* **High-Entropy Passwords:** Mixed alphanumeric strings with custom symbols resisting brute-force cracking.
* **Password Vaults:** Client-side encrypted software solutions for generating and securing unique secrets.
* **Multi-Factor Authentication (2FA / MFA):** Requiring distinct authentication factors (e.g., OTP or hardware token).

### Slide 20: Ethics, Legal Frameworks, and Emerging Frontiers (05)
* **Cybercrime:** Unauthorized access, credential theft, and financially motivated sabotage.
* **White Hat vs. Black Hat:** Legally authorized vulnerability assessments versus malicious intrusions.
* **Statutory Compliance:** Regulatory standards for data protection and privacy enforcement (e.g., GDPR).
* **Artificial Intelligence (AI):** AI-powered real-time anomaly detection contrasted with automated phishing and deepfakes.
* **Quantum Computing:** Physical semiconductor limits and the emerging algorithmic risk to RSA/ECC, necessitating Post-Quantum Cryptography (PQC).
* **Conclusion:** Cybersecurity is an ongoing lifecycle demanding sustained coordination across technology, regulation, and individual vigilance.

### Slide 21: Artificial Intelligence and Future Threats (05.1)
* **AI in Defense:** Automated real-time intrusion detection, anomaly tracking, and machine-speed response.
* **AI in Offensive Operations:** Automated generation of convincing, tailored spear-phishing messages.
* **Deepfake Technology:** Synthetic media generation (video and cloned voice) utilized in social engineering and fraud schemes.
* **IoT Security:** Securing ubiquitous smart devices, networked home appliances, sensors, and peripherals against compromise.

### Slide 22: Quantum Computing & The Future of Cryptography (Conclusion)
* **Silicon Limits:** Physical scaling and gate boundaries of conventional silicon microprocessors.
* **Quantum Computing:** Qubits and quantum states providing exponential compute acceleration.
* **Cryptographic Disruption:** High-scale quantum processors breaking legacy asymmetric algorithms (RSA, ECC).
* **Post-Quantum Cryptography (PQC):** Engineering and adopting quantum-resistant cryptographic standards.
* **Conclusion:** Cybersecurity is an ongoing lifecycle requiring balanced synergy between technical controls, compliance standards, and user awareness.
