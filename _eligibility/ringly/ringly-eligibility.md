---
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: If you are under 13, or do not have the authority to bind your company, do not use the Product.
    type: business
  minimum_age:
    text: If you are under 13, or do not have the authority to bind your company, do not use the Product.
    value: '13'
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
name: Ringly
provenance_date: '2026-11-10'
provider_name: Ringly
provider_slug: ringly
slug: ringly-eligibility
source_date: '2026-11-10'
source_filename: ringly-eligibility.yml
source_heading: Eligibility
source_page: https://www.ringly.io/terms-of-service
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Ringly\naid: ringly\nurl: https://www.ringly.io/terms-of-service\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: If you are under 13, or do not have the authority to bind your company, do not use the Product.\nrestricted_uses: []\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '13'\n  text: If you are under 13, or do not have the authority to bind your company, do not use the Product.\n"
source_yaml_url: https://artifacts.apis.io/ringly/eligibility/ringly-eligibility.yml
stated_fields:
- entity_types
- minimum_age
summary_line: 2 quoted statements, read from Ringly's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Artificial Intelligence
- Voice
- Customer Service
- E-Commerce
- Shopify
- Phone Support
- Conversational AI
---
