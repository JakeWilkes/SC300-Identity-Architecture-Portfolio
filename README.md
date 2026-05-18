# Enterprise Cloud Identity Architecture Portfolio

## Professional Profile
* **Target Role:** Weekend Infrastructure & Identity Security Engineer (Out-of-Hours P1 Incident Triage)
* **Specialization:** Microsoft Entra ID, Identity Governance, and Zero Trust Architecture
* **Compliance Standards:** NCSC Cloud Security Principles, UK Data Protection Act 2018 / UK GDPR

## Portfolio Overview
This repository functions as a live production runbook portfolio demonstrating enterprise-grade implementation of the Microsoft SC-300 (Identity and Access Administrator) blueprint. Every configuration is optimized for UK enterprise environments, prioritizing strict access isolation, auditable change control, and the Principle of Least Privilege.

### Module 1: Identity Management Solution
* **[1.3 Administrative Units & UK Regional Compliance](./Module-1-Identity-Management/1.3-Administrative-Units-UK-Compliance.md):** Isolation of helpdesk administrative privileges between distinct geographical business units (London HQ vs. Edinburgh Operations) to eliminate tenant-wide lateral privilege escalation.

## Architectural Principles
1. **Explicit Verification:** Every access request is evaluated on full contextual telemetry (Identity, Device Health, Location, Risk).
2. **Least Privilege Access:** Eliminating standing permanent administrative privileges using scoped boundaries.
3. **Assume Breach:** Limiting blast radiuses via strict segmentation of administrative personnel.
