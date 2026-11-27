---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: If you are entering into these Terms on behalf of a company or other organization, you hereby represent and warrant that you are authorized to enter into these Terms on behalf of such company or other organization
    type: business
  minimum_age:
    text: Our services are for those 18 years old and above.
    value: '18'
  restricted_uses:
  - summary: Lawful purposes only
    text: You may use Service only for lawful purposes and in accordance with Terms.
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
name: Item
provenance_date: '2026-11-09'
provider_name: Item
provider_slug: item
slug: item-eligibility
source_date: '2026-11-09'
source_filename: item-eligibility.yml
source_heading: Eligibility
source_page: https://item.app/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Item\naid: item\nurl: https://item.app/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  truncated: true\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: If you are entering into these Terms on behalf of a company or other organization, you hereby represent\n    and warrant that you are authorized to enter into these Terms on behalf of such company or other organization\nrestricted_uses:\n- summary: Lawful purposes only\n  text: You may use Service only for lawful purposes and in accordance with Terms.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text:\
  \ null\nminimum_age:\n  value: '18'\n  text: Our services are for those 18 years old and above.\n"
source_yaml_url: https://artifacts.apis.io/item/eligibility/item-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 3 quoted statements, read from Item's own page on 2026-11-09.
synthetic: false
tags:
- Company
- CRM
- Artificial Intelligence
- AI Agents
- Sales
- Customer Service
- Y Combinator
---
