# PM benchmark for software projects (v4)

108 items in 11 phases, and 8 take-over items (S1 to S8).

## Key

- **PM role:** D = the PM does it. A = the PM approves or signs it. E = the PM makes sure that the responsible person does it.
- **Done when:** the evidence that shows the item is complete.
- **Source** (the item aligns with this standard or practice):
  PMB = PMBOK Guide (principles, performance domains, knowledge areas) · PR2 = PRINCE2 · SG = Scrum Guide ·
  12207 = ISO/IEC/IEEE 12207 · ITIL = ITIL 4 · DORA = DORA metrics · SSDF = NIST SP 800-218 ·
  OWASP = OWASP ASVS and Top 10 · 27001 = ISO/IEC 27001 · AIRMF = NIST AI Risk Management Framework ·
  WCAG = WCAG 2.2 · PRIV = privacy law (for example PIPEDA, GDPR) · OCM = organisational change management practice ·
  FIN = finance practice
- **Flow:** S (if the project is already running) → 0 → 1 → 2 → 3 → 4 → [5 ⇄ 6 repeat each sprint or each 2 weeks] → 7 → 8 → 9 → 10.
  Phase 6 also runs through the whole project.

---

## Phase S: Take-over (the PM joins a project that is already approved or running)

| # | Item | Output | Done when | Timing | PM | Source |
|---|---|---|---|---|---|---|
| S1 | Read the business case, charter, contracts, plan, backlog, RAID log, and status reports | Read-in notes | The notes list the open questions | Week 1 | D | PMB |
| S2 | Meet each key person one to one: "What is success? What worries you?" | Stakeholder notes | All key people met | Week 1 | D | PMB |
| S3 | Find the decision rights: scope, budget, release, vendor | Decision rights table | Each decision type has a named owner | Week 1 | D | PMB, PR2 |
| S4 | Find the past promises: what, to whom, by when | Commitments list | Each promise has an owner and a date, or is renegotiated | Week 1 | D | PMB |
| S5 | Health check: scope, schedule, budget, team, vendor, quality, risks, stakeholders | Health check report | Each area has a RAG status; the top 5 risks have owners | Week 2 | D | PMB |
| S6 | Check the contract against the plan: milestones, acceptance terms, penalties | Contract gap list | Each gap has an action | Week 2 | D | PMB |
| S7 | Re-baseline if the plan is not real | New baseline | The sponsor signs it | Weeks 3–4 | D | PMB, PR2 |
| S8 | Agree reporting, escalation limits, and decision authority with the senior PM or line manager | Escalation agreement | Written and agreed | Week 1 | D | PMB |

After S8, continue from the current phase.

---

## Phase 0: Discovery

| # | Item | Output | Done when | Timing | PM | Source |
|---|---|---|---|---|---|---|
| 1 | Understand the user problem: interviews, data, current process | Problem statement | Users and the sponsor agree the statement | Once | E | PMB, 12207 |
| 2 | Check existing solutions: build, buy, or reuse | Options note | Each option has a cost, a risk, and a fit | Once | E | PMB |
| 3 | Test the riskiest idea with a proof of concept, if needed | PoC result | The idea is proven or rejected | Once | E | PMB |

**Gates:** discovery review. **Touchpoints:** sponsor, users, product owner.

## Phase 1: Initiation

| # | Item | Output | Done when | Timing | PM | Source |
|---|---|---|---|---|---|---|
| 4 | Read the lessons from past similar projects | Lessons to apply | Each lesson has an action in the plan | Once | D | PMB |
| 5 | Set the need, value, and benefits; measure the baseline. The sponsor owns the benefits. | Benefit baseline | Each benefit has a measure and a baseline value | Once | E | PMB, PR2 |
| 6 | Business case: options, cost, benefits, risks. The sponsor owns it; the PM contributes. | Business case | The sponsor approves it | Once | E | PMB, PR2 |
| 7 | Draft the charter: goal, scope, success measures, budget, authority. The sponsor signs it. | Signed charter | The sponsor signed it | Once | D | PMB |
| 8 | Identify the stakeholders: interest, influence, needs | Stakeholder register | Each stakeholder has an engagement approach | Once, then ongoing | D | PMB |
| 9 | Find constraints, assumptions, compliance (privacy, security, accessibility, licences, AI) | Compliance list | Each need has an owner | Once | D | PMB, PRIV, WCAG |
| 10 | List the first high-level risks | RAID log (start) | Each risk has an owner | Once | D | PMB |
| 11 | Choose the method, adapt the governance, and set the entry and exit criteria for each gate | Tailoring note, gate criteria | The sponsor agrees | Once | D | PMB, PR2 |

**Gates:** business case go or no-go, charter sign-off. **Touchpoints:** sponsor kickoff, stakeholder interviews, PMO intake.

## Phase 2: Planning

| # | Item | Output | Done when | Timing | PM | Source |
|---|---|---|---|---|---|---|
| 12 | Requirements: functional and non-functional | Requirements / backlog | Each has acceptance criteria; each non-functional need has a measurable target | Once, then each sprint | E | 12207, PMB |
| 13 | Link each requirement to its tests | Traceability matrix | Each requirement has at least one test | Ongoing | E | 12207 |
| 14 | Scope with acceptance criteria and an out-of-scope list | Scope baseline | The sponsor approves it | Once | D | PMB |
| 15 | Definition of Ready and Definition of Done | DoR, DoD | The team agrees | Once | D | SG |
| 16 | Estimate with the team from past actuals; record the assumptions; add contingency | Estimate | The team agrees | Once, then each release | D | PMB |
| 17 | Schedule: milestones, sprints, critical path; it matches the product roadmap | Schedule / release plan | The sponsor and the product owner agree | Once, then ongoing | D | PMB |
| 18 | Dependencies on other teams; shared resources | Cross-team dependency register | Each dependency has an owner and a date | Once | D | PMB |
| 19 | Budget with run costs (cloud, API, licences) and reserve | Budget | Finance approves it | Once | D | PMB, FIN |
| 20 | Team: roles, RACI, onboarding | RACI | Each role has a person; each person knows the role | Once | D | PMB |
| 21 | Approvers, delegates, approval time limits | Approval matrix | The sponsor agrees | Once | D | PMB |
| 22 | Procurement: vendors, contracts, licences, vendor risk, exit plan | Procurement plan | Each vendor has a contract and an exit plan | Once | D | PMB |
| 23 | Legal: statement of work, NDA, IP and data ownership. Legal signs. | Signed SOW, NDA | Legal signed | Once | E | PMB |
| 24 | Quality: test strategy, review rules, quality gates, independent review | Test strategy | The tech lead and QA agree; the PM approves | Once | A | PMB, 12207 |
| 25 | Risk: owners, responses, escalation limits and path | RAID log, escalation path | The limits and the path are written | Once | D | PMB |
| 26 | Communication: audience, content, frequency; RAG rules | Comms plan | Each stakeholder knows what they get and when | Once | D | PMB |
| 27 | Change control: request, impact check, board, limits | Change process | The sponsor approves it | Once | D | PMB, ITIL |
| 28 | Configuration: versions, baselines, environments | Config plan | Versions, baselines, and environments are named | Once | E | 12207, ITIL |
| 29 | Organisational change: user impact, adoption plan, champions | Change mgmt plan | Each affected group has actions | Once | D | OCM |
| 30 | First release, cutover, and rollback plan | Release plan | The tech lead and operations agree | Once | D | ITIL |
| 31 | Transition: operations, support, training, hypercare | Transition plan | Operations and support agree | Once | D | ITIL |
| 32 | How to measure the benefits; name the benefits owner | Benefits plan | The owner is named; measures and dates are set | Once | D | PMB, PR2 |

**Gates:** requirements sign-off by the business, estimate review, plan baseline approval.
**Touchpoints:** team, stakeholder, and vendor kickoffs; security; legal; finance.

## Phase 3: Design (gate before the build)

| # | Item | Output | Done when | Timing | PM | Source |
|---|---|---|---|---|---|---|
| 33 | Architecture: components, data flow, data model; an ADR for each key decision | Architecture doc, ADRs | The architect approves | Once, then per change | E | 12207 |
| 34 | API contract first (if the product has an API): versions, errors, authentication, rate limits | OpenAPI spec | The consumers review it | Once, then per change | E | 12207, OWASP |
| 35 | Threat model and security design | Threat model | Security approves | Once, then per change | E | SSDF, OWASP |
| 36 | Privacy review (if personal data): data, retention, location, deletion. The privacy officer signs. | Privacy impact assessment | The privacy officer signed | Once | E | PRIV |
| 37 | Observability: logs, metrics, alerts, dashboards | Monitoring design | Operations agrees | Once | E | ITIL, DORA |
| 38 | Usage data collection to measure the benefits | Analytics plan | Each benefit measure has a data source | Once | E | PMB |
| 39 | Scale and capacity | Capacity plan | The load targets are set | Once | E | ITIL |
| 40 | Continuity: RTO, RPO, backup, recovery | DR plan | Operations and the business agree the targets | Once | E | ITIL, 27001 |
| 41 | Data migration (if the product replaces a system): mapping, cleansing, reconciliation, parallel run, decommission | Migration plan | The data owner approves | Once | E | 12207 |
| 42 | Technology dependencies: fallback, exit plan, version update rule | Technology dependency list | Each dependency has a fallback or an exit plan | Once | E | PMB |
| 43 | AI (if used): data sent, answer checks, evaluation set and pass rule, model and prompt versions, cost limit, human review, bias and harm review | AI design and eval plan | The product owner and the tech lead approve; the evaluation set exists | Once, then per change | E | AIRMF |
| 44 | UX and accessibility: name the standard (for example WCAG 2.2 AA, AODA) and test with users | Accessibility standard, prototype result | The standard is named; the user test is done | Once | E | WCAG |

**Gates:** architecture review, security design review, privacy review, design sign-off → build gate.
**Touchpoints:** architect, security, privacy officer, data owner, users.

## Phase 4: Engineering setup

| # | Item | Output | Done when | Timing | PM | Source |
|---|---|---|---|---|---|---|
| 45 | Repository, branch strategy, branch protection | Repository | The main branch is protected | Once | E | SSDF |
| 46 | Pull request rules: independent reviewer, linked ticket, code owners | PR rules | The repository settings enforce the rules | Once | E | SSDF |
| 47 | CI: build, style, tests, SAST, dependency, secret, and licence scans | CI pipeline | It runs on each PR and blocks the merge on a failure | Once | E | SSDF, DORA |
| 48 | CD: dev, test, staging, prod with approvals; infrastructure as code | CD pipeline | It deploys to each environment with its approval | Once | E | DORA, ITIL |
| 49 | Secrets store; no secrets in code | Secrets store | The secret scan finds no secrets | Once | E | SSDF, 27001 |
| 50 | Jira board, Confluence space, templates, action log | Tools ready | The team uses them | Once | D | PMB |
| 51 | Dependency alerts; technical debt register | Debt register | The alerts are on; the register exists | Once | E | SSDF |
| 52 | Masked or made-up test data | Test data | No real personal data outside production | Once | E | PRIV, 27001 |

**Gates:** environment readiness check. **Touchpoints:** tech lead, DevOps, security.

## Phase 5: Execution

| # | Item | Output | Done when | Timing | PM | Source |
|---|---|---|---|---|---|---|
| 53 | Lead the team: blockers, focus, conflicts, capacity, morale | — | Blockers are cleared within the agreed time | Ongoing | D | PMB |
| 54 | Run the ceremonies (the PM or the Scrum Master) | Sprint plan, retro actions | Each event is held; each action has an owner | Each sprint or 2 weeks | D | SG |
| 55 | Backlog ordered by value and risk. The product owner orders it. | Ordered backlog | The top items are ready for the next 2 sprints | Each sprint or 2 weeks | E | SG |
| 56 | Check the Definition of Ready before work starts | Ready tickets | No work starts on a ticket that is not ready | Each ticket | E | SG |
| 57 | Independent review and green CI before each merge | Merged PRs | No merge without both | Each PR | E | SSDF |
| 58 | Independent QA test design; all test levels including performance, security, accessibility | Test reports | Each level ran; the results are recorded | Each sprint or 2 weeks | E | 12207 |
| 59 | Pass in staging before production | Staging results | Each release passed in staging | Each release | E | DORA, ITIL |
| 60 | Technical debt work in each sprint | Debt items closed | The agreed share of capacity is used | Each sprint or 2 weeks | E | PMB |
| 61 | Keep the Decision Log and ADRs current | Decision Log | Each decision is in the log before Review | Each decision | D | PMB |
| 62 | Docs (README, API, runbooks) change in the same ticket as the code | Updated docs | The DoD check passes | Each ticket | E | 12207 |
| 63 | Accept vendor deliverables against the contract; review vendor performance | Acceptance records, vendor review | Each deliverable is accepted or rejected in writing | Each delivery, monthly | A | PMB |
| 64 | Demos and decisions on time with stakeholders; measure stakeholder satisfaction | Demo feedback, satisfaction score | Each decision is made by its due date; satisfaction is measured each quarter | Each sprint or 2 weeks | D | PMB |
| 65 | AI (if used): run each evaluation sample several times before Review; test with real-like data | Eval results | The pass rate meets the agreed gate | Each AI change | E | AIRMF |
| 66 | Share knowledge; no single point of knowledge | — | Each critical area has 2 people who know it | Ongoing | E | PMB |

**Reviews:** pull request reviews, sprint review and demo, retrospective, QA sign-off, technical review.
**Touchpoints:** stand-up, refinement, 1:1s, vendor check-ins, sponsor update.

## Phase 6: Monitoring and control

| # | Item | Output | Done when | Timing | PM | Source |
|---|---|---|---|---|---|---|
| 67 | Track scope, schedule, and cost, including cloud and AI run costs; forecast; record each use of contingency and reserve | Burndown / EVM | The forecast is updated | Weekly | D | PMB |
| 68 | Compare estimates with actuals; adjust | Variance record | The next estimates use the variance | Each sprint or 2 weeks | D | PMB |
| 69 | Quality: defects, escaped defects, coverage, CI pass rate, DORA metrics | Quality dashboard | The dashboard is current | Each sprint or 2 weeks | D | PMB, DORA |
| 70 | Review the RAID log; escalate at the limits | RAID log | No item is past due without escalation | Each sprint or 2 weeks | D | PMB |
| 71 | Decide change requests; update baselines; signed contract change for client work | Change log | Each request has a decision | Each change | D | PMB, ITIL |
| 72 | Minutes, actions, owners, due dates; follow up | Action log | Each action has an owner and a date | Each meeting | D | PMB |
| 73 | Security: scans, alerts, access reviews, incidents; remove access when a person leaves | Security report | Critical findings are fixed within the agreed time | Each sprint or 2 weeks | E | SSDF, 27001 |
| 74 | Approval wait times; use delegates | — | No approval is past its time limit | Ongoing | D | PMB |
| 75 | Cross-team dependencies and shared resources | Cross-team dependency register | Each date is confirmed | Weekly | D | PMB |
| 76 | Timesheets, invoices, accruals, forecast to finance | Finance report | Sent to finance on time | Monthly | D | FIN |
| 77 | Status reports with RAG | Status report | Sent on schedule; the RAG follows the rules | Weekly | D | PMB |
| 78 | Steering meetings, phase gates, sign-offs | Minutes, sign-offs | Each gate has a signed decision | Monthly and at gates | D | PMB, PR2 |
| 79 | Check that docs match the product | Doc check | No open doc gaps at the sprint review | Each sprint or 2 weeks | D | PMB |
| 80 | Record lessons during the project | Lessons log | Each lesson has a prevention rule | Ongoing | D | PMB |
| 81 | Compliance: audit trail, privacy, licences | Compliance check | No open compliance gaps at a gate | Each phase | E | 27001, PRIV |

**Reviews:** steering committee, phase gates, audits. **Touchpoints:** weekly status, sponsor 1:1, PMO.

## Phase 7: Release (operations and users are ready before go-live)

| # | Item | Output | Done when | Timing | PM | Source |
|---|---|---|---|---|---|---|
| 82 | Operations readiness: runbooks, monitoring, alerts, incident process, on-call. The operations manager accepts before go-live. | Operations acceptance | The operations manager signed | Each major release | E | ITIL |
| 83 | Support model, service levels, warranty. The service owner signs. | SLA | The service owner signed | Once, then per change | E | ITIL |
| 84 | Train users and support before go-live | Training records | The users and the support team are trained | Each major release | D | OCM |
| 85 | Readiness checklist: tickets done, real-user UAT signed, performance and security tests passed, no critical defects, docs ready, items 82–84 done. The PM confirms the checklist; the sponsor accepts. | Readiness checklist | Each criterion is met, or the sponsor waives it in writing | Each release | D | ITIL |
| 86 | Penetration test; fix critical and high findings | Pen test report | No open critical or high findings | Each major release | E | OWASP, SSDF |
| 87 | Go or no-go meeting (the PM runs it); CAB approval (the CAB approves the change) | Go decision, CAB record | The decision is recorded | Each release | D | ITIL |
| 88 | Version, tag, CHANGELOG, release notes | Release notes | They match the deployed version | Each release | E | ITIL |
| 89 | Cutover plan; gradual rollout with feature flags | Cutover runbook | Rehearsed; each step has an owner and a time | Each release | A | ITIL |
| 90 | Tell users and support; release window | Release notice | Sent before the window | Each release | D | PMB |
| 91 | Test migration, backup, and recovery | Test records | Recovery meets the RTO and RPO in a test | Each release | E | ITIL |
| 92 | Deploy and monitor; rollback criteria and decision owner | Deployment log | The checks after deployment pass, or a rollback is done | Each release | E | DORA |

**Gates:** operational acceptance, UAT sign-off, readiness review, go or no-go, CAB.
**Touchpoints:** users, support, operations, sponsor, CAB.

## Phase 8: Hypercare and final handover

| # | Item | Output | Done when | Timing | PM | Source |
|---|---|---|---|---|---|---|
| 93 | Track adoption; support users after go-live | Adoption metrics | Adoption is tracked against the target | Weekly in hypercare | D | OCM |
| 94 | Knowledge transfer from vendors and leavers | KT sign-off | The receiver signs | Once | E | PMB |
| 95 | Hand over access, accounts, licences, run costs | Handover list | Each item has a new owner | Once | D | PMB |
| 96 | Hypercare until the exit criteria are met; post-mortem for each major incident | Hypercare report, post-mortems | The exit criteria are met | Hypercare period | D | ITIL |

**Gates:** hypercare exit. **Touchpoints:** operations, support, users, vendors.

## Phase 9: Closure

| # | Item | Output | Done when | Timing | PM | Source |
|---|---|---|---|---|---|---|
| 97 | Get the final acceptance from the sponsor | Acceptance sign-off | The sponsor signed | Once | D | PMB, PR2 |
| 98 | Close contracts, pay vendors; financial closure: final costs, close cost codes | Financial closure report | All contracts and cost codes are closed | Once | D | FIN |
| 99 | Close RAID, tickets (including epics and parent tickets), change requests; move the rest to the backlog with owners | Next backlog | No open item is without an owner | Once | D | PMB |
| 100 | Hand the benefits measurement to the benefits owner | Benefits handover | The owner accepts the measures and dates | Once | D | PR2 |
| 101 | Remove team and vendor access | Access removal record | No team or vendor access remains | Once | E | 27001 |
| 102 | Final lessons; update the process and estimate data | Lessons report | The process and the estimate data are updated | Once | D | PMB |
| 103 | Archive documents, code, records | Archive | Stored under the records policy | Once | D | PMB |
| 104 | Release the team; feedback and recognition | — | Each person got feedback | Once | D | PMB |
| 105 | Closure report: plan against actual | Closure report | The sponsor accepts it | Once | D | PMB, PR2 |

**Gates:** closure review, PMO closure. **Touchpoints:** sponsor, PMO, team, vendors, finance.

## Phase 10: Benefits after the project

| # | Item | Output | Done when | Timing | PM | Source |
|---|---|---|---|---|---|---|
| 106 | Measure the benefits against the baseline | Benefits report | Measured at 30 and 90 days | At 30 and 90 days | E | PMB, PR2 |
| 107 | Collect user feedback, usage data, and user satisfaction | Feedback summary | The summary is shared with the sponsor | At 30 and 90 days | E | PMB |
| 108 | Report to the sponsor; recommend next steps | Recommendation | The sponsor decides the next steps | At 90 days | E | PMB |

**Gates:** benefits review. **Touchpoints:** sponsor, benefits owner, users, operations.
