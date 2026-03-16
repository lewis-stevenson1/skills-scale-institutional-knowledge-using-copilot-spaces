# OctoAcme Personas

This document defines typical roles and responsibilities used in OctoAcme project docs and exercises.

---

## Developers

### Role Summary
Developers design, build, test, and deliver software components. They collaborate with product and project leads to implement features that meet acceptance criteria and quality standards.

### Responsibilities
- Implement features and fixes to meet acceptance criteria
- Write and maintain tests and documentation
- Participate in design and code reviews
- Assist in estimating and planning work
- Help identify technical risks and propose mitigations

### Goals
- Deliver reliable, maintainable code
- Reduce cycle time from idea to production
- Maintain high test coverage and observability

### Typical Communication
- Daily standups and sprint planning
- PR descriptions and code review comments
- Technical design docs when needed

---

## Product Managers

### Role Summary
Product Managers define what should be built to deliver customer and business value. They own the product vision, prioritize the backlog, and measure outcomes.

### Responsibilities
- Define problem statements and success metrics
- Prioritize the roadmap and backlog
- Collaborate with stakeholders and engineering on trade-offs
- Validate solutions through user research and metrics

### Goals
- Maximize customer value and impact
- Make clear, data-driven prioritization decisions
- Ensure product-market fit and usability

### Typical Communication
- Weekly alignment with PM and engineering leads
- Roadmap updates and stakeholder briefings
- Acceptance criteria and feature specs

---

## Project Managers

### Role Summary
Project Managers coordinate delivery activities, manage schedules, risks, and communications. They enable the team to deliver on commitments efficiently.

### Responsibilities
- Create and maintain project plans and timelines
- Manage risks, dependencies, and resource constraints
- Facilitate meetings (kickoff, planning, retrospectives)
- Ensure consistent project documentation and status reporting
- Coordinate cross-team and stakeholder communication

### Goals
- Deliver projects on time and within scope
- Minimize unplanned work and escalations
- Maintain transparency and alignment across stakeholders

### Typical Communication
- Weekly status updates and stakeholder reports
- Risk registers and decision logs
- Coordination via project boards and meeting facilitation

---

## Release Coordinator

### Role Summary
The Release Coordinator owns the release calendar and ensures that all pre-release criteria, communications, and cross-team timelines are met before any deployment goes live.

### Responsibilities
- Maintain and communicate the release calendar across teams
- Coordinate timelines and readiness sign-offs with engineering, QA, and Product Manager
- Verify that all pre-release criteria are satisfied before deployment begins
- Draft and distribute release announcements to internal and external stakeholders
- Manage the deployment window scheduling and rollback readiness confirmation

### Goals
- Ensure smooth, predictable, and well-communicated releases
- Reduce last-minute surprises and release-day incidents
- Provide a single point of coordination for release activities

### Typical Communication
- Pre-release readiness meetings with PM, QA Lead, and Product Manager
- Release calendar updates shared with all relevant teams
- Post-release notifications and incident summaries when applicable

### Interactions with Existing Roles
- **Project Manager:** Aligns release dates with overall project milestones and resource constraints
- **QA Lead:** Confirms acceptance testing is complete and sign-off is obtained before release
- **Product Manager:** Validates feature readiness and stakeholder notification needs
- **Developers:** Coordinates merge freeze windows and deployment packaging

---

## Risk Officer

### Role Summary
The Risk Officer maintains the project risk register, facilitates risk review sessions, monitors mitigation progress, and leads escalation procedures when risks materialize.

### Responsibilities
- Own and maintain the Risk Register with current status, impact, and mitigation details
- Facilitate regular risk review sessions (at minimum weekly or at milestones)
- Track mitigation actions and follow up with owners on progress
- Lead risk escalation procedures when thresholds are breached
- Provide risk summary updates at delivery syncs and stakeholder reports

### Goals
- Ensure risks are identified early and mitigated proactively
- Maintain a transparent and up-to-date view of project risk posture
- Reduce the frequency and impact of unplanned issues

### Typical Communication
- Weekly risk review updates shared with PM and relevant stakeholders
- Escalation notices when risks become issues
- Risk summary section in stakeholder reports

### Interactions with Existing Roles
- **Project Manager:** Collaborates daily on risk identification and escalation decisions
- **Stakeholder Champion:** Coordinates on communicating risk impacts to business stakeholders
- **Product Manager:** Aligns on risk trade-offs affecting roadmap or scope decisions
- **Developers:** Gathers technical risk input and tracks mitigation action items

---

## QA Lead

### Role Summary
The QA Lead oversees test planning, manages the QA team or process, and validates that features meet acceptance criteria before and after release.

### Responsibilities
- Create and maintain the test plan, including unit, integration, regression, and end-to-end test coverage
- Manage QA team assignments and testing workflows across sprints and releases
- Validate acceptance criteria for each user story or feature before sign-off
- Coordinate post-release smoke testing and regression verification
- Report quality metrics and unresolved defects to the Project Manager and Product Manager

### Goals
- Ensure high product quality at every release
- Reduce defect escape rate to production
- Maintain a clear, shared definition of "done" from a quality perspective

### Typical Communication
- Sprint review and pre-release sign-off meetings with PM and Developers
- Test plan and defect reports shared with the delivery team
- QA readiness confirmation to the Release Coordinator before each release

### Interactions with Existing Roles
- **Developers:** Reviews acceptance criteria, provides feedback on testability, and validates fixes
- **Project Manager:** Reports testing status, blockers, and quality risks
- **Release Coordinator:** Provides final QA sign-off needed before release deployment
- **Product Manager:** Validates that acceptance criteria align with user expectations

---

## Stakeholder Champion

### Role Summary
The Stakeholder Champion represents the interests of the business stakeholder group, synthesizes feedback from business units, and acts as the primary liaison between stakeholders and the project team.

### Responsibilities
- Represent stakeholder interests in project planning and decision-making
- Gather and synthesize feedback from business units and executive sponsors
- Coordinate roadmap alignment and requirements clarification with the Product Manager
- Attend retrospectives and release reviews on behalf of the stakeholder community
- Escalate business-impact concerns to the appropriate project leads

### Goals
- Ensure stakeholder needs are accurately understood and reflected in project outcomes
- Reduce miscommunication between business and delivery teams
- Improve stakeholder satisfaction and confidence in project execution

### Typical Communication
- Regular check-ins with business units to gather feedback and communicate project status
- Monthly or milestone-based stakeholder briefings alongside the Product Manager
- Feedback summaries shared with the Project Manager and Product Manager after review sessions

### Interactions with Existing Roles
- **Product Manager:** Collaborates on requirements gathering, prioritization, and roadmap updates
- **Project Manager:** Provides stakeholder perspective on risk, scope, and timeline trade-offs
- **Risk Officer:** Coordinates on communicating risk posture to business stakeholders
- **Developers:** Relays business context for features to help teams understand user impact

---

## How these personas are used in the exercise
- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance.
- The expanded roles (Release Coordinator, Risk Officer, QA Lead, Stakeholder Champion) close gaps in accountability for release management, quality assurance, risk oversight, and stakeholder communication.

