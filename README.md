# PM Benchmark for Software Projects

A checklist of 108 items that a project manager owns, or makes sure of, in a software project: from
discovery to the benefits after the release. Each item has an output, a "done when" check, a timing,
the PM's role, and the standard it aligns with.

Use it to plan a project, to run a gate review, or to do a health check of a running project.

## Who it is for

- **Project managers and Scrum Masters** who run software projects: web apps, APIs, CLI tools,
  migrations, vendor setups, infrastructure, and AI features.
- **PMs who build alone with an AI assistant.** The solo builder profile marks which items apply.
- **PMO leads** who want a common checklist for gate reviews and health checks.

## What is in this repository

| File | Content |
|---|---|
| [benchmark.md](benchmark.md) | 108 items in 11 phases, and 8 take-over items (S1 to S8) |
| [gates.md](gates.md) | 12 gates (G0 to G11): the evidence to check and the decision owner |
| [project-types.md](project-types.md) | How to adapt the items: solo builder, change to an existing system, web app, API, CLI tool, migration, vendor setup, infrastructure, AI feature |
| [templates.md](templates.md) | Project record, problem statement, charter, stakeholder register, action log, default RAG rules, status report, health check, gate review, RAID entry, Decision Log entry, change request, ticket brief, pull request, review summary, Done comment, closure report |
| [case-study/SRG.md](case-study/SRG.md) | A real health check of a finished project against this benchmark |

## The phases

```
S Take-over (if the project is already running)
0 Discovery → 1 Initiation → 2 Planning → 3 Design → 4 Engineering setup
→ [5 Execution ⇄ 6 Monitoring and control, each sprint] → 7 Release
→ 8 Hypercare and final handover → 9 Closure → 10 Benefits after the project
```

Phase 6 also runs through the whole project. Operations readiness, the service levels, and user
training are in phase 7, before go-live.

## How to use it

1. **Adapt it.** Read [project-types.md](project-types.md). Mark each item that does not apply, with a
   reason. A small tool does not need a change advisory board.
2. **Plan with it.** For each item that applies, set the owner and the due date.
3. **Run the gates.** Use [gates.md](gates.md). For each item, record: met, partly met, not yet due,
   not found, or waived. A waiver needs an owner and a written reason.
4. **Check the health.** Score each item that applies. Each "done" needs evidence: a page, a ticket,
   a sign-off, or a test result. "Not found" becomes "missing" only after the owner confirms.

## PM roles

| Code | Meaning |
|---|---|
| D | The PM does it. |
| A | The PM approves or signs it. |
| E | The PM makes sure that the responsible person does it. |

The benchmark names the real owner where the PM does not have the authority. For example, the sponsor
owns the business case, the product owner orders the backlog, and the operations manager accepts the
service before go-live.

## Standards

Each item names the standard or practice it aligns with. The benchmark is not certified by these
bodies, and it does not copy their text.

| Code | Standard or practice |
|---|---|
| PMB | PMBOK Guide: principles, performance domains, knowledge areas |
| PR2 | PRINCE2 |
| SG | Scrum Guide |
| 12207 | ISO/IEC/IEEE 12207 (software life cycle processes) |
| ITIL | ITIL 4 |
| DORA | DORA metrics |
| SSDF | NIST SP 800-218 Secure Software Development Framework |
| OWASP | OWASP ASVS and Top 10 |
| 27001 | ISO/IEC 27001 |
| AIRMF | NIST AI Risk Management Framework |
| WCAG | WCAG 2.2 |
| PRIV | Privacy law, for example PIPEDA and GDPR |
| OCM | Organisational change management practice |
| FIN | Finance practice |

## Limits

- The benchmark lists duties. It does not replace the judgement of the PM: trade-offs, influence, and
  early warning of problems.
- An organisation's own PMO method comes first. Use this benchmark to find gaps in it.
- Version 1.0 was tested on one real project (see the case study). Feedback from other projects is
  welcome as an issue.

## Author and licence

Made by Aswin Guruswamy (PMP, CSM, CSPO) with Claude as a build assistant.
First used on the [Status Report Generator](https://github.com/aswinguruswamy/status-report-generator).

Licensed under [CC BY 4.0](LICENSE). You can use and change it if you name the author.
