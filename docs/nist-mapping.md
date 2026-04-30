# NIST Mapping Guide

## Purpose

This file explains how the aviation cyber risk map connects practical aviation risks to recognized cybersecurity frameworks.

The project uses two framework views:

1. **NIST SP 800-53 Rev. 5** for control-level mapping.
2. **NIST Cybersecurity Framework 2.0** for high-level risk communication.

This keeps the project practical: each aviation risk maps to specific control ideas instead of becoming a generic compliance essay.

---

## Control Mapping Summary

| Control | Name | Why It Fits This Project |
|---|---|---|
| AC-2 | Account Management | Applies to maintenance systems, scheduling platforms, LMS tools, and admin accounts. |
| AC-3 | Access Enforcement | Applies when systems must prevent unauthorized record or work-order changes. |
| AC-6 | Least Privilege | Applies when users should only access the records, work orders, or systems they need. |
| AC-17 | Remote Access | Applies to remote/admin access into ground or support networks. |
| AC-19 | Access Control for Mobile Devices | Applies to phones/tablets used for documentation, records, or field support. |
| AT-2 | Literacy Training and Awareness | Applies to phishing and vendor communication risk. |
| AU-2 | Event Logging | Applies anywhere record changes must be traceable. |
| AU-6 | Audit Record Review, Analysis, and Reporting | Applies to reviewing logs for tampering, unauthorized changes, and suspicious access. |
| CM-3 | Configuration Change Control | Applies to controlled updates to technical documentation and workflow systems. |
| CM-8 | System Component Inventory | Applies to tracking systems, manuals, devices, and support assets. |
| IA-2 | Identification and Authentication | Applies to MFA and authentication for maintenance, scheduling, LMS, email, and mobile access. |
| MP-5 | Media Transport | Applies when mobile devices or removable media could expose operational data. |
| SC-7 | Boundary Protection | Applies to network segmentation and traffic control around ground/admin networks. |
| SC-28 | Protection of Information at Rest | Applies to encryption of data on phones, tablets, laptops, and databases. |
| SI-4 | System Monitoring | Applies to detecting spoofing, suspicious changes, and telemetry anomalies. |
| SI-7 | Software, Firmware, and Information Integrity | Applies to record integrity, documentation integrity, artifact trust, and tamper detection. |
| SI-8 | Spam Protection | Applies to vendor communication and phishing exposure. |

---

## NIST CSF 2.0 Mapping

| CSF Function | How It Appears in This Project |
|---|---|
| Govern | Shows risk ownership, control selection, and operational impact awareness. |
| Identify | Maps aviation functions to systems, dependencies, and risk areas. |
| Protect | Recommends controls like MFA, least privilege, encryption, segmentation, and approvals. |
| Detect | Uses logging, audit review, anomaly review, and monitoring concepts. |
| Respond | Supports incident handling through documented response steps and runbooks. |
| Recover | Supports rollback, recovery, device response, and restoration of trusted data. |

---

## How to Explain This in an Interview

> I did not just list aviation cyber risks. I mapped them to NIST controls so the project shows how an operational aviation issue becomes a formal security requirement. For example, maintenance record tampering maps to access enforcement, event logging, audit review, and information integrity controls because the risk is not only technical. It affects airworthiness decisions.

---

## Important Note

This project is not claiming official compliance or certification. It is a portfolio demonstration showing how to reason from aviation operations to cybersecurity controls using recognized frameworks.
