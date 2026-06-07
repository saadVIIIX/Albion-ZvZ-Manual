---
status: Draft
audience: Project maintainers
source_layer: Project workflow
patch_sensitivity: Low
last_reviewed: 2026-06-05
---

# Versioning and Storage Workflow

This page preserves the non-technical storage workflow.

## Folder structure

```text
Albion ZvZ Website Project
├── 01_Current Website
├── 02_Version Archive
├── 03_Workbooks
├── 04_Manual Docs
├── 05_Doctrine Archive
├── 06_Images and Icons
└── 07_Blueprints and Plans
```

## How to use new website files

For each new version:

1. Put the source zip and preview zip into **02_Version Archive**.
2. Replace the contents of **01_Current Website** with the newest source zip.
3. Extract the preview zip somewhere easy to open.
4. Open `index.html` from the preview folder to review.

## Current version pattern

- Source: `Albion_ZvZ_Website_Source_v0_X.zip`
- Preview: `Albion_ZvZ_Website_Preview_v0_X.zip`
- Blueprint: `Albion_ZvZ_Website_Blueprint_v0_X.docx`
- Archive: `Albion_ZvZ_Doctrine_Archive_Handoff_vX_X.docx`
- Workbook: `Albion_ZvZ_Workbook_VX_X.xlsx`

## Future GitHub step

GitHub Pages/MkDocs publishing can happen later. Until then, versioned zips and previews are safer for a non-technical workflow.
