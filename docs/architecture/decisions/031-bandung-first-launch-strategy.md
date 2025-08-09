# ADR-031: Bandung-First Launch Strategy
## A strategic decision to launch the MerajutASA platform with a geographically-focused pilot program in Bandung.

> **Decision Date**: 2025-08-09 | **Status**: Proposed
> **Child Safety Impact**: High | **Stakeholder Impact**: High
> **Decision Owner**: @wahyumumtazsyah04 | **Implementation Lead**: TBD

---

## 🎯 Context and Problem Statement

### Problem Description
The MerajutASA platform has a broad, long-term vision to serve all of Indonesia ([Source: `VISION.md`](../../../../VISION.md)). However, a direct national launch ("big bang") presents significant risks in terms of resource allocation, logistical complexity, and the ability to effectively gather feedback and iterate. The project's `ROADMAP.md` requires a clear, actionable, and measurable primary objective for Q1 2025 to focus development and operational efforts. An undocumented or ambiguous launch strategy creates a high risk of misaligned priorities and wasted effort.

### Child Welfare Considerations
- **Impact on child data protection and privacy**: A focused pilot in Bandung allows for the development and testing of robust, in-person and digital consent-gathering protocols with a manageable number of orphanages and families before scaling nationally. It localizes the risk of a potential data privacy incident.
- **Effect on accessibility for children with different abilities**: A local pilot enables direct engagement with children to test and refine the platform's accessibility features, ensuring they are effective and child-friendly.
- **Influence on emergency response capabilities**: Proximity to the pilot group allows for the rapid testing and refinement of emergency communication and response workflows between the platform and local child protection services.
- **Connection to regulatory compliance**: The pilot will serve as a testbed for implementing and validating compliance with Indonesian child protection laws in a controlled environment.

### Stakeholder Impact Analysis
#### 🏛️ Government Stakeholders
A focused pilot allows for deeper collaboration with Bandung-level government agencies (e.g., Dinas Sosial, P2TP2A), creating a model for future national-level partnerships.

#### 🏢 Business Stakeholders
The pilot provides a contained environment for corporate partners to test CSR initiatives and measure local impact, creating compelling case studies for national campaigns.

#### 🎓 Academic Stakeholders
The Bandung pilot offers a rich, well-defined cohort for longitudinal studies on the impact of a digital ecosystem on child welfare.

#### 👥 Community Stakeholders
A local launch fosters a stronger sense of community ownership and allows for more effective, targeted onboarding and support for orphanages, donors, and volunteers.

#### 📰 Media Stakeholders
The pilot provides a concrete, human-centered story ("MerajutASA in Bandung") that is more tangible and compelling for media outreach than a generic platform launch.

### Technical Context and Constraints
- The current architecture is designed for scalability, but has not yet been tested with a live, large-scale user base.
- The `ROADMAP.md` for Q1 2025 has been updated to reflect the Bandung Pilot as the primary objective, with infrastructure development as a key enabler.

### Timeline and Dependencies
This decision directly informs the Q1 2025 roadmap. All Q1 development, partnership, and community-building activities are dependent on this strategy.

---

## 🔍 Decision Drivers

### Functional Requirements
- The launch strategy must provide a real-world test of the core Penta-Helix collaboration model.
- It must allow for the collection of qualitative and quantitative feedback from all five stakeholder groups.
- It must be achievable within the Q1 2025 timeframe.

### Quality Attributes
- **Reliability**: The pilot must be stable enough to be used as the primary portal for participating orphanages.
- **Security**: All security and child safety protocols must be fully enforced.
- **Scalability**: While the pilot is local, the underlying architecture must be implemented in a way that is ready for national scaling.

### Constraints and Limitations
- **Geographic Focus**: Resources for Q1-Q2 2025 will be primarily focused on the Bandung region.
- **Communication**: The launch messaging must be carefully managed to avoid the perception that MerajutASA is a "Bandung-only" project.

### Child Protection Requirements
- The pilot must adhere to all child protection policies outlined in the `security/` directory.
- A clear protocol for reporting and responding to child safety concerns within the pilot must be established.

---

## 📊 Options Considered

### Option 1: Bandung-First Pilot (Chosen)
**Description**: Launch the full MerajutASA platform targeting all orphanages within a single, well-defined metropolitan area (Bandung) for Q1 2025. Use the learnings from this pilot to create a blueprint for a phased national rollout.

**Pros**:
- ✅ **Risk Mitigation**: Significantly de-risks a national launch by identifying issues in a controlled environment.
- ✅ **Focused Resources**: Allows for the concentration of personnel and financial resources for maximum impact.
- ✅ **Rapid Iteration**: Proximity of the core team to the pilot users enables fast feedback loops and quick iteration.
- ✅ **Strong Case Study**: A successful pilot in Bandung creates a powerful model to attract national-level stakeholders and funding.

**Cons**:
- ❌ **Delayed National Impact**: The direct, measurable national impact is deferred.
- ❌ **Perception Risk**: Could be perceived as a purely local initiative if not communicated as the first step of a national strategy.

### Option 2: National "Big Bang" Launch
**Description**: Launch the platform simultaneously across all major provinces in Indonesia, making it available to all orphanages from day one.

**Pros**:
- ✅ **Maximum Reach**: Immediately addresses the national scope of the vision.
- ✅ **Brand Impact**: A national launch could generate significant initial media attention.

**Cons**:
- ❌ **Extremely High Risk**: A single point of failure in technology or process could jeopardize the entire project.
- ❌ **Resource Intensive**: Requires a massive upfront investment in support, logistics, and marketing.
- ❌ **Slow Iteration**: Feedback would be diffuse and difficult to act upon, slowing down meaningful improvement.
- ❌ **Complex Stakeholder Management**: Managing partnerships across the entire country simultaneously would be a major challenge.

### Option 3: Feature-Based Phased Launch
**Description**: Launch a limited set of features (e.g., only donation processing) to a national audience. Add more features over time.

**Pros**:
- ✅ **Technical Simplicity**: Reduces the initial technical complexity.
- ✅ **Faster to Market**: A limited feature set could be deployed more quickly.

**Cons**:
- ❌ **Incomplete Value Proposition**: Does not test the core hypothesis of the Penta-Helix ecosystem, as stakeholders cannot fully interact.
- ❌ **Fragmented User Experience**: Users may be confused or frustrated by the lack of core functionality.
- ❌ **Doesn't Validate the Model**: Fails to prove that the holistic, multi-stakeholder approach can work.

---

## ✅ Decision Outcome

### Selected Option
**Chosen**: Option 1: Bandung-First Pilot

### Decision Rationale
The Bandung-First Pilot was selected because it provides the best balance of ambition and pragmatism. It directly aligns with the platform's mission while providing a structured, risk-managed path to achieving the long-term national vision. It prioritizes learning and iteration—critical for a project of this social complexity—over a high-risk, high-fanfare launch. This approach allows us to prove our model, refine our technology, and build strong, evidence-based case studies before scaling.

### Child Welfare Justification
This decision best serves child welfare by ensuring the platform is safe, effective, and truly meets the needs of children and orphanages before being deployed at scale. The high-touch, in-person engagement possible in a local pilot is critical for validating and refining our child safety protocols, from data privacy to emergency response. It puts the principle of "Child-First" into practice by prioritizing a safe and effective rollout over a fast one.

### Stakeholder Value Creation
- **Government**: Provides a tangible model for digital transformation in social services that can be scaled.
- **Business**: Offers a low-risk, high-impact way to engage in CSR and gather data for future investment.
- **Academic**: Creates a perfect, well-defined "laboratory" for high-quality research.
- **Community**: Empowers a local community to become a beacon for the rest of the nation.
- **Media**: Delivers a focused, compelling narrative of local impact and innovation.

### Alternative Options Rejected
- **National "Big Bang" Launch** was rejected due to the unacceptably high risk of failure and the inability to effectively iterate based on user feedback.
- **Feature-Based Phased Launch** was rejected because it fails to test the core hypothesis of the platform: the integrated, Penta-Helix collaboration model.

---

## 🚀 Implementation Guidance

### Implementation Plan
The implementation of this strategy is the primary focus of the Q1 2025 milestone outlined in the `ROADMAP.md`.

```yaml
Phase 1: Pilot Preparation (Timeline: 4 weeks)
  Activities:
    - Finalize list of all orphanages in Bandung.
    - Establish contact and secure initial partnership agreements.
    - Develop onboarding materials and training schedules.
  Deliverables:
    - A complete, verified list of pilot participants.
    - Signed MOUs with at least 50% of orphanages.
  Success Criteria:
    - 100% of Bandung orphanages contacted.

Phase 2: Stakeholder & Technical Setup (Timeline: 4 weeks)
  Activities:
    - Formalize partnerships with Bandung government and community leaders.
    - Complete setup of the pilot infrastructure (as per ROADMAP.md).
    - Launch local awareness campaign for donors and volunteers.
  Deliverables:
    - Stable pilot environment is live.
    - At least 2 formal government/community partnerships are in place.
  Success Criteria:
    - Pilot environment passes all security and performance tests.

Phase 3: Onboarding & Live Operation (Timeline: 4 weeks)
  Activities:
    - Onboard and train all participating orphanages.
    - Monitor platform usage and gather initial feedback.
    - Manage pilot-focused donation and volunteer activity.
  Deliverables:
    - Onboarding complete for all participating orphanages.
    - Active usage data and initial feedback reports.
  Success Criteria:
    - >90% of participating orphanages onboarded.
    - >50% of onboarded orphanages are actively using the platform weekly.
```

### Risk Mitigation Strategies
- **Risk**: Pilot fails to gain traction. **Mitigation**: A dedicated community manager for Bandung will drive engagement and support.
- **Risk**: Perception as a "Bandung-only" project. **Mitigation**: All external communications will explicitly frame the pilot as the first step in a national rollout, referencing the `VISION.md`.

---

## 📈 Monitoring and Success Metrics

### Business Impact Metrics
- **Orphanage Adoption Rate**: % of Bandung orphanages actively using the platform.
- **Stakeholder Engagement**: Number of active local donors, volunteers, and partners.
- **Feedback Quality**: Volume and actionability of feedback received from pilot participants.

### Monitoring Timeline and Review Schedule
- **Weekly Reviews**: Pilot team to review adoption metrics and user feedback.
- **Monthly Assessments**: Review progress against roadmap goals with all stakeholders.
- **Quarterly Evaluations**: Evaluate overall success of the pilot and make a data-driven decision on the timeline for national expansion.

---

## 🔗 Related Resources

### Related ADRs
- This ADR informs the implementation of all other technical ADRs by providing a clear initial user base and scope.

### Technical Documentation
- **ROADMAP.md**: This ADR is the justification for the Q1 2025 milestones in the [project roadmap](../../../../ROADMAP.md).
- **VISION.md**: This strategy is the first step towards achieving the national goals outlined in the [vision document](../../../../VISION.md).

---

## 📝 Decision History and Updates
- **2025-08-09**: Proposed by the core team to provide strategic focus for the Q1 2025 launch. Awaiting review from stakeholder representatives.
