# Case study: Status Report Generator (SRG)

A health check of a real project against this benchmark, done on October 25, 2026, just before the
v1.0.0 release.

## The project

| Item | Value |
|---|---|
| Product | A Python CLI tool that reads Jira and writes a weekly status report. Rules set the RAG status; the Claude API writes a short summary, and the tool checks it. |
| Repository | [aswinguruswamy/status-report-generator](https://github.com/aswinguruswamy/status-report-generator) |
| Project types | Solo builder, CLI tool, AI feature |
| Roles | One person was the sponsor, product owner, PM, and user. An AI assistant was the builder. |
| Plan | 4 sprints, 6 days and 1 buffer day |
| Actual | 4 days, 34 tickets, release 3 days before the target |

## How the benchmark was adapted

- The solo builder profile set the items that apply (see [project-types.md](../project-types.md)).
- Items 37, 39, 40, 48, and 59 do not apply, because the tool is not a deployed service.
- Light versions: the business case is a section of the charter (6); roles only (20); a status report
  at each sprint review (26); a handover note in the README (31); a README as the user guide (84);
  the PM records the go decision, with no CAB (87).

## Score by phase (before the release steps)

| Phase | Done | Partly | Not found | Not yet due |
|---|---|---|---|---|
| 0 Discovery | 1 | 1 | – | – |
| 1 Initiation | 5 | 3 | – | – |
| 2 Planning | 7 | 4 | 4 | – |
| 3 Design | 3 | 2 | 1 | – |
| 4 Engineering setup | 5 | 2 | – | – |
| 5 Execution | 7 | 3 | – | – |
| 6 Monitoring and control | 5 | 2 | – | – |
| 7 Release | 3 | – | 2 | 1 |
| 9 Closure | 1 | 3 | – | 1 |
| 10 Benefits | – | – | – | 3 |

## Main gaps found

| Gap | Items | Result |
|---|---|---|
| The tag, the GitHub release, and the Jira release did not exist yet, but some pages already said "released". | 88, 92, 79 | Fixed: the release was made the same day, and a decision recorded the date difference. |
| The CHANGELOG gave 5 evaluation samples; the set had 6. | 79, 88 | Fixed before the release. |
| The epics were still open. | 99 | Fixed: all 34 tickets closed at the project close. |
| No benefits plan or benefits owner. | 32, 106–108 | Open: a lesson for the next project. |
| No independent code review. One person approved all changes. | 57 | Open: the next project uses a separate AI session as the reviewer. |
| No threat model, and no prompt-injection test for ticket titles that go to the AI. | 35, 43 | Open: moved to v2. |
| No change process, escalation limits, or traceability matrix. | 13, 25, 27 | Accepted for a solo project; the Decision Log was the change log. |

## What the benchmark showed

1. **Records drift near the release.** Pages were written for a planned date before the release
   happened. Check the documents against the real state (item 79) at the release gate.
2. **A solo project hides the missing independent check.** The role rule in the solo builder profile
   makes this a deliberate choice, not a silent gap.
3. **Benefits are the easiest item to forget.** The project met all its success measures, but nobody
   owned the check after the release.
