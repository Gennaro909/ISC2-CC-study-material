# CC – Chapter 1 Lecture Notes

## Overview
This chapter is **foundational**. Every other knowledge domain builds on it.

### Topics Covered
- Information Security vs IT Security vs Cybersecurity  
- CIA Triad and IAAA  
- Privacy  
- Risk and Incident Management  
- Access Control  
- Governance, Laws, and Regulations  
- (ISC)² Ethics  

---

## Information Security vs IT Security vs Cybersecurity
- **Information Security**: All information (paper, voice, data, knowledge).  
- **IT Security**: Hardware, software, firmware, networks, and data.  
- **Cybersecurity**: IT security components accessible via the internet.  

---

## CIA Triad
### Confidentiality
- Prevents unauthorized access to data.  
- Controls: encryption, MFA, access control, least privilege.  
- Threats: cryptanalysis, social engineering, keyloggers, IoT risks.  

### Integrity
- Ensures data is accurate and unaltered.  
- Controls: hashing, checksums, digital signatures, access control.  
- Threats: data alteration, code injection.  

### Availability
- Ensures systems and data are accessible when needed.  
- Controls: redundancy, patching, IDS/IPS, SLAs.  
- Threats: DDoS, hardware failure, application errors.  

### DAD Model (Opposite of CIA)
- Disclosure  
- Alteration  
- Destruction  

---

## IAAA
### Identification
- Claiming an identity (username, ID).  

### Authentication
- Verifying identity using:
  - Something you know (passwords, PINs)  
  - Something you have (tokens, smart cards)  
  - Something you are (biometrics)  

### Authorization
- Defines what resources a user can access.  
- Principles: least privilege, need to know.  

### Accountability
- Traces actions to individuals.  
- Uses logging, auditing, and non-repudiation.  

---

## Access Control Models
- **DAC**: Owner-controlled access.  
- **MAC**: Label and clearance-based.  
- **RBAC**: Role-based permissions.  
- **ABAC**: Attributes, environment, and policy-based.  
- **Context-Based**: Location, time, behavior.  
- **Content-Based**: Data attributes determine access.  

---

## Privacy
- Privacy is a human right.  
- PII must be protected.  
- US privacy laws are fragmented.  
- EU privacy laws (GDPR) are strict and comprehensive.  

---

## Risk Management
### Risk Formula
- Risk = Threat × Vulnerability × Impact  
- Residual Risk = Total Risk − Controls  

### Risk Responses
- Accept  
- Mitigate  
- Transfer  
- Avoid  
- Reject (never acceptable)  

### Risk Analysis
- **Qualitative**: Likelihood vs impact.  
- **Quantitative**: Financial cost (SLE, ALE).  

---

## Access Control Categories
- Administrative  
- Technical  
- Physical  

### Control Types
- Preventive  
- Detective  
- Corrective  
- Recovery  
- Deterrent  
- Compensating  

---

## Governance vs Management
- **Governance**: Direction set by executives, risk appetite.  
- **Management**: Execution and operational control.  

### C-Level Roles
- CEO, CIO, CTO, CSO, CISO, CFO  

---

## Policies and Documentation
- Policies (mandatory, high-level)  
- Standards (mandatory, specific)  
- Guidelines (recommended)  
- Procedures (mandatory, step-by-step)  

---

## Laws and Regulations
- Criminal Law  
- Civil Law  
- Administrative Law  
- Private Regulations (e.g., PCI-DSS)  

### Key Regulations
- HIPAA  
- CFAA  
- ECPA  
- PATRIOT Act  
- PCI-DSS  
- GDPR  

---

## Ethics
### (ISC)² Code of Ethics
- Protect society and infrastructure  
- Act legally and responsibly  
- Provide competent service  
- Advance the profession  

### Organizational Ethics
- Know and follow your organization’s code of ethics.  

---

## Summary
This chapter covered:
- Security domains  
- CIA Triad and IAAA  
- Privacy  
- Risk Management  
- Access Control  
- Governance and Ethics



# CC – Chapter 2 Lecture Notes  
Business Continuity, Disaster Recovery, and Incident Management

---

## Overview
This chapter focuses on how organizations **prepare for, respond to, and recover from disruptive events**. It introduces Business Continuity Planning (BCP), Disaster Recovery Planning (DRP), and Incident Management.

### Domain 2 Topics
- Business Continuity Planning (BCP)
- Disaster Recovery Planning (DRP)
- Incident Management

---

## Business Continuity Plan (BCP)

### Definition
The Business Continuity Plan is the **overarching, long-term strategic plan** that defines how an organization continues operations after a disruptive event.

### Key Characteristics
- Covers the **entire organization**, not just IT
- Includes policies, procedures, and plans for continued operation
- Addresses multiple disaster scenarios
- Written in advance and continuously improved
- Developed with input from key staff and sometimes external consultants

### Common Scenarios
- Critical supplier failure
- Natural disasters (earthquake, flood)
- Facility inaccessibility
- Workforce unavailability

### Related Plans within BCP
- COOP (Continuity of Operations Plan)
- Disaster Recovery Plan (DRP)
- Cyber Incident Response Plan
- Crisis Management Plan (CMP)
- Crisis Communications Plan
- Occupant Emergency Plan (OEP)
- Business Recovery Plan (BRP)
- Information System Contingency Plan (ISCP)
- Continuity of Support Plan

---

## Senior Management Involvement
- Senior management must sponsor, approve, and own BCP/DRP
- They are legally liable and must demonstrate due care and due diligence
- They set priorities and approve recovery strategies
- Only authorized leadership or legal representatives communicate with the press during crises

---

## Emergency Operations Center (EOC)
- Central command and control facility during emergencies
- Coordinates disaster response and recovery
- Often located offsite and in a secure area

---

## BCP and DRP Lifecycle (NIST 800-34 Framework)
1. Project Initiation
2. Scope Definition
3. Business Impact Analysis (BIA)
4. Preventive Controls Identification
5. Recovery Strategy
6. Plan Development
7. Implementation, Training, and Testing
8. Maintenance and Continuous Improvement

BCP and DRP are **iterative processes** and must be updated regularly.

---

## Disaster Categories
- **Natural**: Earthquakes, floods, storms
- **Human**: Malware, terrorism, sabotage, human error
- **Environmental**: Power outages, hardware failure, provider issues

---

## Disaster Recovery Plan (DRP)

### Definition
The DRP focuses on **short-term recovery of critical IT systems** following a disaster. It is a subset of the BCP.

### DRP Core Questions
- What is the objective?
- Who is responsible?
- What procedures must be followed?

### DRP Lifecycle
- Mitigation
- Preparation
- Response
- Recovery

---

## Testing Disaster Recovery Plans

### Simulated Tests
- Plan Review
- Read-Through Checklist
- Tabletop (Walkthrough)
- Simulation Test

### Physical Tests
- Partial interruption
- Application failover testing

---

## Business Impact Analysis (BIA)

### Purpose
Identifies critical systems, processes, and functions and prioritizes them based on impact.

### Key Metrics
- RPO (Recovery Point Objective)
- RTO (Recovery Time Objective)
- MTD (Maximum Tolerable Downtime)
- WRT (Work Recovery Time)
- MTBF (Mean Time Between Failures)
- MTTR (Mean Time to Repair)
- MOR (Minimum Operating Requirements)

---

## Recovery Strategies

- Redundant Site (most expensive, near-zero downtime)
- Hot Site
- Warm Site
- Cold Site
- Reciprocal Agreement Site
- Subscription / Cloud Site
- Mobile Site

Recovery strategy selection depends on **MTD, cost, and risk tolerance**.

---

## Lessons Learned
- Conducted after incidents or tests
- Focus on improvement, not blame
- Feeds back into BCP and DRP updates
- Identifies gaps, control failures, and process improvements

---

## Incident Management

### Purpose
Provides a **structured, predictable response** to security events and incidents.

### Key Concepts
- Event: Observable change
- Alert: Triggered warning
- Incident: Adverse event
- Problem: Incident with unknown root cause
- Disaster: Facility unusable for 24+ hours
- Catastrophe: Facility destroyed

---

## Incident Categories
- Natural
- Human (intentional and unintentional)
- Environmental

---

## Incident Response Lifecycle (NIST 800-61)

1. Preparation
2. Detection
3. Response
4. Mitigation
5. Reporting
6. Recovery
7. Remediation
8. Lessons Learned

---

## Cyber Incident Response Team (CIRT)
- Senior management
- Incident manager
- Technical teams
- IT Security
- Legal, HR, PR
- Auditors

---

## Root Cause Analysis
- Identifies underlying weaknesses
- Prevents recurrence
- Fixes vulnerabilities across the organization
- Essential for long-term security improvement

---

## Common BCP/DRP Pitfalls
- Lack of executive support
- Scope too narrow
- Poor version control
- Plans not kept current

Plans should be reviewed and updated **at least annually**.

---

## Domain 2 Summary
- BCP is the overarching continuity strategy
- DRP focuses on IT system recovery
- Incident Management ensures structured response to security events
- All plans are iterative and require executive support


# CC – Chapter 3 Lecture Notes  
Access Control, Physical Security, and Identity Management

---

## Overview
This chapter covers **how organizations control access** to people, facilities, systems, and data. It focuses on **physical, technical, and administrative controls**, access control models, and identity lifecycle management.

### Domain 3 Topics
- Physical Security Controls  
- Technical (Logical) Security Controls  
- Access Control Categories and Types  
- Identity and Access Management (IAM)  
- Authorization Models  
- Administrative Security Controls  

---

## Access Control Categories

### Administrative (Directive) Controls
- Policies and procedures  
- Regulations and compliance requirements  
- Security awareness and training  

### Technical (Logical) Controls
- Hardware, software, and firmware controls  
- Firewalls, routers, encryption, IDS/IPS  

### Physical Controls
- Locks, fences, guards, dogs, gates, bollards  

---

## Access Control Types
Many controls fall into more than one category; exam questions rely on **context**.

### Preventive
Prevents an incident from occurring.  
Examples: least privilege, firewalls, IPS, encryption, drug testing.

### Detective
Detects incidents during or after occurrence.  
Examples: IDS, CCTV, alarms, antivirus.

### Corrective
Corrects issues after detection.  
Examples: patching, antivirus remediation, IPS blocking.

### Recovery
Restores systems after an incident.  
Examples: backups, disaster recovery environments, high availability.

### Deterrent
Discourages attacks.  
Examples: fences, lighting, guards, warning signs.

### Compensating
Alternative controls when primary controls are impractical or too costly.

---

## Physical Security Controls

### Perimeter Defense

#### Fences
- Serve as deterrent and preventive controls  
- Short fences deter; tall fences prevent access  
- Funnel entry through controlled points  

#### Gates
- Installed at perimeter control points  
- Classified by ASTM standards:
  - Class I: Residential  
  - Class II: Commercial  
  - Class III: Industrial  
  - Class IV: Restricted (airports, prisons)

#### Bollards
- Prevent vehicle access while allowing foot traffic  
- Can be static or electronically controlled  

#### Lighting
- Acts as deterrent and detective control  
- Static, motion-activated, or searchlights  
- Measured in lumens or lux  

#### CCTV
- Detective and deterrent control  
- Analog (legacy) vs digital (CCD with DVR)  
- Retention requirements may apply  
- Static or pan-tilt-zoom cameras  

---

## Locks and Access Devices

### Key Locks
- Physical keys; vulnerable to copying and picking  
- Pin tumbler (Yale) locks  
- Lock picking and lock bumping risks  
- Master keys require strict control  
- Interchangeable core locks use control keys  

### Combination Locks
- Low security and weak accountability  
- Dial, button, or keypad-based  
- Susceptible to brute force and shoulder surfing  

### Smart Cards
- Integrated Circuit Cards (ICC)  
- Contact and contactless (RFID-based)  

### Magnetic Stripe Cards
- No embedded circuit  
- Easy to clone  

---

## Entry Control Mechanisms

### Tailgating / Piggybacking
- Unauthorized entry by following an authorized user  
- Often combined with social engineering  

### Mantraps
- Two-door system; one must close before the other opens  
- Multiple authentication factors  
- May use weight sensors and cameras  

### Turnstiles
- Allow one person per authentication  
- Prevent tailgating  
- Must support emergency evacuation  

---

## Detection and Alarm Systems

### Motion Detectors
- Light-based, ultrasonic, microwave, infrared, laser  
- Active sensors detect changes in returned signals  

### Perimeter Alarms
- Door and window sensors  
- Layered defense approach  

### Structural Security
- Secure walls, floors, and ceilings  
- Slab-to-slab construction  
- Fire-rated materials  

---

## Guards and Monitoring

### Security Guards
- Preventive, detective, deterrent, compensating  
- Professional, amateur, or pseudo guards  
- Require clear rules and training  

### Dogs
- Used in controlled environments  
- Deterrent and detective control  
- Liability considerations  

---

## Restricted Areas and Escorts
- Visitor badges, logs, and escorts  
- Badge return enforcement  
- Vendors must be escorted at all times  

---

## Site Selection and Facility Design

### Data Centers and Server Rooms
- Must support current and future needs  
- HVAC, power, and environmental risks  
- Avoid poorly designed “bolt-on” server rooms  

---

## Identity and Access Management (IAM)

### Identity Concepts
- Entities can have multiple identities and attributes  
- Access varies by role and context  

### Identity Lifecycle Management
- Account provisioning and deprovisioning  
- Password compliance  
- Inactive account detection  
- Contractor and vendor access revocation  

---

## Federated Identity
- Links identities across multiple systems  
- Federated Identity Management (FIDM)  
- Single Sign-On (SSO) as a subset  

---

## Access Control Systems

### Centralized vs Decentralized
- Centralized: consistent policy, easier management, stronger security  
- Decentralized: faster response, less dependency on connectivity  
- Hybrid models combine both  

### Role-Based Access Control (RBAC)
- Most commonly used  
- Permissions assigned to roles  
- Supports separation of duties and prevents privilege creep  

---

## Authorization Models

### Discretionary Access Control (DAC)
- Owner controls access  
- Uses discretionary ACLs  
- Prioritizes availability  

### Mandatory Access Control (MAC)
- Based on labels and clearances  
- Used when confidentiality is critical  

### Role-Based Access Control (RBAC)
- Access based on job roles  
- Simplifies administration  

### Attribute-Based Access Control (ABAC)
- Access based on subject, object, and environment attributes  

### Context-Based Access Control
- Location, time, device, or behavior-based  

### Content-Based Access Control
- Access determined by data classification or content  

---

## Core Security Principles
- Least Privilege  
- Need to Know  
- Separation of Duties  

---

## Administrative Security Controls

### Job Rotation
- Detects fraud and errors  
- Reduces burnout  

### Mandatory Vacations
- Forces task separation  
- Enables auditing  

### Non-Disclosure Agreements (NDAs)
- Protect confidential information  

### Background Checks
- Employment, education, criminal, credit  
- Continuous for sensitive roles  

### Privilege Monitoring
- Increased monitoring for high-privilege users  

---

## Domain 3 Summary
- Physical, technical, and administrative controls work together  
- Access control models enforce confidentiality, integrity, and availability  
- IAM ensures proper provisioning, monitoring, and revocation of access  


# CC – Chapter 4 Lecture Notes  
Networking, Infrastructure, Attacks, and Resilience

---

## Overview
Domain 4 is the **largest CC domain**, covering networking fundamentals, communication models, infrastructure, attacks, and fault tolerance. It focuses on **how data moves**, **how networks are built**, and **how they are attacked and protected**.

### Domain 4 Topics
- Network basics and definitions  
- OSI & TCP/IP models  
- IP, ports, and MAC addresses  
- Wireless and Wi-Fi technologies  
- Attacks and attackers  
- IDS/IPS, firewalls, SIEM/SOAR  
- Virtualization, cloud, and distributed systems  
- Fault tolerance, backups, and redundancy  
- Secure design principles  

---

## Network Basics

### What Is Networking
- A network is a group of computers sharing data or resources  
- Defense-in-depth applies to internal and external networks  

### Communication Types
- **Simplex**: One-way communication  
- **Half-duplex**: Send or receive (one at a time)  
- **Full-duplex**: Send and receive simultaneously  

### Network Transmission
- **Baseband**: Single channel (Ethernet)  
- **Broadband**: Multiple channels (Internet)  

### Network Types
- **PAN**: Personal Area Network  
- **LAN**: Local Area Network  
- **MAN**: Metropolitan Area Network  
- **WAN**: Wide Area Network  
- **GAN**: Global Area Network  
- **VPN**: Secure tunnel over public networks  

### Switching
- **Circuit Switching**: Dedicated path, guaranteed bandwidth  
- **Packet Switching**: Shared paths, no guarantee (QoS can prioritize traffic)  

---

## OSI Model (7 Layers)

1. **Physical** – Cables, signals, hubs  
2. **Data Link** – MAC addresses, switches  
3. **Network** – IP addressing, routing  
4. **Transport** – TCP / UDP  
5. **Session** – Session setup and teardown  
6. **Presentation** – Encryption, compression  
7. **Application** – User-facing protocols  

Mnemonic: *Please Do Not Throw Sausage Pizza Away*

### Common Threats by Layer
- Layers 1–3: Sniffing, spoofing, flooding  
- Layers 4–7: Malware, exploits, application attacks  

---

## TCP/IP Model

### Layers
- **Link** (OSI 1–2)  
- **Internet** (OSI 3)  
- **Transport** (OSI 4)  
- **Application** (OSI 5–7)  

### Key Concepts
- Encapsulation and de-encapsulation  
- TCP = reliable, connection-oriented  
- UDP = fast, connectionless  

---

## Addressing

### MAC Addresses
- 48-bit (EUI-48) or 64-bit (EUI-64)  
- Can be spoofed  

### IP Addresses
- **IPv4**: 32-bit, limited address space  
- **IPv6**: 128-bit, massive address space, IPSec built-in  

### IP Classes
- Public IPs: Internet routable  
- Private IPs (RFC 1918):  
  - 10.0.0.0/8  
  - 172.16.0.0/12  
  - 192.168.0.0/16  

### Ports
- 0–1023: Well-known  
- 1024–49151: Registered  
- 49152–65535: Ephemeral  

Common Ports:
- 22 SSH  
- 80 HTTP  
- 443 HTTPS  
- 3389 RDP  

---

## IP Support Protocols
- **ARP**: IP → MAC resolution (vulnerable to poisoning)  
- **ICMP**: Ping, traceroute  
- **DHCP**: Automatic IP assignment  

---

## Network Media

### Copper
- UTP and STP  
- Vulnerable to EMI, attenuation, crosstalk  

### Fiber
- Faster, longer distance, more secure  
- Single-mode and multi-mode  

---

## LAN Topologies
- **Bus**: Unstable, single break fails network  
- **Star**: Most common, fault-tolerant  
- **Ring**: Rare today  
- **Mesh**: High availability and redundancy  

---

## Wireless Networks

### Wi-Fi
- IEEE 802.11 standards  
- Easier to compromise than wired networks  

### Wi-Fi Attacks
- Rogue APs  
- Evil Twins  
- Jamming / interference  

### Bluetooth
- Short-range PAN  
- Vulnerable to bluejacking, bluesnarfing, bluebugging  

### Other Wireless
- **Li-Fi**: Light-based data transfer  
- **Zigbee**: Low power IoT mesh  
- **Cellular**: 3G, 4G, 5G  
- **Satellite**: High latency, improving with Starlink  

---

## Attacks and Attackers

### Attacker Types
- White Hat  
- Black Hat  
- Grey Hat  
- Script Kiddies  

### Threat Sources
- **Outsiders**: Majority of attacks  
- **Insiders**: Authorized misuse  
- **Hacktivists**  
- **Nation States**  

### Botnets
- Compromised systems controlled via C2 servers  

---

## Malware
- **Viruses**: Require user action  
- **Worms**: Self-propagating  
- **Trojans**: Malicious code hidden in legit software  
- **RATs**: Full remote control  

---

## IDS, IPS, and Monitoring

### IDS
- Detects attacks  
- Generates alerts only  

### IPS
- Detects and blocks attacks  

### Detection Methods
- Signature-based  
- Heuristic (behavior-based)  
- Hybrid  

### Alert Types
- True Positive / True Negative  
- False Positive / False Negative  

### SIEM & SOAR
- **SIEM**: Centralized log correlation  
- **SOAR**: Automated incident response  

---

## Firewalls

### Types
- Packet filtering (L1–3)  
- Stateful (L1–4)  
- Application-layer (L7)  
- Next-generation firewalls (NGFW)  

### Deployment
- Network-based  
- Host-based  
- DMZ architectures  

---

## Virtualization & Cloud

### Virtualization
- Multiple VMs on one host  
- Type 1 (bare metal) vs Type 2 hypervisors  
- Risks: VM escape, resource exhaustion  

### Cloud Models
- Private  
- Public  
- Hybrid  
- Community  

### Cloud Services
- **IaaS**  
- **PaaS**  
- **SaaS**  

---

## Distributed Computing
- Distributed systems appear as one service  
- Includes HPC, edge computing, CDNs  

---

## Fault Tolerance & Resilience

### Power Protection
- Surge protectors  
- UPS  
- Generators  

### Backups
- Full  
- Incremental  
- Differential  
- Copy  

### Redundancy
- RAID 0, 1, 5  
- Clustering  
- Load balancing  
- Geographic redundancy  

---

## Fire Suppression
- Remove oxygen, heat, or fuel  
- Water, gas-based systems, extinguishers  
- PASS method  

---

## Secure Design Principles
- Least Privilege  
- Need to Know  
- Separation of Duties  
- Defense in Depth  
- Secure Defaults  
- Fail Securely  
- Zero Trust  
- Privacy by Design  
- Shared Responsibility  

---

## Domain 4 Summary
- Networking fundamentals underpin security  
- Attacks target every OSI layer  
- Defense requires layered controls  
- Availability depends on redundancy and resilience  
- Secure design principles guide all architectures

# CC – Chapter 5 Lecture Notes  
Security Operations, Cryptography, Data Handling, and Human Risk

---

## Overview
Domain 5 focuses on **day-to-day security operations**. It covers how organizations **secure systems, data, and people** through cryptography, configuration management, governance, and user awareness.

### Domain 5 Topics
- Configuration, patch, and change management  
- Cryptography and hashing  
- Attacks on cryptographic systems  
- Data handling, classification, retention, and disposal  
- Administrative (directive) controls  
- Security awareness and training  
- Social engineering  

---

## Cryptography

### Purpose of Cryptography
Cryptography supports:
- **Confidentiality** – keeping data secret  
- **Integrity** – ensuring data is not altered  
- **Authentication** – verifying identity  
- **Non-repudiation** – preventing denial of actions  

### Key Definitions
- **Cryptology**: Science of secure communication  
- **Cryptography**: Creating secure messages  
- **Cryptanalysis**: Breaking encryption  
- **Cipher**: Cryptographic algorithm  
- **Plaintext**: Unencrypted data  
- **Ciphertext**: Encrypted data  

### Historical Ciphers (Testable)
- **Spartan Scytale** – Transposition cipher  
- **Caesar Cipher** – Substitution cipher  

---

## Encryption Types

### Symmetric Encryption
- Single shared key  
- Fast and strong per bit  
- Key distribution is difficult at scale  

### Asymmetric Encryption
- Public and private key pair  
- Slower, weaker per bit  
- No pre-shared secret required  

### Hybrid Encryption
- Asymmetric encryption exchanges a session key  
- Symmetric encryption handles data transfer  
- Used in TLS/HTTPS  

---

## Hashing

### Hash Functions
- One-way functions used for **integrity**
- Fixed-length output (message digest)
- Small data changes result in entirely different hashes  

### Key Concepts
- **Collision**: Two inputs produce the same hash (rare)  
- Hashing is not encryption and cannot be reversed  

---

## Attacks on Cryptography

### Common Attacks
- **Key theft** – Stealing private keys  
- **Brute force** – Trying all possible keys  
- **Man-in-the-Middle (MITM)** – Intercepting communication  
- **Side-channel attacks** – Using power, timing, or hardware data  

### Defensive Techniques
- Key stretching  
- Strong key management  
- Secure key storage  

---

## Logging and Monitoring

### Security Audit Logs
- Centralized, secure, and automated  
- Limited administrator access  
- Retention policies required  

### Common Logging Problems
- Logs not reviewed regularly  
- Inadequate retention  
- Lack of correlation tools  
- Poor prioritization of alerts  

---

## Data Handling and Lifecycle

### Sensitive Data Handling
- Access limited to trusted individuals  
- Logging of access and usage  
- Secure, controlled storage locations  

### Data Retention
- Keep data only as long as required  
- Follow legal and regulatory requirements  
- Industry-specific rules apply  

### Data Disposal

#### Paper
- Cross-shredding recommended  

#### Digital
- **Delete / Format**: Recoverable  
- **Overwrite (Clear)**: Writes over data  
- **Purge**: Makes recovery infeasible  
- **Degaussing**: Destroys magnetic media  
- **Physical destruction**: Crushing, shredding, incineration  

### Information Lifecycle
1. Data creation  
2. Data use  
3. Archival  
4. Disposal  

---

## Configuration Management

### System Hardening
- Close unused ports  
- Disable unnecessary services  
- Remove default accounts  
- Apply secure baselines  

### Best Practices
- Use hardened OS images  
- Vulnerability scanning before production  
- Monitor deviations from baselines  

---

## Patch Management
- Apply patches regularly  
- Includes OS, applications, network devices, and IoT  
- Centralized patching tools improve consistency  

---

## Change Management

### Change Control Process
1. Identify change  
2. Submit proposal  
3. Risk assessment  
4. Approval  
5. Testing  
6. Scheduling  
7. Notification  
8. Implementation  
9. Post-change review  

### Key Principles
- Documentation is mandatory  
- Auditors verify process adherence  
- Changes introduce residual risk  

---

## Access Control Categories

### Categories
- **Administrative** – Policies and procedures  
- **Technical** – Firewalls, encryption  
- **Physical** – Locks, guards  

### Control Types
- Preventive  
- Detective  
- Corrective  
- Recovery  
- Deterrent  
- Compensating  

---

## Information Security Governance

### Policies
- Acceptable Use Policy (AUP)  
- BYOD Policy  
- Privacy Policy  
- Password Policy  

### Data States
- **At Rest**  
- **In Motion**  
- **In Use**  

---

## Security Awareness

### Human Risk
- Users are the largest attack surface  
- Training builds knowledge  
- Awareness changes behavior  

### Goal
- Create a cybersecurity culture  
- Improve cyber hygiene  

---

## Social Engineering

### What Is Social Engineering
- Manipulating people to bypass security  
- Often more effective than technical attacks  

### Common Techniques
- Authority  
- Intimidation  
- Urgency  
- Scarcity  
- Familiarity  
- Consensus  

### Attack Types
- **Phishing** – Mass email attacks  
- **Spear phishing** – Targeted attacks  
- **Whaling** – Executives targeted  
- **Vishing** – Voice-based attacks  

---

## Domain 5 Summary
- Focuses on operational security practices  
- Cryptography protects confidentiality and integrity  
- Data must be classified, protected, and destroyed properly  
- Change, patch, and configuration management reduce risk  
- Humans remain the most exploited vulnerability  
