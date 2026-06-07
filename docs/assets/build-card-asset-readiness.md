---
status: Draft
audience: Project maintainers / visual editors
source_layer: Project synthesis
patch_sensitivity: Medium
last_reviewed: 2026-06-05
---

# Build Card Asset Readiness

Build-card visuals should not begin until the asset system is ready.

## Ready checklist

Before adding item icons to build cards, confirm:

- icon tier theme is chosen
- item ID naming convention is chosen
- icon files are saved locally
- every icon has a text label fallback
- build-card layout is stable
- build cards are mapped to workbook builds
- patch-sensitive status is visible

## Recommended folder plan

```text
docs/assets/images/items/t8/
docs/assets/images/items/t7/
docs/assets/images/builds/control-comp/
```

Use only one public tier folder in final build cards unless the page intentionally explains a tier difference.

## Current state

Not ready for bulk icon work yet.

The project should first finish:

1. public-copy workbook strategy
2. build library to build-card mapping
3. build-card visual layout
4. icon tier decision
