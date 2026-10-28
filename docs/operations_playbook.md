# Customer Success & Support Operations Playbook

> **Simulation:** All scenarios are fictional. This document is a learning artifact, not an internal Recruit CRM policy.

## 1. Standard ticket workflow
1. **Acknowledge:** Confirm the user's issue and the business impact.
2. **Clarify:** Ask for the specific page/workflow, expected result, observed result, when it began, and whether it affects one or many users.
3. **Reproduce safely:** Use a test workspace or approved sample data; never ask for passwords or sensitive candidate information.
4. **Triage:** Select priority based on impact, scope, urgency, and availability of a safe workaround.
5. **Resolve or guide:** Give numbered steps in plain language and check whether the user can complete them.
6. **Escalate:** Transfer with a concise summary, evidence, attempted steps, impact, and customer expectation.
7. **Close the loop:** Confirm outcome, document root cause if known, and share prevention guidance.

## 2. Suggested priority rubric

| Priority | Example | Response approach |
|---|---|---|
| Urgent | Suspected security incident, data loss, or widespread critical outage | Follow security/incident process immediately; notify responsible lead; do not improvise a fix. |
| High | A core workflow blocked for multiple users with no workaround | Acknowledge promptly, gather impact, escalate to the appropriate owner, give update cadence. |
| Normal | One user blocked but a safe workaround exists | Troubleshoot with clear steps; agree on follow-up if unresolved. |
| Low | How-to question or cosmetic issue with little business impact | Explain the supported workflow; provide documentation and invite follow-up. |

The rubric is illustrative. Real teams must use their own approved severity definitions and service-level agreements.

## 3. Escalation triggers
- Possible exposure of candidate/client data, account compromise, or permission bypass.
- Data appears lost, duplicated at scale, or incorrectly assigned across workspaces.
- A widespread outage or a critical workflow is blocked for multiple users.
- The issue reproduces after standard troubleshooting or appears to be a product defect.
- Billing, contract, legal, or security decisions require an authorised specialist.

## 4. Customer communication standards
- Start with a short acknowledgement and reflect the impact.
- Ask one or two focused questions rather than sending a long checklist immediately.
- Avoid blame and unexplained jargon.
- Separate confirmed facts from hypotheses.
- Never promise a fix time unless an authorised owner has confirmed it.
- Give a workaround only when it is safe, approved, and does not risk data integrity.
- State the next action, owner, and when the customer can expect an update.

## 5. Ticket note template
- **Issue:** What is failing?
- **Impact/scope:** Who is affected and which recruitment workflow is blocked?
- **Expected vs observed:** What should happen and what happened instead?
- **Environment/context:** Page, browser, time zone, relevant timestamps, and non-sensitive error text.
- **Steps attempted:** What was checked and what changed?
- **Priority rationale:** Impact, urgency, scope, and workaround.
- **Next action/owner:** Who will do what by when?
- **Customer update:** What has been communicated?

## 6. Example metrics
- First response time: time from ticket creation to first human response.
- Resolution time: elapsed time until the issue is resolved; define whether waiting time is included.
- Backlog: unresolved tickets at a point in time, segmented by age and priority.
- Reopen rate: resolved tickets reopened within a chosen period.
- Customer satisfaction: survey response and score, with response rate shown.
- Escalation rate: tickets transferred to another team, interpreted alongside issue complexity.

Metrics in the portfolio dashboard come from synthetic data and are not real operational performance. Do not optimise for speed by sacrificing clarity or resolution quality.

## 7. Fictional scenario: candidate import fails
1. Acknowledge that the import blocks the recruiter from finding candidate records.
2. Ask for the non-sensitive error text, file template version, approximate time, and whether every row or only some rows failed.
3. Check column names, required fields, date formats, duplicates, and result counts.
4. Ask the customer to test a small, approved sample rather than repeatedly importing the full file.
5. If it still fails, escalate with the template, sanitized example row, exact steps, and impact.
6. Confirm the count imported/skipped/failed and ensure the customer can find the expected test record.
