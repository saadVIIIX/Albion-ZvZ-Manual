---
status: Publication audit
audience: Project maintainers / mechanics reviewers
source_layer: Project audit
patch_sensitivity: High
last_reviewed: 2026-06-06
---

# Mechanics Verification Queue

This page tracks content that may need current-game verification before stable publication.

## Why this exists

Albion item behavior, cooldowns, meta status, and exact mechanics can change. The public manual should avoid unsupported hard numbers and current-meta claims.

## Automated scan

This table scans weapon, build, role, and fight concept pages for verification-sensitive wording.

| Page | Terms found | Audit note |
|---|---|---|
| build-cards/control-comp/great-fire.md | cooldown, cooldowns | Patch-sensitive or verification-related wording present. |
| build-cards/control-comp/index.md | meta, patch-sensitive, verification | Patch-sensitive or verification-related wording present. |
| build-cards/control-comp/oathkeepers.md | cooldown | Patch-sensitive or verification-related wording present. |
| build-cards/status-guide.md | cooldown, cooldowns, exact, patch-sensitive | Patch-sensitive or verification-related wording present. |
| build-cards/template.md | patch-sensitive | Patch-sensitive or verification-related wording present. |
| fight-concepts/counter-engage-windows.md | cooldown, cooldowns | Patch-sensitive or verification-related wording present. |
| fight-concepts/engage-counter-engage.md | AoE escalation, cooldown | Patch-sensitive or verification-related wording present. |
| fight-concepts/high-value-targets.md | cooldown, cooldowns | Patch-sensitive or verification-related wording present. |
| fight-concepts/index.md | cooldown, cooldowns | Patch-sensitive or verification-related wording present. |
| fight-concepts/movement-positioning.md | cooldown, cooldowns, exact | Patch-sensitive or verification-related wording present. |
| fight-concepts/pressure-types.md | cooldown, cooldowns | Patch-sensitive or verification-related wording present. |
| fight-concepts/qw-pressure-floor.md | AoE escalation, cooldown, cooldowns | Patch-sensitive or verification-related wording present. |
| fight-concepts/qw-pressure.md | cooldown, cooldowns | Patch-sensitive or verification-related wording present. |
| fight-concepts/target-selection.md | AoE escalation, cooldown, cooldowns | Patch-sensitive or verification-related wording present. |
| roles/all-players.md | cooldown, cooldowns, exact | Patch-sensitive or verification-related wording present. |
| roles/caller-officers.md | cooldown | Patch-sensitive or verification-related wording present. |
| roles/dps-overview.md | cooldown, cooldowns | Patch-sensitive or verification-related wording present. |
| roles/engage-clump-tanks.md | cooldown | Patch-sensitive or verification-related wording present. |
| roles/healers.md | cooldown | Patch-sensitive or verification-related wording present. |
| roles/melee-dps.md | cooldown | Patch-sensitive or verification-related wording present. |
| roles/melee-pressure-dps.md | AoE escalation, cooldown, cooldowns | Patch-sensitive or verification-related wording present. |
| roles/nature-healers.md | cooldown, cooldowns | Patch-sensitive or verification-related wording present. |
| roles/ranged-dps.md | cooldown, cooldowns | Patch-sensitive or verification-related wording present. |
| roles/scouts-information.md | cooldown | Patch-sensitive or verification-related wording present. |
| roles/stopper-defensive-tanks.md | cooldown | Patch-sensitive or verification-related wording present. |
| roles/stopper-tanks.md | cooldown | Patch-sensitive or verification-related wording present. |
| roles/supports.md | cooldown, cooldowns | Patch-sensitive or verification-related wording present. |
| weapon-notes/aou-extracted-index.md | exact, meta, patch-sensitive, verification | Patch-sensitive or verification-related wording present. |
| weapon-notes/armor-defensive-tools.md | cooldown, exact, patch-sensitive, verify | Patch-sensitive or verification-related wording present. |
| weapon-notes/dps-weapons.md | cooldown, cooldowns, exact, meta, patch-sensitive, verification, verify | Patch-sensitive or verification-related wording present. |
| weapon-notes/extraction-backlog.md | meta, verification | Patch-sensitive or verification-related wording present. |
| weapon-notes/how-to-read-weapon-notes.md | exact, verification | Patch-sensitive or verification-related wording present. |
| weapon-notes/index.md | patch-sensitive, verification | Patch-sensitive or verification-related wording present. |
| weapon-notes/patch-sensitive-notes.md | cooldown, exact, meta, patch-sensitive, verification, verify | Patch-sensitive or verification-related wording present. |
| weapon-notes/tank-cc-weapons.md | cooldown, cooldowns, exact | Patch-sensitive or verification-related wording present. |

## Verification categories

| Category | Risk |
|---|---|
| Exact cooldowns | high patch sensitivity |
| Item ability behavior | high patch sensitivity |
| Meta status | high recency sensitivity |
| Item tier/enchantment visuals | medium publication sensitivity |
| General positioning concepts | lower patch sensitivity |

## Publication rule

Before stable release, either verify the claim or soften the wording.

Good wording:

> This is patch-sensitive and should be verified before stable publication.

Risky wording:

> This exact cooldown/meta status is permanently true.

## Batch 1 verification additions

Batch 1 adds several patch-sensitive topics that should be checked before stable release:

- exact cooldowns on burst melee tools,
- Energy Shaper stacking/overlap behavior,
- Kingmaker escalation behavior,
- current Siege Bow meta/mechanics,
- current Brimstone/Fire Q/W ability behavior,
- armor/helmet ability behavior such as Judicator, Demon, Cleric, Night Helmet, and Face Scale-style tools.
