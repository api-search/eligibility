---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: You are 16 or older; c. You have the authority to enter into the Agreement personally.
    type: individual
  minimum_age:
    text: You are 16 or older
    value: '16'
  restricted_uses:
  - summary: Lawful purposes only
    text: You will only use the Services for lawful purposes, and not for deceptive or fraudulent purposes
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
name: Sambazon
provenance_date: '2026-11-10'
provider_name: Sambazon
provider_slug: sambazon
slug: sambazon-eligibility
source_date: '2026-11-10'
source_filename: sambazon-eligibility.yml
source_heading: Eligibility
source_page: https://www.sambazon.com/policies/terms-of-service
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Sambazon\naid: sambazon\nurl: https://www.sambazon.com/policies/terms-of-service\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: You are 16 or older; c. You have the authority to enter into the Agreement personally.\nrestricted_uses:\n- summary: Lawful purposes only\n  text: You will only use the Services for lawful purposes, and not for deceptive or fraudulent purposes\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '16'\n  text: You are 16 or older\n"
source_yaml_url: https://artifacts.apis.io/sambazon/eligibility/sambazon-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 3 quoted statements, read from Sambazon's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Food and Beverage
- Consumer Packaged Goods
- E-Commerce
- Agentic Commerce
- Universal Commerce Protocol
- MCP
- Shopify
- Retail
- Sustainability
---
