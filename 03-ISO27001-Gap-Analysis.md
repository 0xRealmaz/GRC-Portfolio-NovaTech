📌 Overview

This document presents a gap analysis between ISO/IEC 27001 requirements and the current security posture of the fictional company NovaTech Online Store.

The goal is to identify missing controls and recommend improvements.

 Gap Analysis Table
Control Area	ISO 27001 Requirement	Current Status	Gap	Risk Level	Recommendation
Access Control	Unique user accounts, least privilege, RBAC	Basic role management only	No Role-Based Access Control (RBAC)	High	Implement RBAC and least privilege model
Authentication	Multi-Factor Authentication (MFA) required	Password-only authentication	No MFA	High	Enable MFA for all users
Password Policy	Strong password complexity rules	Weak password rules	No password complexity enforcement	High	Enforce strong password policy (length, complexity, expiry)
Backup Management	Regular and secure backups	No formal backup process	No backup policy	High	Implement automated encrypted backups
Logging & Monitoring	Security event logging and monitoring	Not implemented	No monitoring system	High	Deploy centralized logging / SIEM
Incident Response	Documented incident response plan	Not defined	No incident response plan	Medium	Create and document IR policy
Data Encryption	Data encrypted at rest and in transit	Partially implemented	Weak encryption controls	High	Enforce full encryption (TLS + DB encryption)
🧠 Summary

The analysis shows that NovaTech Online Store has significant security gaps, especially in:

Access control
Authentication mechanisms
Monitoring and logging
Incident response readiness

Addressing these gaps will significantly improve the organization’s security posture and compliance level.

 Outcome

By implementing the recommended controls, the company can align with ISO/IEC 27001 requirements and reduce overall cybersecurity risk exposure.
