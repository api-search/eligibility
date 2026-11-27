---
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: The Site is intended for users who are at least 18 years of age.
    type: individual
  - text: a legally binding agreement made between you, whether personally or on behalf of an entity
    type: business
  minimum_age:
    text: The Site is intended for users who are at least 18 years of age. If you are under 18, you should not use this Site.
    value: '18'
  restricted_uses:
  - summary: Illegal or unauthorized purpose
    text: You will not use the Site for any illegal or unauthorized purpose
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
name: Super73
provenance_date: '2026-11-10'
provider_name: Super73
provider_slug: super73
slug: super73-eligibility
source_date: '2026-11-10'
source_filename: super73-eligibility.yml
source_heading: Eligibility
source_page: https://super73.com/policies/terms-of-service
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Super73\naid: super73\nurl: https://super73.com/policies/terms-of-service\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: The Site is intended for users who are at least 18 years of age.\n- type: business\n  text: a legally binding agreement made between you, whether personally or on behalf of an entity\nrestricted_uses:\n- summary: Illegal or unauthorized purpose\n  text: You will not use the Site for any illegal or unauthorized purpose\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n\
  \  value: '18'\n  text: The Site is intended for users who are at least 18 years of age. If you are under 18, you should not use\n    this Site.\n"
source_yaml_url: https://artifacts.apis.io/super73/eligibility/super73-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 4 quoted statements, read from Super73's own page on 2026-11-10.
synthetic: false
tags:
- Electric Bikes
- Micromobility
- E-Commerce
- Agentic Commerce
- Consumer Hardware
- MCP
- Universal Commerce Protocol
- Shopify
- Direct to Consumer
- IoT
- Transportation
---
