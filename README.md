# chadCmp-
Markdown 
# Strategic Security Engineering & Enterprise Threat Architecture Portfolio

## Executive Profile
Highly disciplined operational leader and security practitioner with a Bachelor of Science in Information Assurance structured around the CIA Triad. Combines 7 years of high-accountability manufacturing team leadership with deep, self-taught expertise in network threat analysis, log telemetry, and offensive exploitation frameworks. Proven history of managing mission-critical operations and optimizing enterprise SIEM platforms to capture advanced threat actor behaviors. Focused entirely on leveraging an attacker's mindset to engineer high-fidelity defensive controls.

---

## Technical Skills Matrix
* **Defensive Engineering**: Centralized Log Management, Detection Engineering, Traffic Analysis, Network Segmentation.
* **SIEM / Analytics Platforms**: AlienVault OSSIM, Open-Source Elastic Architecture (ELK), Splunk Core.
* **Offensive Security / Pen-Testing**: Armitage Framework, Metasploit, Nmap, Network Mapping, Remote Access Exploitation.
* **Malware Research**: Behavioral Monitoring, Persistence Vector Tracking, Command & Control (C2) Identification.
* **Protocols & Architecture**: SMB (445), NetBIOS (139), RPC Parsing, Active Directory Controls, TCP/IP Suite.

---

## Professional Leadership Milestone
### Manufacturing Team Lead | Public Safety & Enforcement Systems (2019 – Present)
* **Operational Command**: Direct a high-output assembly and manufacturing team responsible for building critical emergency lighting and siren arrays utilized nationally by law enforcement and public safety vehicles.
* **Zero-Failure Standards**: Enforce rigorous quality assurance (QA) frameworks and technical compliance metrics, ensuring absolute hardware reliability for first responders in high-stress field scenarios.
* **Resource Optimization**: Manage cross-functional team scheduling, training programs, and resource allocation while accurately bridging the gap between engineering blueprints and physical output.

---

## Core Technical Projects

### Project 1: Isolated Enterprise SIEM & Telemetry Lab
* **Objective**: Designed and deployed a multi-zone virtual infrastructure to aggregate enterprise telemetry and test alert structures against modern lateral movement patterns.
* **Deployment Architecture**:
  * Managed network choke points using dedicated routing segments to separate production telemetry from attack zones.
  * Configured **AlienVault OSSIM** to serve as the centralized logging authority across diverse endpoints.
* **Log Ingestion & Parsing**:
  * Implemented structured endpoint logging on Windows assets by deploying Microsoft Sysmon optimized with advanced event filtering.
  * Integrated network-layer intrusion detection systems (Suricata/Snort) via mirrored virtual switch interfaces to intercept live traffic.

### Project 2: Legacy OS Memory Corruption Analysis
* **Objective**: Analyzed network-level exploitation vectors against unpatched legacy systems to evaluate historical shifts in operating system security.
* **Attack Scenario Execution**:
  * Conducted focused scanning via `nmap` against an isolated **Windows XP SP2** target to map active Server Service protocols on Port 445.
  * Executed remote code execution (RCE) via the historical **MS08-067 (NetAPI)** vulnerability using the Armitage/Metasploit pipeline.
  * Demonstrated architectural memory corruption concepts by exploiting the path-parsing buffer overflow within `netapi32.dll` to return a SYSTEM-level shell.
* **Defensive Reconstruction**:
  * Evaluated how modern architectural controls—specifically **ASLR** (Address Space Layout Randomization) and **DEP** (Data Execution Prevention)—effectively neutralize this entire class of memory corruption exploits in current enterprise operating systems.

### Project 3: Post-Exploitation Process Injection & Keylogging Analysis
* **Objective**: Tracked the digital footprint of host-level process hijacking to identify clear Indicators of Compromise (IOCs).
* **Execution & Migration**:
  * Stabilized an active reverse TCP Meterpreter payload inside Armitage by migrating the execution thread out of volatile initial access spaces into persistent userland processes (`explorer.exe`).
  * Initialized kernel-level keyboard hooks via Meterpreter's `keyscan_start` subsystem to monitor input stream modifications.
* **Detection Engineering (The Blue Team Fix)**:
  * Isolated **Sysmon Event ID 8 (CreateRemoteThread)** as the primary telemetry warning sign for unauthorized process injection.
  * Engineered predictive SIEM correlation rules designed to trigger instant high-severity alerts when untrusted binaries invoke Windows input APIs (`SetWindowsHookExA`).

---

## Career Milestones & Historical Trust Metrics
* **Early Infrastructure Administration (Y2K Era)**: Selected for trusted hardware deployment and asset distribution duties within state corrections facilities under the direction of the Principal IT Systems Administrator (Toan). Maintained physical responsibility for the transportation, imaging (Symantec Ghost), and setup of administration-level workstations.
* **Academic Foundation**: Completed a Bachelor of Science Degree in Information Assurance, mastering data confidentiality, structural system integrity, and asset availability standards.
