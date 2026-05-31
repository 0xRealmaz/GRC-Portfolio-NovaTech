# NIST Cybersecurity Framework (CSF) Assessment – NovaTech Online Store

## Overview
This document assesses the cybersecurity maturity of NovaTech Online Store using the NIST Cybersecurity Framework (CSF).

The framework evaluates security posture across five core functions:
Identify, Protect, Detect, Respond, and Recover.

---

## Assessment Table

| Function | Category | Current Status | Maturity Level | Gap | Recommendation |
|----------|----------|----------------|----------------|-----|----------------|

### Identify
| Identify | Asset Management | No asset inventory | Low | Lack of visibility over IT assets | Create and maintain a complete asset inventory |
| Identify | Risk Management | Informal risk handling | Low | No formal risk management process | Implement structured risk management framework |

---

### Protect
| Protect | Access Control | Weak role management | Low | No RBAC implementation | Implement Role-Based Access Control |
| Protect | Authentication | Password-only authentication | Low | No MFA enabled | Enable Multi-Factor Authentication |
| Protect | Data Security | Partial encryption | Medium | Weak data protection controls | Enforce full encryption (TLS + Database encryption) |

---

### Detect
| Detect | Logging & Monitoring | No monitoring system | Low | No visibility of security events | Implement SIEM solution |
| Detect | Continuous Monitoring | Not implemented | Low | No real-time detection capability | Deploy continuous monitoring tools |

---

### Respond
| Respond | Incident Response | No incident response plan | Low | No structured response process | Develop Incident Response Plan |
| Respond | Communications | No communication plan | Low | No breach communication strategy | Define incident communication procedures |

---

### Recover
| Recover | Backup & Recovery | No backup system | Low | Risk of data loss | Implement automated backup solution |
| Recover | Disaster Recovery | Not defined | Low | No recovery strategy | Develop disaster recovery plan |

---

## Summary

The assessment highlights weak cybersecurity maturity across all five NIST CSF functions.

Key weaknesses include:
- Lack of asset visibility (Identify)
- Weak access control and authentication (Protect)
- No monitoring or detection systems (Detect)
- No incident response capability (Respond)
- No backup or recovery strategy (Recover)

Addressing these gaps will significantly improve the organization’s overall security posture and resilience.
