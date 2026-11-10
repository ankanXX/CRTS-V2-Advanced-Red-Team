☢️ Nuclear Power Grid — Advanced Red Team Operations

CRTS V2 | Enterprise Infrastructure | Active Directory | Power Grid Simulation

An advanced cybersecurity research and documentation project based on the Certified Red Team Specialist V2 (CRTS V2) training curriculum by CyberWarFare Labs.

This repository documents practical red team methodologies, command references, attack techniques, infrastructure analysis, tooling, and technical findings within a simulated enterprise environment connected to a nuclear power-grid scenario.

The project explores how an adversary could navigate a complex enterprise infrastructure, move across interconnected network segments, abuse identity infrastructure, and reach simulated operational technology (OT) environments.

---

⚡ Project Overview

The simulated infrastructure represents a segmented enterprise environment with interconnected systems, including:

- Operation Support Network
- Engineering Department
- Interconnect Network
- Multiple Active Directory Forests
- Certificate Authority Infrastructure
- Linux Domain Controllers
- Bastion Hosts
- Human-Machine Interface (HMI)
- OTP Authentication Infrastructure
- Physical Network
- Electric Power Grid Simulation

The primary objective is to understand advanced enterprise attack paths, identity infrastructure weaknesses, cross-network movement, and the security implications of interconnected IT and OT environments.

---

🏗️ Infrastructure Architecture

The project follows the simulated infrastructure architecture presented in the CRTS V2 curriculum.

Infrastructure| Components
Operation Support Network| Web, Exchange, Production Applications
Engineering Department| Development Machines, CI/CD, Databases, GitLab
Interconnect Network| Bastion Hosts, MFA Devices, Gateway
Active Directory| Multiple Forests, Domain Controllers
Identity Infrastructure| AD CS, Certificate Authority
Physical Network| Linux KDC, HMI, OTP Server
Operational Environment| Electric Power Grid Simulation

---

🎯 Technical Domains

01. Initial Access & Cyber Kill Chain

- Web Application Vulnerability Exploitation
- Leaked Personal Access Tokens (PAT)
- Self-Hosted GitLab Runner Abuse
- Adversary-in-the-Middle (AiTM)
- Exchange Rule Manipulation
- Enterprise Application Impersonation
- Zoom and Visual Studio Application Abuse

02. Advanced Active Directory Operations

Kerberos Delegation

- S4U2Self
- User-to-User (U2U)
- Combined S4U2Self + U2U
- Diamond Tickets
- Sapphire Tickets

Linux Active Directory

- Credential Discovery
- Kerberos in Linux
- Credential Extraction

Group Managed Service Accounts

- Machine-Level Access
- User-Level Access

Active Directory Certificate Services

- Certificate Authentication
- ESC1, ESC4, ESC6 and ESC8
- Golden Certificate
- UnPAC the Hash
- Shadow Credentials
- Certificate Template Misconfigurations

Cross-Forest Operations

- Cross-Forest Kerberoasting
- ACL Abuse
- Foreign Security Principals
- Trust Key Abuse
- Privileged Access Management (PAM)
- Over-Permissive Certificate Templates

---

🛠️ Repository Contents

This repository is organized as a technical knowledge base containing:

- Command references and syntax
- Attack methodology documentation
- Tool usage and configurations
- Practical examples
- Technical research
- Infrastructure analysis
- Screenshots and lab evidence
- Troubleshooting notes
- Custom scripts and automation
- Technical findings and reports

Each documented technique aims to explain not only WHAT a command does, but also WHY, WHEN, and HOW it is relevant during an authorized security assessment.

---

🔬 Research Objectives

1. Understand complex enterprise attack surfaces.
2. Study identity infrastructure and Kerberos-based attack techniques.
3. Investigate Active Directory Certificate Services weaknesses.
4. Understand cross-forest trust relationships and attack paths.
5. Explore enterprise application and CI/CD security weaknesses.
6. Examine segmented IT/OT infrastructure and security boundaries.
7. Develop practical command references and technical documentation.
8. Improve red team operational methodology and technical reporting.

---

📚 Training Reference

Certified Red Team Specialist V2 (CRTS V2)
CyberWarFare Labs

This project is independently maintained as a learning and portfolio resource. It is not an official CyberWarFare Labs publication.

---

⚠️ Disclaimer

This repository is intended strictly for cybersecurity education, authorized penetration testing, and controlled laboratory research.

All infrastructure and operational technology references relate to simulated environments. No real nuclear facilities, power grids, industrial control systems, or critical infrastructure are targets of this project.

Do not use documented techniques against systems without explicit authorization.

---

Author: ankanX
Focus: Advanced Red Team Operations | Enterprise Security | Active Directory | IT/OT Security
