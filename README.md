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
