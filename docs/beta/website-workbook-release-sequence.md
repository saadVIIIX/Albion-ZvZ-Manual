---
status: Draft
audience: Project maintainers / workbook maintainers
source_layer: Project synthesis
patch_sensitivity: Low
last_reviewed: 2026-06-06
---

# Website / Workbook Release Sequence

The website and workbook should not be released in the wrong order.

## Correct sequence

1. Website preview reaches beta.
2. Trusted reviewers check site navigation and role pages.
3. Workbook master remains private.
4. A public workbook copy is created.
5. Public workbook copy passes privacy/readability/functionality checks.
6. Website links to public workbook copy, not the master.
7. Public beta release note is published.
8. Feedback is triaged into fix/backlog/verify/high-level/out-of-scope.

## Why this matters

The website is mostly teaching. The workbook can contain live operational details. Accidentally exposing the wrong workbook is a much higher risk than publishing a draft website page.

## Public workbook link rule

A public website should only link:

- a cleaned public workbook copy
- a template copy link
- or a placeholder saying workbook link pending

It should not link the private/master workbook.

## Future improvement

Later, the website can host more workbook-like static pages, but live signups and party assignment are still better handled by Google Sheets unless a real web app is built.
