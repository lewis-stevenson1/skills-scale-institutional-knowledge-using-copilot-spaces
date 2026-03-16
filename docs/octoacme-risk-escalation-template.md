# OctoAcme — Risk Escalation Template

## Purpose
Provide a standard process and documentation template for escalating project risks when they exceed the team's ability to resolve them independently or when their impact threatens project success.

---

## When to Escalate a Risk

Escalate a risk when any of the following conditions are met:
- The risk has been open for more than one sprint without a viable mitigation in place
- The potential impact is High and the likelihood is Medium or greater
- The mitigation requires resources, decisions, or authority outside the delivery team's control
- A risk has become an active issue affecting delivery, quality, or stakeholder commitments

---

## Escalation Levels

| Level | Trigger | Escalate To | Timeframe |
|-------|---------|-------------|-----------|
| 1 | Team can resolve with existing resources | Team standup / Risk Officer | Same sprint |
| 2 | Needs cross-team coordination or PM decision | Project Manager + Product Manager | Within 2 business days |
| 3 | Business impact or resource constraint beyond PM authority | Sponsor / Executive Stakeholder | Within 1 business day |
| 4 | Security, legal, or compliance risk | Security/Legal team + Sponsor | Immediately |

---

## Risk Escalation Record Template

Use this template to document each escalated risk. Add a new entry to the Risk Register and attach this record to the relevant project documentation.

---

**Risk ID:** _(e.g., RISK-007)_

**Date Identified:** _(YYYY-MM-DD)_

**Identified By:** _(Name and Role)_

**Risk Title:** _(Short descriptive title)_

**Risk Description:**
> Provide a clear, factual description of the risk. Include what could happen, under what conditions, and the expected timeframe.

**Category:** _(e.g., Technical / Schedule / Resource / Compliance / Vendor)_

**Impact:** High / Medium / Low

**Likelihood:** High / Medium / Low

**Risk Score:** _(Impact × Likelihood — use team-agreed scoring method)_

**Affected Areas:** _(e.g., release date, quality, team capacity, stakeholder commitments)_

**Current Mitigation Attempts:**
> Summarize what has been tried or is in progress, and why escalation is now needed.

**Requested Decision or Action:**
> Be specific about what is needed from the escalation recipient (e.g., approve additional budget, provide a decision on scope reduction, engage a third-party vendor).

**Escalation Level:** _(1 / 2 / 3 / 4)_

**Escalated To:** _(Name and Role)_

**Date Escalated:** _(YYYY-MM-DD)_

**Response Deadline:** _(YYYY-MM-DD)_

**Owner (Post-Escalation):** _(Name and Role — who is accountable for resolution)_

**Resolution / Decision Recorded:**
> _(Filled in after the escalation is resolved)_

**Date Resolved:** _(YYYY-MM-DD)_

---

## Escalation Process Steps

1. **Risk Officer** identifies that a risk meets escalation criteria.
2. **Risk Officer** completes the Risk Escalation Record above and notifies the appropriate escalation level.
3. **Project Manager** is always CC'd on Level 2+ escalations.
4. **Stakeholder Champion** is notified if the escalation affects business commitments or stakeholder expectations.
5. Escalation recipient reviews the record and provides a decision or action plan within the stated deadline.
6. **Risk Officer** updates the Risk Register with the resolution and closes or demotes the escalation.
7. Outcome is summarized in the next weekly status update and stakeholder report.

---

## Escalation Communication Template

Use this template when sending the escalation notification.

```
Subject: [RISK ESCALATION] <Risk Title> — <Project Name> — Action Required by <Date>

Hi <Escalation Recipient Name>,

We are escalating the following risk for your awareness and decision:

Risk ID: <RISK-XXX>
Project: <Project Name>
Risk: <Risk Title>
Impact: <High/Medium/Low>
Likelihood: <High/Medium/Low>

Summary:
<2–3 sentences describing the risk and why it needs escalation>

What we need from you:
<Specific decision, resource, or action required>

Response needed by: <YYYY-MM-DD>

Full details are in the attached Risk Escalation Record and the project Risk Register.

Thank you,
<Risk Officer Name>
<Contact Information>
```

---

## Related Documents
- `docs/octoacme-risks-and-communication.md` — Risk Register format and lifecycle
- `docs/octoacme-roles-and-personas.md` — Risk Officer role description
- `docs/octoacme-stakeholder-communication-templates.md` — Stakeholder communication templates
