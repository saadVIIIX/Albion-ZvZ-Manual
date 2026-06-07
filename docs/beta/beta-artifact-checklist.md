---
status: Draft
audience: Project maintainers
source_layer: Project workflow
patch_sensitivity: Low
last_reviewed: 2026-06-06
---

# Beta Artifact Checklist

Use this checklist whenever a beta package is prepared.

## Required files

- Website Source ZIP
- Website Preview ZIP
- Website Blueprint DOCX
- Workbook XLSX
- Doctrine Archive / Handoff DOCX
- Public Beta Review Pack DOCX
- Public Beta Release Readiness DOCX

## Storage locations

| Folder | Store |
|---|---|
| `01_Current Website` | extracted latest source |
| `02_Version Archive` | source ZIP and preview ZIP |
| `03_Workbooks` | workbook versions |
| `04_Manual Docs` | legacy DOCX/manual references |
| `05_Doctrine Archive` | archive/handoff versions |
| `06_Images and Icons` | sourced icons and visuals later |
| `07_Blueprints and Plans` | website blueprints and plans |
| `08_Review Packs` | review packs and release readiness docs |

## Integrity checks

- Source ZIP opens.
- Preview ZIP opens.
- `index.html` opens from preview.
- Internal links check passes.
- Image/assets check passes.
- Workbook formula/error scan passes.
- Archive version matches website version note.
- Workbook Website Hub matches current versions.

## Release note

Do not send loose random files to reviewers. Send the preview ZIP plus review pack, then keep source/workbook/archive stored safely.
