# Information Assurance Project — ISO 27001-Aligned ISMS

## Overview

This project presents the design of an **ISO 27001-aligned Information Security Management System (ISMS)** for the **Accounting & Finance (A&F) Department at FAST-NUCES Islamabad**.

The project follows an end-to-end information assurance and risk management lifecycle: defining the ISMS scope, identifying and classifying assets, assessing security risks, selecting risk treatments and controls, performing a gap analysis, preparing a Statement of Applicability (SoA), and documenting security policies.

The project was prepared for the **Information Assurance** course in 2025. The project presentation states that its purpose is to protect **financial, academic, and personal data** within the defined A&F environment.

> **Note:** This repository contains academic project documentation demonstrating an ISO 27001-aligned ISMS design and assessment. It should not be interpreted as a certification audit or proof of ISO 27001 certification.

---

## Project Objectives

The main objectives of the project are to:

- Define an appropriate ISMS scope for the Accounting & Finance Department.
- Identify important information assets and supporting infrastructure.
- Identify, assess, and prioritize information security risks.
- Use a **5 × 5 Likelihood × Impact risk matrix** to evaluate risks.
- Prioritize critical and high-risk security issues.
- Define appropriate controls and risk-treatment measures.
- Identify security gaps between the current environment and the desired security posture.
- Map identified gaps to practical security improvements.
- Develop an ISO 27001-aligned **Statement of Applicability (SoA)**.
- Document security policies relevant to the department.
- Demonstrate a complete ISMS lifecycle from scope definition through security improvement.

---

## Project Scope

The ISMS scope covers the following areas:

### Organizational Scope

- Accounting & Finance Department
- Fintech Lab

### Information Systems

- ERP systems
- Payroll systems
- Cloud ERP
- Microsoft OneDrive

### Physical Information

- Examination papers
- Physical storage used for sensitive documents

### Security Environment

- Departmental computers and laptops
- NAS/storage systems
- Printers
- Network switches
- Wi-Fi access points
- Firewall rules

### Out of Scope / Exclusions

The project explicitly excludes:

- IT infrastructure outside the Accounting & Finance Department
- Learning Management System (LMS)
- HR systems

The defined scope is intended to protect the department's **financial, academic, and personal data**.

---

## Organizational Context

### Stakeholders

The project identifies both internal and external stakeholders.

#### Internal Stakeholders

- Finance Staff
- Faculty
- IT Team

#### External Stakeholders

- Auditors
- Vendors
- Banks
- Cloud Providers

### Activities Covered

The ISMS considers security requirements associated with:

- Teaching
- Examination activities
- Fee processing
- Procurement
- Financial reporting

---

## Key Information Assets

The project identifies several categories of confidential and business-critical information.

### Confidential Assets

- Payroll records
- Vendor invoices
- Examination papers
- Student records
- Financial reports

These assets require appropriate protection against unauthorized access, disclosure, modification, loss, and other security threats.

---

# Asset Inventory

The project documents **45+ assets** across multiple categories.

## Hardware

Examples include:

- Desktop PCs
- Laptops
- NAS devices
- Printers
- Network switches

## Software

Examples include:

- ERP
- Payroll software
- Microsoft Office
- Antivirus software

## Cloud Systems

Examples include:

- Microsoft OneDrive
- Cloud ERP

## Network Infrastructure

Examples include:

- VLANs
- Wi-Fi Access Points
- Firewall rules

The asset inventory provides the foundation for the subsequent risk assessment because security risks can be associated with specific assets, systems, processes, or information.

---

# Risk Assessment

## Methodology

The project uses a **5 × 5 Likelihood × Impact matrix** to evaluate information security risks.

The assessment identified:

| Risk Level | Number of Risks |
|---|---:|
| Critical | 7 |
| High | 10 |
| Medium | 7 |
| **Total** | **24** |

This prioritization allows the department to focus security treatment on risks that could have the greatest impact or likelihood.

---

## Critical Risks

The project identifies the following major critical risks:

1. **No MFA on ERP & Email**
2. **Phishing attacks**
3. **Ransomware**
4. **USB data exfiltration**
5. **Exam paper leakage**
6. **Student misuse of Lab PCs**
7. **Cloud sharing misconfiguration**

These risks cover identity and access management, social engineering, malware, data loss, physical information protection, endpoint misuse, and cloud security.

---

# Risk Control Management

The project proposes specific controls and risk-treatment measures for critical and high risks.

## Controls for Critical Risks

### Multi-Factor Authentication

**Risk addressed:** No MFA on ERP and email.

The proposed treatment is the implementation of MFA to provide an additional authentication factor beyond a password.

### USB Port Blocking

**Risk addressed:** USB data exfiltration.

USB ports can be restricted, with controlled or approved devices allowed where required.

### BitLocker Encryption

**Risk addressed:** Protection of data stored on endpoints.

BitLocker encryption is proposed as an endpoint data-protection measure.

### Patch Management

**Risk addressed:** Exploitation of vulnerable or outdated systems.

A patch-management process is proposed to keep relevant systems updated.

### Email Security Upgrades

**Risk addressed:** Phishing and email-based attacks.

Improved email security is proposed as part of the treatment for phishing-related risks.

### Examination Cabinet Protection

**Risk addressed:** Examination paper leakage.

Physical protection is proposed through improved examination-paper storage.

### Lab Monitoring & Logging

**Risk addressed:** Student misuse of laboratory PCs.

Monitoring and logging are proposed to improve visibility and accountability.

---

## Controls for High Risks

The project proposes the following treatments for high risks:

### Data Loss Prevention (DLP)

DLP is proposed to help protect sensitive information against unauthorized disclosure or transfer.

### WPA3 Wi-Fi

WPA3 is proposed to strengthen wireless network security.

### Vendor Verification SOP

A vendor verification Standard Operating Procedure is proposed to improve third-party/vendor security.

### Backup Restore Testing

Backup restoration should be tested to ensure that backups can actually be recovered when required.

### Unlicensed Software Removal

Removing unlicensed software reduces software-related security and compliance concerns.

---

# Gap Analysis

The gap analysis compares identified weaknesses with proposed security improvements.

| Identified Gap | Proposed Solution |
|---|---|
| No MFA | MFA implementation |
| Weak passwords | Strong password policy |
| USB fully open | Block ports + whitelist devices |
| Weak Wi-Fi | WPA3 + MAC filtering |
| Exam papers unprotected | Locked cabinet + digitization |
| Logs not reviewed | Monthly reviews |

## Key Improvements

### Authentication

The lack of MFA is addressed by introducing multi-factor authentication.

### Password Security

Weak passwords are addressed through a stronger password policy.

### Removable Media

Unrestricted USB access is addressed through port blocking and device whitelisting.

### Wireless Security

Weak Wi-Fi security is addressed using WPA3 and MAC filtering.

### Examination Security

Unprotected examination papers are addressed using locked physical storage and digitization.

### Logging and Monitoring

The absence of regular log review is addressed through monthly reviews.

---

# Statement of Applicability

The project includes a **Statement of Applicability (SoA)** as one of its major deliverables.

The SoA forms part of the project's ISO 27001-aligned documentation and supports the process of documenting applicable security controls for the defined ISMS scope.

The repository should be treated as an academic demonstration of this process rather than an independently verified ISO 27001 certification package.

---

# Security Policies

The project includes four security-policy deliverables:

1. **Security Policy Document**
2. **ISMS Document**
3. **Risk Control Management Document**
4. **Statement of Applicability**

These documents complement the risk assessment and gap analysis by documenting governance, security requirements, controls, and applicability.

---

# Project Deliverables

The project consists of the following documentation:

| File | Purpose |
|---|---|
| `ISMS Document-Anf.docx` | Documents the Information Security Management System for the A&F environment |
| `Asset Risk Assessment Document.docx` | Documents the asset/risk assessment |
| `Asset Inventory.csv` | Contains the project's asset inventory |
| `Risk Control Management Document.docx` | Documents risk treatments and security controls |
| `Gap Analysis Document.docx` | Documents identified security gaps and proposed solutions |
| `Statement Of Applicability.docx` | Provides the Statement of Applicability |
| `Security Policy Document.docx` | Documents security-policy requirements |
| `IA Project Brief.pdf` | Project brief/reference material |
| `IT infomation security_HOD information ...pdf` | Supporting information-security/HOD material |
| `1.txt` | Supporting project notes/data |
| `Information-Assurance-Project.pptx` | Project presentation summarizing the overall ISMS work |

> The filename `IT infomation security_HOD information ...pdf` is shown truncated in the Windows Explorer screenshot; the exact full filename should be preserved when uploading it to GitHub.

---

# Recommended Repository Structure

```text
Information-Assurance-Project/
│
├── README.md
│
├── presentation/
│   └── Information-Assurance-Project.pptx
│
├── ISMS/
│   └── ISMS Document-Anf.docx
│
├── Asset-Management/
│   └── Asset Inventory.csv
│
├── Risk-Assessment/
│   └── Asset Risk Assessment Document.docx
│
├── Risk-Control-Management/
│   └── Risk Control Management Document.docx
│
├── Gap-Analysis/
│   └── Gap Analysis Document.docx
│
├── Statement-of-Applicability/
│   └── Statement Of Applicability.docx
│
├── Security-Policies/
│   └── Security Policy Document.docx
│
├── Project-References/
│   ├── IA Project Brief.pdf
│   ├── IT infomation security_HOD information ...pdf
│   └── 1.txt
│
└── docs/
    └── additional-project-documentation/
```

---

# ISMS Lifecycle Demonstrated

The project demonstrates the following high-level lifecycle:

```text
                    ┌─────────────────────┐
                    │   Define ISMS Scope │
                    └──────────┬──────────┘
                               │
                               ▼
                    ┌─────────────────────┐
                    │  Identify Assets    │
                    └──────────┬──────────┘
                               │
                               ▼
                    ┌─────────────────────┐
                    │ Assess Security     │
                    │ Risks               │
                    └──────────┬──────────┘
                               │
                               ▼
                    ┌─────────────────────┐
                    │ Prioritize Risks    │
                    └──────────┬──────────┘
                               │
                               ▼
                    ┌─────────────────────┐
                    │ Select Risk         │
                    │ Treatments/Controls │
                    └──────────┬──────────┘
                               │
                               ▼
                    ┌─────────────────────┐
                    │ Perform Gap         │
                    │ Analysis            │
                    └──────────┬──────────┘
                               │
                               ▼
                    ┌─────────────────────┐
                    │ Prepare SoA &       │
                    │ Security Policies   │
                    └──────────┬──────────┘
                               │
                               ▼
                    ┌─────────────────────┐
                    │ Improve Security    │
                    │ Posture             │
                    └─────────────────────┘
```

---

# Project Outcomes

According to the project presentation, the resulting ISMS design focuses on improving:

- **Data confidentiality**
- **Access control**
- **Cloud security**
- **Physical protection**
- **Exam integrity**
- **Incident detection**

The project therefore demonstrates how an organization can move from identifying security requirements and risks toward documented controls and security improvements.

---

# Key Security Areas Covered

## 1. Identity & Access Management

- MFA
- Strong password policy
- Access control

## 2. Endpoint Security

- BitLocker encryption
- Patch management
- USB restrictions
- Antivirus software

## 3. Network Security

- VLANs
- Firewall rules
- WPA3
- MAC filtering

## 4. Email Security

- Phishing protection
- Email security improvements
- MFA for email accounts

## 5. Data Protection

- DLP
- Encryption
- USB restrictions
- Cloud-sharing controls

## 6. Cloud Security

- Microsoft OneDrive
- Cloud ERP
- Cloud-sharing configuration

## 7. Physical Security

- Protected examination papers
- Locked cabinets
- Physical storage controls

## 8. Monitoring & Detection

- Lab monitoring
- Logging
- Monthly log reviews

## 9. Third-Party Security

- Vendor verification
- Vendor-related security procedures

## 10. Business Resilience

- Backups
- Backup restoration testing

---

# Risk-to-Control Mapping

A simplified view of the project's treatment approach is:

| Risk | Treatment / Control |
|---|---|
| No MFA on ERP & Email | MFA implementation |
| Phishing attacks | Email security upgrades |
| Ransomware | Patch management, backups and restoration testing |
| USB data exfiltration | USB port blocking + device whitelisting |
| Exam paper leakage | Locked cabinet + digitization |
| Student misuse of Lab PCs | Lab monitoring & logging |
| Cloud sharing misconfiguration | Cloud-sharing controls / DLP |
| Weak passwords | Strong password policy |
| Weak Wi-Fi | WPA3 + MAC filtering |
| Vendor-related risk | Vendor verification SOP |
| Unlicensed software | Removal of unlicensed software |

---

# Technologies and Security Concepts

The project covers or references the following technologies and security concepts:

- ISO 27001 / ISMS
- Risk assessment
- Risk treatment
- Likelihood × Impact matrix
- Multi-Factor Authentication (MFA)
- Data Loss Prevention (DLP)
- BitLocker
- Patch management
- WPA3
- MAC filtering
- VLANs
- Firewalls
- Cloud security
- Microsoft OneDrive
- Cloud ERP
- Logging and monitoring
- Backup and restore testing
- Vendor security
- Security policies
- Statement of Applicability

---

# Skills Demonstrated

This project demonstrates practical understanding of:

- Information security governance
- ISMS design
- ISO 27001 alignment
- Asset identification and classification
- Risk identification
- Risk analysis and prioritization
- Risk treatment planning
- Security control selection
- Gap analysis
- Security policy development
- Statement of Applicability preparation
- Cloud security assessment
- Access control
- Endpoint security
- Network security
- Physical security
- Security monitoring
- Third-party/vendor risk management
- Security documentation

---

# Project Workflow

The project can be understood as the following workflow:

### Step 1 — Establish Context

Identify the department, stakeholders, activities, information, systems, and boundaries of the ISMS.

### Step 2 — Define Scope

Establish which systems, processes, assets, and information are included and excluded.

### Step 3 — Build Asset Inventory

Document the assets supporting departmental operations.

### Step 4 — Identify Risks

Identify threats and security weaknesses affecting the assets and activities within scope.

### Step 5 — Assess Risks

Use the 5 × 5 Likelihood × Impact matrix to evaluate and prioritize risks.

### Step 6 — Treat Risks

Select appropriate controls and treatments for critical and high risks.

### Step 7 — Perform Gap Analysis

Identify weaknesses and define practical improvements.

### Step 8 — Document Applicability

Prepare the Statement of Applicability to document the applicability of security controls.

### Step 9 — Develop Policies

Document security requirements through appropriate policy documents.

### Step 10 — Demonstrate Security Improvement

Show how the proposed ISMS strengthens confidentiality, access control, cloud security, physical protection, exam integrity, and incident detection.

---

# Repository Usage

This repository is intended to provide a complete academic record of the Information Assurance project.

For reviewers, the recommended reading order is:

1. `Information-Assurance-Project.pptx`
2. `ISMS Document-Anf.docx`
3. `Asset Inventory.csv`
4. `Asset Risk Assessment Document.docx`
5. `Risk Control Management Document.docx`
6. `Gap Analysis Document.docx`
7. `Statement Of Applicability.docx`
8. `Security Policy Document.docx`
9. Supporting project/reference files

This order follows the overall project flow from organizational context and scope through assets, risks, treatments, gaps, applicability, and policies.

---

# Academic Context

**Project:** Information Assurance Project  
**Organization/Case Environment:** Accounting & Finance Department, FAST-NUCES Islamabad  
**Course:** Information Assurance  
**Prepared By:** Ahmed  
**Year:** 2025

---

# Conclusion

This project demonstrates an end-to-end **ISO 27001-aligned Information Security Management System** for an Accounting & Finance Department.

The work begins with defining the ISMS scope and understanding the organization's information-security context. It then identifies 45+ assets and assesses 24 risks using a 5 × 5 Likelihood × Impact matrix. The identified risks are prioritized into 7 critical, 10 high, and 7 medium risks.

The project then proposes risk treatments such as MFA, USB restrictions, BitLocker, patch management, email security improvements, DLP, WPA3, vendor verification, backup restoration testing, physical protection for examination papers, and regular log reviews.

Finally, the project brings these activities together through gap analysis, an ISMS document, a Statement of Applicability, security policies, and supporting documentation.

The result is a structured academic demonstration of how information assurance principles can be applied to protect **financial, academic, and personal information** while improving the overall security posture of the defined department.

---

## Disclaimer

This is an academic Information Assurance project. The documentation describes an **ISO 27001-aligned ISMS design** based on the project's defined scope, assets, risks, controls, and policies. It does not constitute an ISO 27001 certification, independent audit, or formal compliance attestation.
