# ISO 27001 Gap Analysis – NovaTech Online Store

## Overview
This document compares ISO 27001 requirements against the current security posture of NovaTech Online Store to identify gaps and recommend improvements.

---

## Gap Analysis Table

| Control Area | ISO 27001 Requirement | Current Status | Gap | Risk Level | Recommendation |
|--------------|----------------------|----------------|-----|------------|----------------|
| Access Control | Enforce least privilege and RBAC | Basic role management only | No Role-Based Access Control | High | Implement RBAC and least privilege model |
| Authentication | Multi-Factor Authentication (MFA) required | Password-only authentication | No MFA | High | Enable MFA for all users |
| Password Policy | Strong password complexity and rotation | Weak password rules | No enforced password policy | High | Enforce password complexity + expiry policy |
| Backup Management | Regular secure backups and recovery testing | No formal backup system | Missing backup policy | High | Implement automated encrypted backups |
| Logging & Monitoring | Continuous monitoring and security logging | Not implemented | No monitoring or logging system | High | Deploy centralized logging / SIEM solution |
| Incident Response | Documented incident response plan | Not defined | No IR process | Medium | Develop Incident Response Plan |
| Data Encryption | Encrypt data at rest and in transit | Partial encryption | Weak encryption coverage | High | Enforce full encryption (TLS + database encryption) |

---

## Summary

The assessment shows significant security gaps across key ISO 27001 control areas, especially in:
- Access management
- Authentication
- Monitoring and logging
- Incident response readiness

Addressing these gaps will significantly improve the organization’s security posture and compliance level.
