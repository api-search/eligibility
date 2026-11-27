---
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: “you” and “your” refer to you and any organization that you are acting on behalf of in signing up for a subscription to the Services.
    type: business
  minimum_age:
    text: null
    value: null
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: You may need to provide additional information to verify your identity before completing your transaction
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: EcoCart
provenance_date: '2026-11-09'
provider_name: EcoCart
provider_slug: ecocart
slug: ecocart-eligibility
source_date: '2026-11-09'
source_filename: ecocart-eligibility.yml
source_heading: Eligibility
source_page: https://ecocart.io/terms-conditions/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: EcoCart\naid: ecocart\nurl: https://ecocart.io/terms-conditions/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: “you” and “your” refer to you and any organization that you are acting on behalf of in signing up for a\n    subscription to the Services.\nrestricted_uses: []\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: You may need to provide additional information to verify your identity before completing your transaction\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/ecocart/eligibility/ecocart-eligibility.yml
stated_fields:
- entity_types
- verification
summary_line: 2 quoted statements, read from EcoCart's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Sustainability
- Carbon Offsets
- E-Commerce
- Climate
- Checkout
- Shipping Protection
- Returns
---
