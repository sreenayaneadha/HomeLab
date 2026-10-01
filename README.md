# Cybersecurity Homelab

A hands-on cybersecurity laboratory built with VMware Workstation Pro to develop practical skills across offensive security, defensive security, networking, system administration, security architecture, vulnerability management, incident response, SIEM, cloud security, and GRC.

The lab is designed to progressively simulate a small enterprise environment using isolated virtual machines and security tools.

## Objectives

The primary goals of this project are to:

* Build practical cybersecurity skills through hands-on experimentation
* Understand how operating systems, networks, applications, and security controls work
* Develop both offensive and defensive security capabilities
* Practice security monitoring, detection, investigation, and incident response
* Learn vulnerability assessment and management
* Develop familiarity with enterprise security tools
* Understand security architecture and defense-in-depth
* Practice identity and access management
* Explore cloud security concepts
* Apply governance, risk, and compliance principles
* Document technical work and lessons learned in a reproducible format

## Lab Environment

The laboratory is being developed using:

* **Host OS:** Windows 11
* **Hypervisor:** VMware Workstation Pro
* **Initial Guest OS:** Ubuntu
* **Device:** GIGAGBYTE AERO X16 Laptop - AMD Ryzen AI 7 350 - 32 GB DDR5 - RTX 5070 - 1 TB SSD

Additional virtual machines and security infrastructure will be introduced progressively as new areas are studied.

## Planned Environment

The lab will eventually include systems such as:

* Windows
* Kali Linux
* Parrot OS
* Security monitoring infrastructure
* SIEM/logging infrastructure
* Vulnerability scanning infrastructure
* Network security tooling
* Cloud security environments

Tails OS may also be used for selected privacy and security experiments.

## Major Areas of Study

### Networking & Infrastructure

* TCP/IP
* IPv4/IPv6
* DNS
* DHCP
* Routing
* NAT
* TCP/UDP
* Ports and services
* Network segmentation
* VPNs
* Firewalls
* Network monitoring

### Linux & Windows Security

* Users and groups
* Permissions
* Authentication
* Authorization
* Processes
* Services
* System administration
* SSH
* PowerShell
* Windows Event Logs
* Active Directory

### Defensive Security

* Security monitoring
* IDS/IPS
* Log analysis
* Detection engineering
* Threat hunting
* Incident response
* Digital forensics concepts
* SIEM

### SIEM & Security Monitoring

* Wazuh
* Splunk
* Elastic/ELK Stack
* ArcSight concepts
* Log collection
* Correlation
* Alerting
* Detection rules

### Offensive Security

* Kali Linux
* Nmap
* Metasploit
* Burp Suite
* Penetration testing
* Vulnerability assessment
* Exploitation concepts
* Exploit development
* Red-team methodologies

All offensive security exercises will be performed against systems controlled by this lab or other explicitly authorized environments.

### Vulnerability Management

* Vulnerability discovery
* CVEs
* CVSS
* Vulnerability prioritization
* Remediation
* Verification
* Nessus
* Qualys
* OpenVAS/Greenbone

### Security Architecture

* Defense in depth
* Zero Trust
* Least privilege
* Network segmentation
* Secure design patterns
* Trust boundaries
* Identity-centric security
* Security controls

### Cryptography

* Symmetric encryption
* Asymmetric encryption
* Hashing
* Digital signatures
* Certificates
* PKI
* TLS
* Key management

### Malware & Reverse Engineering

* Static analysis
* Dynamic analysis
* File analysis
* Network behavior
* Ghidra
* Debugging
* Malware-analysis lab isolation

### Web Security

* HTTP/HTTPS
* Authentication
* Authorization
* Sessions
* APIs
* OWASP Top 10
* Burp Suite
* Web application testing

### Development & DevSecOps

* Python
* Bash
* PowerShell
* Git/GitHub
* Secure software development
* SAST
* DAST
* Dependency security
* Secrets management
* Containers
* Docker
* Infrastructure as Code

### Cloud Security

* AWS
* IAM
* EC2
* S3
* VPC
* Security Groups
* CloudTrail
* CloudWatch
* KMS
* Shared responsibility model
* Cloud identity and access management

### Governance, Risk & Compliance

* Risk management
* Security policies
* Security controls
* Auditing
* Control testing
* NIST Cybersecurity Framework
* NIST 800-53
* CIS Controls
* ISO 27001
* SOC 2
* GDPR
* HIPAA

## My Documentation Approach

Each laboratory exercise will document:

1. **Objective** — what the exercise is intended to teach
2. **Environment** — systems and tools used
3. **Configuration** — relevant setup
4. **Commands** — commands actually used
5. **Results** — observed output and behavior
6. **Security Relevance** — why the exercise matters
7. **Lessons Learned** — concepts understood from the exercise

The goal is to document practical understanding rather than simply collect commands or cybersecurity terminology.

## Lab Progress

### Phase 01 — Virtualization & Lab Infrastructure

* [ ] Configure VMware environment
* [ ] Create Ubuntu VM
* [ ] Configure virtual networking
* [ ] Document lab architecture

### Phase 02 — Linux Fundamentals

* [ ] Linux filesystem
* [ ] Users and groups
* [ ] Permissions
* [ ] sudo
* [ ] Processes
* [ ] Services
* [ ] SSH
* [ ] Linux logging

### Phase 03 — Networking

* [ ] IP addressing
* [ ] TCP/UDP
* [ ] Ports
* [ ] DNS
* [ ] Network interfaces
* [ ] Nmap
* [ ] Wireshark

Additional phases will be added as the project develops.
