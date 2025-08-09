---
title: "MerajutASA Platform Roadmap"
summary: "Development milestones and strategic initiatives for advancing child welfare through penta-helix collaboration"
audience: ["developers", "administrators", "government", "business", "academia", "community", "media"]
stakeholder: ["government", "business", "academia", "community", "media"]
owner: "@wahyumumtazsyah04"
status: "approved"
version: "1.0.0"
last_reviewed: "2025-08-08"
tags: ["child-safety", "architecture", "compliance", "roadmap"]
---

# MerajutASA Platform Roadmap

## Purpose
Provide transparent visibility into platform development priorities that advance child welfare outcomes through systematic penta-helix stakeholder collaboration, architectural improvements, and impact measurement capabilities.

## Scope & Audience
- **Covered**: Near-term development milestones, architectural decisions, stakeholder-focused initiatives
- **Audience**: All penta-helix stakeholders requiring development visibility
- **Not Covered**: Detailed implementation specifications (see ADRs), operational metrics (see impact dashboards)

## Links

### Architectural Decisions (ADRs)
- [docs/architecture/decisions/README.md](docs/architecture/decisions/README.md) — Comprehensive architectural decision documentation with 30+ ADRs covering technology stack, security framework, and platform choices
- [docs/architecture/decisions/009-deployment-orchestration.md](docs/architecture/decisions/009-deployment-orchestration.md) — GitOps deployment strategy with ArgoCD implementation timeline and child safety considerations
- [docs/architecture/decisions/022-performance-monitoring-selection.md](docs/architecture/decisions/022-performance-monitoring-selection.md) — DataDog APM selection for comprehensive performance monitoring and stakeholder-specific dashboards

### Monitoring Dashboards
- [monitoring/dashboards/impact/README.md](monitoring/dashboards/impact/README.md) — Impact dashboard index enabling measurement of child welfare outcomes and stakeholder value creation
- [monitoring/dashboards/stakeholder/media/media-engagement-dashboard.md](monitoring/dashboards/stakeholder/media/media-engagement-dashboard.md) — Media engagement metrics and performance tracking dashboard

### Governance & Standards
- [GOVERNANCE.md](GOVERNANCE.md) — Penta-helix governance framework with decision-making processes and stakeholder collaboration structure
- [docs/STYLE_GUIDE.md](docs/STYLE_GUIDE.md) — Documentation standards ensuring child-safety-first, accessible content creation
- [docs/stakeholders/](docs/stakeholders/) — Stakeholder-specific documentation and engagement frameworks

## Milestones

### Short-term: Q1 2025 — Bandung Pilot Launch & Community Onboarding
**Goal**: To validate the MerajutASA platform's core functionality and value proposition by successfully onboarding all orphanages in Bandung, establishing `MERAJUTASA.id` as their primary portal for stakeholder collaboration. This milestone serves as the first concrete step towards the strategic objective of onboarding 100 orphanages across Indonesia ([Source: `VISION.md`](./VISION.md)).
- **Deliverables**:
  - **Orphanage Onboarding**: Achieve >90% onboarding rate for all identified orphanages within the Bandung region.
  - **Stakeholder Engagement**: Establish formal collaboration with key Bandung-level government agencies (e.g., Dinas Sosial) and community leaders.
  - **Community Launch**: Execute a targeted awareness campaign for local donors, volunteers, and media partners in the Bandung area.
  - **Feedback & Iteration**: Collect and synthesize feedback from all pilot participants to create a prioritized backlog for Q2 2025 development.
- **Success Criteria**: >80% of onboarded orphanages actively using the platform weekly; measurable increase in local donation and volunteer engagement; 3+ formal stakeholder partnerships established; comprehensive feedback report delivered.
- **Child Safety Impact**: Direct, in-person engagement with a focused group of orphanages allows for rapid feedback on and iteration of child safety protocols, ensuring our digital and physical safety measures are effective before a national rollout.

### Key Enabler: Platform Infrastructure Foundation
**Goal**: Establish robust deployment and monitoring infrastructure **to support the Bandung Pilot Launch** and ensure reliable, secure, and scalable child welfare service delivery.
- **Deliverables**: 
  - **GitOps Deployment Implementation** (4-month timeline per [docs/architecture/decisions/009-deployment-orchestration.md](docs/architecture/decisions/009-deployment-orchestration.md))
    - Phase 1: ArgoCD foundation setup with RBAC and secret management (Month 1)
    - Phase 2: Multi-environment orchestration with blue-green deployment to support pilot testing and production launch (Month 2)
    - Phase 3: Security integration and stakeholder workflows tailored for pilot users (Month 3)
    - Phase 4: Performance optimization and team training (Month 4)
  - **Performance Monitoring Deployment** (3-month timeline per [docs/architecture/decisions/022-performance-monitoring-selection.md](docs/architecture/decisions/022-performance-monitoring-selection.md))
    - Month 1: DataDog APM core setup with distributed tracing for all services.
    - Month 2: Advanced configuration with dashboards specifically monitoring the health and performance of the Bandung pilot.
    - Month 3: Optimization and comprehensive team training.
- **Success Criteria**: 99.9% deployment success rate for pilot-related services; zero-downtime deployments; 100% service monitoring coverage for the pilot environment.
- **Child Safety Impact**: Reliable infrastructure ensures continuous availability of child protection services and provides the stable foundation required for a safe and successful pilot launch.

### Mid-term: Q2 2025 — Impact Measurement & Optimization
**Goal**: Operationalize comprehensive impact dashboards and performance-driven optimization for child welfare outcomes
- **Deliverables**:
  - **Impact Dashboard Integration** per [monitoring/dashboards/impact/README.md](monitoring/dashboards/impact/README.md)
    - Deploy stakeholder-specific performance dashboards with real-time metrics
    - Establish baseline metrics for child safety and penta-helix collaboration effectiveness
    - Implement automated reporting for government compliance and media transparency
  - **Performance-Driven Optimization**
    - 25% platform performance improvement through monitoring insights
    - Real-time emergency response system optimization (<1 second response time)
    - Child data access performance optimization (50% faster access during emergencies)
- **Success Criteria**: Real-time dashboard availability, >95% stakeholder adoption, 99.95% platform availability
- **Child Safety Impact**: Data-driven optimization of child protection services with measurable welfare outcome improvements

## Accessibility & Child Safety
All roadmap initiatives prioritize:
- **Child Protection**: Every milestone includes explicit child safety impact assessment
- **Accessibility**: WCAG 2.1 AA compliance for all stakeholder-facing deliverables  
- **Privacy by Design**: Implementation follows security policies in [security/](security/) directory
- **Cultural Sensitivity**: Development respects Indonesian context and community values

## Review Cadence

### Regular Assessment Schedule
- **Monthly Reviews**: Progress assessment against milestone success criteria with technical team leads and domain experts per [GOVERNANCE.md](GOVERNANCE.md)
- **Quarterly Stakeholder Reviews**: Comprehensive stakeholder feedback collection and roadmap adjustment with penta-helix representatives
- **Bi-annual Strategic Review**: Strategic alignment assessment with child welfare objectives and platform evolution planning

### Review Process Alignment
- **ADR Updates**: Roadmap milestone completion triggers related ADR status updates and implementation outcome documentation
- **Dashboard Integration**: Review process informed by real-time metrics from [monitoring/dashboards/impact/README.md](monitoring/dashboards/impact/README.md)
- **Governance Compliance**: All reviews follow governance framework in [GOVERNANCE.md](GOVERNANCE.md) with child safety and stakeholder value assessment

### Decision Evolution Triggers
- Performance metrics indicating need for milestone adjustment or acceleration
- Stakeholder feedback requiring roadmap scope or timeline modification
- Child safety requirements necessitating priority changes or additional milestones
- Technology evolution opportunities for enhanced child welfare service delivery

## Validation & Monitoring
- **Monthly Reviews**: Progress assessment against defined success criteria
- **Stakeholder Feedback**: Quarterly collection via established channels in [docs/stakeholders/](docs/stakeholders/)
- **Impact Measurement**: Continuous tracking via [monitoring/dashboards/impact/](monitoring/dashboards/impact/)
- **Course Correction**: Adaptive planning based on child welfare outcome data

## Changelog
- 1.0.0 (2025-08-08): Finalized roadmap with concrete milestones aligned to ADR-009 (GitOps deployment) and ADR-022 (DataDog APM) implementation timelines, added review cadence section, updated links to specific ADRs and monitoring dashboards
- 0.1.0 (2025-08-08): Initial roadmap structure with Q1-Q2 2025 milestones linked to architectural decisions and impact measurement capabilities