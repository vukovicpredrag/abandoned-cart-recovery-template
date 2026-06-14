# Abandoned Cart Recovery (Mautic Campaign Library template)

Wins back shoppers who left items in their cart: reminder email, then open- and click-tracking that branches into purchase-intent scoring + a `hot-cart` tag, with a 10% discount fallback for non-openers.

**Industry:** E-commerce / Retail · **Keywords:** abandoned-cart, e-commerce, recovery, discount, email

## Contents
- 1 campaign (6 events: `email.send`, `email.open`, `email.click`, `lead.changepoints`, `lead.changetags`, `email.send`)
- 2 emails, 1 segment
- Mechanics shown: open + click decisions, point scoring and tag assignment on the engaged branch

## Structure
- `entity_data.json` — campaign export (Campaign Library Phase 1 format)
- `composer.json` — Packagist / Marketplace metadata (`type: mautic-resource`)
- `assets/` — referenced binary files (if any)
