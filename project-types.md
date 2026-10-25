# Project types

Use this at the start of a project to adapt the benchmark. A project can have more than one type.
Record the types and the items marked "not applicable" (with reasons) in the project record.
Item numbers refer to references/benchmark.md.

## Solo builder

One person runs the project and builds it, often with an AI assistant as the builder.

**Roles**
- The PM holds these roles: sponsor, product owner, PM, user, and approver for each gate.
- The builder (a person or an AI assistant) holds these roles: developer, tester, technical writer, and record keeper.
- The independent reviewer is a person, or a separate AI session that did not build the change.
- Record the roles in the project record. A health check does not report role collapse as a gap.

**Items that apply** (the core set)
1, 2, 4, 5, 7, 8, 9, 10, 11, 12, 13, 14, 15, 16, 17, 19, 24, 25, 27, 30, 32, 33, 35, 42, 45, 46, 47, 49, 50, 51, 52,
54, 55, 56, 57, 58, 60, 61, 62, 64, 67, 68, 69, 70, 77, 79, 80, 85, 88, 90, 92, 97, 99, 102, 103, 105, 106, 107, 108.

**Items that apply when the product needs them**
34 (API), 36 (personal data), 38 (benefit measures), 43 and 65 (AI), 44 (user interface), 48 and 59 (deployed service), 41 and 91 (migration).

**Light version**
- 6: the business case is a short section of the charter.
- 20: record the roles only.
- 26: the status report cadence only.
- 31: a short handover note in the README.
- 37, 40: logs and a repository backup only.
- 84: a README or a short user guide.
- 87: the PM records the go or no-go decision. No CAB.

**Not applicable by default** (reason: no team, no vendors, no operations organisation, no budget process)
3, 18, 21, 22, 23, 28, 29, 39, 53, 59 (unless deployed), 63, 66, 71 (contract part), 72, 73 (access part), 74, 75, 76, 78, 81,
82, 83, 86, 89, 93, 94, 95, 96, 98, 100, 101, 104.
Mark one of these as applicable when the project needs it, for example 86 for a public web service.

**Gates in a solo project:** G2 (charter), G3 (plan), G4 (design, light), G6 (each sprint), G7 and G8 (release), G10 (closure), G11 (benefits).

## Other types

| Type | Main focus | Items to stress | Items often not applicable |
|---|---|---|---|
| Change to an existing system | Impact on current users, regression, release train | 12, 13, 27, 58, 85, 90, 92 | 1–3, 6, 29 |
| Web page or app | UX, accessibility, performance, release cadence | 44, 38, 58, 59, 84, 89, 93 | 41 |
| Service or API | API contract, versions, SLAs, consumers | 34, 37, 39, 42, 83 | 44 |
| CLI tool or library | Install steps, versions, CHANGELOG, package release. Rollback is a patch release or a withdrawn release. | 45–47, 85, 88, 90, 92 | 37, 39, 40, 48, 59, 82, 83, 89, 91, 93–96 |
| Data or system migration | Data quality, mapping, reconciliation, cutover, parallel run, decommission | 41, 40, 52, 89, 91, 92, 96 | 34, 44 if no new user interface |
| Vendor or COTS setup | Configure, not build; contract; vendor management | 2, 22, 23, 42, 63, 94 | 45–47 if the vendor owns the code |
| Infrastructure or cloud | Capacity, cost, security, resilience | 19, 39, 40, 48, 67, 73 | 44 |
| AI feature | Data sent, evaluation, safety, cost, human review | 43, 65, 36, 42, 38; references/ai-checklist.md | — |

## Main risks by type

- **Solo builder:** one person holds all approvals; governance heavier than the work; no independent check.
- **Change to an existing system:** regression, users not told, release conflicts.
- **Web or app:** scope creep, device and browser issues, low adoption.
- **Service or API:** breaking changes, load, unclear ownership.
- **CLI tool or library:** breaking changes for users, install problems on other systems, a bad release that users already downloaded.
- **Migration:** data loss, long downtime, failed rollback, hidden data issues.
- **Vendor or COTS:** too much customisation, vendor delay, lock-in.
- **Infrastructure:** cost overrun, outages, access errors.
- **AI feature:** wrong answers, data leaks, model changes, model retirement, cost growth.
