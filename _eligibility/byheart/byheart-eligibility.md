---
claim_count: 5
description: ''
doc:
  countries:
    excluded: []
    served:
    - US
    text: Products can be shipped to all 50 United States at this time.
  entity_types:
  - text: The Site is intended for use by individual consumers only.
    type: individual
  minimum_age:
    text: By using this Site, you agree that you are at least 13 years of age.
    value: '13'
  restricted_uses:
  - summary: No commercial use
    text: You may not use the Site for any commercial purposes, including the promotion or advertisement of any goods, services, or opportunities
  - summary: No resale or wholesale purchases
    text: Purchases are not intended for use by resellers or wholesalers unless ByHeart gives advance express written consent.
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: null
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: ByHeart
provenance_date: '2026-11-09'
provider_name: ByHeart
provider_slug: byheart
slug: byheart-eligibility
source_date: '2026-11-09'
source_filename: byheart-eligibility.yml
source_heading: Eligibility
source_page: https://byheart.com/pages/terms-and-conditions
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: ByHeart\naid: byheart\nurl: https://byheart.com/pages/terms-and-conditions\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served:\n  - US\n  excluded: []\n  text: Products can be shipped to all 50 United States at this time.\nentity_types:\n- type: individual\n  text: The Site is intended for use by individual consumers only.\nrestricted_uses:\n- summary: No commercial use\n  text: You may not use the Site for any commercial purposes, including the promotion or advertisement of any goods,\n    services, or opportunities\n- summary: No resale or wholesale purchases\n  text: Purchases are not intended for use by resellers\
  \ or wholesalers unless ByHeart gives advance express written\n    consent.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '13'\n  text: By using this Site, you agree that you are at least 13 years of age.\n"
source_yaml_url: https://artifacts.apis.io/byheart/eligibility/byheart-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- minimum_age
summary_line: 5 quoted statements, read from ByHeart's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Consumer
- Infant Nutrition
- Baby Formula
- Direct to Consumer
- E-Commerce
- Health
- Shopify
---
