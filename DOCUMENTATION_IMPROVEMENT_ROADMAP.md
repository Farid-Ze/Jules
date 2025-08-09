# Documentation Improvement Roadmap

## 1. Introduction
This document outlines the strategic roadmap for improving the documentation of the MerajutASA platform. It is based on a comprehensive audit of the `docs/` directory conducted on 2025-08-08. The goal of this roadmap is to address existing gaps, improve consistency, and ensure all documentation meets the high standards of quality, clarity, and safety required by the project's mission.

## 2. Audit Findings Summary
The audit revealed a documentation suite that is comprehensive and well-structured in many areas, but has several key areas for improvement:
*   **A significant number of documents are in a "draft" or "in_review" state.** This creates uncertainty and indicates a need to finalize the foundational documentation.
*   **There is some redundancy and repetition**, particularly in the `docs/stakeholders/academia/` section concerning security guidelines.
*   **There is a critical content gap**: A referenced `api-documentation.md` for academic stakeholders is missing, leading to broken links.
*   **There is a large volume of technical debt** in the form of markdown linting errors and likely broken links throughout the repository.

## 3. High-Level Milestones

This roadmap is broken down into four strategic milestones. Each milestone represents a major phase of work to improve the documentation.

---

### Milestone 1: Foundational Document Finalization
*   **Goal**: To move all "draft" and "in_review" documents to an "approved" state, establishing a stable and reliable baseline for the entire documentation suite.
*   **Success Metric**: 0 documents with "draft" or "in_review" status in the `docs/` directory.

**Actionable Tasks:**
*   [ ] Finalize `docs/_agents/charter.md`
*   [ ] Finalize `docs/stakeholders/academia/conference-presentations.md`
*   [ ] Finalize `docs/stakeholders/academia/data-anonymization.md`
*   [ ] Finalize `docs/stakeholders/academia/grant-opportunities.md`
*   [ ] Finalize `docs/stakeholders/academia/publication-guidelines.md`
*   [ ] Finalize `docs/stakeholders/academia/student-projects.md`
*   [ ] Finalize `docs/stakeholders/media/brand-guidelines.md`
*   [ ] ... (and all other draft documents identified in the audit).
*   [ ] Move all "in_review" documents through the final approval process, including the `collaboration-framework.md` and `ethics-guidelines.md`.

---

### Milestone 2: Structural Refactoring & Consistency
*   **Goal**: To improve the information architecture by removing redundancy and ensuring a consistent structure and language across the documentation.
*   **Success Metric**: A more streamlined and consistent documentation structure with fewer, more comprehensive documents.

**Actionable Tasks:**
*   [ ] Consolidate `data-security.md`, `research-pipeline.md`, and `service-security.md` in the `docs/stakeholders/academia/` directory into a single `academic-security-guidelines.md`.
*   [ ] Review other stakeholder directories (e.g., `business`, `community`) for similar opportunities to consolidate overlapping documents.
*   [ ] Perform a language consistency pass across all key policy and framework documents to ensure a single, clear primary language (English) is used, with translations handled as a separate concern.

---

### Milestone 3: Content Gap Fulfillment
*   **Goal**: To create essential documents that are currently missing but are referenced from other parts of the documentation.
*   **Success Metric**: Elimination of broken links to critical, non-existent documentation.

**Actionable Tasks:**
*   [ ] Create a new `api-documentation.md` file within the `docs/stakeholders/academia/` directory.
*   [ ] The new document should detail the API endpoints, authentication methods, and data schemas relevant to the academic research use case.
*   [ ] Update all documents in the `academia` directory that currently have broken links to point to the new, correct API documentation file.

---

### Milestone 4: Comprehensive Quality Assurance
*   **Goal**: To perform a full quality assurance sweep of the entire documentation repository to fix technical issues.
*   **Success Metric**: A successful (zero-error) run of the link checker and a significant reduction in linting errors.

**Actionable Tasks:**
*   [ ] Configure and run the `lychee` link checker across the entire repository to identify and fix all broken internal and external links.
*   [ ] Systematically work through the markdown linting errors reported by `markdownlint`, focusing first on the highest-level documents (`README.md`, stakeholder root guides) and then moving to more detailed pages.
*   [ ] Update the CI workflow in `docs-quality.yml` to fail on new linting errors or broken links to prevent future technical debt.
