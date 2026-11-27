---
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: GoWabi Cashback and its benefit is limited to individuals for private use only.
    type: individual
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Commercial use of cashback
    text: The commercial use of GoWabi Cashback is prohibited.
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
name: GoWabi
provenance_date: '2026-11-09'
provider_name: GoWabi
provider_slug: gowabi
slug: gowabi-eligibility
source_date: '2026-11-09'
source_filename: gowabi-eligibility.yml
source_heading: Eligibility
source_page: https://www.gowabi.com/en/terms_and_conditions
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: GoWabi\naid: gowabi\nurl: https://www.gowabi.com/en/terms_and_conditions\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: GoWabi Cashback and its benefit is limited to individuals for private use only.\nrestricted_uses:\n- summary: Commercial use of cashback\n  text: The commercial use of GoWabi Cashback is prohibited.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/gowabi/eligibility/gowabi-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
summary_line: 2 quoted statements, read from GoWabi's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Beauty
- Wellness
- Booking
- Marketplace
- Spa
- Consumer
- Southeast Asia
- Thailand
---
