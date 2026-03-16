# OctoAcme — Stakeholder Communication Templates

## Purpose
Provide ready-to-use templates for common stakeholder communication scenarios so that project teams can communicate consistently, clearly, and at the right cadence.

---

## Stakeholder Identification & Communication Plan

Before using the templates below, complete this stakeholder communication plan at project initiation:

| Stakeholder Group | Key Contacts | Interest / Need | Communication Frequency | Preferred Channel | Responsible Role |
|-------------------|-------------|-----------------|------------------------|-------------------|-----------------|
| Executive Sponsors | | Strategic alignment, budget, risk | Monthly | Executive briefing | Project Manager |
| Business Units | | Roadmap, feature status, impacts | Bi-weekly | Email / Meeting | Stakeholder Champion |
| Engineering Leads | | Technical decisions, dependencies | Weekly | Sync meeting | Project Manager |
| Support / Operations | | Release impacts, runbooks | Per release | Release notes | Release Coordinator |
| End Users / Customers | | Feature launches, changes | Per release | Announcement | Product Manager |

---

## Template 1: Weekly Status Update

**Audience:** Project team, Product Manager, key stakeholders  
**Sent by:** Project Manager  
**Frequency:** Weekly (typically end of week)

```
Subject: [Weekly Status] <Project Name> — Week of <Date>

**Overall Status:** 🟢 On Track / 🟡 At Risk / 🔴 Off Track

**Progress This Week:**
- <Completed item 1>
- <Completed item 2>

**Planned for Next Week:**
- <Upcoming item 1>
- <Upcoming item 2>

**Risks & Blockers:**
- <Risk/Blocker 1> — Owner: <Name>, Status: <Active/Mitigated>
- <Risk/Blocker 2> — Owner: <Name>, Status: <Active/Mitigated>

**Decisions Needed / Asks:**
- <Decision or action required from stakeholder(s)>

**Key Metrics (if applicable):**
- Velocity: <value>
- Open defects: <count>
- Release readiness: <% complete>

Questions or concerns? Reply to this email or reach out to <Project Manager Name>.
```

---

## Template 2: Monthly Stakeholder Briefing

**Audience:** Executive sponsors, business unit leads  
**Sent by:** Project Manager + Stakeholder Champion  
**Frequency:** Monthly or at major milestones

```
Subject: [Monthly Briefing] <Project Name> — <Month YYYY>

Hi <Stakeholder Name(s)>,

Here is the monthly update for <Project Name>.

**Milestone Progress:**
| Milestone | Target Date | Status | Notes |
|-----------|------------|--------|-------|
| <Milestone 1> | <Date> | 🟢/🟡/🔴 | <Notes> |
| <Milestone 2> | <Date> | 🟢/🟡/🔴 | <Notes> |

**Highlights:**
- <Key achievement or decision this month>
- <Another highlight>

**Risks & Issues (Summary):**
- <High-level risk summary — full details in Risk Register>

**Upcoming (Next 30 Days):**
- <Planned release or milestone>
- <Upcoming stakeholder touchpoint>

**Feedback Requested:**
- <Specific question or decision that requires stakeholder input>

Full project status is available at: <link to project board or doc>

Thank you,
<Project Manager Name> & <Stakeholder Champion Name>
```

---

## Template 3: Release Announcement

**Audience:** Internal stakeholders, support team, and end users (as appropriate)  
**Sent by:** Release Coordinator + Product Manager  
**Frequency:** Per release

```
Subject: [Release] <Project Name> v<Version> — Released on <Date>

Hi <Audience>,

We are pleased to announce the release of <Project Name> v<Version>, deployed on <Date>.

**What's New:**
- <Feature or fix 1>
- <Feature or fix 2>

**What to Watch For:**
- <Any behavior change, migration step, or known issue>

**Rollback Plan:**
- If issues are encountered, contact <on-call contact> or follow the runbook at: <link>

**Support:**
- For questions or issues, contact <support channel or email>

Thank you for your continued support of this project.

<Release Coordinator Name> | <Product Manager Name>
```

---

## Template 4: Risk Escalation Stakeholder Notice

**Audience:** Business stakeholder, sponsor, or executive  
**Sent by:** Risk Officer (with Project Manager CC)  
**Trigger:** Level 3–4 escalation per `docs/octoacme-risk-escalation-template.md`

```
Subject: [Risk Notice] <Risk Title> — <Project Name> — Response Needed by <Date>

Hi <Stakeholder Name>,

We are bringing the following risk to your attention as it may impact <business commitment / timeline / budget>.

**Risk Summary:**
- Risk ID: <RISK-XXX>
- Description: <Brief description>
- Potential Impact: <What could happen>
- Likelihood: High / Medium / Low

**Current Status:**
<What the team has tried and why escalation is needed>

**What We Need from You:**
<Specific decision, resource approval, or directive>

**Response Needed By:** <YYYY-MM-DD>

Full details are in the Risk Register: <link>

Please reply to this email or contact <Risk Officer Name> at <contact>.

Thank you,
<Risk Officer Name>, Risk Officer
CC: <Project Manager Name>
```

---

## Template 5: Retrospective Stakeholder Summary

**Audience:** Sponsors and business stakeholders  
**Sent by:** Stakeholder Champion  
**Frequency:** After each sprint retrospective or major milestone retrospective

```
Subject: [Retro Summary] <Project Name> — <Sprint/Milestone Name>

Hi <Stakeholder Name(s)>,

Following our retrospective for <Sprint/Milestone Name>, here is a brief summary for your awareness.

**What Went Well:**
- <Item 1>
- <Item 2>

**Areas for Improvement:**
- <Item 1>
- <Item 2>

**Action Items (with owners):**
| Action Item | Owner | Due Date |
|-------------|-------|----------|
| <Action 1> | <Name> | <Date> |
| <Action 2> | <Name> | <Date> |

These improvements are now tracked in the project backlog. We will report on progress in the next monthly briefing.

Thank you,
<Stakeholder Champion Name>
```

---

## Related Documents
- `docs/octoacme-risks-and-communication.md` — Risk management and communication overview
- `docs/octoacme-risk-escalation-template.md` — Detailed risk escalation process
- `docs/octoacme-roles-and-personas.md` — Stakeholder Champion and other role descriptions
- `docs/octoacme-release-and-deployment.md` — Release notes and deployment checklists
