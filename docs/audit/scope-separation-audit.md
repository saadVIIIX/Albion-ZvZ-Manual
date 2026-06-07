---
status: Publication audit
audience: Project maintainers / reviewers
source_layer: Project audit
patch_sensitivity: Low
last_reviewed: 2026-06-06
---

# Scope Separation Audit

This audit checks whether the site is drifting back into a workbook-centered or Great Fire-only guide.

## Separation model

| Layer | What belongs there |
|---|---|
| Public manual | general Albion ZvZ education |
| Weapon and Ability Notes | AOU-specific weapon/tool literacy and patch-sensitive notes |
| Applied Build Cards | package-specific build references |
| Workbooks and Tools | optional operating templates and comp packages |
| Archive | source memory and private material preservation |

## Automated phrase scan

The table below scans general/public sections for package-specific terms. A hit is not automatically wrong. It means the page should be checked for framing.

| Page | Terms found | Audit note |
|---|---|---|
| fight-concepts/defensive-layering.md | Locus, Oathkeepers | Review context; keep if framed as example/link, revise if it reads as default doctrine. |
| playstyles/hybrid-zergs.md | Great Fire Control Formation, workbook, Workbook | Review context; keep if framed as example/link, revise if it reads as default doctrine. |
| playstyles/index.md | Great Fire, Brimstone, Great Fire Control Formation, workbook, Workbook | Review context; keep if framed as example/link, revise if it reads as default doctrine. |
| playstyles/melee-clap-burst.md | Great Fire Control Formation, workbook, Workbook | Review context; keep if framed as example/link, revise if it reads as default doctrine. |
| playstyles/melee-dot-pressure-brawl.md | Great Fire Control Formation, workbook, Workbook | Review context; keep if framed as example/link, revise if it reads as default doctrine. |
| playstyles/ranged-pressure.md | Great Fire, Brimstone | Review context; keep if framed as example/link, revise if it reads as default doctrine. |
| playstyles/style-spectrum.md | workbook | Review context; keep if framed as example/link, revise if it reads as default doctrine. |
| roles/dps-overview.md | workbook | Review context; keep if framed as example/link, revise if it reads as default doctrine. |
| roles/engage-clump-tanks.md | workbook | Review context; keep if framed as example/link, revise if it reads as default doctrine. |
| roles/healers.md | workbook | Review context; keep if framed as example/link, revise if it reads as default doctrine. |
| roles/holy-healers.md | Great Fire Control Formation, workbook | Review context; keep if framed as example/link, revise if it reads as default doctrine. |
| roles/index.md | workbook, Workbook | Review context; keep if framed as example/link, revise if it reads as default doctrine. |
| roles/melee-dps.md | workbook | Review context; keep if framed as example/link, revise if it reads as default doctrine. |
| roles/nature-healers.md | Great Fire Control Formation, workbook | Review context; keep if framed as example/link, revise if it reads as default doctrine. |
| roles/scouts-information.md | workbook | Review context; keep if framed as example/link, revise if it reads as default doctrine. |
| roles/stopper-defensive-tanks.md | workbook | Review context; keep if framed as example/link, revise if it reads as default doctrine. |
| roles/support-dps.md | Great Fire Control Formation, workbook, Locus | Review context; keep if framed as example/link, revise if it reads as default doctrine. |
| roles/supports.md | Great Fire Control Formation, workbook | Review context; keep if framed as example/link, revise if it reads as default doctrine. |
| start-here/first-cta-checklist.md | Workbook | Review context; keep if framed as example/link, revise if it reads as default doctrine. |
| start-here/pick-your-first-role.md | workbook | Review context; keep if framed as example/link, revise if it reads as default doctrine. |
| training/micro-drills.md | Locus, Oathkeepers | Review context; keep if framed as example/link, revise if it reads as default doctrine. |
| weapon-notes/aou-extracted-index.md | Great Fire, Brimstone, Great Fire Control Formation, workbook, Workbook, Carrioncaller, Locus, Oathkeepers | Review context; keep if framed as example/link, revise if it reads as default doctrine. |
| weapon-notes/armor-defensive-tools.md | workbook, Workbook | Review context; keep if framed as example/link, revise if it reads as default doctrine. |
| weapon-notes/dps-weapons.md | Great Fire, Brimstone, Great Fire Control Formation, workbook, Carrioncaller | Review context; keep if framed as example/link, revise if it reads as default doctrine. |
| weapon-notes/extraction-backlog.md | Great Fire, Great Fire Control Formation, workbook | Review context; keep if framed as example/link, revise if it reads as default doctrine. |
| weapon-notes/healing-weapons.md | Great Fire Control Formation, workbook | Review context; keep if framed as example/link, revise if it reads as default doctrine. |
| weapon-notes/how-to-read-weapon-notes.md | Great Fire Control Formation, Workbook | Review context; keep if framed as example/link, revise if it reads as default doctrine. |
| weapon-notes/index.md | workbook | Review context; keep if framed as example/link, revise if it reads as default doctrine. |
| weapon-notes/patch-sensitive-notes.md | workbook | Review context; keep if framed as example/link, revise if it reads as default doctrine. |
| weapon-notes/support-weapons.md | workbook, Locus, Oathkeepers | Review context; keep if framed as example/link, revise if it reads as default doctrine. |
| weapon-notes/tank-cc-weapons.md | Great Fire Control Formation, workbook | Review context; keep if framed as example/link, revise if it reads as default doctrine. |

## Interpretation rule

A general page may mention a specific weapon if it is clearly an example.

A general page should be revised if it makes a specific workbook package feel like the default public doctrine.

## Current decision

Do not remove useful AOU weapon/tool material. Move or frame it correctly:

- broad behavior → role/fight concept page
- tool-specific teaching → Weapon and Ability Notes
- full build/package usage → Applied Build Cards or Workbooks
