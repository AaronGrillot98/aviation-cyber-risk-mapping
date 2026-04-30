# Threat Model — Maintenance Record Integrity

## Asset

Digital maintenance records, inspections, corrective actions, and airworthiness notes.

## Threat

Unauthorized modification, deletion, or manipulation of records.

## Why It Matters

Maintenance decisions depend on accurate records. If records are altered, incomplete, or untrusted, the organization may make poor safety or readiness decisions.

## Attack / Failure Paths

- Compromised user account changes a record
- Insider edits inspection notes
- Weak audit logging prevents investigation
- Poor access control allows broad editing
- Backup failure prevents recovery

## Impact

- Incorrect aircraft status
- Missed maintenance requirement
- Bad compliance evidence
- Reduced trust in system of record

## Recommended Controls

- Role-based access control
- MFA for privileged users
- Immutable audit logs
- Approval workflow for critical edits
- Backups and recovery testing
- Periodic access reviews
