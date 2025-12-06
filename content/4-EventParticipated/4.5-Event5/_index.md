---
title: "Event 5"
date: "2025-11-29"
weight: 5
chapter: false
pre: " <b> 4.5. </b> "
---

# AWS Well-Architected Security Pillar Workshop

### Event Information

**Date & Time:** Saturday, November 29, 2025, 8:30 AM – 12:00 PM  
**Location:** AWS Vietnam Office  
**Role:** Attendee

### Event Purpose

This morning workshop provided a comprehensive deep-dive into the **AWS Well-Architected Security Pillar**, covering all five security domains: Identity & Access Management, Detection, Infrastructure Protection, Data Protection, and Incident Response.

The session was designed to equip participants with practical knowledge on implementing security best practices in AWS environments, with real-world examples from Vietnamese enterprises.

### Agenda

---

#### 8:30 – 8:50 AM | Opening & Security Foundation

**Security Pillar in Well-Architected Framework**

- Role of Security Pillar in the Well-Architected Framework
- Core principles: **Least Privilege – Zero Trust – Defense in Depth**
- AWS Shared Responsibility Model
- Top cloud security threats in Vietnam

---

#### Pillar 1 — Identity & Access Management

**8:50 – 9:30 AM | Modern IAM Architecture**

- IAM fundamentals: Users, Roles, Policies – avoiding long-term credentials
- **IAM Identity Center**: SSO, permission sets
- **SCP & Permission Boundaries** for multi-account environments
- MFA, credential rotation, Access Analyzer
- **Mini Demo**: Validate IAM Policy + simulate access

---

#### Pillar 2 — Detection

**9:30 – 9:55 AM | Detection & Continuous Monitoring**

- **CloudTrail** (org-level), **GuardDuty**, **Security Hub**
- Logging at every layer: VPC Flow Logs, ALB/S3 logs
- Alerting & automation with **EventBridge**
- Detection-as-Code (infrastructure + rules)

---

#### 9:55 – 10:10 AM | Coffee Break

---

#### Pillar 3 — Infrastructure Protection

**10:10 – 10:40 AM | Network & Workload Security**

- VPC segmentation, private vs public placement
- **Security Groups vs NACLs**: application models
- **WAF + Shield + Network Firewall**
- Workload protection: EC2, ECS/EKS security basics

---

#### Pillar 4 — Data Protection

**10:40 – 11:10 AM | Encryption, Keys & Secrets**

- **KMS**: key policies, grants, rotation
- Encryption at-rest & in-transit: S3, EBS, RDS, DynamoDB
- **Secrets Manager & Parameter Store** — rotation patterns
- Data classification & access guardrails

---

#### Pillar 5 — Incident Response

**11:10 – 11:40 AM | IR Playbook & Automation**

- IR lifecycle according to AWS framework
- **Playbooks**:
  - Compromised IAM key
  - S3 public exposure
  - EC2 malware detection
- Snapshot, isolation, evidence collection
- Auto-response with **Lambda/Step Functions**

---

#### 11:40 – 12:00 PM | Wrap-Up & Q&A

- Summary of 5 security pillars
- Common pitfalls & real-world practices in Vietnamese enterprises
- Security learning roadmap (Security Specialty, SA Pro certifications)

---

### Key Learnings

- **Least Privilege** is fundamental – always start with minimal permissions and expand as needed
- **Zero Trust** architecture assumes no implicit trust, even within the network
- **Defense in Depth** requires security controls at multiple layers
- Detection capabilities must be automated and continuous
- Incident response playbooks should be documented and tested regularly

### Application to My Work

- Implement IAM Access Analyzer in current projects
- Set up GuardDuty and Security Hub for centralized security monitoring
- Create incident response playbooks for common scenarios
- Review and tighten Security Group rules using least privilege
- Enable encryption for all data stores (S3, RDS, DynamoDB)

### Personal Experience

This workshop was incredibly valuable for understanding AWS security holistically:

- The practical demos made abstract concepts tangible
- Learning about common security pitfalls in Vietnamese enterprises was eye-opening
- The incident response playbooks provided actionable templates
- Understanding the relationship between all five pillars helps in designing comprehensive security architectures

### Takeaways

- Security is a continuous journey, not a destination
- Automation is key to maintaining security at scale
- The Well-Architected Security Pillar provides a comprehensive framework for cloud security
- Regular security reviews and improvements are essential
- AWS provides powerful native tools for each security domain

### Event Photos

<div style="display: flex; flex-wrap: wrap; gap: 10px; justify-content: center; margin: 20px 0;">
  <img src="/images/E18.jpg" alt="Event Photo 1" style="width: 200px; height: 150px; object-fit: cover; border-radius: 8px; box-shadow: 0 4px 8px rgba(0,0,0,0.1);">
  <img src="/images/E19.jpg" alt="Event Photo 2" style="width: 200px; height: 150px; object-fit: cover; border-radius: 8px; box-shadow: 0 4px 8px rgba(0,0,0,0.1);">
  <img src="/images/E20.jpg" alt="Event Photo 3" style="width: 200px; height: 150px; object-fit: cover; border-radius: 8px; box-shadow: 0 4px 8px rgba(0,0,0,0.1);">
  <img src="/images/E21.jpg" alt="Event Photo 4" style="width: 200px; height: 150px; object-fit: cover; border-radius: 8px; box-shadow: 0 4px 8px rgba(0,0,0,0.1);">
  <img src="/images/E22.jpg" alt="Event Photo 5" style="width: 200px; height: 150px; object-fit: cover; border-radius: 8px; box-shadow: 0 4px 8px rgba(0,0,0,0.1);">
  <img src="/images/E23.jpg" alt="Event Photo 6" style="width: 200px; height: 150px;
  object-fit: cover; border-radius: 8px; box-shadow: 0 4px 8px rgba(0,0,0,0.1);">
  <img src="/images/E24.jpg" alt="Event Photo 7" style="width: 200px; height: 150px;
  object-fit: cover; border-radius: 8px; box-shadow: 0 4px 8px rgba(0,0,0,0.1);">
</div>

