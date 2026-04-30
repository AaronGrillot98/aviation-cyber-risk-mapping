# Aviation System Risk Map with NIST Alignment

## Purpose

Map aviation operational functions to digital systems, cyber threats, operational impacts, practical controls, and NIST framework alignment.

> This is a defensive, conceptual portfolio project. Do not include private aircraft data, DoD data, internal manuals, real credentials, or non-public system details.

| Aviation Function | Digital/System Dependency | Threat | Operational Impact | Practical Control | NIST SP 800-53 Rev. 5 Mapping | NIST CSF 2.0 Function |
|---|---|---|---|---|---|---|
| Maintenance records | Maintenance tracking software | Record tampering | Bad airworthiness decision | Access control, audit logs, approvals | AC-2, AC-3, AU-2, AU-6, SI-7 | Protect, Detect |
| Parts tracking | Inventory/database system | Data integrity failure | Wrong part status or traceability issue | Change logs, role-based access, validation | AC-6, AU-2, AU-6, SI-7 | Protect, Detect |
| Flight scheduling | Scheduling platform | Account compromise | Incorrect schedule, readiness disruption | MFA, least privilege, account review | IA-2, AC-2, AC-6 | Protect |
| Aircraft location tracking | GPS/ADS-B-related tools | Spoofing or false data | Situational awareness issue | Cross-check data sources, anomaly review | SI-4, SI-7, AU-6 | Detect |
| Ground network | Wi-Fi/admin network | Credential theft | Unauthorized access | Network segmentation, MFA, least privilege | AC-17, IA-2, SC-7, AC-6 | Protect, Detect |
| Technical documentation | Digital manuals | Outdated or altered data | Maintenance error | Version control, trusted sources, integrity checks | CM-3, CM-8, SI-7 | Protect |
| Work orders | Maintenance workflow tool | Unauthorized change | Missed corrective action | Approval workflow, audit trail, change review | AC-3, AU-2, AU-6, CM-3 | Protect, Detect |
| Training records | LMS/database | Record manipulation | Unqualified task assignment | Access reviews, logging, approval process | AC-2, AC-6, AU-6, IA-2 | Protect, Detect |
| Vendor communication | Email/portal | Phishing | Credential compromise | Security awareness, email filtering, MFA | AT-2, SI-8, IA-2 | Protect, Detect |
| Mobile devices | Phones/tablets | Lost device or weak lock | Data exposure | MDM, encryption, passcodes, remote wipe | AC-19, MP-5, SC-28, IA-2 | Protect, Recover |

## Key Lesson

Cyber risk in aviation is not only about aircraft hacking. It also includes the digital systems that support readiness, maintenance, logistics, documentation, and decision-making.

If the supporting data is wrong, delayed, altered, or unavailable, the aviation decision can also be wrong.
