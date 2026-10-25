# Templates

Use the organisation's own template when one exists. Use these when none exists.

## Project record (one page for each project)

**Project:** name · **Key:** · **Updated:** YYYY-MM-DD
**Phase:** · **Types:** for example solo builder, AI feature, web app
**Roles:** PM = … (also sponsor, product owner, user, approver) · Builder = … · Independent reviewer = …
**Tools:** ticket system and project key · **Repository:** · **CI:**
**Items not applicable:** item, reason.
**Light items:** item, what the light version is.
**Open gate conditions:** condition, owner, date.
**Status cadence:** weekly, or at each sprint review for a project shorter than 2 weeks.
**Last health check:** date, score, top gaps.
**Reminders:** name, date.

## Problem statement

**Who has the problem:** · **What the problem is:** · **How often, and the cost today:**
**What success looks like (measure, baseline, target):** · **Not in scope:**

## Charter

**Project:** name · **Sponsor:** · **PM:** · **Date:**
1. **Goal:** one sentence.
2. **Background and problem:** link to the problem statement.
3. **Scope / not in scope:**
4. **Deliverables:**
5. **Success measures:** measure, baseline, target.
6. **Milestones:** milestone, date.
7. **Budget:** build cost, run cost, reserve.
8. **Main risks and assumptions:**
9. **Roles and authority:** who decides scope, budget, release.
10. **Gates and criteria:** link to the tailoring note.
**Approval:** sponsor, date.

## Stakeholder register

| Name or group | Role | Interest | Influence | Needs | Engagement approach | Contact cadence |

## Action log

| ID | Date | Action | Owner | Due | Status | Source (meeting or decision) |

## Default RAG rules (use when the project has no written rules)

| Status | Rule |
|---|---|
| 🔴 Red | A milestone or the end date will slip more than 2 weeks, the cost forecast is more than 10% over budget, a critical risk has no response, CI on the main branch fails for more than 1 day, or a critical defect is open |
| 🟠 Amber | A milestone will slip up to 2 weeks, the cost forecast is 5–10% over budget, a decision is past its due date, a high risk or a high defect is open, or work started on a scope change that is not approved |
| 🟢 Green | None of the above |

Write the project's own limits in the charter when they differ.

## Weekly status report

**Project:** name · **Week:** YYYY-Www · **Status:** 🔴 Red / 🟠 Amber / 🟢 Green (reason in one line, from the RAG rules)
**Summary:** 2 or 3 sentences: progress, main risk, decision needed.
| Area | Status | Note |
|---|---|---|
| Scope | | |
| Schedule | | forecast date |
| Budget | | spent / forecast / reserve left |
| Quality | | |
| Risks | | |
**Done this week:** bullets. **Next week:** bullets.
**Decisions needed:** decision, owner, due date.
**Escalations:** item, limit passed, what is needed.

## Health check report

**Project:** name · **Date:** · **Prepared by:**
| Area | RAG | Evidence | Gap |
|---|---|---|---|
(scope, schedule, budget, team, vendor, quality, risks, stakeholders, readiness)
**Benchmark score by phase:** done / partly / not yet due / missing / not applicable.
**Top 5 gaps:** gap, risk, fix, owner, date.
**Decisions needed from the sponsor:** list.

## Gate review

**Gate:** Gn name · **Date:** · **Decision owner:**
| Criterion (item) | Evidence | Result (met / partly / missing / waived) | Note |
|---|---|---|---|
**Recommendation:** go / go with conditions / no-go.
**Conditions:** condition, owner, date.
**Decision:** recorded as Dnn in the Decision Log.

## RAID entry

| ID | Type (risk, assumption, issue, dependency) | Description | Probability | Impact | Owner | Response | Due | Status |

## Decision Log entry

| ID | Date | Decision | Options considered | Reason | Decision owner | Related items |

## Change request

**CR-n:** title · **Raised by:** · **Date:**
**Change:** what and why. **Impact:** scope, schedule, cost, quality, risk.
**Options:** accept, reject, defer. **Recommendation:** · **Decision and owner:** · **Contract change needed:** yes / no.

## Ticket brief

**Ticket:** KEY-n: title · **Goal:** one sentence.
**Scope / not in scope:** · **Acceptance criteria:** numbered, each can be checked.
**Files or pages:** · **Decisions needed:** · **AI ticket:** yes / no.

## Pull request

Title: KEY-n: short description
- What changed
- Decisions (Dnn, added to the Decision Log)
- Tests: number passed; new tests. AI ticket: evaluation pass rate and real-run result.
- Pages changed: rule pages, README, or "none"

## Review summary

KEY-n is in Review. Change: … Tests: n passed, CI green. AI ticket: pass rate, tokens, cost, time.
Decisions: Dnn. Link: … Approve, or give changes.

## Done comment

Approved by the product owner on YYYY-MM-DD. Merged: PR #n, commit abc1234. Decisions: Dnn. Pages changed: …

## Closure report

**Project:** · **Sponsor:** · **Dates:** planned / actual
| Area | Plan | Actual | Variance | Reason |
|---|---|---|---|---|
(scope, schedule, cost, quality)
**Benefits so far:** measure, baseline, now, target. **Benefits owner:**
**Open items moved to the backlog:** item, owner.
**Top lessons:** lesson, prevention rule.
**Acceptance:** sponsor sign-off date.
