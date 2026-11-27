---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: 'If you are a business user, please note that in particular we will not be liable for: loss of profits, sales, business, or revenue'
    type: business
  - text: If you are a consumer user, please note that we only provide our site for domestic and private use.
    type: individual
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: No commercial use by consumers
    text: You agree not to use our site for any commercial or business purposes
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
name: Solvo.ai
provenance_date: '2026-11-10'
provider_name: Solvo.ai
provider_slug: solvo-ai
slug: solvo-ai-eligibility
source_date: '2026-11-10'
source_filename: solvo-ai-eligibility.yml
source_heading: Eligibility
source_page: https://www.solvo.ai/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Solvo.ai\naid: solvo-ai\nurl: https://www.solvo.ai/terms\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: 'If you are a business user, please note that in particular we will not be liable for: loss of profits,\n    sales, business, or revenue'\n- type: individual\n  text: If you are a consumer user, please note that we only provide our site for domestic and private use.\nrestricted_uses:\n- summary: No commercial use by consumers\n  text: You agree not to use our site for any commercial or business purposes\nverification:\n  kyc: null\n\
  \  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/solvo-ai/eligibility/solvo-ai-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
summary_line: 3 quoted statements, read from Solvo.ai's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Logistics
- Container Shipping
- Revenue Management
- Dynamic Pricing
- Freight
- Artificial Intelligence
- Supply Chain
---
