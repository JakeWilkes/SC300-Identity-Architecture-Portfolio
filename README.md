# Enterprise Cloud Identity Architecture Portfolio

## 👤 Professional Profile
* **Target Role:** Weekend Infrastructure & Identity Security Engineer (Out-of-Hours P1 Incident Triage)
* **Specialization:** Microsoft Entra ID, Identity Governance, and Zero Trust Architecture
* **Compliance Standards:** NCSC Cloud Security Principles, UK Data Protection Act 2018 / UK GDPR

## 📑 Portfolio Overview
This repository functions as a live production runbook portfolio demonstrating enterprise-grade implementation of the Microsoft SC-300 (Identity and Access Administrator) blueprint. Every configuration is optimized for UK enterprise environments, prioritizing strict access isolation, auditable change control, and the Principle of Least Privilege.

## 📁 Enterprise Architecture Modules

### [Module 1: Implement an Identity Management Solution](./Module-1-Identity-Management/)

* **1.1 Hybrid Identity Architecture:** Entra Connect Cloud Sync configuration runbook for multi-forest UK retail organizations. `[PENDING]`
  
* **1.2 External Identity Lifecycle:** B2B guest invitation policies with automated cross-tenant access settings.
`[PENDING]`
  
* **1.3 Administrative Units & UK Regional Compliance:** Isolation of helpdesk administrative privileges between London HQ and Edinburgh Operations.
  *`[COMPLETE]`

### [Module 2: Implement an Authentication & Access Management Solution](./Module-2-Authentication-Access/)

* **2.1 Zero-Trust Conditional Access Baseline:** Emergency "Break-Glass" account exclusions, device compliance enforcement, and location-based geofencing (UK-only ingress). *`[PENDING]`
  
* **2.2 Risk-Based Step-Up Authentication:** User and sign-in risk policies targeting automated P1 credential containment.
`[PENDING]`

### [Module 3: Implement Access Management for Applications](./Module-3-Application-Access/)

* **3.1 Enterprise Application Governance:** OAuth permission classification, admin consent workflows, and workload identity monitoring.
`[PENDING]`

### [Module 4: Plan and Implement an Identity Governance Strategy](./Module-4-Identity-Governance/)

* **4.1 Privileged Identity Management (PIM):** Just-In-Time (JIT) role elevation matrices for weekend out-of-hours on-call engineers.
`[PENDING]`
  
* **4.2 Entitlement Management & Access Reviews:** Automated access packages for temporary external contractors with strict expiration boundaries.
  `[PENDING]`

## 🛡️ Architectural Principles

1. **Explicit Verification:** Every access request is evaluated on full contextual telemetry (Identity, Device Health, Location, Risk).
   
2. **Least Privilege Access:** Eliminating standing permanent administrative privileges using scoped boundaries.
   
3. **Assume Breach:** Limiting blast radiuses via strict segmentation of administrative personnel.
