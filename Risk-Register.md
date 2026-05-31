# Risk Register – NovaTech Online Store

## Overview
This document identifies and assesses key cybersecurity risks within NovaTech Online Store, along with their impact and mitigation strategies.

---

## Risk Register Table

| Risk ID | Risk Description | Asset | Threat | Impact | Likelihood | Risk Level | Existing Controls | Recommendation |
|----------|------------------|--------|--------|--------|-------------|------------|------------------|----------------|
| R1 | Weak password policy | User accounts | Brute force attacks | High | High | High | Basic password rules | Enforce strong password policy + MFA |
| R2 | No multi-factor authentication | Authentication system | Credential theft | High | High | High | Password-only login | Implement MFA for all users |
| R3 | No backup system | Company database | Data loss / ransomware | High | Medium | High | No backup process | Implement automated encrypted backups |
| R4 | No logging or monitoring | System infrastructure | Undetected attacks | High | Medium | High | No SIEM | Deploy centralized logging and SIEM |
| R5 | Weak access control | Internal systems | Unauthorized access | High | Medium | High | Basic role structure | Implement RBAC and least privilege model |

---

## Summary

The organization faces several high-risk cybersecurity threats mainly due to weak security controls across authentication, access management, and monitoring.

Key risks include:
- Weak authentication mechanisms
- Lack of backups
- No monitoring or logging
- Poor access control

Implementing the recommended controls will significantly reduce overall risk exposure.
