---
status: Publication audit
audience: Project maintainers
source_layer: Project synthesis
patch_sensitivity: Low
last_reviewed: 2026-06-06
---

# Publication Audit Hub

This section is for finishing, not expanding.

Website v2.3 starts the publication-readiness audit phase. The goal is to make the project cleaner, safer, and easier to publish.

## Audit priorities

| Audit | Purpose |
|---|---|
| [Publication Readiness Audit](publication-readiness-audit.md) | current go/no-go assessment |
| [Scope Separation Audit](scope-separation-audit.md) | make sure public doctrine, weapon notes, and workbook packages stay separated |
| [Mechanics Verification Queue](mechanics-verification-queue.md) | identify patch-sensitive claims before stable release |
| [Beta Candidate Checklist](beta-candidate-checklist.md) | what must be true before Beta Candidate 1 |
| [Navigation Cleanup Notes](navigation-cleanup-notes.md) | track confusing paths and cleanup targets |

## Current publication direction

The project should move toward:

```text
v2.3 — publication-readiness audit
v2.4 — Beta Candidate package
review/fix cycle
v3.0 — Public Beta
```

## Rule for this phase

Do not add new major content branches unless they fix a publication blocker.

## v2.3.8 cleanup trigger

The current weapon/armor/role source-recovery pass is complete. From here, the project should stop adding role/weapon pages temporarily and begin cleanup, consolidation, and Beta Candidate preparation.

## v2.3.9 cleanup result

The source-recovery pass is complete for current weapon/armor/role batches. Deep pages were preserved but moved behind clean indexes. The next target is [Beta Candidate Action Plan](beta-candidate-action-plan.md).

## v2.4 Beta Candidate 1

The cleanup and source-recovery phases are complete enough for targeted review. Use [Beta Candidate 1](../beta-candidate/index.md) and [Beta Candidate Action Plan](beta-candidate-action-plan.md) for the next release step.
