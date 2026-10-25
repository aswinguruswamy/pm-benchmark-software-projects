# Gates

For each gate: the evidence to check and who decides. Item numbers refer to references/benchmark.md.
The PM runs the review and records the decision. The decision owner decides.
In a solo project, the PM is the decision owner for each gate (see references/project-types.md, "Solo builder").

| Gate | When | Evidence to check (items) | Decision owner |
|---|---|---|---|
| G0 Discovery review | End of phase 0 | Problem statement, options note, PoC result (1–3) | Sponsor |
| G1 Business case go or no-go | Phase 1 | Benefit baseline, business case (5, 6) | Sponsor, portfolio board |
| G2 Charter sign-off | Phase 1 | Signed charter, stakeholder register, compliance list, first risks, gate criteria (7–11) | Sponsor |
| G3 Plan baseline approval | End of phase 2 | Items 12–32 | Sponsor, steering committee |
| G4 Design sign-off (build gate) | End of phase 3 | Items 33–44 | Architect, security, privacy officer, sponsor |
| G5 Environment readiness | End of phase 4 | Items 45–52 | Tech lead, operations |
| G6 Sprint review | Each sprint or 2 weeks | Test reports (58), Decision Log (61), docs (62), demo feedback (64), RAID review (70), doc check (79) | Product owner |
| G7 Release readiness | Before each release | Operations acceptance (82), SLA (83), training (84), readiness checklist (85), pen test (86), migration and recovery tests (91) | Operations manager (82), sponsor (85) |
| G8 Go or no-go and CAB | Release day | Go decision and CAB record (87), release notes (88), cutover runbook (89), release notice (90), rollback criteria (92) | Sponsor (go or no-go), CAB (change) |
| G9 Hypercare exit | End of hypercare | Adoption (93), KT (94), handover list (95), hypercare report and post-mortems (96) | Operations manager, sponsor |
| G10 Closure review | Phase 9 | Items 97–105 | Sponsor, PMO |
| G11 Benefits review | 30 and 90 days | Items 106–108 | Sponsor, benefits owner |

## Gate review steps

1. Confirm the gate criteria from the tailoring note (item 11). If the project changed them, use the project's version.
2. Skip the items marked "not applicable" in the project record. Show them in a separate list.
3. For each evidence item, record: met, partly met, not yet due, not found, or waived.
4. For "not found", ask the PM for the link or a confirmation. Mark it "missing" only after the PM confirms.
5. A waiver needs a named owner and a written reason.
6. Recommend: go, go with conditions, or no-go.
7. Each condition has an owner and a date. Track the conditions in the project record.
8. Record the decision and the decision owner in the Decision Log.
