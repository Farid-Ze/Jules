---
title: "Academic Collaboration Framework"
summary: "How academia partners collaborate with MerajutASA within the penta-helix model: roles, governance, mechanisms, cadence, and compliance."
audience: ["academia","administrators"]
stakeholder: ["academia"]
owner: "@academic-collab-lead"
status: "in_review"
version: "0.1.0"
last_reviewed: "2025-08-08"
tags: ["child-safety","accessibility","compliance","governance"]
---

# Academic Collaboration Framework

## Purpose
This document defines a safe, effective, and compliant framework for university and research partners to collaborate with MerajutASA. It is aligned with the platform’s multi-stakeholder model and its core mission of child safety.

## Scope & Audience
- **Audience**: This guide is for academic leaders (deans, center directors), faculty, Principal Investigators (PIs), students, and research administrators.
- **Scope**: This framework covers research projects, student engagements, publications, grant pursuits, and knowledge transfer that use de-identified data and sandbox APIs.

## Prerequisites
Before using this framework, we recommend that you familiarize yourself with the overall project by reading:
- The main project [README.md](../../../README.md) for a high-level overview.
- The project's [VISION.md](../../../VISION.md) to understand our mission and goals.

## Key Facts (Grounded)
This framework is built upon several core documents. Please ensure you are familiar with the following:
- **Overall Governance**: Our [Stakeholder Collaboration Framework](../collaboration-framework.md) and [Governance Model](../governance-model.md).
- **Ethics & Safety**: The foundational [Ethics & Child Protection Guidelines](./ethics-guidelines.md).
- **Data Handling**: The procedures for [Data Access](./research-data-access.md) and [Data De-identification](./data-anonymization.md).
- **API Usage**: The technical specifications for our [Academic APIs](./api-documentation.md).
- **Platform Standards**: Our repository-wide [Style Guide](../../STYLE_GUIDE.md), [Translation Guide](../../TRANSLATION_GUIDE.md), and [Review Process](../../REVIEW_PROCESS.md).
- **Core Architectural Decisions**: Our standards for [Documentation (ADR-011)](../../architecture/decisions/011-documentation-platform.md), [Security (ADR-013)](../../architecture/decisions/013-security-framework.md), and [Accessibility (ADR-014)](../../architecture/decisions/014-accessibility-standards.md).
- **Compliance**: Our principles of [Privacy by Design](../../architecture/compliance/privacy-by-design.md) and our [Audit Trail capabilities](../../architecture/compliance/audit-trail.md).

## Collaboration model
- Principles: child‑first, evidence‑based, privacy‑preserving, documentation‑first, accessibility by default.
- Modes: research collaboration, student projects, grant proposals, shared publications and conference dissemination.

## Roles & responsibilities
- Academic Collaboration Lead: overall coordination; ensures compliance with ethics, security, and documentation standards.
- Principal Investigator (PI): scientific leadership; IRB/DUA compliance; deliverables.
- Data Steward (MerajutASA): dataset provisioning; de‑identification patterns; access monitoring.
- Ethics & Privacy Liaison: IRB coordination; DPIA guidance; review of dissemination materials.
- Security Admin: identities, repository controls, enclaves; incident response alignment.
- Accessibility/Docs Reviewer: ADR‑014 checks; style and translation reviews.

## Working groups (cross‑functional)
- Research Design WG
  - Scope: study design, variables (minimization), methods transparency.
  - References: ./research-data-access.md, ADR‑012 ../../api/decisions/012-testing-strategy.md.
- Data Access & Stewardship WG
  - Scope: dataset readiness, codebooks, transformations, small‑cell controls.
  - References: ./research-data-access.md#6-dataset-provisioning-patterns, ./data-anonymization.md.
- Publications & Dissemination WG
  - Scope: manuscripts, posters, slides, plain‑language summaries; accessibility checks.
  - References: ./publication-guidelines.md, ADR‑014, ../../STYLE_GUIDE.md, ../../TRANSLATION_GUIDE.md.
- Student Engagement WG
  - Scope: capstones, theses, practicums; sandbox access; supervision and reviews.
  - References: ./student-projects.md, ./api-documentation.md.
- Grants & Partnerships WG
  - Scope: funding triage, compliance resourcing, deliverable acceptance criteria.
  - References: ./grant-opportunities.md, ADR‑011/012.

## Coordination cadence
- Weekly: WG stand‑ups (30‑45 min) – blockers, decisions needed, small‑cell/ethics checks in progress. Log in WG notes per ../../REVIEW_PROCESS.md.
- Monthly: Academic Collaboration Council (60‑90 min) – portfolio status, risk review (privacy/security), accessibility and documentation metrics.
- Quarterly: Stakeholder summit (half day) – impact review, lessons learned, roadmap; aligned with ../collaboration-framework.md.

## How‑To / Steps
1) Propose
   - Submit concept (purpose, variables, risks/mitigations) – ./research-data-access.md.
2) Approve
   - Ethics (IRB), Privacy (DPIA need), Security (enclave/repo), Docs (style/translation) – ./ethics-guidelines.md, ADR‑013/014, ../../REVIEW_PROCESS.md.
3) Provision
   - Study workspace, credentials, dataset seeding, monitoring – ./research-data-access.md#7-api-access-contract-academic-v1, ../../architecture/compliance/audit-trail.md.
4) Execute
   - Documentation‑first; tests as applicable; regular WG check‑ins – ADR‑011/012.
5) Disseminate
   - Follow ./publication-guidelines.md and ./conference-presentations.md; ensure accessibility and small‑cell rules.
6) Close
   - Revoke access; archive approvals/logs; publish summaries in Bahasa Indonesia – ./publication-guidelines.md, ../../TRANSLATION_GUIDE.md.

## Deliverables & acceptance
- Evidence packet per ../../REVIEW_PROCESS.md with ethics/DUA refs, small‑cell analysis, accessibility checks, and links to codebooks/methods.
- Acceptance criteria: compliant outputs (no microdata), accessibility pass (ADR‑014), security/privacy sign‑offs (ADR‑013), style/translation adherence.

## Accessibility & Child Safety
- Inclusive, non‑stigmatizing language; alt text and high contrast; avoid imagery that could reveal identities.
- Escalate any discovered risk of harm per ./ethics-guidelines.md.

## Validation & Monitoring
- Immutable access logs and anomaly alerts – ../../architecture/compliance/audit-trail.md.
- Periodic review of WG metrics and documentation health – ADR‑011; ../../REVIEW_PROCESS.md.

## Related
- Parent: ../collaboration-framework.md, ../communication-protocols.md, ../governance-model.md
- Academia: ./research-data-access.md, ./data-anonymization.md, ./publication-guidelines.md, ./student-projects.md, ./grant-opportunities.md, ./conference-presentations.md

## Changelog
- 0.1.0 (2025-08-08): Initial draft grounded to parent framework, ethics, data access, ADR‑011/012/013/014, privacy-by-design, audit trail, style, translation, and review process.
