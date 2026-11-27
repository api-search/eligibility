---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: You may only use our Services for personal, non-commercial, entertainment purposes.
    type: individual
  minimum_age:
    text: Unless otherwise specified, you must be at least 18 years old to play our Games.
    value: '18'
  restricted_uses:
  - summary: Commercial use
    text: Sell or resell our Services or your account
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
name: Wooga
provenance_date: '2026-11-10'
provider_name: Wooga
provider_slug: wooga
slug: wooga-eligibility
source_date: '2026-11-10'
source_filename: wooga-eligibility.yml
source_heading: Eligibility
source_page: https://www.wooga.com/legal/en-terms-of-service
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Wooga\naid: wooga\nurl: https://www.wooga.com/legal/en-terms-of-service\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  truncated: true\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: You may only use our Services for personal, non-commercial, entertainment purposes.\nrestricted_uses:\n- summary: Commercial use\n  text: Sell or resell our Services or your account\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: Unless otherwise specified, you must be at least 18 years old to play our Games.\n"
source_yaml_url: https://artifacts.apis.io/wooga/eligibility/wooga-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 3 quoted statements, read from Wooga's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Gaming
- Mobile Games
- Casual Games
- Game Development
- Entertainment
---
