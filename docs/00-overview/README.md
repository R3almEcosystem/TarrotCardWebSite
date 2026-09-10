---
title: "TarrotCardWebSite — TarrotCardWebSite Documentation Hub"
application_id: "tarrotcardwebsite"
repository: "R3almEcosystem/TarrotCardWebSite"
application_version: "0.1.0"
document_status: "Baseline"
last_reviewed: "2026-09-10"
next_review: "2026-12-10"
---

# TarrotCardWebSite Documentation Hub

> TarrotCardWebSite · Platform · Pre-Alpha

TarrotCardWebSite is cataloged as a Platform application focused on interactive card-reading experiences.

> **Baseline notice:** This document defines the expected operating standard. It does not claim that a control, integration, model, or certification is already implemented; verify the code, configuration, and production evidence before release.

## Quick reference

| Field | Value |
| --- | --- |
| Application ID | `tarrotcardwebsite` |
| Repository | `R3almEcosystem/TarrotCardWebSite` |
| Catalog version | `0.1.0` |
| Lifecycle | Pre-Alpha |
| Domain | interactive card-reading experiences |
| Declared technology | Not yet declared |
| Primary record | Reading |

## Product intent

The working objective is to provide a transparent, respectful interactive card experience. The core lifecycle is **start session → select cards → interpret → review**. Repository implementation and approved product specifications remain authoritative when they are more specific than this baseline.

## Documentation map

| Layer | Documents |
| --- | --- |
| 00 Overview | [Vision](./VISION.md) |
| 01 Architecture | [Architecture](../01-architecture/ARCHITECTURE.md) · [System design](../01-architecture/SYSTEM_DESIGN.md) · [Integration map](../01-architecture/INTEGRATION_MAP.md) |
| 02 Engineering | [Setup](../02-engineering/SETUP.md) · [Contributing](../02-engineering/CONTRIBUTING.md) · [Coding standards](../02-engineering/CODING_STANDARDS.md) · [ADRs](../02-engineering/ADR.md) |
| 03 Data | [Database schema](../03-data/DATABASE_SCHEMA.md) · [Data model](../03-data/DATA_MODEL.md) · [Lineage](../03-data/DATA_LINEAGE.md) · [Sources](../03-data/DATA_SOURCES.md) |
| 04 AI systems | [AI architecture](../04-ai-systems/AI_ARCHITECTURE.md) · [Model registry](../04-ai-systems/MODEL_REGISTRY.md) · [Model governance](../04-ai-systems/MODEL_GOVERNANCE.md) |
| 05 Security & compliance | [Security](../05-security-compliance/SECURITY.md) · [Access control](../05-security-compliance/ACCESS_CONTROL.md) · [Data governance](../05-security-compliance/DATA_GOVERNANCE.md) · [Compliance](../05-security-compliance/COMPLIANCE_ALIGNMENT.md) |
| 06 Operations | [Deployment](../06-operations/DEPLOYMENT.md) · [Environments](../06-operations/ENVIRONMENTS.md) · [Runbook](../06-operations/RUNBOOK.md) · [Monitoring](../06-operations/MONITORING.md) |
| 07 Product | [Roadmap](../07-product/ROADMAP.md) · [Feature specifications](../07-product/FEATURE_SPECIFICATIONS.md) · [User flows](../07-product/USER_FLOWS.md) |
| 08 Governance | [Protocol governance](../08-governance/PROTOCOL_GOVERNANCE.md) · [Risk framework](../08-governance/RISK_FRAMEWORK.md) · [Audit trail](../08-governance/AUDIT_TRAIL_SPEC.md) |

## Ownership

Repository maintainers own technical accuracy. Product, security, data, compliance, and operations owners approve the sections in their domains. Material changes are versioned in Git and linked to an ADR, issue, or change record.
