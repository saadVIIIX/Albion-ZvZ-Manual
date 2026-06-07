---
status: Draft
audience: Project maintainers / visual editors
source_layer: Project synthesis + user asset note
patch_sensitivity: Medium
last_reviewed: 2026-06-05
---

# Item Icon Sourcing and Tier Policy

This page controls how item icons should be handled once visual build cards are implemented.

## Current rule

Do not ask the user to manually provide more item icons. The existing user-provided icons are useful as references, but they may include mixed tiers and inconsistent color palettes.

## Why tier consistency matters

Albion item icons visually differ by tier/enchantment. A build-card system that mixes white, yellow, purple, and mismatched icon frames can look messy and reduce trust.

## Recommended approach

Choose one consistent visual standard for public build cards.

Possible standards:

| Standard | Visual effect | Use case |
|---|---|---|
| 8.0 icons | white / clean high-tier look | clean public documentation, neutral visual style |
| 7.0 icons | yellow / premium-looking but not as stark | stronger Albion fantasy look |
| mixed actual tiers | realistic to builds | only if the workbook truly needs exact item-tier visuals |

## Current recommendation

Use a consistent icon tier theme for the website, probably **8.0** or **7.0**, and let the workbook handle exact item/IP practical details.

The website's job is to teach roles and build identity. The workbook's job is to run live content.

## Future workflow

```text
Build card item name
→ map to Albion item ID
→ fetch/source matching-tier icon
→ save locally in docs/assets/images/items/
→ reference icon from build card
→ verify page still works without images
```

## Safety rules

- Keep icons local once sourced so the site does not depend on external image loading.
- Do not mix icon tiers randomly.
- Do not publish private build screenshots with player/guild names.
- Mark item/build pages as patch-sensitive.
- Keep text labels so pages remain readable if an icon fails.
